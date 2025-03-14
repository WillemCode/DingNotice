## 简介

> 钉钉官方为了确保自定义机器人使用过程的安全性，提供三种保护措施来保障你的自定义机器人安全运行。
> 这些措施包括：设置自定义关键词、加签（使用签名加密）和 IP 地址（段）。通过这些方法，可以有效保护你的机器人不受恶意攻击

详细链接 [参考钉钉](https://open.dingtalk.com/document/orgapp/customize-robot-security-settings)

本项目使用加签方式发送
加签的方式是钉钉机器人与开发者双向进行安全认证，以此来验证安全性。

## 安装与配置

```
git clone https://github.com/WillemCode/DingNotice.git
cd DingNotice

vim dingding.sh
```

修改以下配置, 修改为钉钉生成的 `token` 和 `secret`

```
  7 DD_TOKEN=""
  8 DD_SECRET=""
```


## 使用方法

```

bash dingding.sh "主题" "信息内容" "访问链接"

bash dingding.sh "主题" "信息内容" "访问链接" >/dev/null 2>&

```


---

## 技术支持

- **问题反馈**：请提交Issue至[GitHub仓库](https://github.com/WillemCode/ScriptTools/issues)。

---

## 许可证说明

本项目采用 [GNU General Public License (GPL)](./LICENSE) 进行开源发布。  
这意味着：

- 你可以自由复制、修改和分发本项目的源代码，但修改后的项目也必须继续以 GPL 或兼容的许可证进行发布；
- 分发或发布时，需包含本项目的原始版权声明与 GPL 协议文本，并提供完整的源代码获取方式。

请参阅 [LICENSE](./LICENSE) 文件获取详细条款。若你对 GPL 的使用及合规性有任何疑问，请查阅 [GNU 官网](https://www.gnu.org/licenses/) 或咨询相关专业人士。

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=WillemCode/DingNotice&type=Date)](https://www.star-history.com/#WillemCode/DingNotice&Date)

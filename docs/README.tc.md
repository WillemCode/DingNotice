## 簡介

> DingTalk 官方為了確保自定義機器人使用過程中的安全性，提供三種保護措施來保障你的自定義機器人安全運行。
> 這些措施包括：設置自定義關鍵字、加簽（使用簽名加密）和 IP 地址（段）。通過這些方法，可以有效保護你的機器人不受惡意攻擊。

詳細鏈接 [參考 DingTalk](https://open.dingtalk.com/document/orgapp/customize-robot-security-settings)

本專案使用加簽方式發送
加簽的方式是 DingTalk 機器人與開發者雙向進行安全認證，以此來驗證安全性。

## 安裝與配置

```
git clone https://github.com/WillemCode/DingNotice.git
cd DingNotice

vim dingding.sh
```

修改以下配置，修改為 DingTalk 生成的 `token` 和 `secret`

```
  7 DD_TOKEN=""
  8 DD_SECRET=""
```

## 使用方法

```

bash dingding.sh "主題" "信息內容" "訪問鏈接"

bash dingding.sh "主題" "信息內容" "訪問鏈接" >/dev/null 2>&1

```

---

## 技術支持

- **問題反饋**：請提交 Issue 至 [GitHub 倉庫](https://github.com/WillemCode/ScriptTools/issues)。

---

## 授權說明

本專案採用 [GNU General Public License (GPL)](./LICENSE) 開源發布。

這意味著：

- 你可以自由複製、修改和分發本專案的源代碼，但修改後的專案也必須繼續以 GPL 或兼容的許可證進行發布；
- 分發或發布時，需包含本專案的原始版權聲明與 GPL 協議文本，並提供完整的源代碼獲取方式。

請參閱 [LICENSE](./LICENSE) 文件獲取詳細條款。若你對 GPL 的使用及合規性有任何疑問，請查閱 [GNU 官網](https://www.gnu.org/licenses/) 或諮詢相關專業人士。

---

## Star 歷史

[![Star History Chart](https://api.star-history.com/svg?repos=WillemCode/DingNotice&type=Date)](https://www.star-history.com/#WillemCode/DingNotice&Date)

## 概要

> DingTalk 公式では、カスタムロボットの使用中のセキュリティを確保するために、3つの保護手段を提供しています。
> これらの手段には、カスタムキーワードの設定、署名（署名暗号化の使用）、および IP アドレス（範囲）の制限が含まれています。これらの方法で、ロボットは悪意のある攻撃から効果的に保護されます。

詳細については、[DingTalk ドキュメント](https://open.dingtalk.com/document/orgapp/customize-robot-security-settings)を参照してください。

このプロジェクトは署名方法を使用してメッセージを送信します。
署名方法は、DingTalk ロボットと開発者の間で双方向のセキュリティ認証を行い、セキュリティを確認します。

## インストールと設定

```
git clone https://github.com/WillemCode/DingNotice.git
cd DingNotice

vim dingding.sh
```

次の設定を変更し、DingTalk で生成された `token` と `secret` を設定してください。

```
  7 DD_TOKEN=""
  8 DD_SECRET=""
```

## 使い方

```

bash dingding.sh "件名" "メッセージ内容" "アクセスリンク"

bash dingding.sh "件名" "メッセージ内容" "アクセスリンク" >/dev/null 2>&1

```

---

## 技術サポート

- **問題報告**: [GitHub リポジトリ](https://github.com/WillemCode/ScriptTools/issues)に問題を提出してください。

---

## ライセンス

このプロジェクトは [GNU General Public License (GPL)](./LICENSE) の下で公開されています。

これにより：

- このプロジェクトのソースコードを自由にコピー、修正、配布できますが、変更されたプロジェクトも GPL または互換性のあるライセンスで公開する必要があります；
- 配布または公開時には、元の著作権表示と GPL 契約書を含め、完全なソースコードへのアクセス方法を提供する必要があります。

詳細な条項については、[LICENSE](./LICENSE) ファイルをご覧ください。GPL の使用と遵守について質問がある場合は、[GNU のウェブサイト](https://www.gnu.org/licenses/)を参照するか、専門家に相談してください。

---

## Star 歴史

[![Star History Chart](https://api.star-history.com/svg?repos=WillemCode/DingNotice&type=Date)](https://www.star-history.com/#WillemCode/DingNotice&Date)

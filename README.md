Node Static Site 
====================

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

 * Node.jsを使った静的サイトのテンプレート
 * public以下にソースを配置
 * heroku等にデプロイして使うといいと思う

BASIC認証の設定
--------------

以下の環境変数を追加する。
**BASIC_AUTH_USER**が設定されている場合、BASIC認証が有効になる。

* **BASIC_AUTH_USER**：ユーザー
* **BASIC_AUTH_PASS**：パスワード

### Herokuコマンドによる設定

```
$ heroku config:set BASIC_AUTH_USER=<user name> BASIC_AUTH_PASS=<password>
```

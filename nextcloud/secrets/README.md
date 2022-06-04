# Nextcloud Secrets

ここに記載されているのは、このリポジトリで定義している Nextcloud 用の Application で利用する Secrets のキーとその使用例です。

Secrets には認証情報を含む機密情報を定義するので、このような形で公開リポジトリに配置してはなりません。
各キーの値は base64 によるエンコードがされているだけなので、元の値は容易に取得可能です。

## Secrets

この Application で指定する Secret と、それぞれに指定可能な Key は下記のとおりです。

### nextcloud-secret

Nextcloud 本体の秘匿情報を定義します。

|Key|Description|
|---|---|
|admin_username|Nextcloud の管理者のユーザ名を指定します。|
|admin_password|Nextcloud の管理者のパスワードを指定します。|

### nextcloud-mariadb-secret

|Key|Description|
|---|---|
|root_password|MariaDB の root ユーザのパスワードを指定します。|
|username|Nextcloud が MariaDB に接続するのに利用するユーザのユーザ名を指定します。|
|password|Nextcloud が MariaDB に接続するのに利用するユーザのパスワードを指定します。|

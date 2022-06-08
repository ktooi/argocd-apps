# Nextbox Secrets

ここに記載されているのは、このリポジトリで定義している Nextbox 用の Application で利用する Secrets のキーとその使用例です。

Secrets には認証情報を含む機密情報を定義するので、このような形で公開リポジトリに配置してはなりません。
各キーの値は base64 によるエンコードがされているだけなので、元の値は容易に取得可能です。

## Secrets

この Application で指定する Secret と、それぞれに指定可能な Key は下記のとおりです。

### netbox-secret

Netbox 本体の秘匿情報を定義します。

TBD

### netbox-pgsql-secret

TBD

### netbox-redis-secret

TBD

SAML_SPの設定が必要

private/saml_sp/auth_openidc.conf

下に環境に合わせて各種値を設定してください。

参考
https://tech-lab.sios.jp/archives/19319


初回
./docker/docker-compose up -d

変更があったとき
./docker/docker-compose up -d --build
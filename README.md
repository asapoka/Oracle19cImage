# Run Oracle19c

1. ブラウザで開く → https://container-registry.oracle.com/ords/ocr/ba/database
2. Oracle アカウントで sign in する
3. 右側の利用規約に同意する
4. docker login container-registry.oracle.com でログインする
5. docker pull container-registry.oracle.com/database/enterprise:19.3.0.0
6. docker compose up -d

## Oracle Enterprise Manager Database Express

https://localhost:5500/em/

example
UserName → sys
Password → pass
Container Name → ORCLPDB1

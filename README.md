# tmp-hoge

```marmaid
graph TD
    User -->|アクセス| WebServer[Web サーバ]
    WebServer -->|API リクエスト| AppServer[アプリケーションサーバ]
    AppServer -->|データ操作| DB[(データベース)]
    AppServer -->|ログ送信| LogSystem[ログシステム]
    WebServer -->|静的ファイル提供| CDN[CDN]
    DB --> Backup[バックアップサーバ]

```

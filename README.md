# githubtest-C

## Express.js 学習用リポジトリ

このリポジトリは、Express.jsの学習をサポートするために作成されました。

## セットアップ手順

1. このリポジトリをクローンします。
   ```bash
   git clone【このリポジトリのURL】

2. 必要な依存関係をインストールします。
    ```bash
    npm install express

3. app.jsファイルを作成する。
　　```javascript
    const express = require('express');
    const app = express();
    const port = 3000;

    app.get('/', (req, res) => {
        res.send('Hello, Codespaces!');
    });

    app.listen(port, () => {
        console.log(`Server is running at http://localhost:${port}`);
    });


3. サーバーを起動します。
    ```bash
    node app.js

4.　ブラウザで http://localhost:3000 にアクセスして、「Hello, World!」が表示されることを確認します。

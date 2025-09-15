## 使い方

1. DockerとVSCodeをインストールしてください。
   - Dockerは、[こちら](https://docs.docker.com/get-docker/)からインストールできます。
   - VSCodeは、[こちら](https://code.visualstudio.com/)からインストールできます。
2. このリポジトリをVSCodeを開き、プロジェクトのフォルダを開いて、VSCodeの左下の「><」という感じのアイコンをクリックすると上のプルダウンメニューが出てきますので、「Reopen in Container」をクリックします。
3. しばらくコンテナイメージのダウンロード＆ビルドが行われます。これには時間がかかる場合がありますので、しばらくお待ちください
4. これでJupyterの開発環境が整いました。これ以降は、同じPCであれば、すぐに使えます。

## Dockerfileについて
このdevcontainerは、以下のDockerイメージをベースにしています。

https://hub.docker.com/r/ykunisato/dev-con-jupyter

DockerイメージのDockerfileは、以下のリポジトリにあります。

https://github.com/ykunisato/devcontainer-docker

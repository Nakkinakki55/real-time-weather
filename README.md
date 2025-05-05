# 天気予報表示システム

このリポジトリでは、気象庁のAPIを利用して天気予報を取得し、シンプルなWebページで表示するためのソースコードを提供しています。  
GitHub Pages を使って公開すれば、誰でもURLを開くだけで最新の天気情報を確認できます。
![image](https://github.com/user-attachments/assets/b61a43f9-e0e0-4078-a15f-c34a9bf84212)

今回発行したURLは下記の通りです。

[https://nakkinakki55.github.io/real-time-weather/real-time-weather.html](https://nakkinakki55.github.io/real-time-weather/real-time-weather.html)

## このプロジェクトについて

このプロジェクトは、以下の目的で作成されました。

- **リアルタイムの天気予報を簡単に確認できる**
- **特別な開発環境を用意せずに動作させられる**
- **パソコンやスマホなど、どのデバイスからでもアクセス可能**

元々は Raspberry Pi を使ってデジタルサイネージのように表示するシステムを作成しましたが、  
「もっと簡単に、誰でもどこからでも見られる方法がいい！」というフィードバックを受け、GitHub Pages を使った方法を考案しました。

詳しくは、以下の記事をご覧ください。

- **[無料で簡単！天気予報サイトを公開する方法をやさしく解説](https://qiita.com/nishifeoda/items/de3e8b7081a9381c0ce7)**
- **[Raspberry Piを使って簡単・低コストで天気予報を大型画面に表示する方法](https://qiita.com/nishifeoda/items/6d7fecb8dcc4c3bbad21)**

## 使用技術

- **HTML** + **JavaScript**（フロントエンドのみ）
- **Bootstrap**（デザイン）
- **気象庁のAPI**（天気データ取得）

## 使い方

1. リポジトリをクローンする  git clone https://github.com/Nakkinakki55/real-time-weather
2. `real-time-weather.html` をブラウザで開く
3. 天気予報が表示されることを確認する

## GitHub Pagesで公開する方法

1. このリポジトリを **Fork** する（もしくはCloneして自身のリポジトリにアップロード）
2. GitHubのリポジトリページで「Settings」→「Pages」を開く
3. 「Branch」を `main` に設定して保存
4. 数分後、**https://your-username.github.io/weather-display/real-time-weather** でページが公開される


---

**誰でも簡単に天気予報をチェックできるWebページを作れるので、ぜひ試してみてください！**

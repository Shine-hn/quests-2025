# Quests

この授業の、毎週のリーディング・ライティングのクエストです。毎週、新しいクエストのフォルダ
（`quest-00/`、`quest-01/`、…）がこのリポジトリに追加されます。

クエストで読む文書は英語です。進め方の説明は日本語で書いてあります。

これは**オープンソースのプロジェクト**でもあります。誤字やリンク切れ、わかりにくい文を見つけたら、
直してプルリクエストを送れます。[CONTRIBUTING.md](CONTRIBUTING.md)（英語）を見てください。

## はじめに

このリポジトリの**自分用のコピー**（*fork* と呼びます）で作業します。
**GitHub Codespaces** を使います。Python と git がすぐ使える、ブラウザの中のコンピューターです。

1. このページの右上の **Fork** を押し、**Create fork** を押します。
2. **自分の fork** で、**Code** → **Codespaces** → **Create codespace on main** を押します。
   ブラウザの中で VS Code が開きます。ターミナルは下にあります。
3. 作業が終わったら、codespace を止めます。自分の fork で **Code** → **Codespaces** →
   **...** → **Stop codespace** を押します。アカウントには毎月の無料の時間があり、動いている codespace はその時間を使います。
   次からは、同じメニューから同じ codespace を開きます。

## 毎回の授業の前に：新しいクエストを受け取る

新しいクエストは、元のリポジトリ（*upstream* と呼びます）に追加されます。
それを自分の fork に取り込みます。

1. GitHub で自分の fork を開き、**Sync fork** → **Update branch** を押します。
2. codespace のターミナルで、次を実行します。

       git pull

> **メモ：** ファイルを変更したせいで `git pull` が失敗したときは、`git stash` を実行してから、もう一度試してください。

## クエストの遊び方

はじめての人は、まず [introduction.md](introduction.md) を読んでください。クエストの舞台と、Quest 0 までのいきさつが書いてあります。

1. codespace のターミナルで、クエストのフォルダに移動します。たとえば次のようにします。

       cd quest-00

   フォルダが見つからないときは、上の「毎回の授業の前に」を見てください。

2. クエストの `README.md` を読みます。
3. `quest.py` を実行して、すべてのステージに答えます。最後にフラグがもらえます。

       FLAG{xxxxxxxxxx}

4. **HQ** の **Submit a Flag** のフォームで、フラグを提出します。
   https://github.com/kwaka1208/quests-hq-2025/issues/new/choose

フラグはあなたの GitHub ID から作られるので、あなたにしか使えません。

## チームのページと、新人のためのクエスト

このリポジトリには、クエストのほかに、みんなで作るフォルダが2つあります。

- [`team/`](team/README.md)：チームのページ。Quest 14 で、自分のページをプルリクエストで足します
- [`welcome/`](welcome/README.md)：来月入ってくる新人のためのクエスト。第14・15回に、1人1つ作ります

## ファイルを壊してしまったら

クエストでは、いくつかのファイルを変更します。ファイルを壊してしまい、最初からやり直したいときは、元に戻せます。

    git restore quest-00/README.md

パスは、戻したいファイルのものにしてください。**そのファイルへの変更は消えます。** やり直したいときだけ使いましょう。
どのファイルを変更したかは、`git status` でわかります。

## 貢献する

- 問題を見つけたら：[Issue を出す](https://github.com/kwaka1208/quests-2025/issues/new/choose)
- 自分で直したいときは：[CONTRIBUTING.md](CONTRIBUTING.md)（英語）を読む
- 取り組むものを探しているときは：
  [`good first issue`](https://github.com/kwaka1208/quests-2025/labels/good%20first%20issue) のラベルがついた Issue を見る

## ライセンス

[MIT](LICENSE)

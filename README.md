# コンフリクトの解消
コンピュータ概論IIの課題です。

mainブランチとfeatureブランチに対して、テキストとバイナリーでコンフリクトを起こして解決した後に、この（tpu-game-2024/comp2_2_conflictの）mainブランチにプルリクエストを出してください。

# 修正場所

「feature/another_update」ブランチで修正しました

![画像](image.png)

# 進め方

## ローカルの体制の構築
* 本リポジトリをforkしてください（「Copy the main branch only」を外して、全てのブランチをコピーしてください）
* リポジトリをローカルにCloneします

## テキストのコンフリクトと解消
* 「main」ブランチを「feature/another_update」ブランチの差分を確認しましょう
* 「main」ブランチに「feature/another_update」ブランチをマージしてください
* コンフリクトを解消して、「main」ブランチを「feature/another_update」の状態にしてください
* GitHubにpushしてください
* GitHubのInsightsタブの「Network」をみてマージされていることを確認してください

## 提出

* 自身のリポジトリのmainリポジトリから、本リポジトリ（tpu-game-2024/comp2_2_conflict）のmainリポジトリににプルリクエストをしてください

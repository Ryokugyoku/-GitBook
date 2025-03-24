---
description: 主にチーム開発に必要な知識を記載する
icon: react
---

# GitHub

## GitHub基本知識

### 基本用語

{% embed url="https://qiita.com/shinshingodmt/items/637cf9e5c6660509c460" %}
参考サイト
{% endembed %}

<table><thead><tr><th width="184" align="center">用語</th><th width="488">概要</th></tr></thead><tbody><tr><td align="center">コミット</td><td>ローカル内で変更を保存する</td></tr><tr><td align="center">プッシュ</td><td>コミットされたローカルリポジトリのデータを<br>リモートリポジトリに反映する</td></tr><tr><td align="center">プル</td><td>リモートリポジトリの内容をローカルリポジトリに反映する</td></tr><tr><td align="center">ローカルリポジトリ</td><td>自分自身のパソコンの保存領域のこと</td></tr><tr><td align="center">リモートリポジトリ</td><td>GitHuに保存される作業領域のこと<br>こちらにアップロードされることで、変更を共有できる</td></tr><tr><td align="center">クローン</td><td>リモートリポジトリの内容を自分のローカル環境にコピーする</td></tr><tr><td align="center">フォーク</td><td>他の人のリモートリポジトリを<br>自分のリモートリポジトリにコピーする</td></tr><tr><td align="center">ブランチ</td><td>作業単位で異なる保存領域を確保する<br>基本イシュー単位でブランチが作成される</td></tr><tr><td align="center">マスターブランチ</td><td>ソースコードの大元。<br>基本リリースされているソースなどがこれにあたる</td></tr><tr><td align="center">マージ</td><td>修正・変更を加えたブランチをブランチ元に統合する</td></tr><tr><td align="center">リセット</td><td>誤ってコミットした内容を消すコマンド<br>コミットログまで削除するため、マージする際は基本利用しない</td></tr><tr><td align="center">リバート</td><td>コミットログを残す形で変更を取り消す方法</td></tr><tr><td align="center">リベース</td><td>指定したコミットをブランチを変えて作り直すことができる</td></tr><tr><td align="center">チェリーピック</td><td>他ブランチのコミットを自信のブランチに反映させることができる</td></tr><tr><td align="center">スタッシュ</td><td>作業中の変更を一時的に退避させる<br>急なブランチ変更などを行った際に利用する</td></tr><tr><td align="center">フェッチ</td><td>リモートリポジトリの変更を反映する<br>※マージが自動に行われないのがプルとの違い</td></tr><tr><td align="center">フェッチ</td><td>自信のブランチを特定のリポジトリにマージ依頼を投げる</td></tr></tbody></table>

## コミットログの確認方法



1. 対象リポジトリのGitHubページに遷移する\
   <img src="../.gitbook/assets/スクリーンショット 2025-03-24 20.55.57 (1).png" alt="" data-size="original">
2. 青いCodeボタンの下にあるCommitsという文字をクリックする
3. コミットログの一覧が表示される\
   ![](<../.gitbook/assets/スクリーンショット 2025-03-24 21.01.15.png>)\

4. コミットのタイトル名をクリックすることで変更内容を確認することができる\
   ![](<../.gitbook/assets/スクリーンショット 2025-03-24 21.03.16.png>)






# コミットができる

## 1. ローカルリポジトリの新規作成
<!-- 
任意の場所に git_practice という名前の新規ディレクトリを作成してください。作成したディレクトリに移動して、Git のローカルリポジトリを新規作成してください。 -->

## 2. 変更をステージに追加

<!-- 作成したディレクトリの下に README.md というファイルを作成してください。次に、作成したファイルをステージに追加してください。 -->

## 3. 変更を記録

<!-- ステージに追加した変更をローカルリポジトリに記録してください。なお、変更の記録のことを「コミット」と言います。 -->
===============================

# 変更状況を確認できる
<!-- 
Git で管理されているディレクトリに移動してください。任意のファイルに何らかの変更を追加してください。 -->

## 1. 変更状況の確認
<!-- 
現在何のファイルが変更されているかを確認してください。 -->

## 2. 変更内容の確認
<!-- 
何が変更されたか、変更内容を確認してください。 -->

## 3. 変更履歴

<!-- 変更の履歴（ログ）を確認してください。 -->

===============================

# 変更を元に戻すことができる

<!-- Git で管理されているディレクトリに移動してください。任意のファイルに何らかの変更を追加してください。 -->

## 1. ファイルの変更の取り消し

<!-- ファイルへの変更を取り消してください。 -->

## 2. ステージの変更の取り消し
<!-- 
任意のファイルに変更を行い、ステージに追加してください。

ステージに追加された変更を取り消して、ワークツリーに戻してください（ステージに変更は追加されておらず、ワークツリーに変更内容が残っている状態にしてください）。 -->

===============================

# GitHub を使って開発を進めることができる

## 1. リモートリポジトリ

<!-- GitHub 上に新規リポジトリを作成してください。 -->

## 2. プッシュ

<!-- ローカルの PC 上に GitHub 上で作成したリポジトリの同じ名前のディレクトリを作成し、そのディレクトリ内に README.md　ファイルを作成してください。

次に、ローカルリポジトリを新規作成し、変更をステージに追加、コミットしてください。

リモートリポジトリを登録してください。そして GitHub に変更をプッシュしてください。 -->

## 3. 追加の変更をプッシュ

<!-- README.md に変更を追加してください。そしてその変更を GitHub にプッシュしてください。 -->

## 4. クローン

<!-- GitHub 上にある他者が作成したリポジトリを自分の PC 上にクローンしてください。クローン対象は何でも良いです。 -->

===============================
# ブランチを利用して開発を進めることができる

<!-- Git で管理されているディレクトリに移動してください。 -->

## 1. ブランチの新規作成
<!-- 
feature という名前のブランチを新規作成してください。 -->

## 2. ブランチの切り替え

<!-- ローカルリポジトリのブランチを feature ブランチに切り替えてください。 -->

## 3. マージ

<!-- feature ブランチでファイルの変更を行い、コミットしてください。そしてローカルリポジトリのブランチを main ブランチに切り替えてください。 -->

<!-- 次に、feature ブランチの変更を main ブランチに取り込んでください。なお、他のブランチの変更を取り込むことをマージと言います。 -->

## 4. ブランチの名前の変更

feature ブランチの名前を rename という名前に変更してください。

## 5. ブランチの削除

rename ブランチを削除してください。

===============================
# GitHub フローに従って開発を進めることができる

GitHub にプッシュをしたことのあるローカルリポジトリ（自分の PC 上のディレクトリ）に移動してください。

## 1. プルリクエストとは

プルリクエストは何か、何のためにあるかをプログラミング初心者にわかるように説明してください。

## 2. プルリクエストの作成

以下のことを行い、プルリクエストを作成してください。

1. ローカル（自分の PC ）で pullrequest ブランチを新規作成し、切り替えてください
2. 任意のファイルに変更を行ってください
3. 変更をコミットしてください
4. GitHub に pullrequest というブランチ名で変更をプッシュしてください
5. GitHub を開き、pullrequest ブランチから main ブランチへのプルリクエストを作成してください
6. 変更内容を確認し、問題なければ GitHub 上で変更をマージしてください
7. GitHub 上の pullrequest ブランチを削除してください

## ３. ローカルへのリポートリポジトリの変更内容の取り込み

ローカルリポジトリのブランチを main ブランチに切り替えてください。

次に、リモートリポジトリ（GitHub）の main ブランチの内容をローカルリポジトリの main ブランチに取り込んでください。

それができたらローカルリポジトリの pullrequest ブランチを削除してください。

※開発を行う際はここから1に戻り、この1~2のステップを繰り返します

## 4. GitHub フロー

[GitHub フロー](https://docs.github.com/ja/get-started/quickstart/github-flow) の公式リファレンスを一読してください。

その上で、今後の開発は GitHub フローに基づいて行ってください。多くの組織における基本的な開発フローは GitHub フローもしくは GitHub フローをベースにしたものになります。今から GitHub フローに慣れていきましょう。

[![Gitter](https://badges.gitter.im/fra-dev-ops-bu/community.svg)](https://gitter.im/fra-dev-ops-bu/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![GitHub contributors](https://img.shields.io/github/contributors/fra-dev-ops-bu/githubinar_github.svg)](https://GitHub.com/fra-dev-ops-bu/githubinar_github/graphs/contributors/)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/fra-dev-ops-bu/githubinar_github.svg)](http://isitmaintained.com/project/fra-dev-ops-bu/githubinar_github "Percentage of issues still open")


# :fish: 水研職員のためのGitHub学習の手引き

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [はじめに](#%E3%81%AF%E3%81%98%E3%82%81%E3%81%AB)
  - [コンセプト](#%E3%82%B3%E3%83%B3%E3%82%BB%E3%83%97%E3%83%88)
  - [学ばないこと](#%E5%AD%A6%E3%81%B0%E3%81%AA%E3%81%84%E3%81%93%E3%81%A8)
- [GitHubを5秒で表現すると？](#github%E3%82%925%E7%A7%92%E3%81%A7%E8%A1%A8%E7%8F%BE%E3%81%99%E3%82%8B%E3%81%A8)
- [絶対にハズせない三大機能](#%E7%B5%B6%E5%AF%BE%E3%81%AB%E3%83%8F%E3%82%BA%E3%81%9B%E3%81%AA%E3%81%84%E4%B8%89%E5%A4%A7%E6%A9%9F%E8%83%BD)
  - [Issueを立ててみよう](#issue%E3%82%92%E7%AB%8B%E3%81%A6%E3%81%A6%E3%81%BF%E3%82%88%E3%81%86)
- [バージョン管理をしてみよう](#%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E7%AE%A1%E7%90%86%E3%82%92%E3%81%97%E3%81%A6%E3%81%BF%E3%82%88%E3%81%86)
- [Pull Requestをしてみよう](#pull-request%E3%82%92%E3%81%97%E3%81%A6%E3%81%BF%E3%82%88%E3%81%86)
- [仕事をスムーズにすすめるための補助機能](#%E4%BB%95%E4%BA%8B%E3%82%92%E3%82%B9%E3%83%A0%E3%83%BC%E3%82%BA%E3%81%AB%E3%81%99%E3%81%99%E3%82%81%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AE%E8%A3%9C%E5%8A%A9%E6%A9%9F%E8%83%BD)
- [自分のマシンで編集してみよう](#%E8%87%AA%E5%88%86%E3%81%AE%E3%83%9E%E3%82%B7%E3%83%B3%E3%81%A7%E7%B7%A8%E9%9B%86%E3%81%97%E3%81%A6%E3%81%BF%E3%82%88%E3%81%86)
- [水研業務のコンテキストから見たGitHub](#%E6%B0%B4%E7%A0%94%E6%A5%AD%E5%8B%99%E3%81%AE%E3%82%B3%E3%83%B3%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E3%81%8B%E3%82%89%E8%A6%8B%E3%81%9Fgithub)
- [読者の感想](#%E8%AA%AD%E8%80%85%E3%81%AE%E6%84%9F%E6%83%B3)
- [Appendix](#appendix)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 第1章 はじめに

### コンセプト
:tada: さぁ、:octocat:GitHubを学びましょう！ :tada:

ただし、講師から習うのではありません :no_good:
学習の手引きを読み、不明点は[Issue](https://github.com/fra-dev-ops-bu/githubinar_github/issues/new)として運営に投げてみましょう。
[Pull Request](https://github.com/fra-dev-ops-bu/githubinar_github/compare)による変更の提案も大歓迎てす。
この学びかた自体がもはや共同開発です。

> 「ここまで読んだだけで既に知らない用語がある...」> :cry:

:man_dancing: <大丈夫。下の方で解説されているはずです。解説に不備があったら、[ここ](https://github.com/fra-dev-ops-bu/githubinar_github/issues/new)から教えてください。

### 学ばないこと

ここでは、GitHubの使い方に集中するため、まずブラウザ上でGitHubを操作することからはじめます。
ターミナルでのコマンド入力は、第5章『自分のマシンで作業してみよう』までは出てきません<sup>[1](#gitcommand)</sup>。
まずはじっくり、GitHub の概念を理解することに集中してください。


そもそも、GitHubとGitはどのような関係にあるのでしょうか。
これを理解するには、GitHubが車、Gitをエンジンに例えるとよいでしょう。
エンジンを意識せずとも、車を運転することはできます。
もちろん、Gitの強力なコマンドたちは、日常業務の大きな助けとなります。
興味のある方は [GitHubinar of Git](https://github.com/fra-dev-ops-bu/githubinar_git)にご参加ください。

<hr>

## 第2章 GitHubを5秒で表現すると？

チームプレーに必要な全てが詰まったナレッジベースです。

## 第3章 絶対にハズせない三大機能

GitHubにはたくさんの機能がありますが、特に重要な機能は3つ&mdash;
「バージョン管理」「Issue」「Pull Request」です<sup>[2](#bigthree)</sup>。
いちばん重要な機能はバージョン管理ですが、ここでは簡単な順に学んでいきましょう。

### Issueを立ててみよう
今あなたがこれを Web ブラウザ上で読んでいるのなら、Issueを立てるのは簡単です。
`g i`（Go to Issue）そして`c`（Create）とタイプするだけです。

さて、Issueとは何かの説明をしていませんでした;
Issueとは、プロジェクトの課題を管理するための機能です。
課題にはどのようなものがあるかというと:

- バグ報告
- ユーザーからの機能追加などの要望
- 開発者が認識している內部の改善案

ほかには...?
うーん、思いつかないので[Issue](https://github.com/fra-dev-ops-bu/githubinar_github/issues/8)にしておきます。

#### Issueを使う理由

さて、Issueを使うと、なにかよいことがあるのでしょうか。
まず、Issue番号を使うことで、課題を指す時に誤解がありませんし、URLリンクが使えるようになります。

Issueの検索機能（`Ctrl` + `/`）を使うことで、このプロジェクトに過去にどのような問題があったのかを調べることができます。
また、「いつ」「誰が」「どんな方法で」解決したのかを検索できるようになります（[このように](https://github.com/fra-dev-ops-bu/githubinar_github/issues/4)）。

Issueが解決されたときには、"Close"ボタン押すことでIssueを閉じることができます。
ただし、これは手動でIssueを閉じる方法ですので、なるべく避けてください。
好き勝手にIssueを閉じると、
あとから振り返ったときにその問題が「なぜ」「どのように」解決されたかわからなくなり、GitHubがナレッジベースとして機能しなくなります。
Issueを手動でCloseするときには、最低限、理由を書いてください。
「どのように」を連動させる方法は、あとで学びます。

さて、Issueについての理解を深めるために、別の表現で言い替えてみましょう:
車でいうところのアクセル、仕事の動機です。
仕事は、Issueがあって初めて始まります。
Issueの数は、「Issues」タブに常に表示されていますが、
ここがゼロになると、プロジェクトは止まります。

さて、何度か「仕事」という言葉が出てきました。
バージョン管理を学ぶ準備ができたということです。

### バージョン管理をしてみよう

さてお気づきの通り、GitHubにはファイルが置かれています<sup>[3](#asyouknow)</sup>。
（`gc`（Go to Code）とすれば見ることができます）。
ここに見えているファイルはすべて、既にバージョン管理されています。
正しくは、「Gitというバージョン管理システムを使って」バージョン管理されています。

#### バージョン管理システムを使う理由

じつは、バージョン管理システムがなくとも、バージョン管理はできます。

「最終版.txt」「最終版_改.txt」「最終版_改_ファイナル.txt」というのも、
手動ではありますが立派なバージョン管理です。
手動バージョン管理の問題点は何でしょうか？

「最新版がどれかわからない」
「バグまで複製される」
「粒度と安全性のトレードオフが悩みの種」...
もっともらしく聞こえる問題点はいくらでも挙がりますが、
一番かんたんかつ重要な問題点は「見た目が汚くなる」です。

#### コミットしてみよう

バージョン管理システムを導入したプロジェクトでは、
ファイルの変更は全て上書きして構いません。
後でもとに戻すことができます。
バージョン管理システムでは、ファイルの変更のことを「コミット」といいます。

GitHub上でコミットするのは簡単です:

- 編集したいファイルに移動し
- 鉛筆のボタンを押して編集モードに入る<sup>[4](#edit)</sup>
- 「お作法（後述）」に従ってコミットメッセージを入力
- 左下の"Commit changes"を押す

コミット時には、必ずコミットメッセージ（仕事の内容が大まかにわかるような要約文）を入力する必要があります。
このコミットメッセージの書き方にはお作法があり、例えば次のように入力します:

`Write about commit message`

（空行)

`To explain importance of building knowledge base.`

`This commit resolves #123`

コミットメッセージの
1行目は、コミットの要約、
3行目以降は詳細説明です。
これらは、GitHub上でファイルを編集したとき、ページ下方に見える二つのメッセージ入力ウインドウに対応しています。
それぞれ入力の仕方を解説します。

##### 要約の書き方

ここは、[ファイルの変更履歴](https://github.com/fra-dev-ops-bu/githubinar_github/commits/master/README.md)を一覧したときに表示されますので、
なるべくきれいに書く必要があります。
プロジェクトの方針によって決めて構いませんが、一応の慣習があります（参考: https://chris.beams.io/posts/git-commit/ ）:

- 英語で
- 頭文字は現在形の動詞で、大文字はじめる
- 末尾ピリオドなし
- 50文字以内で

一覧の状態でつらつらと読めるように「要するに何をしたのか」を書いてください。
具体的な変更内容は、ファイルの変更差分を見ればわかりますので書く必要はありません。
余談ですが、コミットメッセージを読まなくとも、変更内容の種類を大まかに伝えるための方法として、絵文字の使用も推奨されています（参考: https://medium.com/@sa.nitawaki/enjoy-your-commit-with-gitmoji-c-1eca5fe35143 ）。

##### 詳細の書き方

コミットメッセージには、必要であれば詳細を入力することができます。
ここには、「なぜ」を書いてください。
ただし、いちばんよい方法は、Issue番号を書くことです。
コミットとは、貢献のこと。
その仕事（変更）がなされた理由は、Issueにあるはずです。
下に示すように、`#`につづけてIssue番号を書けば、GitHub上でIssueとコミットとの間にリンクが形成され、
Issueが自動でCloseされます。

- `This commit resolves #123`
- `Fix #123`
- `Close #123`

Issue側から見ると、その課題が「どのように」解決されたかが明確になります（例えばhttps://github.com/fra-dev-ops-bu/githubinar_github/issues/4 ）。
これは、手動でIssueを閉じる手間を省略するためではなく、ナレッジベースを育てるために有効な方法です。

#### ブランチを切ってみよう

さて、「上書きするのはちょっと恐いよ...」と思われた方、正解です。
上書きはやめてください。`master`ブランチの上書きは。
ブランチを切りさえすれば、いくらでも上書きして構いません。

ブランチを切るのは簡単です。
`g c`（Go to Code）と打ってコード置き場のトップに行き、
`w`（sWitch）を打って、お好みのブランチ名を入力してください。
何の仕事をするのかを忘れないために、ブランチ名は`issue/123`のようにIssue番号をつけるのがおすすめです（仕事は必ずIssueから生じることを忘れないでください）。
ブランチを作りましたか？
ブランチコントロールボタンに今作ったブランチ名が表示されているのを確認できたら、自由にファイルを編集してかまいません。
もしよければ、このチュートリアルの読みにくい箇所を書き換えてください。

### Pull Requestをしてみよう

Pull Requestとはなんでしょうか。
共同開発者に、変更を提案することです。
複数人での仕事は、コミュニケーションコストが伴います。
相手に変更を指示するよりも自分で変更した方が早いとき、
「このように変更しました。異論なければ受け入れてください」というふうに、仕事を進めることがてきます。

言い方を変えましょう。
先程、「`master`ブランチの上書きはダメ」と言いました。
では、`master`ブランチは、いつ更新されるのでしょうか。
Pull Requestが承認されたときです。

Pull Requestを出すのは簡単です。
`g p`（Go to Pull request）のあと`c`（Creat）とタイプするだけです。

"Campare changes"というページに飛び、"base"と"compare"というブランチボタンが表示されます。
"compare"に、あなたの作業ブランチを指定してみましょう。
あなたが自分の作業ブランチで何らかの変更（コミット）をしていれば、差分が表示されるはずです（なにも作業していなければ、差分は出ません）
変更内容がこれでよければ、Pull Requestを作ってみましょう。

メッセージのお作法は、コミットメッセージとだいたい同じです。
ただし、Pull Requestを受け取る側は、あなたが思っている以上に変更内容を理解できないものです。
「要は何をしたのか」をかいつまんで説明することを心がけてください。
「## やったこと」などのように、Markdown記法をうまく使って内容を整理しましょう。

ナレッジベースを育てるために、Pull requestのメッセージにも関連するIssue番号を書いてください。
`Resolve #123`と書けは、そのPull requestが承認（mergeといいます）された時に自動的にIssueがcloseされます。

## 第4章 仕事をスムーズにすすめるための補助機能
  - fork
  - History
  - Blame
  
## 第5章 自分のマシンで編集してみよう
  - Gitの環境構築
  - クリックでやっていたことをコマンドでやってみよう
  - コラム: GitHubとGitの関係は？ 
  
## Appendix
### 水研業務のコンテキストから見たGitHub
### 読者の感想
### さらなる学びのために

<a name="gitcommand">1</a>: git (reset|revert|rebase|stash|cherry-pick|bisect)は割愛します

<a name="bigthree">2</a>: 車の運転でいえば「アクセル」「ブレーキ」「ハンドル操作」といったところでしょうか

<a name="asyouknow">3</a>: 「そんなこと知らないよ！」という方は、Issueに追加してください。ショートカットは`gi` `c`ですよ

<a name="edit">4</a>: ファイル編集にもショートカットがありますが、ブラウザ上での編集は避けるべきなので解説しません

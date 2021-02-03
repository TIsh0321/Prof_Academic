# Prof_Academic

このレポジトリは[Website](https://jovial-blackwell-11ad0a.netlify.app/)の構築を目的として作成しています。

## 編集環境｜R Studio 
Rprojectファイル`Prof_Academic.Rproj`で編集をしています。

URL：https://github.com/TIsh0321/Prof_Academic/blob/main/Prof_Academic.Rproj

## Hugo Theme

Hugoを使用して構築しています。Hugothemeはstarter-academic`wowchemy/starter-academic`を使用しています。

## Deploy
このレポジトリを[Netlify](https://app.netlify.com/teams/tish0321/overview)経由でDeployしています。

## 構築手順

1．RstudioでNew Project->New registory -> Website using blogdonw
2. Projファイルを作成するときにthemeを読み込ませる(wowchemy/starter-academic)
3．config.yamlファイルのgithubのURL:`https://tish0321.github.io`を入力
4. blogdown::build_site()を実行
5．blogdown::serve_site()を実行
6. githubにレジストリを作成、commit and push.
7．githubにレジストリを作成する時に、公開設定をprivateではなくpublicになっていることを確認
8. netlifyにアクセスし、ログイン。`new site from Git`より公開手順を踏む。
9. deployを行って、サイトを構築


# test
<p align="center"><a href="https://wowchemy.com" target="_blank" rel="noopener"><img src="/content/home/gallery/gallery/" alt="Wowchemy Website Builder"></a></p>


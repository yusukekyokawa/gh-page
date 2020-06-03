# My Blog

## 記事作成方法

```shell
$hugo new /post/{filename}.md
```
で`/content/post/`にfilenameのmarkdownファイルが作成される．

markdownで記事を書く．GitHubPagesに載せたければ`draft`をfalseにするのを忘れずに

書いたら
```shell
$./deploy.sh "commit message"
```
でGitHubPagesに更新がかかる．

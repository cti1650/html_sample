# html_sample

html でシングルページサイトを作成する際のテンプレート

## ローカルへのコピー

以下を clone  
`git clone https://github.com/cti1650/html_sample.git`

## リポジトリをミラーする

1. Git Bash を開いてください。

2. リポジトリのベアクローンを作成します。
   `$ git clone --bare https://github.com/cti1650/html_sample.git`

3. 新しいリポジトリをミラープッシュします。
   `$ cd old-repository.git`
   `$ git push --mirror https://github.com/exampleuser/new-repository.git`

4. 先ほど作成した一時ローカルリポジトリを削除します。
   `$ cd .. `
   `$ rm -rf old-repository.git`

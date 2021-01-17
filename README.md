# html_sample

html でシングルページサイトを作成する際のテンプレート

## ローカルへのコピー

以下を clone  
```bash
git clone https://github.com/cti1650/html_sample.git
```

## リポジトリを複製する

1. Git Bash を開いてください。

2. リポジトリのベアクローンを作成します。   
   ```bash
   git clone --bare https://github.com/cti1650/html_sample.git
   ```

3. 新しいリポジトリをミラープッシュします。(--mirror 以降は複製先のリポジトリを指定)  
   ```bash
   cd html_sample.git
   git push --mirror [複製先リポジトリURL]
   ```

4. 先ほど作成した一時ローカルリポジトリを削除します。  
   ```bash
   cd ..
   rm -rf html_sample.git
   ```
   
5. 先ほど作成した複製先のリポジトリをクローンします。  
   ```bash
   git clone [複製先リポジトリURL]
   ```

> [GitHubでCloneでもForkでもなくリポジトリの複製が欲しい](https://qiita.com/taquaki-satwo/items/f8482c45dc91b6df9d34)

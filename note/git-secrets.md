## git-secrets

```
$ brew install git-secrets

// setting
$ git secrets --reegister-aws --global
$ git secrets --install ~/.git-templates/git-secrets
$ git config --global init.templatedir '~/.git-templetes/git-secrets'
```

上記設定後、謝ってコミットした場合にエラーを表示してくれる
```
git commit -m "commit message"
main.ts:2: access_key = "xxxxxxxxx"
main.ts:3: secret_key = "xxxxxxxxx"

[ERROR] Matched one or more prohibited patterns
```

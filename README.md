# empty-github-commit
> push a new empty commit on GitHub using API  
> 推送一个空的GitHub提交到远程仓库

## 安装
```sh
npm i empty-github-commit
pnpm i empty-github-commit
```

## 使用
```js
const emptyGitHubCommit = require('empty-github-commit')
emptyGitHubCommit({
  owner: 'username',
  repo: 'repo name',
  token: 'token',
  message: 'a empty commit message from empty-github-commit',
  branch: 'main'
}).then(console.log).catch(err => {
  console.error(err)
})
```

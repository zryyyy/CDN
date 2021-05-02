## jsDelivr

### 使用说明

```
// load any GitHub release, commit, or branch
// note: we recommend using npm for projects that support it
// 加载任何GitHub版本、提交或分支
// 注意：我们建议在支持npm的项目中使用它
https://cdn.jsdelivr.net/gh/user/repo@version/file

// load jQuery v3.2.1
// 加载jQuery v3.2.1
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js

// use a version range instead of a specific version
// 使用一个版本范围而不是一个特定的版本
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js
https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js

// omit the version completely to get the latest one
// you should NOT use this in production
// 完全省略版本，以获得最新的版本
// 你不应该在生产中使用这个
https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js

// add ".min" to any JS/CSS file to get a minified version
// if one doesn't exist, we'll generate it for you
// 在任何JS/CSS文件中添加".min "以获得一个最小化的版本
// 如果没有这个版本，我们将为你生成它
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js

// add / at the end to get a directory listing
// 在结尾处添加"/"以获得一个目录列表
https://cdn.jsdelivr.net/gh/jquery/jquery/
```

### 提交

```bash
git status //查看状态

git add . //添加所有文件到暂存区

git commit -m '第一次提交' //把文件提交到仓库

git push //推送至远程仓库
```


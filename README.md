## jsDelivr

### 使用说明

```text
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

### 通过jsDelivr引用资源

使用方法：https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径

例如：

```text
https://cdn.jsdelivr.net/gh/TRHX/CDN-for-itrhx.com@1.0/images/trhx.png
https://cdn.jsdelivr.net/gh/TRHX/CDN-for-itrhx.com@2.0.1/css/style.css  
https://cdn.jsdelivr.net/gh/moezx/cdn@3.1.3//The%20Pet%20Girl%20of%20Sakurasou.mp4
```

注意：版本号不是必需的，是为了区分新旧资源，如果不使用版本号，将会直接引用最新资源，除此之外还可以使用某个范围内的版本，查看所有资源等，具体使用方法如下：

```text
// 加载任何Github发布、提交或分支
https://cdn.jsdelivr.net/gh/user/repo@version/file

// 直接访问（暂不知道如何更新缓存）
https://cdn.jsdelivr.net/gh/user/repo/file

// 访问最新文件
https://cdn.jsdelivr.net/gh/user/repo@latest/file

// 文件列表
https://cdn.jsdelivr.net/gh/user/repo/

// 访问统计
https://www.jsdelivr.com/package/gh/user/repo

// 将“.min”添加到任何JS/CSS文件中以获取缩小版本，如果不存在，将为会自动生成
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js
```

### 注意事项

#### 被禁止的使用：

以下行为是被禁止的：

托管或访问以下内容：

1. 含有恶意软件或任何形式的有害代码

   - 侵犯他人的专有权利
   - 是色情的
   - 在欧盟或美国可能是非法的

2. 滥用服务和其资源，或**将jsDelivr作为一个通用的文件或媒体托管服务**。这包括，例如：

   - 运行一个图片托管网站，并**使用jsDelivr作为所有上传图片的CDN**
   - **托管视频，文件备份，或其他大量的文件**
我们承认，有一些合法的项目是由大量的文件组成的，这些不被视为滥用。例如：有大量资产的图标包、应用程序或游戏

3. 试图以任何方式绕过我们的限制或约束。我们将很高兴为合法项目取消限制或提供定制的解决方案

#### 在中国的其他限制：
jsDelivr持有中国政府颁发的ICP许可证，这使得我们可以直接在中国大陆运营基础设施。为了保持这个许可证，并允许我们的中国用户受益于它所提供的性能改进，任何通过我们的中国网络提供的内容必须符合中国的政策。有可能违反中国政策的内容在中国可能会被封锁，而不会有任何警告

#### 原文

##### Prohibited Use

The following behavior is prohibited:

1. Hosting or accessing content that:

   - contains malware or harmful code in any form,
   - violates proprietary rights of others,
   - is sexually explicit,
   - is potentially illegal in the EU or the USA.

2. Abusing the service and its resources, or using jsDelivr as a general-purpose file or media hosting service. This includes, for example:

   - running an image hosting website and using jsDelivr as a storage for all uploaded images,
   - hosting videos, file backups, or other files in large quantities.

   We recognize that there are legitimate projects that consist of a large number of files, and these are not considered abuse. For example: icons packs, apps, or games with a large number of assets.

3. Trying to bypass our limits or restrictions in any way. We will be happy to remove limits or provide custom solutions for legitimate projects.

##### Additional Restrictions in China

jsDelivr holds an ICP license issued by the Chinese government, which allows us to operate infrastructure directly in Mainland China. To keep this license and allow our Chinese users to benefit from the performance improvements it provides, any content served via our Chinese network must conform to Chinese policies. Content potentially violating Chinese policies may be blocked in China without warning.
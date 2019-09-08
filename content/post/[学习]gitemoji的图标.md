---
title: "[学习]Gitemoji的图标"
date: 2019-09-07T10:46:38+08:00
author: koco
tags: ['学习','Git']
draft: false
---

gitmoji的使用方式和一些官方的moji的解释  
<!--more--> 
-------------
> <label style="color:#FF00FF">moji用法</label>

git提交代码的常用命令： git commit -m '此次提交的内容说明'  

我们可以给提交的信息添加了emoji表情说明，我们来看看其命令语法

```
git commit -m ':emoji: 此次提交的内容说明'
git commit -m ':emoji1: :emoji2: :emoji3: 此次提交的内容说明' 
```

在提交内容的前面增加了emoji标签： :emoji: ，其中emoji是表情图标的标签，列表见下面的附录表格

> <label style="color:#FF00FF">gitmoji表格</label>

 中文解释 | 图标 | 代码 | 英文
 ------------ | ------ | ------------ | ------------ 
 改进代码结构/代码格式|🎨|:art:|Improving structure/format of the code.  
 提升性能|⚡️|:zap:|Improving performance.
 移除代码或文件|🔥|:fire:|Removing code or files.
 修复 bug|🐛|:bug:|Fixing a bug.
 重要补丁|🚑|:ambulance:|Critical hotfix.
 引入新功能|✨|:sparkles:|Introducing new features.
 撰写文档|📝|:pencil:|Writing docs.
 部署功能|🚀|:rocket:|Deploying stuff.
 更新 UI 和样式文件|💄|:lipstick:|Updating the UI and style files.
 初次提交|🎉|:tada:|Initial commit.
 更新测试|✅|:white_check_mark:|Updating tests.
 修复安全问题|🔒|:lock:|Fixing security issues.
 修复 macOS 下的问题|🍎|:apple:|Fixing something on macOS.
 修复 Linux 下的问题|🐧|:penguin:|Fixing something on Linux.
 修复 Windows 下的问题|🏁|:checkered_flag:|Fixing something on Windows.
 修复 Android 下的问题|🤖|:robot:|Fixing something on Android.
 修复 iOS 下的问题|🍏|:green_apple:|Fixing something on iOS.
 发行/版本标签|🔖|:bookmark:|Releasing / Version tags.
 移除 linter 警告|🚨|:rotating_light:|Removing linter warnings.
 工作进行中|🚧|:construction:|Work in progress.
 修复 CI 构建问题|💚|:green_heart:|Fixing CI Build.
 降级依赖|⬇️|:arrow_down:|Downgrading dependencies.
 升级依赖|⬆️|:arrow_up:|Upgrading dependencies.
 将依赖项固定到特定版本|📌|:pushpin:|Pinning dependencies to specific versions.
 添加 CI 构建系统|👷|:construction_worker:|Adding CI build system.
 添加分析或跟踪代码|📈|:chart_with_upwards_trend:|Adding analytics or tracking code.
 重构代码|♻️|:recycle:|Refactoring code.
 关于Docker的工作|🐳|:whale:|Work about Docker.
 增加一个依赖|➕|:heavy_plus_sign:|Adding a dependency.
 减少一个依赖|➖|:heavy_minus_sign:|Removing a dependency.
 修改配置文件|🔧|:wrench:|Changing configuration files.
 国际化与本地化|🌐|:globe_with_meridians:|Internationalization and localization.
 修复 typo|✏️|:pencil2:|Fixing typos.
 编写需要改进的错误代码|💩|:poop:|Writing bad code that needs to be improved.
 还原更改|⏪|:rewind:|Reverting changes.
 合并分支|🔀|:twisted_rightwards_arrows:|Merging branches.
 更新编译的文件或包|📦|:package:|Updating compiled files or packages.
 由于外部API更改而更新代码|👽|:alien:|Updating code due to external API changes.
 移动或重命名文件|🚚|:truck:|Moving or renaming files.
 添加或更新许可证|📄|:page_facing_up:|Adding or updating license.
 引入突破性变化|💥|:boom:|Introducing breaking changes.
 添加或更新资产|🍱|:bento:|Adding or updating assets.
 由于代码审阅更改而更新代码|👌|:ok_hand:|Updating code due to code review changes.
 提高无障碍性|♿️|:wheelchair:|Improving accessibility.
 记录源代码|💡|:bulb:|Documenting source code.
 愉快写代码|🍻|:beers:Writing code drunkenly.
 更新文本和文字|💬|:speech_balloon:|Updating text and literals.
 执行与数据库相关的更改|🗃|:card_file_box:|Performing database related changes.
 添加日志|🔊|:loud_sound:|Adding logs.
 移除日志|🔇|:mute:|Removing logs.
 添加参与者|👥|:busts_in_silhouette:|Adding contributor(s).
 改善用户体验/可用性|🚸|:children_crossing:|Improving user experience / usability.
 进行架构更改|🏗|:building_construction:|Making architectural changes.
 致力于响应式设计|📱|:iphone:|Working on responsive design.
 娱乐的东西|🤡|:clown_face:|Mocking things.
 加一个复活节彩蛋|🥚|:egg:|Adding an easter egg.
 添加或更新.gitignore文件|🙈|:see_no_evil:|Adding or updating a .gitignore file
 添加或更新快照|📸|:camera_flash:|Adding or updating snapshots
 尝试新事物|⚗|:alembic:|Experimenting new things
 改进搜索引擎优化|🔍|:mag:|Improving SEO
 关于Kubernetes的工作|☸️|:wheel_of_dharma:|Work about Kubernetes
 添加或更新类型（流、类型脚本）|🏷️|:label:|Adding or updating types (Flow, TypeScript)
-------------------

**<label style="color:green">借鉴</label>**
   
> <a href="http://gitmoji.carloscuesta.me" target="_blank">gitmoji官网</a>  




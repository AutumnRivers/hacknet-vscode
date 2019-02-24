<p align="center">
    <img src="https://cdn.discordapp.com/attachments/377284586326982666/548680013453590548/GitHubLogo.png"/>
</p>

# Hacknet-VSCode

## 别管官方文档了, 欢迎使用偷懒的法子.

---

[TOC]



---

# 关于这篇文档

​	**这篇文档由 MXYLR 翻译, 原文本参见https://github.com/SmartieCodes/hacknet-vscode, 作者 : Smartie. **

**以下为翻译后的原文 :**

​	制作 Hacknet 的扩展内容 ( 就是创意工坊上面的内容 ) 是一件很麻烦的事情. 你可以问那些作者. 而这个 VS code 的扩展插件就是为了改变这个现状, 从而让制作 Hacknet 的扩展更加简单迅速.

## 写作动机

​	官方的教程很不错, 但是它也有点不好理解. 而这个 VS code 扩展插件会把一些流程简化, 让制作过程变得更简单, 更容易理解. 我希望这个可以让更多人加入制作 Hacknet 扩展的行列, 虽然这不是一个 Extension Creator, 但它向前进了一步 !

# 如何使用这个插件

​	首先你需要在 VS code 中安装这个扩展插件 ( 废话 ), 然后打开一个 XML 文件 ( 用于游戏扩展内容的开发 ), 或者打开一个 TXT 文件 ( 用于黑客脚本的开发 ).

​	当你在编辑的时候, 你可以使用 tab 来跳转到下一个占位符 ( placeholder ). 如果某些东西不是占位符, 那么你应该留下这个东西.

​	如果某个标签或者属性是高亮突出显示的, 这说明你可以安全地删除它. 如果你不想删除它, 当然你也不需要删除它, 你直接按 tab 就行了.

## 预设模板

1. [SequencerAction](#Sequencer 模板)
2. [HacknetMission](#任务模板)
3. StartingAction
4. SabotagedPacemaker
5. SequencerMission

​	这里有些内容并没有列出来, 那是因为这些内容都不足以被视为 " 模板 ". 此扩展程序支持[官方指南](https://steamcommunity.com/sharedfiles/filedetails/?id=914587661)中的任何内容，以及指南中未包含的一些内容！

# 模板

## Sequencer 模板

![](https://cdn.discordapp.com/attachments/453489057117372417/548239180031852554/SequencerExample.gif)

## 数据库模板

![](https://cdn.discordapp.com/attachments/377282421504344065/548321665785004034/DatabaseExample.gif)

## 黑客脚本模板

![](https://cdn.discordapp.com/attachments/377282421504344065/548355937254244371/HackerScriptExample.gif)

## 任务模板

![](https://cdn.discordapp.com/attachments/377284586326982666/548712683260608547/MissionExample.gif)

# 安装这个插件

1.[下载最新版本的插件](https://www.github.com/SmartieCodes/hacknet-vscode/releases)

2.跟着这个指南 : ![](https://cdn.discordapp.com/attachments/377284586326982666/549048572545335296/InstallationExample.gif)

如果你不喜欢手动操作, [你可以直接在 VS code 中安装这个插件](https://marketplace.visualstudio.com/items?itemName=Smartie.hacknet-vscode)

# 直接编译源代码

1. 克隆这个 repo
2. 安装`vsce`, 如果你还没有安装的话
3. 如果你想在里面加点东西, 记得把你想加的放到`package.json`中
4. 在根目录中运行`vsce package`
5. 给这个 VSIX 文件随便起个名字
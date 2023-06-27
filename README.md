<h1 align="center">网盘快开助手</h1>
网盘快开助手可以快速打开鼠标选中文本（背景为蓝色）中的网盘链接，并自动解析和记忆提取码和解压密码
<p align="center">
  <img src="https://img.shields.io/badge/TamperMonkey-v4.13-brightgreen.svg" alt="tampermonkey">
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-lightgrey.svg" alt="LICENSE">
  </a>
  <img src="https://img.shields.io/badge/Chrome-≥76.0-brightgreen.svg" alt="chrome">
  <img src="https://img.shields.io/badge/Edge-≥88.0-brightgreen.svg" alt="edge">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Mac%20%7C%20Linux-blue.svg" alt="platform">
</p>


划一划，快速打开文本中的网盘链接，支持20+网盘，能自动提取提取码和解压密码。同时为了防止忘记链接相关信息，还会整合提取码和解压密码在链接里面，更有解压密码提示助手，在浏览器的历史记录里面打开，就会跳出提醒框，一键复制解压密码！！！。以及有分享的KK链接，要说的都在链接里面，插件全帮你搞定，直接网址打开无需多言（对方也要装网盘快开插件才行）。还有前后台打开模式，快开和弹窗模式，设置最适合自己的。沉浸式上网冲浪！

油猴下载地址：[https://greasyfork.org/zh-CN/scripts/460184](https://greasyfork.org/zh-CN/scripts/460184)

脚本视频演示：[https://www.acfun.cn/v/ac40763378](https://www.acfun.cn/v/ac40763378)

目前简单测试解压码提示可用的有：
<font color="red">**百度网盘，蓝奏云，123云盘, 夸克网盘**</font>

> 其他的网盘因为没有相应链接，所以可能支持度不够，但还是能用的，自动填写提取码提交什么的，解压码提示会在后续时间里慢慢更新(先用着吧，有问题反馈)



## 🚀KK链接
包含了提取码和解压密码的链接，脚本会读取里面的信息并自动填写提取码，提示解压密码（如果有的话）
独特的机制让浏览器的历史纪录无论何时打开，都会弹出解压密码，历史记录里面选中打开链接，还是会提示解压密码！
这下不用再翻来覆去的找了

分享给安装了本插件的他人，无论是直接在地址栏粘贴，还是使用快捷键都会自动识别。


## ⌨快捷键操作
Ctrl+V：
    识别当前粘贴板中的内容
    应用场景：快速将在一些聊天工具中的复制的内容识别出来，省去手动输入的烦恼！

Enter & Esc
    Enter 键打开链接、复制KK链接，Esc 关闭
    应用场景：对弹窗的快速操作，左边Enter，右边Esc


## ⚙️设置讲解
点击右上角插件油猴的图标，会弹出菜单，脚本内有设置面板，点击设置进入
弹出设置面板，点击下拉框进行切换!

---

### 插件运行模式

🕞快开模式：
    划一下，马上打开，不用点击，懒人专用（默认）
    但是在快开模式中不方便进行选中要识别链接的复制
    所以设置了单独的弹窗，方便复制KK链接。

🚟弹窗模式：
    划一下，弹窗会提示你要不要现在打开
    该模式下方便复制链接的文本。

---

### 快开模式显示复制弹窗
可以设置在快开模式中设置单独的复制窗口，因为快开模式不进行弹窗

---

### 新窗口打开方式
新窗口打开：在新的页面打开
后台打开：在后台打开，当前页面不变。沉浸式的逛论坛看帖子

---

### 选中链接后
选中链接后->自动复制->自动复制到剪切板

选中链接后->取消选中状态
默认选中链接后取消选中的状态，也就是划一划文本的蓝色背景
设置取消后会遗留，方便进行复制等操作

---

## 题外话，感谢支持
本来是想学习JS进行逆向的，网上找了教程后觉得还是不会写，就想到了从插件进行学习
边学习边验证融合自己的想法，代码里面有大量注释
非常感谢[油小猴]('https://github.com/syhyz1990/panAI')的项目！！！我学习到了很多


## 更新历史
v1.1.8
<br>修复 1.1.7版本更新后本地缓存未进行验证导致的网址问题
<br>修复 一些懒得写的凑数提取码导致提取失败的问题
<br>新增 夸克网盘自动提取的支持
<br>新增 彩云网盘自动提取的支持
<br>新增 说明文档中关于设置的解释
<br>预告 因为当前脚本不能满足一些使用，将进行大量的重构

v1.1.7
<br>修复 1.1.6版本手误导致未更新的Bug
<br>更改 部分样式

v1.1.6
<br>修复 Bug

v1.1.5
<br>修复 部分情况下无法获取提取码的问题
<br>修复 部分情况不弹窗提示解压密码的问题
<br>修复 部分链接自动打开跳转问题
<br>优化 README.md文档

v1.1.4
<br>优化 设置中的文本显示，更加明了
<br>修复 文本过滤逻辑，能更好的识别了

v1.1.3
<br>新增 设置中新增可选是否在选中链接的时候不失焦（之前是主动失焦）

v1.1.2
<br>新增 设置中可选识别时是否自动复制到剪贴板
<br>更改 部分样式

v1.1.1
<br>修复 打开其他网盘例如蓝奏云链接也跳出解压密码框的问题
<br>修复 不以空格为结尾的解压密码不匹配的问题

v1.1.0 重大更新
<br>修复 commonAncestor在特定情况下的报错，以及不解析的问题
<br>修复 百度强制刷新以后提示框不可见和链接改动导致在历史记录中打开链接不提示解压密码等问题。！！！
<br>修复 KK链接的复制粘贴错误
<br>修复 点击按钮无法复制到粘贴板的错误
<br>修复 其他插件也使用了swal2后，显示样式会被改变的问题
<br>修复 因为会识别并清空所以无法粘贴网盘链接的问题
<br>修改 大量使用逻辑，快捷键操作统一，并更改了复制按钮的颜色和大小样式
<br>更新 README.md 文件的大量文本，更加详细的说明
<br>新增 快开模式弹出复制提示框的选项
<br>新增 可以对解压码123465这样的文本提取出解压码了
<br>~~新增 设置面板中，本地缓存链接最大值滑动调整条~~(搁置)
<br>~~新增 本地缓存链接，以及读取等方法。~~(搁置)

v1.0.1 
修改了自动输入网盘提取码后无法点击的问题，增加了md文件的描述，忘记说热键功能了。
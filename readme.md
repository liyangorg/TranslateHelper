# Chrome 浏览器 插件

## 插件名

翻译助手 TranslateHelper

## 用途

在常见的网页翻译网页的页面上，提供如下方便实用小功能：

1. 点击“除换行”按钮，可自动去除待翻译文本中的换行符(两个空格会替换成一个空格)。
2. 可设置“除换行”按钮的键盘快捷键。
3. 点击“复制”按钮，一键复制翻译结果。
4. 翻译网页上按下 backspace 键，焦点将回到原文输入框。
5. 按下 tab 键，输入框的发音按钮自动获取焦点，此时再按下 enter 键，即可发音。此处只针对原文输入框。
6. 同时按下 shift 和 backspace 键（应先按 shift 键），可直接清空原文输入框内容。

## 可使用的网页翻译页面

1. 百度翻译：https://fanyi.baidu.com/
2. 谷歌翻译：https://translate.google.cn/、https://translate.google.com.hk/、https://translate.google.com
3. 有道翻译：http://fanyi.youdao.com/
4. 必应翻译：https://cn.bing.com/translator/

## 在线安装

Chrome 网上应用店 [网络安装](https://chrome.google.com/webstore/detail/%E7%BF%BB%E8%AF%91%E5%8A%A9%E6%89%8B/ldhdmpimmbbjemmbklofidofnkgpakaa)

## 本地安装

在 Github 上[获取本插件](https://github.com/And-ZJ/TranslateHelper)

本安装方法，可能不适合最新版浏览器，但设置起来大同小异，请耐心设置

针对谷歌浏览器的安装方法：

1. 单击右上侧“三点”选项按钮
2. 选择“更多工具”-->“拓展程序”
3. 勾选页面上方“开发者模式”
4. 点击“加载已解压的拓展程序”
5. 选择本文件夹所在目录（或者是选中 manifest.json 文件）
6. 此时本插件已可以在上述页面（已打开的页面需要刷新）使用

针对QQ浏览器的设置方法（相关翻译页面需运行在极速模式下）

1. 打开QQ浏览器，进入“设置”，左侧选择“我的应用”图标。
2. 上方选择“管理我的应用”。
3. 右侧勾中“开发者模式”。
4. 左侧选择“加载已解压的拓展程序”，弹出文件夹选择框。
5. 选择本插件所在的文件夹，点击“确定”即可.

其他可使用 Chrome 插件的浏览器设置类似（显然不支持 Microsoft Edge 或 IE 类浏览器）。

## 插件设置

可进入“选项”界面进行设置。选项进入方法：右键点击本插件图标(图标一般在浏览器右上角)，选择“选项”即可。

目前选项中，可选择启用上述功能。

## 注意事项

 1. 本地安装启用开发者模式后，每次打开谷歌浏览器，可能会提示:

    ​	“请停用以开发者模式运行的拓展程序”等内容。

    ​	这是正常现象，不是本插件有任何危害计算机或浏览器或网页的问题。

    ​	您可以点击“x”按钮，不理会此消息。

    ​	也可以在需要时去“拓展程序”中，启用本插件， 而在不需要使用时，停止本插件。

    ​	若从 Chrome 网上应用店 安装本插件，则并不需要启动开发者模式，也不会有此提示。

## 已知 Bug

1. 谷歌翻译界面有时候存在无法出现“除换行”按钮的情况，暂不清楚原因。
       可右键点击本插件图标，选择“选项”，选择不同的“嵌入模式”或“版本”。
       若上述方法不能解决问题，可联系作者，或查看Github页面是否已更新版本。
2. 谷歌翻译页面由于网络原因加载时间过长时，偶尔出现按钮不出现，无法使用的情况。
       暂不清楚原因。请刷新页面重试。

## 不完善之处

1. 使用复制功能时，若翻译结果中存在多行，则复制结果里会多出换行。
       此复制功能采用 clipboard.js 实现，该库的原生功能会造成此效果，暂没有解决。
2. 若输入文本含有中文，则将换行符全部删除会导致部分英文恰好存在换行时，也被删除，而不是替换成空格。
3. 如果原文含有 tab，tab 并不会被删除。

## 使用到的其他库

1. [jquery](https://github.com/jquery/jquery)
2. [clipboard](https://github.com/zenorocha/clipboard.js)
3. [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys)
4. [bootstrap](https://github.com/twbs/bootstrap)

也许有遗漏，在此全部感谢。

## 声明

1. 本插件开源，仅限学习交流，例如学习插件的简易开发。
2. 如使用本插件进行不当行为，本人不承担责任。
3. 如对上述网站构成侵权，请立即使用下方联系方式进行联系删除。
4. 本插件不采集任何个人或团体隐私信息，不使用网络。
5. 从 Chrome 网上应用店 可免费获取本插件内容。
6. 如需联系作者（例如：不能使用或出错了），可给下方的邮箱发邮件。

## 联系作者

And_ZJ

ZJ.Cosmos@gmail.com

## 更新日志

2019-10-13

    1. 已发布到 Chrome 网上应用店。采用非公开，仅通过链接进入的方式进行发布。
       2. 更新 readme，并删除多余日志。

2019-06-25

1. 版本 0.7
2. 必应翻译网页也可以使用本插件了.

2019-04-01

1. 版本 0.6.1
2. 点击“除换行”后，会给原文输入框最后添加一个换行符，方便在后面粘贴新的内容。

2019-03-31

1. 版本 0.6
2. 添加“复制”按钮，可复制翻译结果（某些页面自带，某些没有）。
3. 结构再次重排（强迫症555）
4. 如果输入框文字中，含有中文，则将换行符去除（之前是默认都替换成空格）。此处会引入问题，以后修复。

2018-11-29

1. 版本 0.5

2. 今天发现谷歌翻译所有网页又改版了，晕，为了防止它又改回去，导致本软件频繁更改，于是对本插件进行了重大升级。

3. 新增“选项”，可在选项中，设置启用不同的功能，使用不同“嵌入模式”或选择不同的“版本”。

   如果网页改回去了，“版本”中选择“旧版”。

   如果“除换行”不能出现，尝试使用不同的“嵌入模式”。

4. 新增“除换行”功能的快捷键，并且可设置快捷键。若“除换行”因BUG不能出现，快捷键还是可以用的。
   如果快捷键不起作用，可选择不同的“版本”，然后重试。

5. 默认只启用“除换行”功能和“除换行”功能的快捷键。

6. 添加背景页，在翻译界面图标会高亮（并不明显）。
如果您在安装和使用“眼不见心不烦”插件的过程中遇到问题，请先在本文中查找是否有您的问题；如果您遇到的问题不在其中，请在插件的 [Issue Tracker](http://code.google.com/p/weibo-content-filter/issues) 中报告，或联系作者 [@富平侯](http://weibo.com/salviati)。**在本文评论中提出的问题不会得到回复。**


---




# 提问相关 #

## Q001：插件的某项功能似乎出了问题，我应该如何向作者报告？ ##

插件的运行环境千差万别，新浪微博在不停地发生改变，插件作者也只是水平有限的业余开发者，因此总会出现各式各样的问题。作者已经将常见的问题整理在本文档中，如果您遇到了本文档中 **未列出** 的问题，欢迎您及时向作者反馈。

请注意，“插件不能用啊”、“插件好像失效了”之类过于模糊的描述无助于解决您的问题。在报告问题时，请您提供尽可能多的信息，以便让作者更容易确定问题所在：

  1. 您正在使用的浏览器及版本（注意：作者只对Firefox与Chrome提供支持，详见本文Q101：“眼不见心不烦”支持哪些浏览器？）
  1. 您正在使用的“眼不见心不烦”插件版本
  1. 插件导出设置（插件设置窗口→设置，请用私信附件发送）
  1. 问题的具体表现（与预期不符之处）
  1. 问题的重现步骤（如何操作可以**确保**重现该问题）

## Q002：我的新浪微博页面上出现了新的模块（或者某个应该被屏蔽的模块未被屏蔽）怎么办？ ##

新浪微博的版面经常发生各种用户肉眼可见或不可见的改变，这可能导致页面上出现新的模块，或者插件对原有模块的屏蔽失效。

出现此类问题时，**请先确认该模块的对应的选项是否已经存在并被选中**；一个简单的验证方法是选择插件当前可以屏蔽的所有模块（插件设置窗口→模块→全选），如果目标模块消失，则说明是您漏选了对应选项。

如果全选屏蔽模块仍不能去除该模块，请您将其报告给作者。由于新浪微博通常会将新的功能投放给少数用户进行测试，您看到的页面版式很可能并不是作者看到的样子，因此请**务必将模块所在页面另存为html（Ctrl+S）用私信附件发给作者 [@富平侯](http://weibo.com/salviati)，而不要只提供一张模块的截图。**

## Q003：我希望插件能够增加某项功能，应该做些什么？ ##

作者欢迎您提出对新功能的需求，但请注意：

  1. 相比增加新功能，作者更乐于修正插件的错误，以及除去新浪微博的某些民愤极大的新功能和模块（根据作者个人观感和微博搜索判断）。
  1. 过于个性化的功能建议一般不会被采纳。
  1. “眼不见心不烦”的基本理念是给日益臃肿的新浪微博做减法：简化用户操作，减少来自新浪微博本身的干扰，提高信息的质量和摄取效率。违背这一理念的新功能需求通常会被作者谢绝。

# 安装相关 #

## Q101：“眼不见心不烦”支持哪些浏览器？ ##

作者提供支持的浏览器：
  * [Chrome](http://www.google.com/chrome)（v20及以上版本）：在 [Chrome应用商店](https://chrome.google.com/webstore/detail/aognaapdfnnldnjglanfbbklaakbpejm) 安装
  * [Firefox](http://firefox.com.cn/)：需要安装 [Greasemonkey](https://addons.mozilla.org/zh-CN/firefox/addon/greasemonkey/)

作者未明确支持，但有用户报告可以安装使用：
  * 其它基于 Chromium 的浏览器（如 [360极速浏览器](http://chrome.360.cn/)、[猎豹浏览器](http://liebao.cn/)）：安装方法同 Chrome
  * [遨游浏览器](http://www.maxthon.cn/)：需要安装 [暴力猴](http://extension.maxthon.cn/detail/index.php?view_id=1680) （鸣谢 [@画中有话](http://weibo.com/208078910)）
  * [搜狗浏览器](http://ie.sogou.com/)：需要安装 [Tampermonkey](http://ie.sogou.com/tools/tool_1987.html) （请参考 [@搜狗浏览器技术支持](http://e.weibo.com/1975501395/z8uRmc2lp) 提供的教程）
  * [Opera](http://www.opera.com/)：需要安装 [Violent monkey](https://addons.opera.com/zh-cn/extensions/details/violent-monkey)
  * [Safari](http://www.apple.com.cn/safari/)：需要安装 [GreaseKit](http://8-p.info/greasekit/) 或 [NinjaKit](https://github.com/os0x/NinjaKit)
注意：对于 Chrome 与 Firefox 以外的浏览器，作者并不保证插件始终可以在这些浏览器上使用，也不会提供技术支持。

此外，由于“眼不见心不烦”是浏览器插件，从技术上讲并无可能直接移植到移动客户端（如新浪微博 iPhone/iPad 版、Android版、Weico等），所以请勿向作者询问“何时能推出手机版”之类的问题。部分非官方微博客户端具有屏蔽关键词、用户的功能，如 [@Moke\_墨客](http://weibo.com/u/2092187763)（[iOS](https://itunes.apple.com/cn/app/moke/id510355161?mt=8)）和 [@四次元App](http://weibo.com/u/2984891190)（[Android](https://play.google.com/store/apps/details?id=org.qii.weiciyuan)）。

## Q102：Chrome安装插件时提示“只可添加来自Chrome网上应用店的扩展程序、应用和用户脚本” ##

Chrome 用户请勿在 [插件主页](https://userscripts.org/scripts/show/114087) 直接点击 Install 按钮，请转到 [Chrome应用商店](https://chrome.google.com/webstore/detail/aognaapdfnnldnjglanfbbklaakbpejm) 安装“眼不见心不烦”。扩展版本的“眼不见心不烦”具有 Chrome 浏览器的一些专属功能（自动升级、自动同步插件设置等）。

如果您对 Chrome 扩展版本有疑虑，请参考 Q105 与 Q106.

## Q103：Firefox安装插件时只显示一片“乱码” ##

请确认 [Greasemonkey](https://addons.mozilla.org/zh-CN/firefox/addon/greasemonkey/) 附件组件已经安装并正确启用（“工具”菜单->Greasemonkey->“启用”）。

## Q104：使用“眼不见心不烦”是否有隐私风险？ ##

“眼不见心不烦”对微博内容的分析和屏蔽是即时进行的，**作者承诺不会收集用户的任何个人数据**。在使用 Chrome 的自动同步功能时，您的设置会上传到 Google 的服务器，作者是看不到的。插件的全部源代码都是公开的（目前托管于 [Google Code](https://code.google.com/p/weibo-content-filter/source/browse)），并无做手脚的余地，请放心使用。

插件在本地储存的内容仅限于插件的相关设置（关键词、屏蔽模块等），这些设置并未加密，其他人使用您的浏览器时有可能看到您的设置（利用 [Firebug](http://getfirebug.com/) 或 [Chrome开发人员工具](https://developers.google.com/chrome-developer-tools/) 查看 DOM Storage）。

## Q105：插件的Chrome扩展版与脚本版有何区别，是否会占用更多资源？ ##

请注意：并不是所有 Chrome 扩展都会常驻后台并占用内存，只有那些使用了 [Background Page](http://developer.chrome.com/extensions/background_pages.html) 或 [Event Page](http://developer.chrome.com/extensions/background_pages.html) 的 Chrome 扩展才会如此。

“眼不见心不烦”的 Chrome 扩展版本已经考虑到了资源占用的问题，目前只使用了 [Content Script](http://developer.chrome.com/extensions/content_scripts.html) 把脚本版本包装起来，程序只在微博页面打开的时候才会载入，资源占用和脚本版本是完全一样的，您可以使用 Chrome 的“查看后台网页”（Shift+Esc）功能确认这一点。通过包装为扩展版本，插件得以使用 Chrome 扩展才可以使用的一些特殊功能（如设置同步）。

## Q106：为什么要提示正在使用脚本版的Chrome用户改用扩展版？ ##

由于历史原因，“眼不见心不烦”插件在 Chrome 上有三种方式存在：

  1. 直接安装的脚本版（“扩展程序”列表中可见）
  1. 通过 [Tampermonkey](http://tampermonkey.net/) 安装的脚本版（“扩展程序”列表中不可见）
  1. 通过 [Chrome 应用商店](https://chrome.google.com/webstore/detail/aognaapdfnnldnjglanfbbklaakbpejm) 安装的扩展版（“扩展程序”列表中可见）

长期以来插件只有1和2两种方式。但是从2013年3月的 Chrome 27.0.1447.3 开始，Chrome 修复了插件一直以来用于获取 unsafeWindow 的一个 [安全漏洞](http://crbug.com/222652)，导致脚本版无法在 Chrome 27 及以上版本工作。作者于是重写了代码并从 v1.1 开始在 Chrome 应用商店上架（方式3），并逐步停止对方式1和2的支持。如果您是脚本版（方式1或方式2）用户，可以直接卸载并到 Chrome 应用商店安装扩展版，插件设置不会丢失。扩展版可以在不同设备之间同步插件设置，资源占用也并不比脚本版更多（详见本文Q105：插件的Chrome扩展版与脚本版有何区别，是否会占用更多资源？）。

对于 Chrome 27 及以上版本，三种方式的支持情况如下：

  1. 直接安装的脚本版：**停止支持**
  1. 通过 Tampermonkey 安装的脚本版：**不提供支持，仅推荐高级用户使用**；需要 Tampermonkey 3.0 以上版本并启用 [unsafeWindow 获取](http://tampermonkey.net/faq.php?ext=dhdg#Q404)
  1. 通过 Chrome 应用商店安装的扩展版：**长期支持**

## Q107：如何卸载“眼不见心不烦”？ ##

  * Chrome：工具→扩展程序（或在地址栏中输入chrome://extensions），找到“眼不见心不烦”，取消选中“已启用”（禁用插件）或点击右侧的垃圾桶图标（卸载插件）；
  * Firefox：工具→Greasemonkey→管理用户脚本，找到“眼不见心不烦”并点击右侧的“禁用”或“移除”。

作者仅知晓插件在Chrome与Firefox浏览器中的卸载方式，其它浏览器的卸载方式请查看该浏览器的使用帮助，或咨询其客服。

## Q108：无法安装，错误信息为“程序包无效。详细信息：Cannot load extension with file or directory name _. Filenames starting with "_" are reserved for use by the system.” ##

这个问题仅出现于 Chrome 34 以下版本，或者采用了 Chrome 34 以下版本内核的浏览器，详见：
https://code.google.com/p/chromium/issues/detail?id=369895
升级到最新版本的 Chrome 可以解决此问题。


---


# 设置相关 #

## Q201：安装后如何对“眼不见心不烦”进行设置？ ##

“眼不见心不烦”的设置按钮的位置在：
  * “我的首页”：微博发布栏下方，“全部微博”、“我的微群”、“猜你喜欢”右侧
  * 用户主页：“个人照片”下方，“微博”“心情”“他/她的资料”标签栏右侧
  * 浮动设置按钮（可以在“高级”中关闭）：右边栏右侧“返回顶部”按钮下方的“★”

具体位置请查看 [插件主页](http://userscripts.org/scripts/show/114087) 上的截图。点击设置按钮打开设置窗口，设置完成后点击“确定”即可生效。

## Q202：为什么安装后在页面上找不到“眼不见心不烦”的设置按钮？ ##

如果您是 Firefox 用户，请先确认 [Greasemonkey](https://addons.mozilla.org/zh-CN/firefox/addon/greasemonkey/) 附加组件已正确安装并已启用（“工具”菜单->“Greasemonkey”->“启用”）。

此外，如果您安装了其它新浪微博的非官方增强插件，本插件可能会失效。由于扩展众多，作者无力保证插件与其它扩展的兼容性。

如果并无以上两点问题，而且问题只是偶尔出现，请您刷新页面再试。由于新浪微博采用 [BigPipe](http://www.facebook.com/note.php?note_id=389414033919) 技术，不同模块载入的顺序并不确定，在某些特殊情况下可能导致插件暂时失效，一般刷新页面即可解决。

## Q203：为什么我的设置会莫名其妙地丢失，或者无法保存更改？ ##

此问题仅出现在 Chrome 上。如果该问题只是随机出现，不能通过一定的步骤【确保】重现，请尝试刷新页面；如果该问题每次都会出现（如每次刷新页面时都会清空设置、每次点击插件设置窗口的“确定”后设置都未被保存），请按F12键叫出调试窗口，切换到Console，刷新页面，观察调试窗口中是否会出现类似下面的红色错误信息：

```
storage.get: Failed to open database: Corruption: 1 missing files; ... chrome-extension://aognaapdfnnldnjglanfbbklaakbpejm/main.js
```

如果出现类似这样的错误信息，则说明是Chrome的数据库损坏。这是一个尚未修复的 [Chromium bug](https://code.google.com/p/chromium/issues/detail?id=261623)，暂时可以通过以下方式解决（仅限Windows）：关闭Chrome，然后删除以下两个文件夹：

  * %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\Local Extension Settings\aognaapdfnnldnjglanfbbklaakbpejm
  * %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\Sync Extension Settings\aognaapdfnnldnjglanfbbklaakbpejm

以上操作仅会删除“眼不见心不烦”插件的数据库（“aognaapdfnnldnjglanfbbklaakbpejm”是插件的GUID），不会影响其它个人数据与插件设置。

作者建议您使用设置导出功能及时保存设置（需v0.8及以上版本），这样在设置丢失时可以迅速恢复。

## Q204：我选择了“自动同步设置”，为什么设置没有被同步？ ##

原因可能有以下两种：

  1. 未 [登录Chrome浏览器](http://support.google.com/chrome/bin/answer.py?hl=zh-Hans&answer=185277) 或使用了不同的Google账号登录：插件设置仅在 **开启了“自动同步设置”选项** 并 **使用同一Google账户登录** 的不同设备之间同步。
  1. 新浪微博随 Chrome 启动（如“固定标签页”）：Chrome启动后会立即开始同步设置，但这一过程需要一定时间。如果过早打开微博页面，设置可能尚未同步完成，读取的仍为上次储存的设置。此时不要对插件进行设置操作（包括切换极简阅读模式等，以免本地设置覆盖云端设置），过一段时间刷新微博页面让插件重新载入云端设置即可。

【注意】如果您曾经使用过“眼不见心不烦”低于 v1.1 的版本，且微博随 Chrome 启动，可能会导致 **首次运行新版插件时** 本地设置覆盖先前其它设备上传到云端的设置：由于“自动同步设置”功能默认开启，如果新版插件首次运行时同步尚未完成，插件会认为云端还没有设置，因此会把本地设置上传到云端。

## Q205：我在Chrome应用商店中安装了插件，为什么有时插件会自动消失（在插件列表中找不到）？ ##

作为浏览器插件，“眼不见心不烦”并没有卸载自身的权限。您很可能启用了 Chrome 与 Google 账户的同步，并且同步内容包括各种插件及其设置内容；因网络连接等原因导致同步失败时，可能导致本插件的自动消失。您可以尝试以下解决方案：

  * 关闭其它 Chrome 运行实例（包括在其它计算机上正在运行的、与同一个 Google 账户同步的 Chrome 实例），只保留一个 Chrome 窗口；在 Chrome 设置中断开与 Google 账户的连接，在 [Chrome应用商店](https://chrome.google.com/webstore/detail/aognaapdfnnldnjglanfbbklaakbpejm) 中重新安装插件，然后重新连接 Google 账户。
  * 在 Chrome 设置中断开与 Google 账户的连接，或者在高级同步设置中取消选中“扩展程序”；**注意这样将停止本机的 Chrome 与其它计算机的同步**。
  * 如果您之前没有将 Chrome 与 Google 账户同步，[启用同步可能可以解决问题](http://rendezvouswithpavan.wordpress.com/2012/12/19/are-your-google-chrome-extensions-disappearing-out-of-nowhere-heres-a-temporary-fix)。
  * 如果不只是“眼不见心不烦”而是 **全部** 已安装插件无故消失，请 [创建新的浏览器用户配置文件](https://support.google.com/chrome/answer/142059)。


---


# 使用相关 #

## Q301：“眼不见心不烦”改造版面的效果（透明背景、极简阅读模式、去除模块等）只有我自己看得到么？ ##

是的，甚至您自己也不一定看得到。换一个没有安装“眼不见心不烦”插件的浏览器，您看到的都是原来的样子。

“眼不见心不烦”是浏览器插件，修改的只是网页在这些浏览器上的表现形式，网页本身的内容并没有变化，因此在没有安装插件的浏览器上看都是原样。

由于网页内容是从新浪微博服务器上获得的，因此可以负责任地说，**任何浏览器插件都不可能做到让改造后的页面在所有人、所有浏览器看来都一样**，这种功能只能由新浪微博官方实现。“眼不见心不烦”只能让您自己使用微博时更舒服一些而已。

## Q302：不小心点了某项设置，页面工具栏和边栏都消失了，如何恢复？ ##

这是插件的“极简阅读模式”，在此模式下只有微博时间线可见，其它模块均被隐藏。首次进入极简阅读模式时插件会给出提示。

您可以直接按【F8】键切换极简阅读模式，也可以在插件设置窗口（在极简阅读模式下可以通过点击“返回顶部”浮动按钮下面的星星【★】按钮进入）的“改造版面”中关闭“极简阅读模式”。

## Q303：“眼不见心不烦”的关键词屏蔽是怎样工作的？ ##

一条微博的正文（包括转发内容）均在扫描范围之列，转发内容与正文用“////”隔开，“眼不见心不烦”会自动为微博发布者的ID前加上“@”。比如用户 @路人甲 原创的一条微博被 @路人乙 转发，实际进行关键词扫描的内容为：

```
@路人乙: [转发内容]////@路人甲: [转发原帖内容]
```

因此如果将“@路人甲”设为屏蔽关键词，可以屏蔽 @路人甲 本人发布的微博、别人转发ta的微博以及任何人提到ta的微博；将“////@路人甲”设为关键词可以屏蔽任何人转发的 @路人甲 的 **原创** 微博。

## Q304：为什么我设置的关键词没有被屏蔽？ ##

有很多用户曾经报告设置的关键词并未被屏蔽，经检查，绝大多数都是用户自己的设置问题，最常见的原因如下：
  * 选择了“高级”->“暂停屏蔽”；
  * 微博内容包含白名单中的关键词（白名单优先级最高）；
  * 关键词的全半角、简繁体与微博内容不一致；
  * 关键词中有多余的符号。

如果某条应该被屏蔽的微博没有被屏蔽，而且不存在以上问题，请您将插件的设置（利用插件设置中的导出功能）和未被屏蔽的微博地址私信给作者 [@富平侯](http://weibo.com/salviati)，作者会进行检查。此类问题请勿在 [Issue Tracker](http://code.google.com/p/weibo-content-filter/issues) 中报告，以免泄露您的隐私。

## Q305：如何使用正则表达式过滤微博？ ##

正则表达式是威力强大的文本分析工具，可以更有针对性地过滤微博。被斜杠（/）包围的关键词将被视为正则表达式，如下面的正则表达式：
```
/(转发|评论)此微博.*就有机会/
```
将匹配所有 **同时** 包含“转发此微博”（或“评论此微博”）与“就有机会”的微博（常见于抽奖微博）。

如果您不熟悉正则表达式，推荐您阅读 [《揭开正则表达式的神秘面纱》](http://www.regexlab.com/zh/regref.htm) 。

## Q306：如何设置区分大小写的关键词？ ##

可以通过正则表达式方式设置关键词，如/abc/只匹配小写的abc，其它形式如Abc, aBC等均不匹配。

## Q307：如何设置带有分隔符（空格）的关键词？ ##

如果您使用的是 v1.0.4 及以上版本，可以将整个关键词置于一对半角双引号之内（如"I love you"），其中的空格不会被视为分隔符，而作为关键词的一部分。

您还可以通过正则表达式方式设置关键词，空格用\s代替，如/I\slove\syou/.

## Q308：如何屏蔽同时包含多个关键词的微博？ ##

关键词之间是“或”逻辑，某条微博只要包含黑名单中的 **任何一个** 关键词就会被屏蔽；如果您希望某条微博同时包含多个关键词时才被屏蔽（“与”逻辑），可以将这些关键词用加号（+）连接，如“A+B+C”将匹配同时包含A、B、C的微博，缺少其中任何一个的微博都不匹配。

如果您希望将分隔符（加号）作为关键词的一部分，请使用正则表达式，如关键词“C++”可用正则表达式/C\+\+/匹配。

## Q309：为什么我在插件中屏蔽了某用户，仍能看到别人转发ta的微博？ ##

屏蔽用户功能仅对这些用户**本人原创或直接转发**的微博有效，对间接转发的情况无效。

比如，您只屏蔽了用户A，但如果用户A转发用户B的某条原创微博被您关注的用户C转发（间接转发），那这一条微博仍然会出现在您的 timeline 中。

出现这种情况是因为新浪微博并没有多次转发的追踪机制，间接转发的情况实际是A转发了C的原创微博同时带上了B的转发内容，与A发布了一条@B的微博本质上是一样的。

如果您希望用户A的名字彻底从 timeline 中消失，请将其 ID 设为屏蔽关键词，但如果对方改名就需要重新设置。

## Q310：为什么我屏蔽了指向 taobao.com 的链接，还是会有淘宝广告漏网？ ##

这些淘宝广告的链接并未直接指向 taobao.com，而是采用了与新浪短链接服务（t.cn）类似的短链接重定向，如 [淘宝短网址](http://taourl.com)（taourl.com）和 [第一微博](http://www.dyweibo.com)（dyweibo.com）等。对于这种“二次重定向”的情况，“眼不见心不烦”也无法判断其真实指向的地址，您需要将这些短链接域名都加入屏蔽名单，但这样有误伤非广告链接的可能性。

将鼠标悬停在广告链接上，即可显示其指向的地址，将其域名加入屏蔽名单即可。

## Q311：为什么第一次载入页面时有些本应被屏蔽的微博会短暂显示？ ##

插件在页面完全载入后才会生效，因此第一次载入页面时请稍安勿躁。页面载入完成后，动态载入的内容（如点击“有n条新微博，点击查看”后载入的新微博）则会在显示之前就被处理。

## Q312：如何使用自定义CSS改造页面？ ##

请参考《[使用自定义CSS改造新浪微博页面](CustomCSS.md)》。
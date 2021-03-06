安卓编年史（14）：Android 2.3 Gingerbread——第一次 UI 大变
================================================================================
### 语音操作——口袋里的超级电脑 ###

2010 年 8 月，作为语音搜索应用的一项新功能，“[语音命令][1]”登陆了安卓市场。语音命令允许用户向他们的手机发出语音命令，然后安卓会试着去理解他们并完成任务。像“导航至[地址]”这样的命令会打开谷歌地图并且开始逐向导航至你所陈述的目的地。你还可以仅仅通过语音来发送短信或电子邮件、拨打电话、打开网站、获取方向，或是在地图上查看一个地点。

注：youtube视频地址
<iframe width="500" height="281" frameborder="0" src="http://www.youtube-nocookie.com/embed/gGbYVvU0Z5s?start=0&amp;wmode=transparent" type="text/html" style="display:block"></iframe>

语音命令是谷歌新应用设计哲学的顶峰。语音命令是那时候最先进的语音控制软件，秘密在于谷歌并不在设备上做任运算。一般来说，语音识别是 CPU 密集型任务。实际上，许多语音识别程序仍然有“速度与准确性”设置，用户可以选择他们愿意为语音识别算法运行等待的时间——更多的 CPU 处理意味着更加准确。

谷歌的创新在于没有劳烦手机上能力有限的处理器来进行语音识别运算。当说出一个命令时，用户的声音会被打包并通过互联网发送到谷歌云服务器。在那里，谷歌超算中心的超级计算机分析并解释语音，然后发送回手机。这是很长的一段旅程，但互联网最终还是有足够快的速度在一两秒内完成像这样的任务。

很多人抛出词语“云计算”来表达“所有东西都被存储在服务器上”，但这才是真正的云计算。谷歌在云端进行这些巨量的运算操作，又因为在这个问题上投入了看似荒唐的 CPU 资源数目，所以语音识别准确性的唯一限制就是算法本身了。软件不需要由每个用户独立“训练”，因为所有使用语音操作的人无时不刻都在训练它。借助互联网的力量，安卓在你的口袋里放了一部超级电脑，同时相比于已有的解决方案，把语音识别这个工作量从口袋大小的电脑转移到房间大小的电脑上大大提高了准确性。

语音识别作为谷歌的项目已经有一段时间了，它的出现都是因为一个 800 号码。[1-800-GOOG-411][2]是个谷歌从 2007 年 4 月起开通的免费电话信息服务。它就像 411 信息服务一样工作了多年——用户可以拨打这个号码询问电话号码——但是谷歌免费提供这项服务。查询过程中没有人工的干预，411 服务由语音识别和文本语音转换引擎驱动。在人们教谷歌如何去听之后，又用了三年才有实现语音命令的可能。

语音识别是谷歌长远思考的极佳范例——公司并不怕在一个可能成不了商业产品的项目上投资多年。今天，语音识别驱动的产品遍布谷歌。它被用在谷歌搜索应用的输入，安卓的语音输入，以及 Google.com。同时它还是 Google Glass 和 [Android Wear][3] 的默认输入界面。

谷歌甚至还在输入之外的地方使用语音识别。谷歌的语音识别技术被用在了转述 Youtube 视频上，它能自动生成字幕供听障用户观看。生成的字幕甚至被谷歌做成了索引，所以你可以搜索某句话在视频的哪里说过。语音是许多产品的未来，并且这项长期计划将谷歌带入了屈指可数的拥有自家语音识别服务的公司行列。大部分其它的语音识别产品，像苹果的 Siri 和三星设备，只能使用 Nuance 的语音识别，并且为其支付了授权费。

在计算机听觉系统设立运行之后，谷歌下一步将把这项策略应用到计算机视觉上。这就是为什么像 Google Goggles，Google 图像搜索和 [Project Tango][4] 这样的项目存在的原因。就像 GOOG-411 的那段日子，这些项目还处在早期阶段。当[谷歌的机器人部门][5]造出了机器人，它会需要看和听，谷歌的计算机视觉和听觉项目会给谷歌一个先机。

![Nexus S，第一部三星制造的Nexus手机。](http://cdn.arstechnica.net/wp-content/uploads/2014/03/NS500.png)

*Nexus S，第一部三星制造的 Nexus 手机。*

### Android 2.3 Gingerbread——第一次UI大变 ###

Gingerbread（姜饼人）发布于2010年12月，这已是2.2发布整整七个月之后了。尽管如此，等待是值得的，因为安卓2.3整个系统的每个界面几乎都改变了。这是从安卓0.9最初的样式以来第一次重大的更新。2.3开始了一系列持续的改进，试着将安卓从丑陋的小鸭子变成能承载它自己的合适的样子——从美学角度——来对抗iPhone。

说到苹果，六个月前，它发布了iPhone 4和iOS 4，新增了多任务处理和Facetime视频聊天。微软同样也终于重返这场游戏。微软在2010年11月发布了Windows Phone 7，也进入了智能手机时代。

安卓2.3在界面设计上投入了很多精力，但是由于缺乏方向或设计文档，许多应用仅仅止步于获得了一个新的定制主题而已。一些应用用了更扁平的暗色主题，一些用了充满渐变，活泼的暗色主题，其他应用则是高对比度的白色和绿色组合。尽管2.3并没有做到风格统一，Gingerbread还是完成了让系统几乎每个部分变得更现代化的任务。这同样是件好事，因为下一个手机版安卓要在将近一年后才到来。

Gingerbread的首发设备是Nexus S，谷歌的第二部旗舰设备，并且是第一部由三星生产的Nexus设备。尽管今天我们已经习惯了每年都有更新型号的CPU，那时候可不是这个样子。Nexus S有个1GHz Cortex A8处理器，和Nexus One是一样的。GPU从速度来说略微有所变快。Nexus S稍微比Nexus One大一点，拥有800×480分辨率的AMOLED显示屏。

从参数上来说，Nexus S看起来只是个平淡无奇的升级，但他确实开了安卓的许多先河。Nexus S是谷歌第一部没有MicroSD卡槽的旗舰，板载16GB存储。Nexus One只有512MB存储空间，但它有MicroSD卡槽。移除SD卡槽为用户简化了存储管理——现在只有一个存储地点了——但是影响了高级用户的扩展能力。它是谷歌第一部带有NFC的手机，手机背面的一个特殊芯片能够在和其他NFC芯片接触时传输数据。Nexus S暂时只能读取NFC标签，而不能发送数据。

托Gingerbread中一些升级的福，Nexus S是第一部不带有硬件十字方向键或轨迹球安卓手机之一。Nexus S缩减到只有电源，音量以及四个导航键。Nexus S同时还是如今[疯狂的曲面手机][6]的先驱，因为三星给Nexus S配备了一块略微有些弯曲的玻璃。

![Gingerbread更改了状态栏和壁纸，并且添加了许多新图标。](http://cdn.arstechnica.net/wp-content/uploads/2014/02/appdrawershop.png)
Gingerbread更改了状态栏和壁纸，并且添加了许多新图标。
Ron Amadeo供图

升级过的“Nexus”动态壁纸作为Nexus S的独占发布。这个壁纸基本上和Nexus One的一样，带有带动画轨迹的光点。在Nexus S上，去除了方阵设计，取而代之的是波浪形的蓝/灰色背景。底部dock有了直角和彩色图标。

![新通知面板和菜单。](http://cdn.arstechnica.net/wp-content/uploads/2014/02/32.png)
新通知面板和菜单。
Ron Amadeo供图

状态栏自0.9的首次登场以来终于得到了重制。状态栏从白色渐变变成纯黑，所有图标重绘成了灰色和绿色。所有东西看起来都更加清爽和现代，这要感谢锐角图标设计和高分辨率。最奇怪的决定可能是从状态栏时钟移除了时间段显示以及信号强度那令人疑惑的灰色。尽管灰色被用在状态栏的许多图标上，而且上面截图有四格灰色信号，安卓实际上指示的是没有信号。绿色格表示信号强度，灰色格指示的是“空”信号格。

Gingerbread的状态栏图标同时还作为网络连接的状态指示。如果你的设备连接到了谷歌的服务器，图标会变绿，如果没有谷歌的连接，图标会是白色的。这让你可以在外出时轻松了解你的网络连接状态。

通知面板的设计从安卓1.5的设计改进而来。我们看到UI部分再次从浅色主题变为暗色主题，有个深灰色顶部，黑色背景以及在灰色底色上的黑色文本。

菜单颜色同样变深了，背景从白色变成了带点透明的黑色。菜单图标和背景的对比并没有它应该有的那么强烈，因为灰色图标的颜色和它们在白色背景上的时候是一样的。要求改变颜色意味着每个开发者都得制作新的图标，所以谷歌在黑色背景上使用了先前就有的灰色。这是系统级别的改变，所以这个新菜单会出现在每个应用中。

----------

![Ron Amadeo](http://cdn.arstechnica.net/wp-content//uploads/authors/ron-amadeo-sq.jpg)

[Ron Amadeo][a] / Ron是Ars Technica的评论编缉，专注于安卓系统和谷歌产品。他总是在追寻新鲜事物，还喜欢拆解事物看看它们到底是怎么运作的。

[@RonAmadeo][t]

--------------------------------------------------------------------------------

via: http://arstechnica.com/gadgets/2014/06/building-android-a-40000-word-history-of-googles-mobile-os/14/

译者：[alim0x](https://github.com/alim0x) 校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](http://linux.cn/) 荣誉推出

[1]:http://arstechnica.com/gadgets/2010/08/google-beefs-up-voice-search-mobile-sync/
[2]:http://arstechnica.com/business/2007/04/google-rolls-out-free-411-service/
[3]:http://arstechnica.com/gadgets/2014/03/in-depth-with-android-wear-googles-quantum-leap-of-a-smartwatch-os/
[4]:http://arstechnica.com/gadgets/2014/02/googles-project-tango-is-a-smartphone-with-kinect-style-computer-vision/
[5]:http://arstechnica.com/gadgets/2013/12/google-robots-former-android-chief-will-lead-google-robotics-division/
[6]:http://arstechnica.com/gadgets/2013/12/lg-g-flex-review-form-over-even-basic-function/
[a]:http://arstechnica.com/author/ronamadeo
[t]:https://twitter.com/RonAmadeo

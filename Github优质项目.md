# 摘自HelloGithub公众号

# 魔镜魔镜，今天有雨吗？——GitHub 热点速览 v.21.25                

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V8u15IQ3ib4XITmKYEs7s1SBJvHQE1EiaNF7WaZjLkHKs3PHibxv48GAmkw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

<p style="text-align:center;">作者：HelloGitHub-小鱼干</p>

上周智能驾驶项目的作者曾经做过一个透明小电视机，同透明电视机类似 MagicMirror 也是一个神奇的智能项目，使用它进行模块定制开发，你将拥有一块非常酷炫的智能镜子，你可以在上面看到天气、你终端输出的  HelloWorld 以及其他信息。本周 GitHub Trending  上还有其他有意思的项目，例如，给它一个神秘的字符串它能帮你解析它代表了什么的 pyWhat，还有无代码也能构建自己内部工具的  ToolJet，以及给音视频、图片、文本加点额外数据信息的 AugLy…

以下内容摘录自微博@HelloGitHub 的 GitHub Trending 及 Hacker News 热帖（简称 HN 热帖），选项标准：`新发布` | `实用` | `有趣`，根据项目 release 时间分类，发布时间不超过 14 day 的项目会标注 `New`，无该标志则说明项目 release 超过半月。由于本文篇幅有限，还有部分项目未能在本文展示，望周知 🌝

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V82crn47m1ic9hCUljeiaCekU7coUOMD9wibQxsGibsCtibGFGvA1WnOHB97A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

##  1. 本周特推 

### 1.1 文本识别：pyWhat

**本周 star 增长数：1,700+**

pyWhat 能识别文本背后含义的工具，当你不知道特定一串文本代表什么时，它能快速判断它是否是 email、油管视频编号、手机号  或者是其他信息格式。你给它一个 .pcap 文件或者一段文本，它能告诉你这个文件或是文本代表了什么。同搜索不同，pyWhat  会自动进行文本分断，例如 `5f4dcc3b5aa765d61d8327deb882cf99` 如果没有完全匹配的信息格式，pyWhat 会切断文本进行多个不同字符串长度的完全匹配（参考下图示例）。

> GitHub 地址→https://github.com/bee-san/pyWhat

![图片](https://mmbiz.qpic.cn/mmbiz_gif/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V8v0cEzepMG0VD67Fp5GTBJsMIYRG4E0LD6geMYlVib0m8vtSMyH7OrYA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)

### 1.2 新的建站方式：astro

**本周 star 增长数：800+**

建站方式千千万，为什么要特推下 Astro 呢。它的介绍里有句话 `Keep your eyes to the skies, astronauts!` 我将它理解为 Focus 在你的星辰大海，当然它本身也很优秀。它结合了近十年来的性能最佳实践与面向组件时代的 DX，对它们进行改进，尽量使用少的 JavaScript 来建站。

> GitHub 地址→https://github.com/snowpackjs/astro

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V8LJZvuMWQB6Qps8mXfKamvDlWB0x5kN9OD1EhAYU6mDXnXRvRODcdGQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

##  2. GitHub Trending 周榜 

### 2.1 加点数据：AugLy

**本周 star 增长数：1,500+**

`New` AugLy 是 Facebook 研究所开源的数据增强库，支持语音、文本、视频和图片。如下图所示，使用 AugLy 你可以往图片中增加特定的数据信息。

> GitHub 地址→https://github.com/facebookresearch/AugLy

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V8ichSfR0ELic5pekG3uMic3MFumiaHt1fmpoUAxPwiaEmDAxwbqdMLwX4riaw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.2 零代码构建内部工具：ToolJet

**本周 star 增长数：200+**

ToolJet 一个用于构建和部署内部工具的开源无代码平台。你可以连接数据源，诸如 PostgreSQL、MongoDB、Elasticsearch  这些数据库，也能连接API 端点（ToolJet 支持导入 OpenAPI 规范及 OAuth2 授权）和外部服务（如  Stripe、Slack、Google 表单、Airtable）以及使用内置的 UI 组件构建内部工具。

> GitHub 地址→https://github.com/ToolJet/ToolJet

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V87sKFWEJOibgXNNlZ49mST3kOIlBPEYBFGVkugVB5Iuu2qkQNxcCpN6A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.3 智能镜子：MagicMirror

**本周 star 增长数：400+**

MagicMirror 是一个开源的模块化智能镜像平台。随着可安装模块的增加 MagicMirror 可以让你把你的走廊或浴室的镜子变成你的个人助理。

> GitHub 地址→https://github.com/MichMich/MagicMirror

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V8BZ3icXlVkTW5bosu5x7IqztLic69zcZDWmyr5f8FhEPEmkTK5GiawAnkw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.4 新型 shell：nushell

**本周 star 增长数：2,600+**

nushell 是一个新的 shell 工具，它能详细地罗列你所查看文件、环境等等信息。

> GitHub 地址→https://github.com/nushell/nushell

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V8JL2eYMEr2EFsCsJHic0QpJZNfObibxjiaYtKib7AVfZcXS7vnibCf9jicXwA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.5 面向教师的会议视频工具：nettu-meet 

**本周 star 增长数：100+**

`New` Nettu Meet 是一个面向教师的视频会议系统，你可以用它来共享白板绘制图案，也能共享屏幕、共享文件进行文字聊天。

> GitHub 地址→https://github.com/fmeringdal/nettu-meet

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNPKzfP9n2bOnn1m4dyOz8V8Vo654M9oaa1gY7ObzvuRhEuQjM5SJ4zvLNDkRUicIibILCdO2RoCKUsA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



# 自动驾驶的自行车——GitHub 热点速览 v.21.24                

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2G5zOQwZyxDoFiafggYAHzcq7ygTNyu5Bygcox1eY7J70ByfTGKtdGmA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

<p style="text-align:center;">作者：HelloGitHub-小鱼干</p>

用什么词来概述这周的 GitHub 热点呢？大概是`人工智能是真的神`！它能让 EssayKiller_V2 写出规范的高考作文，工整又对仗，也能用 XUAN-Bike  让自行车名副其实——自动骑行，避让周遭的障碍物，实现无人骑行。而 Jina  则实现了神经搜索即服务，让你分分钟搭建一个自己的搜索服务来检索非结构化的，例如 PDF、音视频等数据。

以下内容摘录自微博@HelloGitHub 的 GitHub Trending 及 Hacker News 热帖（简称 HN 热帖），选项标准：`新发布` | `实用` | `有趣`，根据项目 release 时间分类，发布时间不超过 14 day 的项目会标注 `New`，无该标志则说明项目 release 超过半月。由于本文篇幅有限，还有部分项目未能在本文展示，望周知 🌝

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2ic412QLGm4SLPmhOht2YAgjZSBNrUichpcjBicGfeYaZxW84faJXZJqdw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

##  1. 本周特推 

### 1.1 自行车自动驾驶：XUAN-Bike

**本周 star 增长数：2,500+**

`New` 没错，小鱼干粉的 B 站博主 peng-zhihui 开源了个新的项目——XUAN-Bike  是一个让自行车自动驾驶的项目，加入自动控制系统、传感器、AI  芯片以及注入一点灵魂的感知和控制算法，就可以让你的自行车自动驾驶了，还可以有效地避让障碍物，即便车头挂有重物也能维持本身车子的平衡。不过，唯一缺陷的是，目前这辆车不能载人[手动狗头]，但是作为一个自动驾驶实践玩具它还是很酷炫的。整个项目的设计制作过程可以见视频：【自制】我把自行车做成了 自 动 驾 驶 ！！【硬核】

> GitHub 地址→https://github.com/peng-zhihui/XUAN-Bike

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2XibnVGu8Ck1ZYy3syMGIjsqYa0NWkoEahV0NMLNSJIuxMCbmYxvicMkQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 1.2 macOS 开发环境自动化：mac-dev-playbook

**本周 star 增长数：350+**

Mac Development Ansible Playbook 是一个让你可以通过 Ansible 来自动安装配置 Mac 软件的工具。虽然 macOS 中的一些东西很难自动化，你仍需要手动配置一些文件，但是至少实现了大部分的软件安装部署自动化。

> GitHub 地址→https://github.com/geerlingguy/mac-dev-playbook

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2a2RGS1Ot0SXFMS8X3pn78hS8H1zKUYInNwSPqWFD0GeZQHg3oniaXYQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 1.3 高考作文写作：EssayKiller_V2

因为本周是高考周，所以来推荐一个基于开源 GPT2.0 的初代创作型人工智能——EssayKiller，它是基于 OCR、NLP 领域的最新模型所构建的生成式文本创作 AI  框架，目前第一版 finetune  模型针对高考作文（主要是议论文），可以有效生成符合人类认知的文章，多数文章经过测试可以达到正常高中生及格作文水平。虽然缺少了一点灵魂，但是文笔真的是比我好…

> GitHub 地址→https://github.com/EssayKillerBrain/EssayKiller_V2

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2zPibhDiahLMTwrPKFibtVDIEzLsGfDJEAfyujrdjlzwLtpib624mvzFamQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

##  2. GitHub Trending 周榜 

### 2.1 金庸群侠传 3D 重制版：jynew

**本周 star 增长数：700+**

`New` jynew 是使用 Unity 引擎实现的金庸群侠传 3D 重制版，且支持后续一系列 MOD 和二次开发。

> GitHub 地址→https://github.com/jynew/jynew

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl23cjotLiaSTIA4rhQaIIkpvDXo2TRCVWiaaiags92SL0nCUsZ6oZ1PmbBg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.2 Python GUI 界面帮手：Tkinter-Designer

**本周 star 增长数：1,100+**

Tkinter-Designer 是一个让你通过拖拽即可实现一个高颜值 Tkinter GUI 的工具，它通过知名设计软件 Figma 的 API 接口来分析设计文件及创建 GUI 所需的代码和文件。

> GitHub 地址→https://github.com/ParthJadhav/Tkinter-Designer

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2AQQYvVYPtyprauVt5n8faQqMmTfib5GlTykbN2Yiatl9AoSzk2lagmrw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.3 搜索即服务：jina

**本周 star 增长数：950+**

Jina 让你在几分钟内即可构建基于深度学习的搜索即服务。它具有以下特性：

- 支持所有数据类型：大规模的索引数据及查询诸如视频、图像、源代码等非结构化数据；
- 云原生：一开始就采用分布式架构，支持容器化、分布式、数据流、并发及 REST/gRPC/WebSocket 等异步调度方式；
- 省时：你几分钟之内即可搭建一个搜索服务；

> GitHub 地址→https://github.com/jina-ai/jina

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2cDpCII7pNjOrKXF9I1m50rffp4w4IQs18fyFhjyyldhd0WoL54L6CQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.4 Infra 即 Code：terraform

**本周 star 增长数：550+**

Terraform 是由 HashiCorp 开源的基础架构即代码软件工具，可将 API 编码为声明性配置文件，该文件可以在团队成员之间共享，作为代码、编辑、审核和版本化。

> GitHub 地址→https://github.com/hashicorp/terraform

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2ulWspGcPJIEiapF51KNkwuDTaiaIaHBmddsfcUGOdNZqaJ5iasCI05zyw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2.5 文档工具：docz

**本周 star 增长数：800+**

Docz 是方便你记录事件的工具，你使用 MDX 即可快速地创建一个实时加载、搜索友好、生产就绪的文档站点，如果你需要定制化交互的话，你可以通过 GatsbyJS 及其主题来实现。

> GitHub 地址→https://github.com/pedronauck/docz

![图片](https://mmbiz.qpic.cn/mmbiz_png/xBgIbW1vdNMZIx5EmZM1fevjhLqN5cl2SHTXLseHgf2ibo1lnEKRhxrbBl8JCLQlHcVAzM6g3MNFfzbvlHT7F1A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)


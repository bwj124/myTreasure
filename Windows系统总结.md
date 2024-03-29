> 加粗的是我认为常用的
>
> 持续更新

[TOC]

# Windows系统总结

## 快捷键

### win类（win就是Windows徽标键）

---

**win+R 打开运行**

**win+E 打开资源管理器**

**win+D 返回桌面**

**win+，按住返回桌面，松手后恢复原样**

**win+Ctrl+D 新建一个桌面**

**win+Ctrl+← 前一个桌面**

**win+Ctrl+→ 后一个桌面**

**win+Ctrl+F4 删除当前桌面（还在执行任务会被扔到上一个桌面）**

**win+Tab 任务视图**

**win+ ↑ 最大化**

**win+↓ 最小化**

**win+← 向左靠**

**win+→ 向右靠**

**win+Space（空格）切换输入法**

**win+S/Q 搜索**

**win+L 锁定，返回登录界面，适用于要离开去上厕所的情况**

**win+X 相当于右键开始，我一般常用的是：**

- **win+X，U，S 睡眠**
- **win+X，U，U 关机**
- **win+X，U，R 重启**

win+。表情符号

win+M 所有应用最小化

win+= 打开放大镜，再次按下放大

win+- 放大倍数缩小

win+esc 退出放大镜

win+V 剪贴板

win+A 打开通知

win+B 选中桌面工具栏

win+T 选中桌面任务栏

**win+Shift+S 系统自带截图**

win+G 打开Xbox Game Bar（主要用于游戏），里面可以录屏（win+Alt+R）截图（Win+Alt+Prtsc）

**（这里说一下Prtsc这个键，直接按下会将整个屏幕截图到剪贴板，如果Alt+Prtsc会将当前使用的应用截图）**

win+F 反馈（此操作会同时截屏，截图保存在图片>Feedback下）

win+K 连接

win+P 投影

**win+I 全部设置**

**win+U 系统设置**

**win+W 也可以截图**

**win+数字n 打开任务栏的第n个应用（n为1~9）**

win+Home 最小化所有其他应用

### Alt类

---

**Alt+Tab 切换任务**

Alt+F 打开文件菜单

Alt+V 打开视图菜单

Alt+E 打开编辑菜单

Alt+I 打开插入菜单

Alt+O 打开格式菜单

Alt+T 打开工具菜单

Alt+A 打开表格菜单

Alt+W 打开窗口菜单

Alt+H 打开帮助菜单

Alt+回车 查看文件属性

Alt+双击文件 查看文件属性

**Alt+F4 关闭当前程序**

**Alt+← 资源管理器中返回上一页，也可用于浏览器**

**Alt+→资源管理器中返回下一页，也可用于浏览器**

Alt+空格+C 关闭窗口

Alt+空格+N 最小化当前窗口

**Alt+空格+R 恢复最大化窗口**

Alt+空格+X 最大化当前窗口

### Ctrl类

---

**Ctrl+A 全选**

**Ctrl+C 复制**

**Ctrl+X 剪切**

**Ctrl+V 粘贴**

**Ctrl+F 查找**

**Ctrl+S 保存**

**Ctrl+P 打印**

**Ctrl+Z 撤销**

**Ctrl+Y 撤回撤销（有的软件可能是Shift+Ctrl+Z）**

**Ctrl+W 关闭当前窗口**

**Ctrl+鼠标滚轮滚动（即中键）缩放**

Ctrl+B 粗体

Ctrl+I 斜体

Ctrl+U 下划线

Ctrl+Shift输入法切换

**Ctrl+鼠标单击 选中所有鼠标点击的文件**

**Ctrl+Shift+Esc 打开任务管理器**

**Ctrl+Alt+delete 安全选项**

**Ctrl+Alt+A QQ截图**

**Ctrl+Alt+S QQ录屏**

**Ctrl+Alt+O QQ文字识别**

**Ctrl+Alt+Z 快速弹出QQ**

**Ctrl+Alt+W 快速弹出微信**

**Alt+A 微信截图**

### Shift类

---

**右键文件后Shift+D 直接删除而不是放到回收站**

**先按下Shift再右键可以在当前文件夹下打开powershell，在Powershell中输入start cmd可以直接进入当前目录的cmd，这样可以不用使用大量cd命令切换**

**Shift+鼠标单击 选中从上一个选中的文件到当前文件的所有文件**

**Shift+Home 选中本行光标之前所有的内容**

**Shift+End 选中本行光标之后所有的内容**

**Shift+ ↑ 向上选中**

**Shift+↓ 向下选中**

**Shift+← 向前选中**

**Shift+→ 向右选中**

**Shift+鼠标滚轮滚动（中键）左右滚动**

### Fn

---

F1 帮助

F2 重命名

F3 搜索

F5 刷新

F6 定位到输入框

F11 浏览器全屏

F12 浏览器开发者模式

### 其他

---

**Home 切换到最顶端或者本行的最前端**

**End 切换到最低端或者本行的最后端**

**有时我们想要选中一行，有的软件支持Ctrl+d选中一行，但是很多都不支持，我们可以先用Home/End切换到行首/行尾，然后Shift+End/Home来选中一行**



## 运行(win+r)

### appwiz.cpl

程序卸载或更改

### calc

计算器

### certmgr.msc

证书

### cipher

加密目录文件夹和文件

### cleanmgr

清理磁盘垃圾

### cmd(Tab键可快速补全|按下Ctrl+C可以结束当前的命令）

---

​	arp 查看本机的ARP缓存表

​	assoc 查看文件扩展名关联信息

​	**cd 切换路径** 

```
cd .. 返回上一级目录
若要跳转到某个磁盘，如E盘，输入"e:"
```

​    chcp 查看和更改cmd的编码格式

```
936是GBK 输入：chcp 936 改为GBK编码格式
65001是UTF-8 输入：chcp 65001 改为UTF-8编码格式
```

​	**chkdsk 修复磁盘，如修复F盘：chkdsk f: /f** 

​	**cls 清除屏幕**

​	cmd 打开另一个 Windows 命令解释程序窗口

​	convert 将 FAT 卷转换成 NTFS。不能转换当前驱动器

​	copy [-a] [-b] <输入的文件名> <输出的文件名> a表示ASCII码，b表示二进制

```
比如我想将多个文本文件复制且合并输出为一个文件：
copy -a *.txt output.txt
或者想将多个视频复制且合并输出为一个视频（假设原格式都是mp4）：
copy -b *.mp4 output.mp4
音频也一样（假设原格式都是mp3）：
copy -b *.mp3 output.mp3

扩展：如何把一个压缩包隐藏成一个图像？
copy /b 图片.jpg + 需要隐藏的文件.zip 图片.jpg
将图片后缀改成 .zip 解压就能继续使用，后缀改回来就能变回图片
```

​	date 显示/设置日期

​	**del或erase 直接删除文件（不放到回收站）** 

​	**dir 查看文件列表**

​    diskpart 

 ```
Diskpart是一款磁盘分区管理工具，包括创建分区、删除分区、合并（扩展）分区，完全可取代分区魔术师等第三方工具软件，它还有分区魔术师无法实现的功能，如设置动态磁盘、镜像卷等，而且设置分区后不用重启电脑也能生效。
切换硬盘、U盘盘符：
1. 在cmd中输入diskpart回车
2. list volume回车查看所有卷
3. select volume 7 选择卷标7（卷标是数字，盘符前面）
4. assign letter=F 切换盘符为F，想换成其他盘符也可以
 ```

​	dism

```
就是部署映像服务和管理 (DISM.exe) 用于安装、卸载、配置和更新脱机 Windows(R) 映像和脱机 Windows 预安装环境 (Windows PE) 映像中的功能和程序包。（DISM++相当于GUI的dism）
 dism /Online /Cleanup-image /RestoreHealth 可以把系统映像文件中与官方文件不相同的文件还原成官方系统的源文件（联网）
```



​    driverquery 显示当前设备驱动程序状态和属性

​	**echo 显示消息，或将命令回显打开或关闭**

```
还可以用来创建文件：
echo hello world!>test.txt
type test.txt
hello world!
注：>是重定向符，echo本来要将hello world!显示到屏幕上，但是>将echo要显示的内容重定向到文件test.txt中，所以就会创建一个新的文件了
```

​	**@echo off 后面所有命令都没有回显（包括本身这一条）** 

​	**echo off  后面所有命令都没有回显（不包括本身这一条）** 

​	**exit 退出当前cmd** 

​	**explorer 打开任务管理器，explorer . 打开当前目录** 

​	fc 比较两个文件或两个文件集并显示它们之间的不同

​	find 搜索文件

​	**findstr 可以用通道过滤信息** 

```
如：netstat -ano | findstr "8080" 查找端口为8080的程序信息（也不全对，只要匹配到8080都会返回）
```



​	**help 查看帮助信息** 

​	**ipconfig 查看本机IP地址 ** 

```
/all 查看详细信息
/flushdns 刷新 DNS 解析缓存
```

​	**md或mkdir 创建目录** 

​	mklink 创建符号链接

​	**move 移动文件** 

​	netsh winsock reset 

```
这个命令可以重新初始化网络环境，以解决由于软件冲突、病毒原因造成的参数错误问题。当执行完winsock的命令重启计算机后，需要重新配置IP。局域网的话需要DNS选择一下，另外因机而异可能会断网或网速变慢，这个就需要继续再进行解决。
```

​	**net start 启动服务** 

​	netstat 查看网络状态（netstat -an 可以查看当前开放的端口）

​	nslookup 解析IP地址

​	pathping ping并且跟踪节点（和tracert很像）

​	**pause 暂停** 

​	**ping 测试网络** 

​	powercfg 配置电源选项

​	powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61 打开卓越性能选项

​	rename 重命名文件

​	replace 替换文件

​	**rmdir或rd 直接删除文件夹 （/s 删除非空文件夹；/q 跳过确认）** 

​	route print 打印与目标主机的路由

​	sfc /scannow 扫描并修复系统文件

​	shutdown 关机/重启

```
常用参数有"-s"正常关机、"-f"强制关机、"-r"重启、"-h" 休眠、-t 数字（单位：秒）"定时关机、"-c" 设置提示信息、"-a" 是取消定时关机、"-i" 是打开对话框、"-l" 是注销 
```

​	slmgr.vbs -xpr 查看系统许可证信息

​	**systeminfo 查看系统信息** 

​	taskkill 终止进程

​	tasklist 进程列表s

​	time 显示/设置时间

​	title 设置窗口标题

​	tracert 追踪节点

​	tree 打印当前目录的文件树

​	type 显示文本文件的内容

​	ver 显示版本

​	**where 查看命令的位置** 

​	winver 显示版本详细信息

---

### compmgmt.msc

计算机管理

### control

打开控制面板

### desk.cpl

打开显示设置

### devmgmt.msc

设备管理器

### dfrgui

优化硬盘。HDD->分析(整理碎片)；SSD->优化（同时可以点击下面的更改设置，关闭驱动器的自动优化，可以提高SSD使用寿命）

### dfrg.msc

磁盘碎片整理

### diskmgmt.msc

磁盘管理工具

### dxdiag

检查DirectX信息，可查看硬件信息（想要更详细信息可以使用CPUZ、GPUZ等工具，无需安装即可直接使用）

### eventvwr.msc

事件查看器

### fsmgmt.msc

共享文件夹管理

### gpedit.msc

用户、分组策略管理工具

### hdwwiz.cpl

设备管理器

### iexpress

木马捆绑工具，系统自带

### inetcpl.cpl

IE的Internet选项

### intl.cpl

更改日期、时间或数字格式

### joy.cpl

游戏控制器

### lusrmgr.msc

本地用户、组管理

### main.cpl

鼠标属性

### mmsys.cpl

声音

### mrt

恶意软件删除工具

### msconfig

系统配置，可以打开系统服务和开机启动项等

### msinfo32

系统信息

### mspaint

画图

### mstsc

远程连接

### ncpa.cpl

网络连接

### notepad

记事本

### ntbackup

系统备份和还原

### osk

屏幕键盘

### perfmon/perfmon.msc

计算机性能监视器

### powercfg.cpl

电源选项

### powershell

打开PowerShell（powershell兼容了cmd，同时也有自己独特的指令规则）

### printmanagement.msc

打印管理

### psr

屏幕录制

### recent

查看近期浏览的文件夹及浏览时间

### regedit

打开注册表 

1. HKEY_CLASS_ROOT

   (1) HKEY_CLASSES_ROOT/*/shellex/ContextMenuHandlers 下删除桌面右键菜单

   (2) HKEY_CLASSES_ROOT/Directory/shell和HKEY_CLASSES_ROOT/Directory/shellex/ContextMenuHandlers下删除文件夹右键菜单

   有时在HKEY_CLASSES_ROOT/Folder/shell和HKEY_CLASSES_ROOT/Folder/shellex/ContextMenuHandlers也有

   (3)  HKEY_CLASS_ROOT下面的.xxx文件是后缀名为.xxx文件的默认打开方式

2. 小狼毫配置

   (1) 删除输入法在任务栏的图标
   HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\CTF\TIP\ 
   下面相对应的输入法ID就可以了：

   比如，小狼毫的是{A3F4CDED-B1E9-41EE-9CA6-7B4D0DE6CB0A} 
   那么就删除
   HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\CTF\TIP\{A3F4CDED-B1E9-41EE-9CA6-7B4D0DE6CB0A}

   (2) 小狼毫删除Windows8以上的不是TSF的那个

   HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\

   Ctrl+F 搜索weasel.ime

   会找到3个：Ime File、Layout File、Layout Text，全部删除即可
   
3. 经常容易被修改的注册表键值
   (1) IE起始页的修改
    HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main右半部分窗口中的Start Page就是用户当前设置的IE浏览器主页地址了

   (2) Internet选项按钮灰化&失效
    HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Control  Panel下的DWORD值“Setting”=dword:1 “Links”=dword:1  “SecAddSites”dword:1全部改为0之后再到HKEY_USERS.DEFAULT\Software\Policies\Microsoft\Internet Explorer\Control Panel下的DWORD值“homepage”键值改为0则无法使用“Internet选项”修改IE设置

   (3) “源文件”项不可用HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Restrictions的“NoViewSource”被设置为1了，改为0就可恢复正常

    (4) “运行”按钮被取消&失效HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer的“NoRun”键值被改为1了，改为0就可恢复

    (5) “关机”按钮被取消&失效HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer的“NoClose”键值被改为1了，改为0就可恢复

    (6) “注销”按钮被取消&失效HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer的“NoLogOff”键值被改为1了，改为0就可恢复

    (7) 磁盘驱动器被隐藏
    HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer的“NoDrives”键值被改为1了，改为0就可恢复。
   
4. 控制面板的ID
   .{21EC2020-3AEA-1069-A2DD-08002B30309D}

5. 添加或删除程序在注册表的位置：
   计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\

   计算机\HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Microsoft\Windows\CurrentVersion\Uninstall
   
6. “右键->新建”在注册表中的位置：
   计算机\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Discardable\PostSetup\ShellNew

7. 文件夹“右键”在注册表中的位置：
   计算机\HKEY_CLASSES_ROOT\Directory\Background\shell

### resmon

资源监视器

### rsop.msc

管理策略查看

### secpol.msc

本地安全设置

### services.msc

服务管理

### shell:startup

开机自启的文件夹

### slidetoshutdown

滑动关机

### snippingtool

截图工具（可直接使用 Win+Shift+S 截图）

### sysdm.cpl

打开系统属性，点击高级选项卡可以设置环境变量

### taskmgr

任务管理器

### taskschd.msc

任务计划程序

### timedate.cpl

日期和时间

### wf.msc

防火墙

### winchat

局域网聊天

### winver

查看Windows详细版本信息

### wmic 

Windows管理工具，不同于cmd和powershell的运行环境，可以做很多事情

如：查看内存的信息：wmic memorychip

### write/wordpad

写字板

## 问题解决

### WPS关闭广告

1. 找到WPS的安装文件夹

2. 进入版本号的文件夹（如：11.1.0.9564）

3. 进入office6文件夹

4. 双击文件ksomisc.exe

5. 点击高级
   
6. 点击其他选项，去掉对勾


### 文件夹无权限访问

参考https://jingyan.baidu.com/article/49711c6180823afa441b7cd4.html

### 任务栏简单美化（可直接下载软件StartlsBack美化）

#### 1. 任务栏居中（无需软件）

1.  Win+S打开搜索框，搜索字符映射表，选中第5行（k下面的）空白字符并复制
2. 新建一个文件夹（任意位置都可以，只要找的到），把空白字符作为文件夹名字
3. 右键任务栏->工具栏->新建工具栏，选择该文件夹
4. 取消锁定任务栏，再拖动滑动条到适当位置即可（若想取消，再工具栏那里把对勾去掉即可）。

#### 2. 任务栏透明化

从微软商店搜索translucentTB下载后打开即可，在任务栏中选择自己需要的模式。

### 将小狼毫设置为默认输入法

1. 想要将小狼毫设置为默认输入法。打开语言设置->选择始终默认使用的输入法后进行选择，但是发现没有小狼毫的选项，进行第二步。

2. 重新打开语言设置，点击中文(中华人民共和国)->选项，找到键盘，再点击添加键盘，添加小狼毫。然后重复第一步即可。

### 小狼毫无论如何切换中英文，打出的都是中文

原因是没有启动小狼毫算法服务。打开小狼毫安装目录，运行WeaselServer.exe即可

### 电脑蓝屏

下载BlueScreenView.exe。该程序可以自动扫描电脑的蓝屏信息文件（dmp文件，在C:\Windows\Minidump下）并显示其信息。

我的蓝屏信息是：终止代码：SYSTEM_SERVICE_EXCEPTION；失败的操作：WiseFs64.sys

使用BlueScreenView.exe查看后，发现是ntoskrnl.exe的问题。解决方法如下：

1. 以管理员身份运行cmd，输入chkdsk c: /f，再输入y。由于当前有进程占用，因此下次重启电脑自动修复。
2. 下载DirectX Repair工具，点击检测并修复即可。

### 电脑磁盘条变红

当磁盘占用超过90%，我的电脑中磁盘条就会变为红色。可以通过在注册表窗口中打开：

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanServer\Parameters 主键，将DiskSpaceThreshold键值改为自己需要的百分比

### 让所有程序自动以管理员身份运行

1. 打开注册表（Win+R输入regedit）
2. 进入：
    计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System
3. 找到EnableLUA，将数值数据由1改为0，即可关闭用户控制

### Windows 上帝模式

新建文件夹，修改文件夹名称为：

.{ED7BA470-8E54-465E-825C-99712043E01C}

### 解除文件格式关联

1. 打开注册表（Win+R输入regedit）

2. 进入：
    计算机\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\FileExts\.e\

3. 找到你要解除的文件格式，比如.e

4. 那么删除.e\UserChoice，然后重启资源管理器即可

    > #### 重启资源管理器：
    >
    > ---
    >
    > 随便打开一个文件夹或者按Win+E，然后进入任务管理器（Shift+Ctrl+Esc）。找到资源管理器，右键->重新启动

### 关闭我的电脑中的腾讯视频、和彩云网盘

1. 腾讯视频

进入`计算机\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{E701A357-F43B-42c9-98D1-96B6C11EAD87}`，删除默认(ab的那个，数据写着腾讯视频)

2. 和彩云网盘

    删除注册表中的`计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3C6C4AE3-9AE3-436F-BE29-E1C2F38A5EEC}`

    或 `计算机\HKEY_USERS\S-1-5-21-2747554322-978073548-3710153092-1003\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3C6C4AE3-9AE3-436F-BE29-E1C2F38A5EEC}`
    
    (建议同时删除`计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Classes\CLSID\{3C6C4AE3-9AE3-436F-BE29-E1C2F38A5EEC}`)
    
    （具体就是搜索{3C6C4AE3-9AE3-436F-BE29-E1C2F38A5EEC}，然后删除，一直到搜索不到为止）

### Window去除锁屏界面乱七八糟的提示

右键桌面点击个性化，点击锁屏界面。进入后关闭“在锁屏界面上从WIndows和Cortana获取花絮、提示等”即可

### 微软商店无法下载

之前关闭了windows的自动更新，打开即可

### 右键新建中没有了Word、Excel和PowerPoint

安装了Office但是并没有显示这些，可以打开注册表(Win+R)，然后进入HKEY_CLASSES_ROOT按下Ctrl+F搜索docx，然后双击默认，修改值为Word.Document.12，确定。

此时右键新建看有没有这三者，如果没有Excel和PowerPoint，那么相应的：搜索pptx，修改默认值为PowerPoint.Show.12；搜索xlsx，修改默认值为Excel.Sheet.12

### 关闭Windows10插入U盘后自动打开U盘

进入Windows的设置(Win+I)，然后进入设备，在左侧找到自动播放，然后可以看到可移动驱动器，选择不执行操作即可。也可以直接关闭自动播放。想更彻底的话，打开服务，禁用Shell Hardware Detection服务

### Capslock+ 按下“Capslock+，”无法选中当前单词

和其他软件的全局快捷键（“Ctrl+Shift+Right” 冲突）

### 右键新建没有文本文档

新建文档`txt.reg`，文件内容如下：

```
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\.txt]

@="txtfile"

"Content Type"="text/plain"

[HKEY_CLASSES_ROOT\.txt\ShellNew]

"NullFile"="" [HKEY_CLASSES_ROOT\txtfile]

@="文本文档"

[HKEY_CLASSES_ROOT\txtfile\shell]

[HKEY_CLASSES_ROOT\txtfile\shell\open]

[HKEY_CLASSES_ROOT\txtfile\shell\open\command]

@="NOTEPAD.EXE %1"
```

### 使用QuickLook来预览Everything中的文件

无法预览问题的原因是：**权限
**Eveything 的权限比QuickLook高。QuickLook无法读取Everyting的内存 或注入。
**解决方法：**Everthing 与QuickLook都用普通权限运行（都选中开机运行就好了。Everything取消以管理员权限运行）
**或**
想办法让QuickLook以管理员权限运行(右键兼容性。选中以管理员权限运行)

### 卸载Windows10内置应用

以管理员运行Powershell，然后输入后面的指令，卸载相应应用

```powershell
3D Builder：Get-AppxPackage *3dbuilder* | Remove-AppxPackage
闹钟和时钟：Get-AppxPackage *windowsalarms* | Remove-AppxPackage
计算器：Get-AppxPackage *windowscalculator* | Remove-AppxPackage
日历和邮件：Get-AppxPackage *windowscommunicationsapps* | Remove-AppxPackage
相机：Get-AppxPackage *windowscamera* | Remove-AppxPackage
获取 Office：Get-AppxPackage *officehub* | Remove-AppxPackage
获取 Skype：Get-AppxPackage *skypeapp* | Remove-AppxPackage
获取 Started：Get-AppxPackage *getstarted* | Remove-AppxPackage
Groove 音乐：Get-AppxPackage *zunemusic* | Remove-AppxPackage
地图：Get-AppxPackage *windowsmaps* | Remove-AppxPackage
Microsoft Solitaire Collection：Get-AppxPackage *solitairecollection* | Remove-AppxPackage
Money Wallet：Get-AppxPackage *bingfinance* | Remove-AppxPackage
电影和电视：Get-AppxPackage *zunevideo* | Remove-AppxPackage
MSN 咨询：Get-AppxPackage *bingnews* | Remove-AppxPackage
OneNote：Get-AppxPackage *onenote* | Remove-AppxPackage
人脉：Get-AppxPackage *people* | Remove-AppxPackage
你的手机：Get-AppxPackage *windowsphone* | Remove-AppxPackage
照片：Get-AppxPackage *photos* | Remove-AppxPackage
Windows 录音机：Get-AppxPackage *soundrecorder* | Remove-AppxPackage
天气：Get-AppxPackage *bingweather* | Remove-AppxPackage
Xbox：Get-AppxPackage *xboxapp* | Remove-AppxPackage
Microsoft Store（不建议卸载）：Get-AppxPackage *windowsstore* | Remove-AppxPackage
```

### 安装代理软件后有时无法上网（代理错误）

这是因为：可能没有正常关闭代理软件，代理端口没有切换回来，导致我们还是使用的全局代理，不过没有开启代理软件，这个时候当然不能正常联网了。

解决办法：

1.  打开代理软件
2.  控制面板 -> Internet选项 -> 「连接」选项卡 -> 局域网设置 -> 把打勾的代理服务器去掉，变成不打勾的状态

上面的第二步就是因为开启了全局代理，而代理软件又没有打开，所以当然不能联网了，取消红色框中的勾选，然后确定就可以上网了

### Everthing无法创建某个磁盘的USN日志

磁盘修复即可，cmd -> chkdsk d: /f (修复D盘)

### 电脑的浏览器可以连上网，但是图标却还是未连接，系统更新和一些其他应用（如网易邮箱大师）也无法联网

为什么好了我也不知道，就说一下我干了什么吧：

1.  重置winsock，winsock是windows的套接字协议（应该是因为这一步操作解决的）

    >   具体步骤是：
    >
    >   *   以管理员身份打开cmd
    >   *   输入指令：netsh winsock reset

2.  更改dns服务器

    >   具体步骤是：
    >
    >   *   打开控制面板
    >   *   点击网络和共享中心（win10，如果win7的话是网络和internet设置）
    >   *   点击更改适配器设置
    >   *   在打开的网络连接中选择你要连接的网络类型（我连的无线网所以选择WLAN，如果是有线的，那就是以太网），双击进入
    >   *   点击属性
    >   *   找到Internet协议版本4（TCP/IPv4）
    >   *   点击属性
    >   *   选择使用下面的DNS服务器地址
    >   *   将首选DNS服务器改成`8.8.8.8`（通用的DNS服务器）
    >   *   确定

3.  重启电脑

### Chorme内核浏览器开启自带多线程下载

在地址栏输入：

```apl
chrome://flags/#enable-parallel-downloading
```

### 电脑WIFI图标消失

如果是大学生或其他需要客户端认证上网的人员，可参考下面操作此方法也是从吧友那里借鉴：把下面的代码复制粘贴到文本文档，然后改后缀.reg，再运行最后重启就好了。

```
Windows Registry Editor Version 5.00
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\EventLog]
“ServiceDll”=hex(2):25,00,53,00,79,00,73,00,74,00,65,00,6d,00,52,00,6f,00,6f,\
00,74,00,25,00,5c,00,53,00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,\
77,00,65,00,76,00,74,00,73,00,76,00,63,00,2e,00,64,00,6c,00,6c,00,00,00
```

如果无法运行，按win+r启动运行，输入regedit进入注册表项

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\EventLog]

按照上面顺序打开，右键新建 可扩充字符串值，修改;

数值名称ServiceDll

数值数据%SystemRoot%\System32\wevtsvc.dll

最后重启就好了。

问题原因在于Windows1809版本上，安装校园网netkeeper，会导致任务栏网络图标不见，并且网络适配器miniport全部不了见，并且服务中Remote access和Windows Event Log无法启动。

### 其他软件都可以正常上网，但是QQ无法联网（错误代码000001）

关闭网络适配器属性中的IPV6协议

（开启后QQ连接IPV6的那个协议，反正不知道怎么的，IPV4的好用，所以关掉IPV6那个就好了）

### 火绒三套规则

**第一套**

自定义规则.json(阻止流氓软件安装)

自动处理规则.json(阻止扫描读取硬盘)

恶意网址规则.json

这样在流氓软件安装的时候，就会弹出提示，并且默认阻止，比火绒自带的默认提醒更加严格。

**第二套**

腾讯系列的规则

防止腾讯产品扫描电脑本地文件

tencent-auto.json(自动处理规则)

tencent-custom.json(自定义规则)

> 不要在弹出的提示内选择“记住本次操作”，否则会对所有文件生效

**第三套**

主要针对的是系统和office相关的规则

同样这套规则也是分为自动处理和自定义规则，注意分开导入。规则有一些使用的小功能，比如说阻止微软的 Teams 自动安装（在用官方提供的安装方式里 Office 2021 会自动加装 Microsoft  Teams），阻止程序自动创建计划任务（如 Office 计划任务、Edge 浏览器计划任务、搜狗输入法、阿里旺旺、MySQL、Xbox  Game 计划任务，阻止后不影响软件，也可以避免软件在后台偷偷启动检测更新或者执行其他任务）

还有一个就是：

阻止程序在文件资源管理器中“我的电脑”创建快捷方式，比如安装百度或者迅雷或者WPS后，总是会在 C 盘左边自动创建一个快捷方式

还有阻止程序读取浏览器历史记录等功能，具体功能可以导入之后在火绒里查看，不需要的功能可以单独关闭。

### 火狐浏览器在打开某个标签页时，提示“此网页拖慢了您的Firefox。可停止此页面，恢复浏览速度”

我的是打开百度搜索到的页面时会卡死，并占用大量CPU，此时打开其他网页不会卡

排查模式无效，重启电脑无效。

最终清理了火狐的缓存（设置里直接搜索即可），解决问题

### 使用爬虫请求太频繁被封IP但是又不想用IP池

重新分配一个ip地址

1. 先清除

    ```
    ipconfig /release
    ```

2. 再重新分配

    ```
    ipconfig /renew
    ```


### 百度网盘在线看视频倍速

##### 移动端（IOS、Ipad、Android）

1. ES文件浏览器（点击网盘，搜索百度网盘）
2. ALook（切换为移动版）
3. 爱奇艺万能联播（登录百度网盘）

##### 电脑端

1. 浏览器安装油猴脚本-计时掌控者
2. 爱奇艺万能联播（登录百度网盘）

### 在电脑浏览器打开只能在微信内打开的链接

打开开发者选项，将视图换为手机，然后改UA（User Agent, 一般在切换视图后浏览器的右上角的设置中）为：

```
Mozilla/5.0 (Linux; U; Android 2.3.6; zh-cn; GT-S5660 Build/GINGERBREAD) AppleWebKit/533.1 (KHTML, like Gecko) Version/4.0 Mobile Safari/533.1 MicroMessenger/4.5.255
```

### Edge浏览器下载插件出现`Download Interrupted`

1. 打开：C:\Windows\System32\drivers\etc\hosts
2. 在 hosts 文件最后面添加：

```
131.253.33.219 edge.microsoft.com
131.253.33.219 msedgeextensions.sf.tlu.dl.delivery.mp.microsoft.com
```

### 安卓模拟器启动不了以及和WSL的妥协方案（每次都到50%，报错g_bGuestPowerOff fastpipeapi.cpp:1161）

首先原因是由于和Windows自带的Hyper-y虚拟机冲突，因为Hyper-y和其他大多虚拟机都冲突（VirtualBox、VMWare）

所以要想启动虚拟机或者安卓模拟器，就要关闭Hyper-y

首先，我们将wsl切换到1版本，可以使用`wsl --set-default-version 1`切换所有版本（我的这个指令不好用）或者`swl --set-version Ubuntu 1`（这个好用）来切换到1版本，切换后记得用`wsl -l -v`检查一下是否真的切换了。因为WSL1不需要Hyper-y，这样一来WSL还可以使用。

然后使用指令`bcdedit /set hypervisorlaunchtype off`关闭hyper-y（开启的话将off改成auto），并且在程序和功能的启用或关闭Windows功能里，关闭虚拟机平台。

最后重启即可。

### 电脑Wifi查看

1. 使用工具：**电脑wifi密码查看器**或**wifi密码查看器**

2. 命令行操作
    运行cmd，然后输入命令“**netsh wlan show profiles**”，按回车，即能显示所有的已连接的wifi名称。

    最后输入命令“netsh wlan show profiles name="**wifi名称**" key=clear” 回车.

    比如我的wifi名称是"iphone"，那么输入：netsh wlan show profiles name="**iphone**" key=clear，下拉找到密码即可。

    如果你能记住wifi名称，直接输入令“netsh wlan show profiles name="**wifi名称**" key=clear，即可。

### Win10校园网宽带连接频繁秒断

宽带连接连上过后很快就断开。

打开注册表，打开路径：

`计算机\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services\NlaSvc\Parameters\Internet`，将`EnableActiveProbing`的数值改成0（默认是1）

重启

### C盘空间清理但又不想删除文件仍想和原来一样正常使用-创建软链接使得文件正常访问

首先将想要清理的**`目录（软链接只能为目录创建）`**先移动到其他盘，比如原来在`%User%\AppData\Local\`下的`JetBrains`目录，我移动到`E:\userMirror\AppData\Local\`下

移动完之后，在原目录（`%User%\AppData\Local\`）下打开cmd，输入指令：

```shell
mklink /J "JetBrains" "E:\userMirror\AppData\Local\JetBrains"

# 即 mklink /J [软链接位置] [实际位置]
# /J 的意思是软链接 junction point 也叫 soft link
# 除此之外还有
# /H 硬链接 hard link
# /S 符号链接 symbolic links
```

即可在Local创建指向`E:\userMirror\AppData\Local\JetBrains`的软链接，作用是文件存储在E盘里，但是按原路径访问仍然能访问到。

关于链接的详情可以看[文章：Windows硬链接 软链接 符号链接 快捷方式](http://blog.nsfocus.net/shortcuthard-linkjunction-pointsymbolic-link/) 

### 把旧电脑的系统和软件原封不动地迁移到新电脑

可以使用DiskGenius这款软件

用硬盘盒将硬盘接在旧电脑上, (根据需求分好区)然后系统 

用 系统迁移 功能移到新硬盘. 其他分区用克隆方式迁移到新硬盘

> 装之前最好把旧电脑的显卡驱动卸载掉, 还有些独有功能, 如键盘背光,快捷键之类的驱动卸载掉, 这种在新电脑上也用不了, 还可能出问题迁移到新电脑后, ,再将驱动装全

**或者**

使用傲梅轻松备份，先备份再还原

**1.** 准备一个空间足够的外部硬盘驱动器，将其连接到旧电脑并确保系统能够正常检测到它。

**2.** 打开傲梅轻松备份，在主界面中单击**“备份”>“系统备份”**，然后按照提示流程执行系统备份任务。

**3.** 获取系统备份镜像文件之后，将外部硬盘连接到新电脑上，然后打开新电脑上的傲梅轻松备份，单击**“还原”>“选择镜像文件”**。

**4.** 找到系统备份镜像文件，然后勾选**“还原这个系统备份”**选项，单击**“下一步”**。

**5.** 选择目标硬盘之后您将看到操作摘要界面，确认无误后勾选左下方的**“异机还原”**选项，如果新电脑上的硬盘是固态硬盘的话，还可以勾选**“SSD对齐”**选项以优化其读写性能，然后单击**“开始还原”**以将旧电脑系统还原到新电脑上，从而达成将Win11、Win10系统迁移到具有不同硬件的新电脑上的目的。

**或者**

使用傲梅轻松备份，直接克隆

如果旧电脑上有额外的硬盘为的话，可以直接将新电脑上的系统硬盘取下，然后安装到旧电脑上，将旧电脑系统硬盘全部克隆到新电脑硬盘上，然后在将新电脑硬盘取出，装回新电脑即可完成Win11、Win10迁移到新电脑的任务，相较于备份还原方法省略了一个大步骤，能够节省更多时间精力。

**1.** 将新电脑上的系统硬盘取下并安装到旧电脑上，在旧电脑上打开傲梅轻松备份，选择**“克隆”>“磁盘克隆”**并按照提示流程完成磁盘克隆任务。

**2.** 等待克隆完成之后，您可以将新电脑硬盘取出并安装到新电脑上，开机即可完成系统迁移任务。

### 找破解软件（Office）的注册码、激活码

在搜索引擎搜索中搜索时加关键字 94fbr

### 数位板做笔记

分为两种：

1. 纯写字：OneNote、Microsoft Whiteboard、Xournal++
2. 在PDF上做批注：PenBook、Xournal++、PDF-XChange、Drawboard PDF（高级功能收费） 、PDF Reader by Xodo（高级功能收费）

OneNote也可以通过插入图片来做笔记，但是没法直接在PDF上标注

Xournal++最强大，切开源，支持全端，唯一缺点就是界面没那么好看，而且做好的标注是以它自己的格式保存下来的，没办法保存到PDF上

PDF-XChange很不错，和Xournal++差不多，但是不能在空白页面做笔记

PenBook界面简洁好看

### 使用Wifi可以使用代理，但是用网线拨号连接无法使用

解决办法：删除原有的拨号连接，新建一个纯英文名的拨号连接

并在拨号后再启动代理软件

### 通过影视的画面截图或者台词找到原片

* [Yarn](https://getyarn.io/): 这个网站能根据台词，自动搜出对应的电影片段
* [33台词](https://33.agilestudio.cn/): 通过台词找影片素材
* [伪射手网](http://assrt.net/): 收录了超多部电影的字幕
* [SubHD](https://subhd.tv/): 专业免费的影视剧字幕下载网站，不过它里面的字幕比伪射手网好一点，大部分都是双语的。
* [Dialogue](http://dialogue.moe/): 通过台词找动漫，主要针对动漫

### Windows10忘记密码

在Windows登录到桌面前，一般会设置一个账号密码。万一忘记密码就无法登录系统了，这时有很多解决方法。由于使用Windows10的用户最多，今天我们以Windows10为例，介绍两种方法：一是借助系统安装盘，手动**清除开机密码**；二是在WinPE环境下**修改开机密码**。

#### 方法1、手动清除Win10开机密码

制作一个可以从U盘启动的系统安装盘是很容易的事情，假设已经使用Rufus等工具将原版Windows镜像写入了U盘，那么从U盘启动后就会见到如下界面，也就是安装系统的界面，点击下一步。当然，有系统安装光盘也是可以的。

点击左下角的“修复计算机”

选择“疑难解答”→“系统映像恢复”。

根据提示，选择Windows10的启动菜单。

来到下图后，点击“取消”→“下一步”。

点击“高级”→“安装驱动程序”→“确定”。

然后弹出资源管理器窗口。**这里才是重点，前面那么多步骤，其实就是为了找到这个窗口，容易用鼠标操作而已，前面步骤都没什么用**。

找到C:\Windows\System32\目录下的**Utilman**文件，我们把它重命名，随便起个名字：Utilman0。同理，在同目录下找到**cmd**，重命名为Utilman。

然后F5刷新一下，看看修改有没有成功。无误后，关闭所有窗口，然后点击“继续”就可以进到登录界面了。

当进入到Windows10系统登录界面时，点击右下角的“快速访问”按钮，会弹出一个cmd的黑色窗口。这时输入命令：`net user heu8 ""`

请注意，这里的**heu8**代表的是用户名，请自行根据实际名称修改，在当前的登录界面可以看到用户名。

到这里大家就明白了，前面一顿操作猛如虎，其实就是为了改个文件名，点此按钮的时候调出cmd而已~

至此就相当于把Windows10的登录密码已经清除掉了。无需输入密码即可进入系统。

重启计算机，仍从系统安装盘启动，重复上面的操作，**把前面的两个文件名Utilman、cmd，重新改回来**。至此操作完毕！

#### 方法2、借助WinPE修改Win10开机密码

首先打造一个WinPE启动的U盘，可以使用以前推荐过的WePE、FirPE、优启通等，我这里以FirPE为例进行介绍，FirPE的官方网站：https://firpe.cn 

第一步：将FirPE写入U盘，由于是傻瓜式操作，一看就会。

第二步：在BIOS中设置为从U盘启动，这样就可以进入WinPE。如果不会设置，自行百度吧，每个电脑都不太一样，一般开机按F1、F2、F12的居多，也可以逐个尝试。

第三步：进入WinPE后，运行密码修改软件NTPWEdit，点击打开→选择用户名→修改密码。

至此，密码已修改完成！

**温馨提示：**虽然可以无需密码登录Windows10，请大家不要未经允许登录别人的电脑干坏事。本文介绍的方法，只是为了教给大家在忘记自己电脑开机密码的情况下如何操作。大家应该举一反三，掌握原理，不仅局限于以上方法。

其实除了上述方法，还有其他的清除密码的方法、甚至不修改密码直接绕过的方法，以后再给大家介绍。

### 自定义windows系统（通过更改ISO镜像文件）

在安装Windows的时候，我们有时候想给安装完的系统添加一些个性化的设置，比如联想品牌logo、主题。有时还想做一些特殊的设置，比如解除Win11强制使用在线账户登录，再比如禁用Windows Defender等等，这一些列的操作我们都可以对官方原版的ISO进行处理。

今天介绍一个炒鸡简单的方法。准备条件：

1、UltraISO：[点击下载](http://mp.weixin.qq.com/s?__biz=MzA3Nzg3NjYxOQ==&mid=2448154680&idx=1&sn=6675d590670393cf5153e88f2c87fd0d&chksm=8b541cdcbc2395ca78a572795d470a8ef4c97b07c2eebb872cb579872101de2d719c72c2eb8b&scene=21#wechat_redirect)

2、文件包下载：

https://pan.lanzou.com/b00qdqhwf 密码:ciin

来源于MDL论坛：https://forums.mydigitallife.net/threads/multi-oem-retail-project-mrp-mk3.71555

**操作方法：**使用UltraISO打开Windows 11官方原版ISO镜像，将文件包内的$OEM$文件夹拖动到ISO\sources目录下，然后另存为一个新的ISO即可，其他什么都不用操作。

**如果看到这，你觉得这功能也就一般般吧，那就错了，上面的\**“\**文件包”包含的功能非常强大：**

1、它集成了100+款品牌电脑的主题，自动识别电脑品牌；如果检测到主板的SLIC信息，还可以OEM激活方式自动激活Win7/Server相关的系统。（不包含其他的激活方式）

2、除了上面的操作外，文件包内还有另外两个文件夹可供选择使用。首先，Optional文件夹内有自动应答文件Autounattend.xml，直接拖动到ISO的根目录下即可。它实现的功能包括：禁用系统还原、禁用Windows Defender、禁用Windows Firewall、禁用Windows错误报告、设置网络位置(家庭)。

里面还有ei.cfg文件，它可以跳过安装密钥。把它拖动到ISO\sources目录下即可。

3、还有一个文件夹MRPConfigCreator，这个也是自定义功能最强大的地方。运行里面的MRPConfigCreator_v51.0.Exe，可以自行设置后，生成一个配置文件MRPConfig.ini。这个配置文件放到$OEM$\$$\Setup\Scripts文件夹下即可。

在默认情况下，该文件夹下无此配置文件，则使用的是默认设置。添加配置文件后就可以按照我们自己定的要求实现相关的功能了。

我们运行一下MRPConfigCreator_v51.0.Exe，看看都有哪些设置？以Win11为例，点击标题栏Win11，我们可以勾选“Force Local instead of Online Account”，意思是使用本地账户登录，而不是微软强制的在线账户。

还可以做非常多的设置，比如移动开始按钮到任务栏左侧、启用桌面贴纸功能、移除快捷方式图标的小箭头、移除/禁用一些功能等等的。大家可以自行选择。

缺点是软件为英文版，暂无汉化。有需要的可以尝试一下~如果不想这么麻烦，就直接用本文开头的傻瓜式操作，一键生成，什么都不用设置。

**注意：使用上述制作好的ISO安装完系统，进入桌面后，会弹出批处理窗口进行设置，稍等一会设置完毕，则需要重启一次才能生效。**

以下是我用[虚拟机Vmware](http://mp.weixin.qq.com/s?__biz=MzA3Nzg3NjYxOQ==&mid=2448162723&idx=1&sn=0991d45bfb4b85f9d16672d7821c4c15&chksm=8b540347bc238a519d57999630dca93126bff44961c33a0649e6c906899a081f4113c04a06e4&scene=21#wechat_redirect)测试的，好家伙，直接给装了一套虚拟机的主题~

### Win10安装安卓子系统

> 摘自知己而知彼

Windows11上的一大亮点是WSA（安卓子系统），根据微软的介绍仅支持Windows11系统，目前微软已经向多个国家推送，直接在应用商店搜索WSA进行安装即可。针对暂未推送的国家，可以采用离线安装的方式，此前我多次介绍过[如何离线安装WSA](http://mp.weixin.qq.com/s?__biz=MzA3Nzg3NjYxOQ==&mid=2448160712&idx=1&sn=8f7ce679254fa99302f4f4ceb7fb9a44&chksm=8b540b2cbc23823afc60209c705b6d304971ad0f588cbf2ab55f758bee71da45e332bd8952c5&scene=21#wechat_redirect)。

最近Github上的一个开源项目，可以使Win10用户安装WSA，目前Win10用户众多，这是一个很不错的消息。不过，据作者称，需要**Win10** **Build 19045.2311(64位)**版本及以上的才可以。(根据网友反馈 19043.2311、19044.2311版本也可)。也就是说需要2022年12月最新版的ISO：[点击下载](http://mp.weixin.qq.com/s?__biz=MzA3Nzg3NjYxOQ==&mid=2448163392&idx=1&sn=85936adae90e640bb793c54a9f0459f4&chksm=8b53fea4bc2477b27d9238da2c6580c2c386f715007333d39ddeeeb332acca7dabd19256d541&scene=21#wechat_redirect)。

Github访问速度慢的，可以看看[我昨天写的文章](http://mp.weixin.qq.com/s?__biz=MzA3Nzg3NjYxOQ==&mid=2448163463&idx=1&sn=581dd8b5b96955d7f159ade591a2d25a&chksm=8b53fe63bc247775f33b03755048fbaeeca31eb257cb99c4130885fc60910c5c48e933222d30&scene=21#wechat_redirect)。Win10安装WSA的整个过程操作下来还是要费一番功夫的，为了节省大家的时间和操作失误的可能，我用最简单的方法给大家介绍一下整个流程，供不同需求的同学使用。

1、下载WSA APPX安装包(可跳过)

首先下载WSA APPX安装包，在Linux环境中下载并编译集成Magisk。本文用的APPX安装包，来自开源项目：

https://github.com/LSPosed/MagiskOnWSALocal

对于一般用户来说，可以在虚拟机中安装Ubuntu，然后按照该项目介绍的方法下载、编译。对于不熟悉Linux的小伙伴儿来说，确实有一些繁琐。为了省去麻烦，我已经下载好了，大家直接在下文的网盘中下载即可。

2、集成WSA补丁(可跳过)

根据cinit大神分享的方法，我们把上一步下载的WSA APPX安装包集成WSAPatch补丁。这一步是在Windows上操作，想了解制作原理的，大家可以参照如下项目地址：

https://github.com/cinit/WSAPatch

集成补丁的方法十分简单，就是把WsaPatch.dll和icu.dll文件复制到WsaClient 文件夹中，然后修改一下AppxManifest.xml就操作完成了。

我已经修改并集成好了，大家可以直接下载集成了Magisk+WSAPatch补丁的安装包。上文可以都不看，之所以介绍这么多，主要是以后有新版本了，大家可以自己去下载，提供方法比直接投喂更重要🤣。

**WSA APPX安装包下载：**

https://pan.baidu.com/s/1afWp6QHCl_x7T4ttCfgP1g 提取码: 3m6b

备注：版本号2211.40000.10.0。另外提供了支持库，备用。

3、Win10安装WSA

**一、前提条件（配置虚拟化条件）：**

在控制面板→程序→启用或关闭Windows功能，开启以下功能：Hyper-V(可以不开启)、虚拟机平台(必须开启)。然后重启电脑。

**二、安装WSA**

将第2节中下载的“WSA APPX安装包(含Magisk+WSAPatch)”解压，然后把文件夹里的所有文件全部复制到你想安装的位置。例如C:\WSA

双击运行WSA目录下的Run.bat，稍等片刻即可成功安装！

如果遇到安装失败的情况，很可能是缺少支持库导致，上文网盘里提供了支持库，双击即可安装。

**三、安装APP**

安装安卓APP可以使用第三方工具WSAToolbox，这个工具也是开源的。项目地址：

https://github.com/makazeu/WsaToolbox/releases

安装完WSA之后的操作，与Win11上没有区别，大家可以参考我以前写的文章：[点击进入](http://mp.weixin.qq.com/s?__biz=MzA3Nzg3NjYxOQ==&mid=2448160712&idx=1&sn=8f7ce679254fa99302f4f4ceb7fb9a44&chksm=8b540b2cbc23823afc60209c705b6d304971ad0f588cbf2ab55f758bee71da45e332bd8952c5&scene=21#wechat_redirect)。

**总结**

本文看上去内容很多，主要给大家介绍各种软件的来源，供喜欢研究的小伙伴食用。其实大家要做的很简单：1.下载集成了WSAPatch补丁的安装包；2.在控制面板中，启用虚拟机平台；3.解压安装包，双击Run.bat，大功告成！

### 安装Win11解决强制联网

**第一种方法**

1、首先在安装Windows11前，**断开网络！断开网络！断开网络！**安装过程，下一步是灰色的，无法继续下去。

2、按下Shift+F10组合键，调出CMD窗口，运行如下命令后，将自动重启。

> oobe\bypassnro

3、重启后发现下面页面多了一个选项“我没有Internet连接”，点击后，接下来整个过程都不需要联网，也不会强制要求登录微软账户。

**第二种方法**

1. 不需要断网。当出现添加微软帐号的界面，提示登录微软账户的时候。**这时我们要输入一个假账户。**

2. 这个假账户，也不是随便写一个都行。经过测试有一些可行。例如：

    > no@thankyou.com
    >
    > 0@0.com
    >
    > 1@1.com
    >
    > 2@2.com
    >
    > 3@3.com
    >
    > ......

    **密码请随意输入。**

3. 点击“登录”后，会提示：哎呀，出错了。然后点击“下一步”将自动弹出本地账户设置的界面。

    从弹出的介绍来看，因为输入密码错误次数过多，暂时锁定了微软账户，才允许下一步使用本地账户登录。也就是说，如果你用一个真实的微软账户登录，密码输入错误几次是不是也行？（账户会被锁定）

> 友情提示：有一些不太文明的账户是不行的，比如sb@fuck.com、no@qnmlgdsb.com。其他随意虚构的账户大多数也不行。目前只发现上面介绍的那些可行。

### 长虹电视无法直接安装apk文件解决

> 摘自https://blog.csdn.net/weixin_42525369/article/details/117540484

大概步骤：使用爱游戏（系统自带的应用）下载一个应用”安装“（到真安装时候点取消，就是只下载一个安装包就好），然后用欢视助手安装小白文件管理器以进行文件操作。此时软件都准备就绪。然后插入U盘，将准备好的apk文件移动到`egame/downloader`下，并替换成游戏的名字（一串数字），然后进入爱游戏，安装”游戏“即可顺利安装

### Opera浏览器许多网页都打不开

大概率是CN区被什么原因搞了，导致local state文件中定义为cn的全无法打开网页，可以尝试将cn改为HK、US等即可解决

文件位置：[用户目录]\AppData\Roaming\Opera Software\Opera GX Stable或[用户目录]\AppData\Roaming\Opera Software\Opera Stable下的`Local State`文件

修改字段："location":{"country":"CN","country_from_server":"CN"}  CN改成HK（香港）或者US（漂亮国）即可

### Windows家庭版升级专业版

一、品牌机"家庭中文版"升级"专业版"

步骤一、首先断开网络、断开网络、断开网络。这一步是很重要的，如果不断网，可能会收到无法升级的问题。

步骤二、点击“设置→激活→更改产品密钥”。输入下面的密钥，然后点击“下一步”。

    XWHF9-NJ9MR-7KKR3-PRWGG-WXCKG

步骤三、点击“开始”，接下来就是等待。它会自动重启电脑，重启成功后，升级完成，此过程耗费时间较短，大概用5分钟左右升级完成。

温馨提示：需要注意的是，上述密钥仅仅是用于升级，并不能激活。这种情况下，使用激活软件激活一下即可大功告成！

二、普通的"家庭版"升级"专业版"

除了上面的特殊情况以外，其他的家庭版均可以使用下面的通用密钥进行升级。当然这枚密钥也仅仅是升级，并不能激活。具体的操作方法与上一节完全相同，只是使用的密钥不同而已，步骤不再赘述。

    专业版通用密钥：VK7JG-NPHTM-C97JM-9MPGT-3V66T

### 宽带连接命令行-自动任务连接宽带

rasdial [宽带名] [用户名] [密码]

如果需要自动启动，可以加入任务计划程序里

### 2023最新WPS教育版／专业版公开下载地址合集 

> 摘自微信公众号：阿虚同学

1


卸载旧版

还是和之前一样，下载软件之前，请一定先进行第一步：即完全卸载当前版本的WPS

请先用阿虚这篇文章中分享的专用卸载软件，卸载你目前安装的WPS

然后最好还是用这篇文章中分享的本地搜索软件：

分别以wps、kingsoft为关键词进行了全盘的搜索，然后删除相关的文件和文件夹

如果遇到删不掉的文件，务必重启后删除掉！

尤其是C:\ProgramData\Kingsoft\office6下的license2.dat这个文件一定要删掉！因为里面存储的是之前的激活信息！

然后当搜索结果为0的时候，就可以了安装下面的这些软件了



2


WPS教育版

阿虚对以下每个版本都进行了下载、安装、联网测试！确保都是直接安装可用的！

下面按版本号由新到旧排序，小标题后❌表示不可用VBA功能，✅表示可用VBA功能

2.1


洛阳理工学院❌

下载地址：https://www.lit.edu.cn/xxhjszx/info/1269/5945.htm

这个版本下载比较慢，请耐心等待下载

打开后具体为WPS 2022秋季更新（12358）版，具体版本号为11.1.0.12358，可以使用WPS宏，但不支持 Excel VB宏

也可正常使用WPS云文档等各种功能，由于是企业版，未见激活码授权时间，但应该是长期有效

2.2


西北工业大学✅

地址：https://it.nwpu.edu.cn/wps/wpsindex.jsp?urltype=tree.TreeTempUrl&wbtreeid=2436

建议下载多功能版，功能更丰富

打开后具体为WPS 2022秋季更新（12353）版，具体版本号为11.1.0.12353，可使用VB宏等专业版功能

也可正常登录使用WPS云文档等各种功能，由于是企业版，未见激活码授权时间，但应该是长期有效

2.3


石家庄信息工程学院❌

地址：https://www.sjziei.edu.cn/jyjszx/info/1162/1234.htm

打开为WPS 2019专业版11.8.2.11734，可使用JS宏、WPS宏等功能，但不支持Excel VBA宏功能

也可正常登录使用WPS云文档功能，虽然官网说明使用期限截止至2023年8月31日，但打开后实际计算授权时间为2023年12月08日

2.4


温州医科大学✅

地址：https://itc.wmu.edu.cn/info/1165/3364.htm

打开为WPS 2019专业版11.8.2.10912，可用VB宏等高级版功能

缺点是无法使用WPS云文档功能，虽然官网说明授权时间至2022年底，但打开后实际授权时间为永久无限制

2.5


温州大学✅

下载地址：http://sxy.wzu.edu.cn/info/1085/13370.htm

打开为WPS 2019专业版11.8.2.10154，可用VB宏等高级版功能

也可正常登录使用WPS云文档功能，具体授权时间为永久无限制

2.6


中国计量大学✅

地址：https://metc.cjlu.edu.cn/info/1087/1643.htm

打开为WPS 2019专业版11.8.2.10154，可使用VBA等高级版功能

也可正常登录使用WPS云文档功能，具体授权时间为永久无限制

2.7


大庆职业学院✅

下载地址：http://www.dqzyxy.net/xdjy/info/9377/58678.htm

实际提供的是WPS 2016 中国石油专用版，可使用VB宏等高级功能

能登录，但WPS云文档无法正常使用，授权无过期时间



3


政府版

其实政府版和很多学校提供的版本也没差，其实都是WPS专业版

3.1


聊城市✅

下载地址：http://wpspro.support.wps.cn/gov/shandong/liaocheng/download.jsp

打开为WPS 2019专业版11.8.2.11813，可使用VB宏等专业功能

也可正常登录使用WPS云文档功能，具体授权时间为2024年2月28日到期

3.2


广东省✅

下载地址：http://xtbg.gdzwfw.gov.cn/wpspkg/wpsupdate/Download/index.html

打开为WPS 2019专业版11.8.2.11718，可以使用VBA宏等专业功能

缺点是无法登录WPS，具体授权时间为永久无限制

3.3


云南省文山州✅

下载地址1：http://download.yngn.gov.cn/gnoa/bsys/login/d.html

下载地址2：http://www.yanshan.gov.cn/xz/

打开为WPS 2019专业版11.8.6.8722，可使用VBA宏等功能

可正常登录WPS，但貌似WPS云文档使用会有问题（无法加载云文档），具体授权时间为永久无限制

3.4


广东省政务服务数据管理局✅

下载地址：https://yzy.gdzwfw.gov.cn/download.html

版本为WPS 2016 10.8.2.7090，可使用VBA宏等功能

缺点是无法登录使用WPS云文档，激活时间为永久激活

3.5


大祥区党政门户网❌

下载地址：http://info.dxzc.gov.cn/Item/21126.aspx

此版本为WPS 2013 9.1.0.4337 专业版，压缩包内提供序列号，没有VBA宏功能，不能登录使用WPS云功能，没有过期时间

 

最后还是严正声明：本次分享的WPS专业版／教育版下载地址，仅限用于个人学习使用，不得用于任何商业行为！

### Window11修改回Windows10右键菜单

改win10：

`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

改win11：

`reg delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f`

### 火狐浏览器画面闪烁（尤其在鼠标经过时）

切换硬件加速的开启或禁用（网上说默认是开启（true），我的默认是false，切换成true反正可以了）

方法：

地址栏输入about:config，查找layers.acceleration.disabled，双击切换

### [F搜](https://fsoufsou.com)显示白屏，没有页面元素

原因是因为它的[资源网站](https://static.hetaousercontent.com)的证书到期了，所以浏览器默认阻止该网站的响应

只需要访问一下[资源网站](https://static.hetaousercontent.com)，也就是浏览器地址栏输入网址：https://static.hetaousercontent.com，然后点击接受风险，继续以访问之类的选项即可

之后就可以正常使用了

### 申请谷歌帐号/邮箱时，中国大陆号码无法验证

地区改成美国(US)即可

### WechatVideoDownloader下载失效解决

**WeChatVideoDownloader**由网友“**lecepin**”开发，与大多数视频号下载工具只支持 Windows 不同，软件 Windows 和 Mac 双支持。

并且，它还是**开源**的。

遗憾的是，该项目在 2022 年 5月停止了更新，好在软件的嗅探功能，依旧有效。

那要如何它来下载视频号呢？不是已经失效了吗？下面是复活的方法。

**1、安装证书**

下载打开软件后，会提示**安装证书**，软件采用了代理拦截请求的识别方式，所以**软件需要安装证书及开启代理**。

**注意**：如果一直抓取不到数据，请暂时关闭其它“**魔法**”软件。

Mac 的版本，则需要将信息复制到“**终端**”以确定安装证书。（要输入开机密码）

**2、打开视频号**

视频号的交互逻辑，是鼠标经过视频封面时，就会播放。

这时软件就会自动嗅探下载，如果你不想有太多的嗅探结果，**注意鼠标不要划过不想下载视频的封面。**

如果有太多链接，可以点“**清空**”按钮，刷新来重新获取。

**3、获取嗅探链接**

由于软件**许久没有更新**，在这一次视频号升级后，虽然软件依旧可以嗅探，但下载下来的**视频却无法播放了**。

这时，**三次点击链接，然后按 Ctrl+C 复制。**

这时，只需要把复制得到的链接，从 **20302** 改为 **20304**，即可获取原视频链接，比如：

原来复制的链接：

```python
https://finder.video.qq.com/251/20302/stodownload?encfilekey=6xykWLEnztKcKCJZcV0rWCM8ua7DibZkibqXGfPxf5lroyqume2xib2yxib7glOA4wqNXrm5o1WFM1OWIXSjr1rBYgEGHkQhaSWh19rtvgTMgn1ViazU1Z3sb5WSKZXDAJ9aK8RNFGicUMSxtkyIWBibiaMXctcYb733iaUyWIHWSv0GvaeA&a=1&bizid=1023&dotrans=0&hy=SH&idx=1&m=553b215c632b0f72db73b5604399ab23&web=1&token=6xykWLEnztK4PX62Ov4aiceeGWsFwiauM0qP9tj11yLYWtghpQYRePGFAoP0oVJXvzWfQ78dSzxibGJiceDV83FEiaoMWaiahREE86t5Jgr7M6c3c4zlHusQpav602iaZicx5gHJ&fexam=1&X-snsvideoflag=xV6
```


更改后的链接：

```python
https://finder.video.qq.com/251/20304/stodownload?encfilekey=6xykWLEnztKcKCJZcV0rWCM8ua7DibZkibqXGfPxf5lroyqume2xib2yxib7glOA4wqNXrm5o1WFM1OWIXSjr1rBYgEGHkQhaSWh19rtvgTMgn1ViazU1Z3sb5WSKZXDAJ9aK8RNFGicUMSxtkyIWBibiaMXctcYb733iaUyWIHWSv0GvaeA&a=1&bizid=1023&dotrans=0&hy=SH&idx=1&m=553b215c632b0f72db73b5604399ab23&web=1&token=6xykWLEnztK4PX62Ov4aiceeGWsFwiauM0qP9tj11yLYWtghpQYRePGFAoP0oVJXvzWfQ78dSzxibGJiceDV83FEiaoMWaiahREE86t5Jgr7M6c3c4zlHusQpav602iaZicx5gHJ&fexam=1&X-snsvideoflag=xV6
```

然后，将“**更改后的链接**”，放到 **IDM、NDM、迅雷** 等下载软件中下载即可。

注意，下载来的文件可能是 **.jpg** 后缀，改为 **.mp4** 即可。



上面的方法只是普通清晰度的，如何下载到超高清原版视频？

1、先将嗅探得到的链接，从 **20302** 改为 **20304**，比如：

```python
https://finder.video.qq.com/251/20304/stodownload?encfilekey=6xykWLEnztKcKCJZcV0rWCM8ua7DibZkibqXGfPxf5lroyqume2xib2yxib7glOA4wqNXrm5o1WFM1OWIXSjr1rBYgEGHkQhaSWh19rtvgTMgn1ViazU1Z3sb5WSKZXDAJ9aK8RNFGicUMSxtkyIWBibiaMXctcYb733iaUyWIHWSv0GvaeA&a=1&bizid=1023&dotrans=0&hy=SH&idx=1&m=553b215c632b0f72db73b5604399ab23&web=1&token=6xykWLEnztK4PX62Ov4aiceeGWsFwiauM0qP9tj11yLYWtghpQYRePGFAoP0oVJXvzWfQ78dSzxibGJiceDV83FEiaoMWaiahREE86t5Jgr7M6c3c4zlHusQpav602iaZicx5gHJ&fexam=1&X-snsvideoflag=xV6
```

2、将该链接复制到“**笔记本**”里，推荐用 Notepad2、Sublime Text 等带语法高亮的文本软件。

Ctrl+F 搜索 **&**，软件会高亮，然后将 **&token** 之外所有的 & 参数删除 。

只留下 **&token** 参数。

3、将清除 &token 之外所有参数的链接，复制到 IDM、NDM、迅雷 等下载软件中下载即可。

清除参数后的链接：

```python
https://finder.video.qq.com/251/20304/stodownload?encfilekey=6xykWLEnztKcKCJZcV0rWCM8ua7DibZkibqXGfPxf5lroyqume2xib2yxib7glOA4wqNXrm5o1WFM1OWIXSjr1rBYgEGHkQhaSWh19rtvgTMgn1ViazU1Z3sb5WSKZXDAJ9aK8RNFGicUMSxtkyIWBibiaMXctcYb733iaUyWIHWSv0GvaeA&token=6xykWLEnztK4PX62Ov4aiceeGWsFwiauM0qP9tj11yLYWtghpQYRePGFAoP0oVJXvzWfQ78dSzxibGJiceDV83FEiaoMWaiahREE86t5Jgr7M6c3c4zlHusQpav602iaZicx5gHJ
```

### 使用cmd或者powershell等系统命令行工具找不到winget命令（已在微软商店安装应用安装程序并更新到最新版本）

**第一种情况**是商店中的应用安装程序不是最新的，此时要去github下载最新版本：

下载地址：[Releases · microsoft/winget-cli (github.com)](https://github.com/microsoft/winget-cli/releases)

下载msixbundle后缀的文件并安装。

如果提示”若要使该应用良好运行，请尝试启用一个Windows应用包“ 或 这句话的英文，就是安装成功了

**第二种情况**是由于winget没有添加到环境变量Path中（完成第一种情况的安装后也可能出现这个问题）。

此时需要两步走：1. 确定winget命令的位置 2. 将路径添加到环境变量Path里

第一步我用了搜索工具everything，找到3个名为winget的可执行文件，其中一个文件有大小（13kb），两个没有大小（0kb）。经测试，三者都可用。猜测其中两个没有大小的是类似于快捷方式之类的东西。

将路径加入环境变量Path即可，我最后在环境变量Path中加入的是：

```
%LOCALAPPDATA%\Microsoft\WindowsApps
```

因为里面还有很多其他的系统命令，直接加这个一劳永逸，用其他命令也方便。

### 清理C盘（摘自公众号「麦叔编程」）

今天打开电脑准备工作时，发现C盘快爆了！

当初给C盘的80GB的空间，怎么现在只剩了不到2GB的空间？

我也没往C盘装软件，新装的软件都均匀的分布在其他三个盘中。

这就奇怪了，其他盘都没有这种“自身繁殖”的情况出生，唯独C盘有这个情况。

很多小伙伴肯定也很好奇，为什么C盘空间总是会存在不够用的情况？

无论分配多少空间给C盘，它总是会悄悄地变“满”。

而且C盘为系统盘，里面的文件还不太敢去删它。

今天我就不惯着它，就要动它了！
1. 分析C盘

先用自带的磁盘清理功能先收拾出9个G的空间：

再借助SpaceSniffer工具分析下C盘中空间的占用情况：

    SpaceSniffer工具下载地址：
    
    https://www.fosshub.com/SpaceSniffer.html

打开SpaceSniffer工具后选择C盘，点start按键：

然后就能得到一份C盘空间占用图：

根据此图可以看出，C盘被分成3个大的部分：

第一部分为用户数据部分；

而后两部分为系统文件和安装在C盘的软件，这两者我们最好不要去动它。

今天先拿大头AppData开刀，让它搬家！
2. 迁移AppData数据至其他盘

2.a. 为AppData创建新家，我在E盘创建了一个AppData的文件夹用来作迁移的目标路径：

2.b. 同时按下键盘上的win和r打开运行，在输入框输入regedit打开注册列表：

2.c. 定位到计算机\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Shell Folders位置：

双击打开AppData配置：

把当前配置AppData的路径换成它新家的路径，点击确定：

2.d. 再定位到计算机\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\User Shell Folders位置；

同样用第3步的操作，修改成它新家的路径：

修改后：

    %USERPROFILE%为系统变量设置的路径值，用set命令可以看%USERPROFILE%的值（路径）是什么。
    
    图片

上述4步操作做完后我们就可以搬家了！

开始搬AppData

    如果怕有风险的话，可以先备份下数据。

3. 迁移/清除pip缓存数据

在迁移AppData的时候我发现pip cache在C盘里竟然占有4个G的空间。

看来Python也在C盘扎根了。

如果pip缓存文件没啥用的话可以直接使用以下命令直接进行清理：

pip cache purge

清理完之后不想再让pip命令在C盘产生缓存的话，可以使用pip命令重新定义pip缓存路径：

更改pip cache 位置

pip config set global.cache-dir "d:\pythonpipcache"

修改完成后，使用以下命令查看修改后的pip缓存路径。

pip cache dir

    这样操作之后，又给C盘腾出了4个G的空间。

4. 吃C盘大户--WPS

我还发现这WPS也是C盘大户，我也准备让他滚蛋。

    我们在使用office或wps的时候总会产生一些缓存文件用作备份，或者用于Ctrl+Z操作，所以这些办公软件也需要搬家。

搬WPS，我们只要在软件打开后设置下就行了。

把备份放到非C盘就OK了

**最后**

经过以上一系列操作，我终于把C盘重新腾出了近20个G的可用空间。

目前还没感知到任何C盘搬家产生的不良后果。

### Foobar 2000午饭播放m4a, awb, amr等少见音频格式

详见文章：https://zhuanlan.zhihu.com/p/69091833

### 安卓手机自动跳广告

>  以下摘自公众号「阿虚同学」

前段时间各大知名启屏广告自动跳过 APP，诸如李跳跳、叮小跳、蹦跶、大圣净化、一指禅等因收到律师函而停止更新维护的事情闹得人心惶惶

不少粉丝就开始担心起来「今后怎么办啊？」的问题

1 自定义规则

虽然 APP 被迫下架这事令人神伤，但大家其实完全没必要为再没有同类 APP 可用这事担心

首先就是这类 APP 都是依靠安卓系统的无障碍服务，在 APP 启动时模拟人工点击跳过按钮来实现自动跳过开屏广告，实际都是无需联网即可使用的

只不过因为每个 APP 的广告关闭按钮位置都不相同，联网权限只是作者为了给你更新不同 APP 的对应规则

简单来说，就是虽然在应用市场被下架了，但完全不影响 APP 的继续使用！尽管作者以后都不会再更新规则了，但你完全可以自行添加规则继续使用

1.1 简单类

而这类热门的 APP 几乎都是支持自行添加规则的，比如李跳跳

在李跳跳 APP 内，点击更多 » 设置 » 找到你要添加规则的APP，比如中国电信

然后根据不同情况进行添加即可，例如中国电信这个 APP 这种比较简单的开屏广告，我们通过开屏广告的文字按钮即可进行定位，那在第 4 步中就没必要用手势点击，直接设置按钮的文字即可

这样我们就非常轻松的配置好了一条自动跳过广告的规则，在 APP 显示跳过按钮的一瞬间，李跳跳就会自动帮你点击

像中国电信这类 APP，算是最简单的一类，有很明显的跳过按钮，也有文字内容以供李跳跳获取按钮位置

1.2 无文字类

但经常也会有一类 APP 像下面这样，仅在不明显的位置有一个 X 按钮以供关闭

对于这种弹窗开屏广告，如果你想要使用李跳跳来跳过，我们需要得知这个关闭按钮代码层面的 id 或者 bounds

当然我们仅凭截图是没办法获取的，我们可以用 AutoX.js（http://doc.autoxjs.com/）或者阿虚之前介绍过的 Hamibot（https://hamibot.com/）来获取

如果你访问Github困难，建议了解《2022 Github加速访问教程》

阿虚这里用 AutoX.js 来演示一下，安装好 APP 之后点击左上角设置把悬浮窗功能打开

接着打开你要跳过广告的 APP，在广告界面，点击 AutoX.js 的悬浮窗功能，选择布局范围分析，接着点击广告弹窗的关闭按钮，选择查看控件信息，在这里我们点击一下就能复制这个关闭按钮的 bounds 信息（往下翻也可以找到 id 信息，不过一个控件是有可能没有 id 的，但一定会有 bounds）

最后就只需要到李跳跳中，添加跳过规则就行了，注意 bounds 信息在填写的时候要删掉多余内容

1.3 随机 bounds 一类

不过现在很多 APP 也学聪明了，为了避免李跳跳一类的 APP 跳过广告，不仅弹窗广告的关闭按钮控件没有 id，还给你弄了一个随机 bounds——这样自然李跳跳就失效了，因为它无法定位关闭按钮的位置

不过好在问题不大，除了李跳跳我们还有很多 APP 可以考虑，比如轻启动、叮小跳

这俩 APP 同样依靠无障碍服务来运行，但添加规则的方式会更加简单一点，他们都是依据屏幕位置来判断并跳过广告，只要 APP 的广告关闭按钮不是每次都随机位置，就能轻松应对

而轻启动创建规则的方法也相当简单，开启自定义规则功能之后，会有一个悬浮窗按钮。打开 APP 的广告页面，点击悬浮窗，接着就会让你点击广告关闭按钮的位置，你只需要确认并添加规则即可

1.4 应用内广告

不过李跳跳有个强大之处在于，还可以应对一些更复杂的广告，比如微信朋友圈广告图片

同样用 AutoX.js 查看控件信息（朋友圈是上下滑动的所以不能用 bounds）可以看到广告按钮的 ID 是 hs

接着再进一步，更多按钮（那个向下的小箭头）的 id 为 ht

然后我们先在李跳跳内写好规则，返回微信朋友圈你会发现已经自动点击了广告

接着如法炮制，这个新界面的 id 和关闭广告按钮的 id 分别为 jpa 和 jp5

同样的步骤，在里跳跳中依次设置好

同样的方法，查看关闭该广告的原因和直接关闭两个选项的 id，分别为 jpa 和 jp0

依次在李跳跳中添加即可（不得不说微信关闭个广告真的麻烦），最后所有代码是这样的（长按应用图标可以看见实际代码规则）

当你学会了这招的，就可以实现跳过一些应用内的广告，整个 APP 大有可为

注意这种方法对于滑动过程中出现的广告没有用，因为李跳跳只会在新界面打开时监控屏幕内容，不会一直监控。就比如刚进来可以，看了别人朋友圈返回后也生效

2 LiTiaotiao-Custom-Rules

显然，一般用户使用李跳跳的最大阻碍其实就是上面阿虚介绍的自定义规则——更多的用户还是只适合装上 APP 就能用

阿虚也说过，这世界不缺少英雄——在李跳跳收律师函下架停更之后没多久，Github 上就有一位名为@FW27623的用户站出来开始维护一份公开的李跳跳自定义规则

这个开源项目，专门帮你收集了适用于李跳跳的自定义跳过规则，涉及了上百个 App，318 条规则

你要做的仅仅是打开下方地址，点击「复制」按钮：https://fw27623.github.io/LiTiaotiao-Custom-Rules/

备用地址：https://ossso.github.io/LiTiaotiao-Custom-Rules/、https://snoopy1866.github.io/LiTiaotiao-Custom-Rules，另外如果你发现在线规则网站里的规则无法显示，多半是你的网络环境出了问题，点击「JsDelivr」加速即可

然后回到李跳跳 APP 中，点击更多 » 右上角··· » 导入规则，在李跳跳中长按输入框，粘贴刚刚复制的所有内容即可~

该项目作者提供了两种规则，一种是基础规则，一种是增强规则。增强规则是一些自动化的操作。上面在线规则网站提供了基础规则和所有规则，我们选择最全的所有规则即可！

就这么简单，你就轻松的实现了市面上绝大多数 APP 的广告自动跳过~

3 开源跳过广告APP

都说开源是一种精神，它为自由平等而生

在李跳跳一事发生之后，网上就渐渐开始流传开源的自动跳过广告 APP（代码开源意味着人人都可以轻松开发类似的 APP）

3.1 GKD

这里先介绍一个名为 GKD（搞快点）的项目：https://github.com/gkd-kit/gkd

如果你访问Github困难，建议了解《2022 Github加速访问教程》

主要是 LiTiaotiao-Custom-Rules 项目的作者表示：李跳跳自定义规则的局限性，很多弹窗无法编写规则关闭，所以那个项目后续不会再更新应用内广告和弹窗规则

那个作者建议是：如果你有关闭开屏广告以外的需求（跳 APP 内的广告），建议切换至 GKD 使用，GKD 默认订阅后续他会将持续更新

以后有人帮忙更新规则，那不香吗

不过如果没有上述项目，其实这个 APP 局限性还挺大，主要是虽然 APP 功能强大，但缺乏简单的自定义性，想在这个 APP 添加自定义规则需要纯手写代码

这个 APP 的优点就在于：内置订阅规则，装上就能用

市面上大部分 APP 的开屏广告／应用内部任意弹窗广告，它都能跳过（比如百度贴吧帖子广告卡片／知乎回答底部推荐广告卡片）

同时一些快捷操作，如微信电脑登录自动同意／微信扫描登录自动同意／微信自动领取红包这些也是内置有规则

可以算作是懒人首选吧，或者说建议用于搭配其他可以轻松自定义规则的 APP 使用（比如李跳跳、轻启动、叮小跳）

3.2 开屏跳过

开屏跳过，算是李跳跳倒下之后，快速崛起的一颗新星，短短时间内就收获 4000 多星标：https://github.com/zfdang/Android-Touch-Helper

如果你访问Github困难，建议了解《2022 Github加速访问教程》，另外除了在Gituhb（注：Github上下载后需要解压），你也可以在项目官网下载到 APP：https://touchhelper.zfdang.com/

APP 仅 1MB 大小，功能却相当之强大！

可以设置广告按钮的关键词直接适配绝大多数 APP 的开屏广告

同时除了可以通过控件方式获取广告关闭按钮，也支持直接获取屏幕坐标，有了这两大方式可以说能应对几乎所有类型的开屏广告

不过注意，这个 APP 的使用交互还是有点问题，当你进入创建规则模式之后，无论是你点击了「添加控件」还是「添加坐标」，在添加完成之后点击「退出」就已经是成功创建规则了（作者其实改把退出按钮改名为创建）

但实际上，这个项目应该是最近才被人挖出来，再经由软件圈子传播突然火起来的，其实项目早在 2020 年 10 月就开源了图片

但显然作者自己都没想到这个项目突然能火，上个月更新了项目说明，加了以下这几行字：

显然这个 APP 最大的缺点就是以后可能会缺少维护和更新了~

3.3 TapClick

不过，阿虚还替大家翻出了另一个老东西

TapClick，同样是一款基于无障碍服务的自动化点击工具，首个版本提交于 2020 年 2 月，比上述该项目都还早，关键是时至如今还在持续更新中：https://github.com/LGH1996/TapClick

如果你访问Github困难，建议了解《2022 Github加速访问教程》

最关键的是，这款 APP 和开屏跳过一样强大！同样可以通过控件方式获取广告关闭按钮，也支持直接获取屏幕坐标，你还会发现两款 APP 的添加规则界面都几近相同（都是开源软件，其实谁借鉴谁这个不太重要）

不过也是一样，这个 APP 在创建规则模式模式下，添加控件或者添加坐标之后，点击退出就是创建规则了

还有一点要说明的是：添加规则时，首选添加控件，其次才是添加坐标，因为坐标检索的效果远没有控件检索的效果好，其具有很大的不确定性，一般还要额外设置合适的点击次数和延迟点击时间，只有在页面无控件可用时才会考虑添加坐标

更多 APP 的使用说明和细节可以详见项目说明，总的来说和一般的自动跳过 APP 差别不大，很容易就能上手

3.4 SKIP

SKIP 的翻译成中文就是跳过的意思，同样也是借助无障碍权限来实现广告自动跳过，首个版本提交于 2022年6月：https://github.com/GuoXiCheng/SKIP

如果你访问Github困难，建议了解《2022 Github加速访问教程》

不过这个 APP 主打一个开箱即用，能适配绝多大多数常见 APP 的开屏广告

相对于上述项目，功能就比较简陋了，缺乏自定义规则等功能，不过可以收藏一个期待作者继续优化，毕竟项目还在持续更新中

李跳跳、叮小跳、轻启动这些 APP 阿虚这里就不提供下载地址了哈，提供了的话这篇文章就危险了

这些 APP 仅是在各大应用市场下架而已，你只需要稍微百度一下，其实很容易就能找到 APP 下载地址

最后总结一下这篇文章，阿虚个人认为可以把：

        李跳跳单独归位一类（需要搭配 AutoX.js 或者 Hamibot）
    
        叮小跳、轻启动分为一类
    
        GKD、SKIP分为一类
    
        开屏跳过、TapClick分为一类

GKD 搭配后续的 LiTiaotiao-Custom-Rules 项目规则，应该算是一个比较懒人的办法，比较推荐

开屏跳过、TapClick 在针对开屏广告自定义规则这块比较全能，推荐任装一个

李跳跳搭配叮小跳、轻启动也能应对绝大多数情况（包括应用内广告），也值得推荐

### Edge最新版本找不到侧边栏

应该是被识别到在国内，然后隐藏了Copilot

在地址栏输入`edge://settings/sidebar/Appsettings?hubApp=cd4688a9-e888-48ea-ad81-76193d56b1be`，打开`始终显示边栏`即可启用侧边栏，但还是无法使用Copilot

正解是下载国外语言的Edge安装包，安装及使用时要保证梯子一直挂着，并且实测V2Ray不行，就得用Clash（但是Clash已经挂了，且用且珍惜）

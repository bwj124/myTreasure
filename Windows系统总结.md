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
   <img src="C:\Users\hp\AppData\Roaming\Typora\typora-user-images\image-20200522181450700.png" alt="image-20200522181450700" style="zoom:50%;" />

6. 点击其他选项，去掉对勾

   <img src="C:\Users\hp\AppData\Roaming\Typora\typora-user-images\image-20200522181536531.png" alt="image-20200522181536531" style="zoom:50%;" />

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

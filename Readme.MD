![image](https://github.com/AngleHony/WKTools/blob/main/Process_en.bmp)

### About open source

 **I don't plan to share the source code. If you can't accept it, please close the page**

System Support Win7X64 (7601)        Win10X64 (19041,19042,19043,19044,19045)  Win11(22000,22621,22631)

EN:

Change log：

V1.0.0.18（2024-5-7）

1.Change Signature, Fix  ErrorCode 0x800b010c Certificado explicitamente revogado por seu emissor.

V1.0.0.17（2024-2-5）

1.fix some bug

2.Add win11 22631 support

V1.0.0.16（2023-8-4）

1.fix some bug

2 add  show and operate process windows Protect  (PROCESS--->RightClick--->View Process Windows-->RightClick) To  disable App Anti Capture Screen

V1.0.0.14（2023-7-22）

1.fix some bug

- Update the prompt every time you open it
- Driver Load Fail Beacuse signature verification failed

V1.0.0.13（2023-5-11）

1.fix some bug

2.Add Show IRP_UNLOAD address

3 Add Show Protected Process Light(PPL)

V1.0.0.12（2023-03-05）

1.fix some bug

2.Add Scan All Process hook

3  Enhance Inline hook Check

V1.0.0.11（2022-10-31）

1.fix some bug

2.Add Support  19045 22621

V1.0.0.10（2022-05-21）    

1.fix some bug            

2 Add Enum IoRegisterLastChanceShutdownNotification, SeFileSystemCallBack.

3 Enhance Object Hook Enum(CallBack Object).

Change log：
V1.0.0.9（2022-04-16）    

1.fix some bug            

2 Add Other System  check 

3 Enhance Reg Operate

4 Add Forbidden Reg Operate Function

V1.0.0.8（2022-03-20）    

1.fix some bug            

2 Add Show Service PID

3 Add Service Jmp to Process

V1.0.0.7（2022-03-05）    

1.fix some bug        

2.Complete Autorun Manager enum

3.Add Check RPC HOOK

4 Add Show Session ID

V1.0.0.6（2022-01-26）    

1.fix some bug        

2.Complete Standard Filter enum

3.Add Enum IRP Filter

V1.0.0.5（2022-01-19）    

1.fix some bug        

2.Add Decompilation FORWORD&&Back

3.Complete SPI info Show

V 1.0.0.4（2022-01-16）        

1.fix some bug

2.Add Enum && Operate WFP Filter

V1.0.0.3（2021-12-31）Happy New Year

1.fix some bug

2.Add show Process parameters

3 Add EnumDriver IRP Info

4 Chnage Hook Dialog View

V1.0.0.2（2021-12-26）

1.fix some bug

2.Add Win11 22000 System support

3 Add Windows ProcessKernelCallBack hook check

4 Add minifilter check

V1.0.0.1（2021-10-06）

1.fix some bug

2.Add Win10 xxxx System support

V0.0.0.5bet(2021-09-19）

1.fix some bug

2.Add Win10 xxxx System support

V0.0.0.4beta（2020-11-7）

1.fix some bug

V0.0.0.3beta（2020-07-23）

1.fix some bug

V0.0.0.2beta（2020-03-15）

1.fix some bug

V0.0.0.1beta (2019-09-16)

1.first version

*Process Manager

Display system process and thread basic informations.

Detect hidden processes,threads,process modules.

Terminate, suspend and resume processes and threads.

View and manipulate process handles,windows and memory regions.

View and manipulate process hotkeys,privileges,and timers.

Detect and restore process hooks incluing inline hooks,patches,iat and eat hooks, ProcessKernelCallBack hook.

Inject dll,

dump process memory.

Create debug dump,inclue mini dump and full dump.

*Kernel Module Viewer

Display kernel module basic information,include image base,size,driver object,and so on.

Detect hidden kernel modules.

Unload kernel modules.

Dump kernel image memory.

Display and delete system driver service informations.

View Driver IRP Info

*Hook Detector

Detect and restore SSDT,Shadow SSDT,sysenter and int2e hooks.

Detect and restore FSD and keyboard disptach hooks.

Detect and restore kernel code hooks including kernel inline hooks,patches,iat and eat hooks.

Detect and restore message hooks,both global and local.

Detect and restore kernel ObjectType hooks.

Display Interrupt Descriptor Table(IDT).

*Other Kernel Information Viewer

View and remove kernel notifications.

View filters for common devices include disk,volume,keyboard and network devices. 

View IO timers,DPC timers,system threads,and so on.

*Registry Manager

View and edit system registry.

Detect hidden registry entries using live registry hive analysis.

*File Manager

Display file basic information,include file name,size,attributes,and so on.

Detect hidden files.

View and delete locked files and folders.

*Service Manager

Display system services basic informations.

Control services status.

Modify services startup type.

*Autorun Manager

Display almost all kinds of system autorun types.

Enable,disable or permanently delete autoruns.

*Network Viewer

Display current network connections,include TCP and UDP informations.

View and delete IE plugins and context menu.

Display winsock providers(LSP).
View and edit hosts file.

View WfpCallout

说明：

系统支持Win7X64 (7601)        Win10X64 (19041,19042,19043,19044,19045)  Win11(22000,22621)

本工具目前实现功能如下（包括但不限于）：

更新日志：

1.0.0.18（2024-5-7）

1.更新证书,修复签名吊销问题 

1.0.0.17（2024-02-05）

1.修复若干bug

2.支持win11 22631

1.0.0.16（2023-08-04）

1.修复若干bug

2.新增展示和修改进程窗口保护功能(进程-->右键-->查看进程窗口-->右键) 可以用来移除应用反截图功能

1.0.0.14（2023-07-22）

1.修复若干bug

驱动签名吊销

循环提示更新

1.0.0.13（2023-05-11）

1.修复若干bug

2.增加 IRP_UNLOAD 地址展示

3 增强 Protected Process Light（PPL）展示

1.0.0.12（2023-03-05）

1.修复若干bug

2.增加枚举所有进程hook 功能

3 增强 Inline hook 检测

1.0.0.11（2022-10-31）

1.修复若干bug

2.适配 19045 22621

1.0.0.10（2022-05-21）    

1.修复若干bug        

2 增加枚举注册表回调, 注销回调枚举。

3 增强Object Hook 枚举(CallBack Object)

1.0.0.9（2022-04-16）    

1.修复若干bug        

2 增加系统杂项检测

3 增强注册表操作

4 增加注册表禁用功能

1.0.0.8版本（2022-03-20）    

1.修复若干bug

2 增加服务进程ID显示

4 增加服务跳转到进程

1.0.0.7版本（2022-03-05）    

1.修复若干bug

2.完善开机启动项枚举

3 增加RPC HOOK枚举

4 增加Session ID 显示

1.0.0.6版本（2022-01-26）    

1.修复若干bug

2.完善过滤驱动枚举逻辑

3 增加IRP枚举过滤

1.0.0.5版本（2022-01-19）    

1.修复若干bug

2.新增反编译器前进后退操作

3.区分32&&64 SPI信息

1.0.0.4版本（2022-01-16）        

1.修复若干bug

2.新增Wfp Filter 操作    

1.0.0.3版本（2021-12-31）新年快乐

1.修复若干bug

2.新增进程命令行参数显示

3 新增枚举驱动IRP信息

4 修改钩子界面布局

1.0.0.2版本（2021-12-26）

1.修复若干bug

2.新增Win11 22000 系统适配

3 新增Windows Process KernelCallBack hook 检测

4 增加minifilter检测

1.0.0.1版本（2021-10-06）

1.修复若干bug

2.新增Win10 xxxx 系统适配

0.0.0.5beta版本（2021-09-19）

1.修复若干bug

2.新增Win10 xxxx 系统适配

0.0.0.4beta版本（2020-11-7）

1.修复若干bug

0.0.0.3beta版本（2020-07-23）

1.修复若干bug

0.0.0.2beta版本（2020-03-15）

1.修复若干bug

0.0.0.1beta版本 (2019-09-16)

1.首版本

1 进程:

查看模块

查看窗口

查看内存

查看热键

查看定时器

查看Ring3 HOOK

查看ProceeKernelCallBack

查看.......

关闭进程

关闭线程

卸载模块

拷贝进程内存

查找进程模块

创建进程调试DUMP

注入模块

进程隐藏
    ..........

2 内核驱动

查看内核模块加载

查看内核模块启动方式

内核驱动模块的内存拷贝

卸载驱动内核模块

修改驱动驱动方式

查看IRP信息
    ......

3 钩子

SSDT 查看与恢复

SSSDT 查看与恢复

FSD 查看与恢复

键盘 查看与恢复

鼠标 查看与恢复

Disk 查看与恢复

Atapi 查看与恢复

ACPI 查看与恢复

TCPIP 查看与恢复

IDT 查看与恢复

OBJECT 查看与恢复

Kernel 查看与恢复

MessageHook 查看与恢复

4 Notify

CreateProcess ,Ex,Ex2查看与删除；

CreateThread          查看与删除；

LoadImage              查看与删除；

Registry              查看与删除；

Shutdown             查看和删除；

5     DPC和IO定时器等内核定时器的查看和删除；

6    系统线程的查看和结束；

7    磁盘、卷、键盘、网络层等过滤驱动的枚举；

8    MiniFilter 查看和删除；

9    注册表编辑器

10    文件管理器

11    系统服务的枚举和操作；

12  网络连接, LSP, WFP ......

13  Other..............

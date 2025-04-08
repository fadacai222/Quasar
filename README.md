# Quasar

[![构建状态](https://ci.appveyor.com/api/projects/status/5857hfy6r1ltb5f2?svg=true)](https://ci.appveyor.com/project/MaxXor/quasar)
[![下载量](https://img.shields.io/github/downloads/quasar/Quasar/total.svg)](https://github.com/quasar/Quasar/releases)
[![许可证](https://img.shields.io/github/license/quasar/Quasar.svg)](LICENSE)

**免费开源的Windows远程管理工具**

Quasar是一款用C#编写的快速轻量级远程管理工具。其用途涵盖从用户支持到日常管理工作，再到员工监控。凭借高稳定性和易用的用户界面，Quasar是您理想的远程管理解决方案。

请查看[入门指南](https://github.com/quasar/Quasar/wiki/Getting-Started)。

## 截图

![远程终端](Images/remote-shell.png)

![远程桌面](Images/remote-desktop.png)

![远程文件](Images/remote-files.png)

## 功能特性
* TCP网络流（支持IPv4和IPv6）
* 快速网络序列化（Protocol Buffers）
* 加密通信（TLS）
* UPnP支持（自动端口转发）
* 任务管理器
* 文件管理器
* 启动项管理器
* 远程桌面
* 远程终端
* 远程执行
* 系统信息
* 注册表编辑器
* 系统电源命令（重启、关机、待机）
* 键盘记录（支持Unicode）
* 反向代理（SOCKS5）
* 密码恢复（常见浏览器和FTP客户端）
* ...以及更多功能！

## 下载
* [最新稳定版](https://github.com/quasar/Quasar/releases)（推荐）
* [最新开发快照版](https://ci.appveyor.com/project/MaxXor/quasar)

## 支持的运行环境和操作系统
* .NET Framework 4.5.2或更高版本
* 支持的操作系统（32位和64位）：
  * Windows 11
  * Windows Server 2022
  * Windows 10
  * Windows Server 2019
  * Windows Server 2016
  * Windows 8/8.1
  * Windows Server 2012
  * Windows 7
  * Windows Server 2008 R2
* 对于更旧系统，请使用[Quasar 1.3.0版本](https://github.com/quasar/Quasar/releases/tag/v1.3.0.0)

## 编译
使用已安装.NET桌面开发功能的Visual Studio 2019+打开项目`Quasar.sln`，并[还原NuGET包](https://docs.microsoft.com/en-us/nuget/consume-packages/package-restore)。所有包安装完成后，可通过顶部点击`生成`或按`F6`键常规编译项目。生成的执行文件位于`Bin`目录。请参考下方选择合适的生成配置。

## 构建客户端
| 生成配置         | 使用场景       | 说明  
| ----------------|--------------|--------------
| Debug配置       | 测试环境      | 将使用预定义的[Settings.cs](/Quasar.Client/Config/Settings.cs)文件，编译前请编辑此文件。客户端可直接运行并应用指定设置。
| Release配置     | 生产环境      | 运行`Quasar.exe`并使用客户端构建器。

## 贡献指南
参见[CONTRIBUTING.md](CONTRIBUTING.md)

## 发展路线
参见[ROADMAP.md](ROADMAP.md)

## 文档
使用说明及其他文档请参阅[wiki](https://github.com/quasar/Quasar/wiki)

## 许可证
Quasar采用[MIT许可证](LICENSE)分发。  
第三方许可证参见[此处](Licenses)。

## 致谢
我们非常重视各种反馈和贡献。感谢您使用和支持Quasar！

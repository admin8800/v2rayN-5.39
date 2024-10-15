### v2rayN-5.39旧界面版

下载`.NET Framework 4.8`：https://dotnet.microsoft.com/zh-cn/download/dotnet-framework/net48

`SDK`包和`运行时`都要下载安装。

下载`.NET 6 SDK`：https://dotnet.microsoft.com/zh-cn/download/dotnet/6.0

添加变量：此电脑 → 高级系统设置 → 环境变量 → 系统变量 → `Path` → 新建 → 填入`C:\Program Files (x86)\dotnet` → 确认

检查安装：`dotnet --list-sdks`

下载本项目，然后`cd v2rayN`

链接路径`v2rayN\Global.cs`

按钮文字路径`v2rayN\Forms\MainForm.zh-Hans.resx`



构建命令
```
dotnet build --configuration Release
```

> 构建完成后的文件在`bin`目录

---


清理
```
dotnet clean
```
构建
```
dotnet build
```

- v2rayN-5.39旧版
- 可运行在win7系统

win11编译

下载vscode：https://code.visualstudio.com

下载`.NET 6 SDK`环境，选择`x64`版本：https://dotnet.microsoft.com/zh-cn/download/dotnet/6.0

[查看教程图](https://private-user-images.githubusercontent.com/153331261/383936037-d8ad0b09-e327-4bd5-9ead-530694a367df.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzA5ODczNjEsIm5iZiI6MTczMDk4NzA2MSwicGF0aCI6Ii8xNTMzMzEyNjEvMzgzOTM2MDM3LWQ4YWQwYjA5LWUzMjctNGJkNS05ZWFkLTUzMDY5NGEzNjdkZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTA3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEwN1QxMzQ0MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04MDQ4N2UzOTFhYjEwNTkwZThhOWMyYjM0NjRjMmEwMWYwNDg2Yzk2ZjZiNTg1NjE2YTA0OGEzMjQxMmM5NjM1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.UQkbONojXVqCopAjqACGUUoNtii2yNFkw9dWCp_OJOU)

添加变量：此电脑 → 高级系统设置 → 环境变量 → 系统变量 → `Path` → 新建 → 填入`C:\Program Files\dotnet` → 确认

> 或者直接用CMD命令设置`setx PATH "%PATH%;C:\Program Files\dotnet" /M`

检查安装：`dotnet --list-sdks`

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

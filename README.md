<p align="center">
  <img src="https://github.com/Glidema/Swift-Fox-Cleaner/blob/main/AppIcon.png?raw=true" alt="灵狐清理大师图标" width="200"/>
</p>

<h1 align="center">灵狐清理大师</h1>

灵狐清理大师是一款专为 Mac 用户设计的智能清理工具。无论你是技术小白还是资深用户，这款应用都能帮助你轻松管理电脑的存储空间。通过简单的几步操作，清理大师可以自动清理缓存文件、临时文件和不必要的垃圾文件，释放更多的存储空间。

## 主要功能

- **选择性清理**：用户可以根据需要选择清理浏览器缓存、系统日志、应用程序临时文件等。
- **智能备份**：在清理前自动备份重要文件，确保数据安全。
- **空间监控**：当磁盘空间低于设定阈值时，自动提醒用户进行清理。
- **定期清理**：可以使用 Mac 的自带工具如"自动操作"或"日历"来定期运行。例如每周自动运行一次，保持电脑整洁。
- **详细日志**：每次清理后生成报告，方便用户查看清理效果。

## 使用体验

灵狐清理大师界面简洁友好，只需点击几下即可完成复杂的清理任务。它能够有效提升电脑性能，让你的 Mac 运行如新。

## 开始使用

1. 下载：
   - 访问我们的 [GitHub Releases](https://github.com/Glidema/Swift-Fox-Cleaner/releases) 页面。
   - 下载最新版本的 `app.zip` 文件。

2. 安装：
   - 解压下载的 `app.zip` 文件。
   - 将解压出的 `灵狐清理大师.app` 移动到您的"应用程序"文件夹或您喜欢的任何位置。

3. 使用：
   - 直接双击 `灵狐清理大师.app` 即可运行程序。
   - 在首次运行时，macOS 可能会显示安全警告。如果出现此情况，请在"系统偏好设置"的"安全性与隐私"中允许运行。
   - 程序启动后，按照界面提示选择要清理的项目，然后点击相应按钮开始清理。

注意：虽然应用程序可以直接使用，但我们仍建议在首次使用前备份重要数据，以确保数据安全。

如果您希望设置定期自动清理：

1. 打开 Mac 自带的"自动操作"应用程序。
2. 创建一个新的日历提醒任务。
3. 添加"运行 AppleScript" 操作，并设置为打开 `灵狐清理大师.app`。
4. 保存任务，并在"日历"应用中设置重复周期。

## 几点补充说明（这是基于脚本打包成应用的工具）：

- 这个应用程序可以被移动到你想要的任何位置，甚至可以添加到 Dock 栏中以方便访问。

- 如果你之后想要修改脚本，你可以右键点击这个 .app 文件，选择 "显示包内容"，然后导航到 Contents > Resources > Scripts 文件夹。在这里你会找到一个 main.scpt 文件，你可以用脚本编辑器打开并编辑它。

- 如果你想设置这个应用程序定期自动运行，你可以使用 macOS 的 "日历" 应用或 "自动操作" 功能来实现。

- 请记住，由于这个脚本涉及到系统清理操作，首次运行时可能会要求输入管理员密码或请求一些权限。

- 如果你想给应用程序添加一个自定义图标，你可以右键点击 .app 文件，选择 "显示简介"，然后将你喜欢的图标拖到左上角的应用程序图标上。

这样，你就有了一个可以随时运行的独立清理应用程序，既方便又灵活。

## 支持

如果您在使用 灵狐清理大师 时遇到任何问题或有任何建议，我们随时欢迎您的反馈：

- 问题报告：请访问我们的 [GitHub Issues](https://github.com/Glidema/Swift-Fox-Cleaner/issues) 页面提交问题。
- 功能建议：您可以在 Issues 页面提出新功能建议，或直接提交 Pull Request。
- 邮件支持：如果您需要更直接的帮助，请发送邮件至 naxiaoduo001@gmail.com 。

我们会尽快回复您的问题和建议。

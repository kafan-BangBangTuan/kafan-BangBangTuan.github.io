**### 软件介绍**
MathType 是西班牙 WIRIS 公司旗下的一款功能强大的数学公式编辑器，它可以与常见的文字处理软件和演示程序配合使用，能够在各种文档中加入复杂的数学公式和符号。

![image](https://github.com/user-attachments/assets/3770f29c-29da-47f1-b6f0-a410823eabf4)
**已知问题 & 解决方案**
### 1.在 WPS Office 中调用 MathType 时，出现【安全申明】对话框
当您尝试在 WPS Office 中插入 MathType 公式时，可能会出现【】WPS Office 安全申明】对话框，（检测到试图通过 API 调用公式编辑器的行为，这可能会危害您的计算机和数据）。这是因为 MathType 与 WPS Office 自带的【公式编辑器 3.0】程序实际上均为同一开发商的产品，在安装 MathType 后，它会自动接替自带的【公式编辑器 3.0】功能。因此，您可以放心忽略警告。

### 2.在 WPS Office 中无法正常使用 MathType
MathType 依赖于 VBA ，但 WPS Office个人版暂不支持 VBA ， 请尝试更换专业版或安装 VBA 增强包（见附件）。
[wpsvba7.0.zip](https://github.com/user-attachments/files/18251026/wpsvba7.0.zip)

### 3.杀毒软件将程序主文件报告为病毒
请先尝试将防病毒程序更新至最新版本，或向官方反馈，如仍旧报毒则请考虑将主程序加入防病毒软件的信任区。


### 4.与 Office 2003 的兼容性
在 Office 2003 中，MathType 菜单的部分或全部选项可能为英文，不影响其他程序功能。如遇到 Word 2003 中的 MathType 菜单无法使用，并提示“此命令无法执行因为文档处于受保护视图”。请更换新版的 Office 程序。

### 5.Office 出现“宏已被禁用”的提示，或启动速度慢
在 Office 开始页面或“文件”选项卡的界面中，点击左下角的”选项“，然后进入”信任中心“→”信任中心设置“。然后选择性的调整以下选项，应该可以解决问题：
在”宏设置“中，选择“禁用无数字签署的所有宏”或“启用所有宏（不推荐，可能会运行有潜在危险的代码）”；
在“受信任位置”中，点击“添加新位置”按钮，然后选择 MathType 的安装目录，并确保已勾选“同时信任此位置的子文件夹”。

## MathType 6.5下载：
[MathType 6.5 中文破解版.zip](https://github.com/user-attachments/files/18251066/MathType.6.5.zip)
## 公式编辑器下载：
[数学公式编辑器v3.1.zip](https://github.com/user-attachments/files/18251076/v3.1.zip)

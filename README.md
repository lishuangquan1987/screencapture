# screenshot
通过调用微信的截图dll库文件，实现微信截图功能

目前有两个版本：C#和python


通过vs=>Tools=>Visual Studio Command Prompt工具

输入命令dumpbin /exports PrScrn.dll

可以查看dll文件中有一个函数，名为Prscrn，通过实际实验，该函数不需要传入参数，直接调用即可。

C#：

1.使用VS2012建立工程

2.采用.Net Framework4.5（可自行修改）


python：

1.使用了pyqt做界面

2.需要安装pyhk，pyqt4.8库

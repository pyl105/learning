# eclipse设置git插件支持
## 1.添加eclipse插egit
- Help-->install new software
- EGit插件地址：http://download.eclipse.org/egit/updates
## 2.下载github网站下代码到本地
- 找到需要下载的代码，clone代码对应网址；
- 然后在eclipse下点从git工程clone导入，如果是别人的代码，不需要输入用户名密码；
- 点击下一步，选择需要导入的版本，然后一直下一步，import as general project，点击确定后对应工程会下载到你指定的workspace工作空间；
- 导入到eclipse之后，删除导入的工程，（*注意：不要删除本地的工程*）
- 然后点击导入，使用maven方式选择之前放在workspace的工程，点击导入整个结构即符合编译的条件。

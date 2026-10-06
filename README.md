# FiveKeyBean 更新下载

Windows 五按键后台发送工具的公开更新包。

[下载最新版本](https://github.com/DustinKaer/FiveKeyBean-updates/releases/latest)

首次升级：退出旧程序，使用新版 FiveKeyBean.exe 替换旧文件，保留已有 SendKeys.ini。

之后软件会检查更新；发现新版后，由使用者确认下载更新。更新只替换程序，不覆盖个人按键配置。下载文件进行 SHA256 校验，更新下载目录使用非 C 盘。

有正数间隔的按键优先执行，启动时先按一次，再按指定毫秒数重复。只有间隔为 0 或留空且勾选“按住”时才持续发送按下事件。

此仓库提供安装包和最新版本信息，不收集个人配置，也不向朋友发送消息。
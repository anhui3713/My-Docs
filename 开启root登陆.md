1. 设置root密码：`sudo passwd root`
2. 直接切换到root用户: `sudo su` （然后输入root密码即可）
3. 如果需要开机直接登陆到root： `sudo gedit /usr/share/lightdm/lightdm.conf.d/50-unity-greeter.conf`
4. 在文件末尾添加： `greeter-show-manual-login=true`
5. 重启`reboot`之后即可用root登陆

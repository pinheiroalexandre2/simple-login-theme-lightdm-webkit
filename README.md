## Simple LightDM Webkit greeter theme

### Prerequisites
- lightdm
- lightdm-webkit2-greeter

### how to
1. Extract files of this repository;
2. Rename folder to `simple-login-theme`;
3. Move folder to `/usr/share/lightdm-webkit/themes/simple-login-theme`;
4. Edit file `/etc/lightdm/lightdm-webkit-greeter.conf` and chage flollowing line:

<pre>
    webkit-theme=simple-login-theme
</pre>


=================
**This theme was based on [lightdm-webkit-google](https://github.com/omgmog/lightdm-webkit-google)**
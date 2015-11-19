# clean-login-theme-lightdm-webkit

### Prerequisites
- lightdm
- lightdm-webkit2-greeter

### how to
1. Extract files of this repository;
2. Rename folder to `clean-login-theme`;
3. Move folder to `/usr/share/lightdm-webkit/themes/clean-login-theme`;
4. Edit file `/etc/lightdm/lightdm-webkit-greeter.conf` and chage flollowing line:

<pre>
    webkit-theme=clean-login-theme
</pre>


=================
**This theme was based on [simple-login-theme-lightdm-webkit](https://github.com/pinheiroalexandre2/simple-login-theme-lightdm-webkit)**
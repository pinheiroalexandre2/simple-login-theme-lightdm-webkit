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

### License
For this application we use the artwork of  Scott Sherrill, which is distributed under a [Creative Commons Attribution 2.5 License](https://creativecommons.org/licenses/by/2.5/).

For more information see his web site: http://scott.sherrillmix.com/blog/blogger/wp_monsterid/

###### The MIT License (MIT)

Copyright (c) 2015 Alexandre Pinheiro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


=================
**This theme was based on [lightdm-webkit-google](https://github.com/omgmog/lightdm-webkit-google)**
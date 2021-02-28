# Wireguard problem on windows

- Wireguard not support windows filter driver for network interface. The real problem come from Wintun driver.<br/>
make traffic bypass 3rd party firewall or any software that use windows filter driver.<br/>

![sample pic](https://github.com/lessload/wireguard-windows--------------Big-Problem/blob/master/sample.jpg?raw=true)

As you can see in picture. wintun driver not support filter driver and make all apps bypass 3rd party firewall.Cause wintun can not use in many company. <br/>
TAP-Windows support filter driver, making it widely used.<br/>
Many user found this preblem. someone report it to dev team. but seem like developer not care to fix this.<br/>
If you know how to fix it. Please send code to them.<br/>
https://github.com/WireGuard/wintun<br/>

## Wireguard License

This repository is MIT-licensed.

```text
Copyright (C) 2018-2021 WireGuard LLC. All Rights Reserved.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```

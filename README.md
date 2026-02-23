如何使用
========

server

If you use termux

```
pkg update && pkg upgrade -y
pkg install python git -y
pkg install openssh
git clone https://github.com/cutepig123/shadowsocksr.git
```

```
cd shadowsocksr\shadowsocks
python server.py
# Note it uses config "shadowsocksr\config.json"
```

example:

```
(base) D:\codes\shadowsocksr\shadowsocks>python server.py
IPv6 support
2026-02-23 22:24:40 INFO     util.py:85 loading libcrypto from C:\WINDOWS\system32\libcrypto.dll
2026-02-23 22:24:41 INFO     shell.py:72 ShadowsocksR 3.4.0 2017-07-27
2026-02-23 22:24:41 INFO     asyncdns.py:324 dns server: [('8.8.4.4', 53), ('8.8.8.8', 53)]
2026-02-23 22:24:41 INFO     server.py:105 server start with protocol[auth_aes128_md5] password [b'm'] method [aes-256-cfb] obfs [plain] obfs_param []
2026-02-23 22:24:41 INFO     server.py:121 starting server at [b'::']:8388
2026-02-23 22:24:41 INFO     server.py:141 starting server at 0.0.0.0:8388
```

Client:

Android: Install SSRR for android

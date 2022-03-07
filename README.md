# redmi_ac2100_padavan_framework

Redmi Router AC2100 customized framework.

红米路由器AC2100 PADAVAN（老毛子）固件解包自修补

## Extract Tool 解包工具

<https://github.com/TylerTemp/padavan-firmware-modify-tool>

### Usage 工具使用

extract: `modify.sh e firmware.trx`

re-create: `modify.sh c /path/to/unpacked/firmware/folder`

## Original Framework 原版固件

Get from <https://iroot.cc/162.html>

## What be modified 改动部分

主要就是修复了原固件中Adguard Home的启动脚本，路由器后台不能将53端口的udp请求转发给Adguard home的错误。

解决方案来源：<https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=4052341>

Fix the bug in the Adguard Home boot script which let the requests from port 53 can not be forward to the Adguard Home as excepted.

Solution founder: <https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=4052341>

# x-wrt-mirror
x-wrt - Revision 4987: /branches/backfire_10.03/package    
from : http://x-wrt.googlecode.com/svn/branches/backfire_10.03/package/

because we can not visit google in China.   so i mirrored the above packages


for openwrt backfire  

edit  vi   feeds.config.default

comment out the default
src-svn xwrt
src-svn luci
and

add 

src-git xwrt https://github.com/xdodx00/xwrt-mirror.git
src-git luci https://github.com/openwrt/luci.git

by  xdodx00  2016.02.04

2899109958#qq.com

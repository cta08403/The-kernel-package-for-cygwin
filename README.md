The-kernel-package-for-cygwin
=============================

kumquat
索尼内核解包脚本，使用此工具必须有python。

用法解包所有索尼内核，

./unpack kernel.elf  或者   ./unpack boot.img

你将会得到ramdisk文件夹 , 内核kernel   ，CMDLINE cmdline.txt 这几个文件  还会得到一个3文件可以不用！

官方kernel.sin 内核不能用此脚本！
但是官方sin内核用强刷工具再次解包为kernel.elf，可以使用！
打包
 GB内核                 ./gbpack
 ICS JB内核             ./pack
 
 

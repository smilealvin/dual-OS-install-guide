# dual-OS-install-guide
联想拯救者适合用这个教程来安装双系统
[https://zhuanlan.zhihu.com/p/56150978](https://zhuanlan.zhihu.com/p/56150978)
1. 用anaconda设置好环境的名称，里面的包除了python，都用pip装，不要用conda装，这样就没问题
- [bashrc、profile学习](https://www.cnblogs.com/lanye/p/6149273.html)
2. anaconda的版本最好是2
3. python2的文件的路径不能有中文，否则numpy报出莫名其妙的错误
4. 用gparted更改swap分区之后，其uuid就变了，因此resume文件以及fstab文件里面的uuid都要手动更改，否则开机会非常慢

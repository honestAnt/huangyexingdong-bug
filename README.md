# huangyexingdong-bug
荒野行动辅助，透视穿墙。我把源码发出来;
//
首先：开源只为网易更好的修复各种BUG，也希望玩这游戏的老哥们踊跃提交给网易和谐掉，还大家一个公平公正的游戏。
//
//有的老哥未静态编译需要VC运行环境，缺少dll，直接百度:vcredist_x86.exe
//
//Ps:一些不支持DX11的显卡 注入成功也是没效果
//
//秒封号的是被某易封机器码了 需要修改电脑网卡的MAC地址。另外XP不支持DX11 ，所以你懂得。
//
//2018.01.09  某易貌似开始检测ce，所以就不要用ce上色了。
//
//2018.01.12  能看懂源码的，将防封那一块的几个地址重新在游戏里找个空内存跳过去就行了或者申请内存然后再将检测跳空就可以了。
//           0x1F6878C-0x1F87FE4之间任意取三个位差在12个字节及以上的值替换MoudleIni中以TMP结尾的三个地址(C以TMP结尾，E以临时基址结尾)\
//
//估计我以后新改的应该不发了，免得......
       

﻿================================================================================
                                样例使用说明
================================================================================
Date            Author      IAR       MDK       GCC
2022-03-31      CDT         7.70      5.36      10.3.1

================================================================================
平台说明
================================================================================
GCC工程，由Eclipse IDE外挂GNU-ARM Toolchain，再结合pyOCD GDB Server实现工程的编译、
链接和调试。在用Eclipse导入工程后，请将xxxx_PyOCDDebug中pyocd-gdbserver和SVD文件
设置为正确的路径；请将xxxx_PyOCDDownload中pyocd设置为正确的路径。注意，这些路径不
能包含非英文字符。

================================================================================
功能描述
================================================================================
本样例展示IAP的Boot功能。

================================================================================
测试环境
================================================================================
测试用板:
---------------------
EV_F460_LQ100_Rev2.0

辅助工具:
---------------------
Micro USB数据线

辅助软件:
---------------------
无

================================================================================
使用步骤
================================================================================
1）打开工程并重新编译，对目标芯片执行整片擦除；
2）启动IDE的下载和调试功能，关闭IDE下载界面；
3）按下复位按键复位并运行boot程序；
4）按照iap_app样例的readme.txt进行后续操作。

================================================================================
注意
================================================================================
需搭配iap_app样例进行测试，先执行iap_boot样例的操作

================================================================================

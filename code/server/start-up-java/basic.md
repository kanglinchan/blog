# Basic

## 存储
 ### 计算机的最小存储单位

 前面我们已经知道计算机表示数据是用二进制来的， 这里我又要抛出一个问题来了！ 我现在想要在计算机中存储一个整数6，转换为二进制是110，那么计算机中只是存110吗三位数字吗？ 其实不是的，**计算机中最小的存储单位是字节（Byte），一个字节占8位（bit）**，也就是说即使这个数据不足8位也需要用8位来存储。

 ### 不同进制在Java程序中的书写格式
 ```java
    System.out.pirntln('a'+1); //98
    // 2进制 0b
    System.out.pirntln(0b01100001); //97
    // 8进制 0, 1*8^2 4*8*1 1*8^0 => 64 + 32 + 1
    System.out.pirntln(0141); //97
    // 16进制 0x, 6*16^1 1*16*0 => 96 + 1 
    System.out.pirntln(0x61); //97
 ```
# Windows-Redis-compile
Windows Redis compile

1. 访问 ： https://mirrors.tuna.tsinghua.edu.cn/msys2/distrib/ 
   下载  msys2-x86_64-latest.tar.xz 
2. 以管理员身份运行 msys2_shell.cmd 

3. 创建  redis 安装目录 Redis-x64-xxx 

4. 在安装目录下创建redis 组建 目录 （bin,conf,logs,pid,db,sentinel,cluster 等）

5. 安装

   PREFIX=/Redis-x64-6.2.4 make MALLOC=libc test // 测试安装 OK 
 
   PREFIX=/Redis-x64-6.2.4/ make MALLOC=libc //正式安装
 
   PREFIX=/Redis-x64-6.2.4/ make install

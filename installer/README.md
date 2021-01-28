# 安装和打包工程文件

## 目前实现进程
- [x] Windows 小白安装包
    - [x] exe文件
    - [x] 打包JRE
    - [ ] 不用EXE4J
- [ ] Linux 小白安装包
    - [ ] Ubuntu Shell版
    - [ ] CentOS Shell版
    - [ ] Ubuntu DEB包版
    - [ ] CentOS RPM包版
- [ ] MacOS 小白安装包

## 编译所需文件

### EXE4J

这玩意不开源我也没办法,所以暂不能公布其工程文件

| 文件名  | 备注  |
| :------------: | :------------: |
| common.exe4j  |  exe4j 工程文件 |
| landlords-client-x.x.x.jar  |  Ratel客户端 Jar 文件 |
<!-- | landlords-server-x.x.x.jar  |  Ratel服务端 Jar 文件 | -->


### Inno Setup

Congratulation!这款安装包编译软件是开源的:[去康康](https://github.com/jrsoftware/issrc)


| 文件名  | 备注  |
| :------------: | :------------: |
| common.iss  |  Inno Setup 工程文件 |
| op.txt  | 用于安装包启动时的信息  |
| ed.txt  | 用于安装包安装结束时的信息  |
|  LICENSE-2.0.txt | Apache 2.0 开源协议  |
| /source/jre(文件夹)  | Java时运行库  |

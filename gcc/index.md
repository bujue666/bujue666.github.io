---
title: GCC的一些脚本
date: 2023-09-17 15:00:00
comments: true
layout: post
---
### **脚本**

#### **下载地址**：[[蓝奏云](https://wwqw.lanzouj.com/b04q6018b)]密码:**bujue**

## 一、GCC校园网快捷登录,一键登录软件(PC端)

好像GCC校园网新增了一个电信网络，无法保证该软件是否可以正常使用；

若无法登陆，请提供：[[wifi.gcc.edu.cn](http://wifi.gcc.edu.cn)][[10.21.1.234](http://10.21.1.234/)]。手动登陆后的上方网址链接，复制后并留言到下方；以便修改和更新软件。

大概是这样：

``` url
http://10.21.1.234:801/eportal/portal/login?callback=dr1003&login_method=1&user_account=%账号&user_password=密码&wlan_user_ip=10.23.45.82&wlan_user_ipv6=&wlan_user_mac=341cf0c70bac&wlan_ac_ip=10.21.255.254&wlan_ac_name=ME60&jsVersion=4.1.3&terminal_type=2&lang=zh-cn&lang=zh&v=4465
```



### 1、下载压缩包

- #### 把该文件夹放在C盘D盘即可，

![GCC校园网一键登录]( https://image.bujue.eu.org/file/ec8aff9e47a19dd1661e0.png)

### 2、修改config.json

- #### 若没有相关编辑软件，可使用记事本进行编辑在即可，![](https://image.bujue.eu.org/file/ec0dcef0b175f911ed8d7.png)

- #### 填写你的校园网学号和密码

``` bash
 "user_account": "你的GCC校园网学号",
 "user_password": "GCC校园网密码.",
  "user_account": "你的GCC校园网学号",
```

![config.json](https://image.bujue.eu.org/file/f82485a5153549366a116.png)

### 3、修改完成保存，然后对GCC校园网一键登录.exe创建快捷方式到桌面即可，方便使用。



## 二、极域电子教室软件-解除控制

- #### 解除教师端控制，之前一直用都没有问题，自行探索。

![再见极域](https://image.bujue.eu.org/file/db73ba9bebc3cdd47bf38.png)

## 三、抢课

- #### 内网教务系统IP(需连接GCC网络)：自行研究

  ```内网IP
  http://172.22.14.1
  http://172.22.14.2 
  http://172.22.14.13 
  http://172.22.14.22/activate.html 
  ```

  


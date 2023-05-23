# 目的
在outlook配置企业微信邮箱并使用。

# 环境
Windows11
Outlook2021
企业微信

# 操作
登录企业微信邮箱网页版。```https://exmail.qq.com```，需企业微信扫码登录。
登录后，点击邮箱设置。
![image](https://github.com/zhuyifei2023/logMyself/assets/133021061/f9cf0211-b8b4-481e-bc4d-6d20d92963df)
生成专用密码。复制存档并确认创建。
务必保存更改
![image](https://github.com/zhuyifei2023/logMyself/assets/133021061/b7e6ced2-b91d-4f6e-8bbd-d1e1fb41fb21)

配置收发信设置
![image](https://github.com/zhuyifei2023/logMyself/assets/133021061/09bf1e84-c9ac-4857-9627-20e18a831309)

保存配置修改
![image](https://github.com/zhuyifei2023/logMyself/assets/133021061/097c16f6-2aa8-4c5c-8586-3a2efe625230)

参考官方配置开始配置outlook
![image](https://github.com/zhuyifei2023/logMyself/assets/133021061/93cf0a12-a44e-427d-a1f1-ca7423e8b080)

可参考```https://open.work.weixin.qq.com/help2/pc/19885?person_id=1```  
需注意，随着软件更新，可能在未来，该配置无法参考。  
我个人使用pop3
```
POP3/SMTP协议
接收邮件服务器：pop.exmail.qq.com ，使用SSL，端口号995
发送邮件服务器：smtp.exmail.qq.com ，使用SSL，端口号465
```
以上，获取到了企业微信的邮箱账户密码，对接协议和端口。  
剩下操作为outlook客户端配置POP3协议。  
可参考：```https://support.microsoft.com/zh-cn/office/%E5%90%91-outlook-%E6%B7%BB%E5%8A%A0%E7%94%B5%E5%AD%90%E9%82%AE%E4%BB%B6%E5%B8%90%E6%88%B7-e9da47c4-9b89-4b49-b945-a204aeea6726```  
务必手动配置，自动配置会自动匹配一个错误的收发件网址。

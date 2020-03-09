# sendAliyunEmail
用来使用阿里云推送服务的发邮件模板
首先添加依赖
implementation 'com.sun.mail:javax.mail:1.6.2'
然后使用
AliyunEmail(
        "你的发信地址: 用户名@网址",
        "收件地址",
        "发信smtp密码",
        "邮件标题",
        "HTML形式的邮件内容  例:<html><head></head><body>content</body></html>"
    ).send()

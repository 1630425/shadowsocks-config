# shadowsocks-config
<pre>
默认
{
    "server":"0.0.0.0",
    "server_port":8989,
    "local_port":1080,
    "password":"teddysun.com",
    "method":"aes-256-cfb",
    "timeout":600
}
修改
{
    "server":"0.0.0.0",
    "server_port":8989,
    "local_port":1080,
    "password":"chengtong",
    "method":"aes-256-cfb",
    "timeout":600
}

多用户多端口配置文件示例：
配置文件路径：/etc/shadowsocks/config.json
{
    "port_password":{
         "8989":"password0",
         "9001":"password1",
         "9002":"password2",
         "9003":"password3",
         "9004":"password4"
    },
    "method":"your_encryption_method",
    "timeout":600
}
</pre>

## 搭建SSR服务
```bash
$ wget --no-check-certificate https://raw.githubusercontent.COM/haolic/shadowsocksR.sh/main/shadowsocksR.sh

$ chmod +x shadowsocksR.sh

$ ./shadowsocksR.sh 2>&1 | tee shadowsocksR.LOG
```

## 选择对应的加密混淆方式，如果不懂就一直回车用默认的配置
Your Server IP        :  你的服务器地址
Your Server Port      :  默认为 16385
Your Password         :  默认为 teddysun.com
Your PRotocol         :  origin
Your obfs             :  plain
Your Encryption Method:  aes-256-CFb

安装Bbr加速
```bash
$ wget --no-check-certificate https://raw.githubusercontent.COM/haolic/shadowsocksR.sh/main/bbr.sh && chmod +x bbr.sh && ./bbr.sh
```
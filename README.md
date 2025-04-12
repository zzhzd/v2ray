# V2ray搭建教程，一键搭建教程，手机搭建vpn 服务器

## 手机搭建vpn 服务器，手机搭建v2ray节点
1、VPS服务器：https://www.vultr.com/?ref=8753714

2、搭建工具下载：[Termius](https://termius.com/download/)

3、搭建代码：

    apt update -y && apt install -y curl && apt install -y socat #更新服务器
    bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh) 搭建代码

4、放行端口

    iptables -I INPUT -p tcp --dport 8080 -j ACCEPT

5、科学上网客户端：
- Android [v2rayNG >>](https://github.com/2dust/v2rayNG/releases/latest)
- iOS [Shadowrocket >>](https://github.com/kjfx/AppleID)
- Windows [v2rayN >>](https://github.com/2dust/v2rayN/releases/latest)
- Mac Shadowrocket 需[注册美区 Apple ID](https://github.com/kjfx/AppleID) 在 App Store 下载


<br>

## 电脑搭建教程
V2ray搭建视频教程：▶ https://youtu.be/D5pANW0Bv08


## 选择VPS步骤：
<img src="https://raw.githubusercontent.com/kjfx/v2ray1/refs/heads/main/vps%E6%9C%8D%E5%8A%A1%E5%99%A8%E9%80%89%E6%8B%A9%E8%AF%B4%E6%98%8E.png" />



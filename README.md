# 自用测试版

- **请给个⭐支持一下**

# 一、项目介绍

## 核心

- Xray-core
- sing-box

## 协议

> 以下均使用TLS，支持多种协议组合

- VLESS(Reality、Vision(TCP)、WS、gRPC、XHTTP)
- VMess(TCP、WS、HTTPUpgrade)
- Trojan(TCP、gRPC)
- Hysteria2(sing-box)
- Tuic(sing-box)
- NaiveProxy(sing-box)

## 功能

- 支持不同核心之间的配置读取
- 支持个性化安装单个协议
- [支持无域名版本的VLESS Reality搭建]
- [支持多种分流用于解锁（wireguard、IPv6、Socks5、DNS、VMess(ws)、SNI反向代理）]
- [支持批量添加CDN节点并配合ClashMeta自动优选]
- 支持普通证书和通配符证书自动申请及更新
- [支持订阅以及多VPS组合订阅]
- 支持批量新增端口[仅支持Xray-core]
- 支持核心的升级以及回退
- 支持自主更换伪装站点
- 支持BT下载管理以及域名黑名单管理




```
wget -P /tmp -N --no-check-certificate "https://raw.githubusercontent.com/sinian-liu/v2ray-agent/master/install.sh" && chmod +x /tmp/install.sh && /tmp/install.sh && sudo mkdir -p /etc/v2ray-agent && sudo cp /tmp/install.sh /etc/v2ray-agent/install.sh && sudo chmod +x /etc/v2ray-agent/install.sh && sed -i "s|alias sinian='bash </etc/v2ray-agent/install.sh'|alias sinian='bash /etc/v2ray-agent/install.sh'|" /root/.bashrc && echo "alias sinian='bash /etc/v2ray-agent/install.sh'" >> /root/.bashrc && source /root/.bashrc
```


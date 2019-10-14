# net-protocol
<p>
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/brewlin/net-protocol">
<img alt="GitHub" src="https://img.shields.io/github/license/brewlin/net-protocol">
<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/brewlin/net-protocol">
  
  </p>


基于go 实现链路层、网络层、传输层、应用层 网络协议栈 ，使用虚拟网卡实现
## @docs
```
相关md文档在cmd目录下，以及相关协议的demo测试
```
`./cmd/*.md`
## @application 应用层
- [x] http [docs](./cmd/http.md)
- [x] websocket [docs](./cmd/websocket.md)

## @transport 传输层
- [x] tcp [docs](./cmd/tcp.md)
- [x] udp [docs](./cmd/udp.md)
- [x] port 端口机制

## @network 网络层
- [x] icmp
- [x] ipv4
- [x] ipv6

## @link 链路层
- [x] arp [docs](./cmd/arp.md)
- [x] ethernet

## @物理层
- [x] tun tap 虚拟网卡的实现


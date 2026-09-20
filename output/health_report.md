# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 20:21:42 |
| 运行耗时 | 564.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83604 |
| 去重后节点 | 23442 |
| TCP 可达 | 3000 |
| 真实可用 | 438 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23442 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.5 |
| tcp | 39.6 |
| probe | 227.2 |
| real_test | 197.8 |
| generate | 91.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50002 |
| vmess | 13505 |
| shadowsocks | 9925 |
| trojan | 8238 |
| hysteria2 | 1153 |
| http | 580 |
| shadowsocksr | 115 |
| socks | 71 |
| hysteria | 11 |
| tuic | 3 |
| anytls | 1 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 73.97 | trojan | 340.8 | 606.0 | 19.89 | 0.0 | 10.0 | 12.5 | 19.76 | Au1rxx-base64 | 100.42.228.109 |
| 73.93 | shadowsocks | 342.9 | 725.2 | 19.84 | 0.0 | 10.0 | 13.48 | 19.76 | Au1rxx-base64 | 37.19.198.244 |
| 73.84 | shadowsocks | 347.6 | 732.3 | 19.73 | 0.0 | 10.0 | 13.48 | 19.76 | Au1rxx-base64 | 37.19.198.160 |
| 73.21 | vless | 336.8 | 742.7 | 19.98 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 79.141.172.154 |
| 73.15 | shadowsocks | 382.5 | 905.1 | 18.92 | 0.0 | 10.0 | 13.48 | 19.76 | Au1rxx-base64 | 23.150.248.20 |
| 73.07 | shadowsocks | 392.8 | 869.8 | 18.69 | 0.0 | 10.0 | 13.48 | 19.76 | Au1rxx-base64 | 37.19.198.236 |
| 73.04 | vless | 313.9 | 602.5 | 20.51 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 172.235.43.210 |
| 73.01 | hysteria2 | 328.4 | 723.4 | 20.17 | 0.0 | 10.0 | 14.12 | 13.3 | mheidari-all | 159.223.157.129 |
| 72.8 | shadowsocks | 258.3 | 620.2 | 21.8 | 0.0 | 10.0 | 13.48 | 19.76 | Au1rxx-base64 | 156.146.38.167 |
| 72.51 | vless | 401.9 | 808.3 | 18.47 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 169.40.42.225 |
| 72.18 | shadowsocks | 260.1 | 634.5 | 21.76 | 0.0 | 10.0 | 13.48 | 19.76 | Au1rxx-base64 | 156.146.38.170 |
| 72.16 | hysteria2 | 492.3 | 911.8 | 16.38 | 0.0 | 9.64 | 14.12 | 19.76 | Au1rxx-base64 | 5.129.235.85 |
| 72.12 | vless | 398.9 | 738.1 | 18.54 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 169.40.42.202 |
| 72.08 | vless | 404.9 | 817.8 | 18.4 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 169.40.42.35 |
| 72.01 | shadowsocks | 261.5 | 629.0 | 21.72 | 0.0 | 10.0 | 13.48 | 19.76 | Au1rxx-base64 | 156.146.38.168 |
| 71.95 | vless | 361.9 | 726.8 | 19.4 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 195.211.98.43 |
| 71.85 | vless | 417.3 | 799.7 | 18.12 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 169.40.42.232 |
| 71.52 | vless | 423.5 | 791.2 | 17.97 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 167.17.69.171 |
| 71.48 | vless | 454.2 | 970.1 | 17.26 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 216.152.147.28 |
| 71.46 | vless | 410.4 | 766.7 | 18.28 | 0.0 | 10.0 | 10.14 | 19.76 | Au1rxx-base64 | 169.40.42.223 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | 0.912 | 249 | 1621 | prefer |
| mheidari-all | 0.88 | 0.816 | 38 | 16265 | prefer |
| ermaozi | 0.87 | 0.885 | 26 | 314 | prefer |
| DeltaKronecker-all | 0.845 | 0.781 | 32 | 6092 | prefer |
| Surfboard-tg-mixed | 0.691 | 0.612 | 206 | 7161 | observe |
| tg-oneclickvpnkeys | 0.403 | 1.0 | 4 | 74 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| Epodonios-all | 0.255 | None | 0 | 7615 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8753 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5710 | observe |
| barry-far-vless | 0.255 | None | 0 | 5924 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1621 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 26 |
| geo | ClientOSError | - | 23 |
| geo | TimeoutError | - | 20 |
| speed | ClientOSError | - | 14 |
| 204 | ProxyError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | TimeoutError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

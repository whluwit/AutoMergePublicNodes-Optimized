# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 03:11:50 |
| 运行耗时 | 661.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 91 |
| 原始节点 | 96930 |
| 去重后节点 | 27025 |
| TCP 可达 | 3000 |
| 真实可用 | 360 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27025 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.5 |
| tcp | 45.0 |
| probe | 274.6 |
| real_test | 262.6 |
| generate | 72.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57652 |
| vmess | 17016 |
| shadowsocks | 12104 |
| trojan | 8428 |
| hysteria2 | 1271 |
| http | 195 |
| shadowsocksr | 165 |
| socks | 55 |
| anytls | 21 |
| hysteria | 17 |
| tuic | 6 |

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
| 79.12 | shadowsocks | 234.2 | 543.1 | 22.36 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 173.244.56.6 |
| 78.88 | shadowsocks | 233.4 | 545.3 | 22.37 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 95.215.201.18 |
| 78.18 | shadowsocks | 229.7 | 540.2 | 22.46 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 173.244.56.9 |
| 77.61 | shadowsocks | 263.4 | 690.3 | 21.68 | 0.0 | 10.0 | 13.73 | 18.2 | mheidari-all | 216.105.168.18 |
| 77.1 | shadowsocks | 245.5 | 586.7 | 22.09 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 149.22.95.183 |
| 76.16 | shadowsocks | 274.0 | 268.6 | 21.44 | 4.93 | 9.95 | 13.73 | 17.28 | Au1rxx-base64 | 149.22.87.241 |
| 75.43 | shadowsocks | 366.4 | 652.3 | 19.3 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 103.11.76.248 |
| 75.11 | shadowsocks | 295.3 | 641.0 | 20.94 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 156.146.38.170 |
| 75.01 | shadowsocks | 184.6 | 486.2 | 23.5 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 167.160.90.54 |
| 74.98 | shadowsocks | 280.8 | 631.7 | 21.28 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 156.146.38.169 |
| 74.96 | shadowsocks | 289.7 | 644.4 | 21.07 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 156.146.38.168 |
| 74.9 | shadowsocks | 189.4 | 490.9 | 23.39 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 167.160.90.50 |
| 74.9 | trojan | 240.7 | 574.6 | 22.21 | 0.0 | 10.0 | 12.91 | 17.28 | Au1rxx-base64 | 216.106.186.32 |
| 73.46 | hysteria2 | 336.8 | 338.8 | 19.98 | 2.3 | 9.44 | 12.69 | 17.28 | Au1rxx-base64 | 38.175.202.26 |
| 73.0 | shadowsocks | 299.8 | 336.8 | 20.84 | 2.37 | 9.95 | 13.73 | 17.28 | Au1rxx-base64 | 149.22.87.240 |
| 72.9 | shadowsocks | 297.4 | 658.5 | 20.89 | 0.0 | 10.0 | 13.73 | 17.28 | Au1rxx-base64 | 156.146.38.167 |
| 72.58 | hysteria2 | 354.2 | 739.1 | 19.58 | 0.0 | 9.99 | 12.69 | 17.28 | Au1rxx-base64 | clash2.deep-links.com |
| 72.06 | vless | 357.2 | 704.8 | 19.51 | 0.0 | 10.0 | 9.98 | 18.2 | mheidari-all | 172.245.253.16 |
| 72.01 | shadowsocks | 300.2 | 361.6 | 20.83 | 1.44 | 9.95 | 13.73 | 17.28 | Au1rxx-base64 | 149.22.87.204 |
| 71.37 | trojan | 241.3 | 591.0 | 22.19 | 0.0 | 6.49 | 12.91 | 17.28 | Au1rxx-base64 | blog.findlocaljobnetworkandbuildcommunityconnections.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.977 | 128 | 1587 | prefer |
| Surfboard-tg-mixed | 0.976 | 0.907 | 75 | 7097 | prefer |
| mheidari-all | 0.551 | 0.471 | 278 | 24252 | observe |
| zhangkai | 0.533 | 0.625 | 16 | 31 | observe |
| ermaozi-get_subscribe | 0.507 | 0.485 | 33 | 523 | observe |
| DeltaKronecker-all | 0.447 | 0.357 | 28 | 4067 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7591 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10124 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5559 | observe |
| barry-far-vless | 0.255 | None | 0 | 5773 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 99 |
| 204 | ProxyError | - | 32 |
| geo | ClientOSError | - | 26 |
| speed | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 6 |
| 204 | TimeoutError | - | 5 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

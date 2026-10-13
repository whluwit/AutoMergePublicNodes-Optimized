# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-13 13:38:35 |
| 运行耗时 | 849.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99040 |
| 去重后节点 | 27275 |
| TCP 可达 | 3000 |
| 真实可用 | 390 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27275 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 47.8 |
| probe | 343.5 |
| real_test | 366.0 |
| generate | 84.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58279 |
| vmess | 16016 |
| shadowsocks | 12068 |
| trojan | 10670 |
| hysteria2 | 1295 |
| http | 435 |
| shadowsocksr | 169 |
| socks | 58 |
| anytls | 26 |
| hysteria | 18 |
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
| 82.34 | hysteria2 | 282.6 | 604.2 | 21.24 | 0.0 | 10.0 | 14.32 | 19.98 | Au1rxx-base64 | 66.94.121.46 |
| 82.18 | shadowsocks | 243.4 | 638.3 | 22.14 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 156.146.38.167 |
| 81.3 | shadowsocks | 281.5 | 723.5 | 21.26 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 156.146.38.168 |
| 80.02 | shadowsocks | 336.8 | 888.0 | 19.98 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 156.146.38.169 |
| 79.13 | shadowsocks | 307.9 | 757.9 | 20.65 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 37.19.198.244 |
| 78.68 | hysteria2 | 300.1 | 742.7 | 20.83 | 0.0 | 10.0 | 14.32 | 19.98 | Au1rxx-base64 | 129.213.91.185 |
| 78.02 | shadowsocks | 307.5 | 745.8 | 20.66 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 37.19.198.160 |
| 76.98 | shadowsocks | 438.7 | 1138.4 | 17.62 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 37.19.198.243 |
| 75.71 | shadowsocks | 299.3 | 578.8 | 20.85 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 173.244.56.9 |
| 74.94 | shadowsocks | 323.8 | 614.4 | 20.28 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 173.244.56.6 |
| 74.57 | shadowsocks | 329.0 | 774.0 | 20.16 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 64.74.163.69 |
| 74.46 | hysteria2 | 412.5 | 723.8 | 18.23 | 0.0 | 9.77 | 14.32 | 19.98 | Au1rxx-base64 | 62.210.124.146 |
| 74.29 | trojan | 343.1 | 666.0 | 19.84 | 0.0 | 9.09 | 14.04 | 19.98 | Au1rxx-base64 | pro-mako.rooster465.autos |
| 74.07 | shadowsocks | 285.6 | 686.9 | 21.17 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 140.82.63.79 |
| 73.7 | hysteria2 | 463.8 | 872.0 | 17.04 | 0.0 | 9.81 | 14.32 | 19.98 | Au1rxx-base64 | 5.129.235.85 |
| 73.58 | shadowsocks | 385.7 | 951.4 | 18.85 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 15.204.246.132 |
| 73.46 | trojan | 423.0 | 1051.6 | 17.99 | 0.0 | 10.0 | 14.04 | 19.98 | Au1rxx-base64 | 69.164.240.85 |
| 73.38 | shadowsocks | 412.3 | 1016.3 | 18.23 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 51.222.136.236 |
| 73.25 | shadowsocks | 396.1 | 888.7 | 18.61 | 0.0 | 10.0 | 14.06 | 19.98 | Au1rxx-base64 | 149.22.95.183 |
| 71.73 | shadowsocks | 359.6 | 387.5 | 19.45 | 0.47 | 9.62 | 14.06 | 19.98 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.959 | 0.892 | 323 | 1754 | prefer |
| mheidari-all | 0.813 | 0.75 | 28 | 24075 | prefer |
| Surfboard-tg-mixed | 0.796 | 0.723 | 65 | 7206 | prefer |
| zhangkai | 0.675 | 0.923 | 13 | 144 | observe |
| DeltaKronecker-all | 0.565 | 0.484 | 31 | 5076 | observe |
| ermaozi-get_subscribe | 0.344 | 0.316 | 19 | 534 | observe |
| ermaozi | 0.257 | 1.0 | 1 | 60 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5086 | observe |
| Epodonios-all | 0.255 | None | 0 | 7717 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9931 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5725 | observe |
| barry-far-vless | 0.255 | None | 0 | 5973 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4312 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 30 |
| 204 | ProxyError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| geo | TimeoutError | - | 13 |
| speed | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| speed | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:44054: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

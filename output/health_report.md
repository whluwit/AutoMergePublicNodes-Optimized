# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 15:55:31 |
| 运行耗时 | 642.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83937 |
| 去重后节点 | 23204 |
| TCP 可达 | 3000 |
| 真实可用 | 418 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23204 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 40.5 |
| probe | 260.4 |
| real_test | 253.2 |
| generate | 82.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50757 |
| vmess | 12812 |
| shadowsocks | 9907 |
| trojan | 8030 |
| hysteria2 | 1633 |
| http | 599 |
| shadowsocksr | 125 |
| socks | 51 |
| tuic | 12 |
| hysteria | 9 |
| anytls | 2 |

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
| 77.92 | vless | 204.3 | 511.6 | 23.05 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 172.233.139.46 |
| 77.92 | shadowsocks | 215.1 | 537.6 | 22.8 | 0.0 | 10.0 | 13.56 | 15.56 | Surfboard-tg-mixed | 173.244.56.6 |
| 76.89 | hysteria2 | 385.1 | 896.2 | 18.86 | 0.0 | 10.0 | 13.75 | 18.94 | Au1rxx-base64 | 159.223.157.129 |
| 76.88 | vless | 202.0 | 501.1 | 23.1 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 172.235.38.85 |
| 76.8 | shadowsocks | 263.3 | 638.2 | 21.68 | 0.0 | 10.0 | 13.56 | 15.56 | Surfboard-tg-mixed | 173.244.56.9 |
| 76.77 | shadowsocks | 243.3 | 606.7 | 22.15 | 0.0 | 10.0 | 13.56 | 15.56 | Surfboard-tg-mixed | 108.181.118.10 |
| 76.25 | hysteria2 | 353.6 | 614.4 | 19.59 | 0.0 | 10.0 | 13.75 | 18.94 | Au1rxx-base64 | 66.94.121.46 |
| 75.18 | vless | 230.2 | 594.9 | 22.45 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 172.235.43.210 |
| 73.81 | vless | 426.7 | 1040.8 | 17.9 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 79.141.172.154 |
| 73.59 | vless | 324.3 | 706.8 | 20.27 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 188.137.243.243 |
| 73.13 | shadowsocks | 335.2 | 671.3 | 20.02 | 0.0 | 10.0 | 13.56 | 18.94 | Au1rxx-base64 | 198.98.53.130 |
| 73.06 | vless | 346.7 | 353.8 | 19.75 | 1.73 | 9.9 | 10.4 | 18.94 | Au1rxx-base64 | 13.231.7.104 |
| 72.96 | vless | 351.0 | 354.3 | 19.65 | 1.71 | 9.89 | 10.4 | 18.94 | Au1rxx-base64 | 13.231.19.51 |
| 72.67 | shadowsocks | 359.0 | 762.5 | 19.47 | 0.0 | 10.0 | 13.56 | 18.94 | Au1rxx-base64 | 37.19.198.243 |
| 72.39 | vless | 528.1 | 1356.6 | 15.55 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 51.81.203.63 |
| 72.31 | vless | 258.3 | 567.0 | 21.8 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 31.58.50.200 |
| 72.15 | vless | 384.3 | 706.4 | 18.88 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 195.123.235.177 |
| 72.09 | shadowsocks | 327.0 | 859.9 | 20.21 | 0.0 | 10.0 | 13.56 | 12.82 | mheidari-all | 108.181.0.177 |
| 72.08 | vless | 395.8 | 762.5 | 18.62 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 169.40.42.179 |
| 71.78 | vless | 403.8 | 801.0 | 18.43 | 0.0 | 10.0 | 10.4 | 18.94 | Au1rxx-base64 | 167.17.69.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.903 | 0.835 | 254 | 1763 | prefer |
| mheidari-all | 0.787 | 0.712 | 73 | 15708 | prefer |
| Surfboard-tg-mixed | 0.768 | 0.691 | 136 | 7370 | prefer |
| ermaozi | 0.757 | 0.759 | 29 | 377 | prefer |
| DeltaKronecker-all | 0.548 | 0.467 | 75 | 6070 | observe |
| tg-oneclickvpnkeys | 0.32 | 1.0 | 2 | 228 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7833 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8539 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5979 | observe |
| barry-far-vless | 0.255 | None | 0 | 6192 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1763 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 58 |
| 204 | ProxyError | - | 23 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 10 |
| speed | TimeoutError | - | 10 |
| geo | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46534: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

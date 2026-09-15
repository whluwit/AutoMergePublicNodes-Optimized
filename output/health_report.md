# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 03:24:26 |
| 运行耗时 | 1196.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90207 |
| 去重后节点 | 25720 |
| TCP 可达 | 3000 |
| 真实可用 | 501 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25720 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 41.9 |
| probe | 410.8 |
| real_test | 652.1 |
| generate | 83.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55864 |
| vmess | 13238 |
| shadowsocks | 10084 |
| trojan | 8412 |
| hysteria2 | 1754 |
| http | 646 |
| shadowsocksr | 124 |
| socks | 53 |
| hysteria | 14 |
| tuic | 10 |
| anytls | 8 |

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
| 80.72 | shadowsocks | 244.3 | 628.5 | 22.12 | 0.0 | 9.32 | 13.8 | 19.48 | Au1rxx-base64 | 156.146.38.168 |
| 79.41 | shadowsocks | 244.7 | 611.6 | 22.11 | 0.0 | 10.0 | 13.8 | 17.5 | mheidari-all | 156.146.38.169 |
| 79.33 | shadowsocks | 248.2 | 637.9 | 22.03 | 0.0 | 10.0 | 13.8 | 17.5 | mheidari-all | 156.146.38.170 |
| 79.2 | vless | 234.3 | 520.0 | 22.35 | 0.0 | 10.0 | 11.69 | 17.5 | mheidari-all | 47.251.108.158 |
| 78.87 | vless | 282.3 | 599.3 | 21.24 | 0.0 | 10.0 | 11.69 | 19.48 | Au1rxx-base64 | 172.235.38.85 |
| 78.64 | vless | 266.0 | 552.3 | 21.62 | 0.0 | 9.29 | 11.69 | 19.48 | Au1rxx-base64 | 172.235.43.210 |
| 78.43 | vless | 302.5 | 721.5 | 20.78 | 0.0 | 9.2 | 11.69 | 19.48 | Au1rxx-base64 | 79.141.172.154 |
| 78.04 | vless | 300.8 | 561.0 | 20.82 | 0.0 | 10.0 | 11.69 | 19.48 | Au1rxx-base64 | 144.172.104.26 |
| 77.91 | vless | 316.4 | 688.8 | 20.45 | 0.0 | 9.25 | 11.69 | 19.48 | Au1rxx-base64 | 45.149.172.80 |
| 77.87 | vless | 273.1 | 571.2 | 21.46 | 0.0 | 9.24 | 11.69 | 19.48 | Au1rxx-base64 | 45.149.172.74 |
| 77.81 | hysteria2 | 307.4 | 721.2 | 20.66 | 0.0 | 9.14 | 13.33 | 19.48 | Au1rxx-base64 | 107.175.219.48 |
| 77.8 | vless | 291.5 | 511.3 | 21.03 | 0.0 | 10.0 | 11.69 | 17.5 | mheidari-all | 150.241.102.181 |
| 77.33 | vless | 320.3 | 677.2 | 20.36 | 0.0 | 9.26 | 11.69 | 19.48 | Au1rxx-base64 | 198.251.78.29 |
| 76.87 | vless | 342.7 | 764.6 | 19.84 | 0.0 | 9.29 | 11.69 | 19.48 | Au1rxx-base64 | 47.253.226.114 |
| 76.72 | vless | 356.5 | 843.3 | 19.52 | 0.0 | 9.23 | 11.69 | 19.48 | Au1rxx-base64 | 15.204.97.216 |
| 76.59 | shadowsocks | 254.6 | 632.6 | 21.89 | 0.0 | 10.0 | 13.8 | 15.4 | Surfboard-tg-mixed | 23.150.248.20 |
| 76.33 | shadowsocks | 287.1 | 716.6 | 21.13 | 0.0 | 10.0 | 13.8 | 15.4 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.32 | vless | 281.0 | 594.7 | 21.27 | 0.0 | 9.17 | 11.69 | 19.48 | Au1rxx-base64 | 192.3.247.109 |
| 75.76 | vless | 349.1 | 752.4 | 19.7 | 0.0 | 9.3 | 11.69 | 19.48 | Au1rxx-base64 | 216.152.147.28 |
| 75.57 | trojan | 301.0 | 572.6 | 20.81 | 0.0 | 9.28 | 12.5 | 19.48 | Au1rxx-base64 | 100.42.228.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | 0.85 | 294 | 1600 | prefer |
| Surfboard-tg-mixed | 0.622 | 0.667 | 15 | 7572 | observe |
| ermaozi | 0.56 | 0.545 | 33 | 425 | observe |
| DeltaKronecker-all | 0.402 | 0.316 | 19 | 5972 | observe |
| ermaozi-get_subscribe | 0.368 | 0.556 | 9 | 447 | observe |
| mheidari-all | 0.358 | 0.278 | 760 | 21540 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 120 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 8044 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8768 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6105 | observe |
| barry-far-vless | 0.255 | None | 0 | 6333 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4099 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 251 |
| speed | TimeoutError | - | 100 |
| geo | ClientOSError | - | 84 |
| cn-block | ClientOSError | - | 67 |
| speed | ClientOSError | - | 59 |
| cn-block | TimeoutError | - | 29 |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

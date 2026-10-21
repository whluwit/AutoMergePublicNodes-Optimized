# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 03:11:10 |
| 运行耗时 | 572.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 95345 |
| 去重后节点 | 26608 |
| TCP 可达 | 3000 |
| 真实可用 | 396 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26608 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 45.1 |
| probe | 205.9 |
| real_test | 231.9 |
| generate | 80.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56837 |
| vmess | 16817 |
| shadowsocks | 11919 |
| trojan | 8111 |
| hysteria2 | 1210 |
| http | 171 |
| shadowsocksr | 168 |
| socks | 65 |
| anytls | 24 |
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
| 80.4 | vless | 241.7 | 519.4 | 22.18 | 0.0 | 10.0 | 11.35 | 18.16 | mheidari-all | 47.251.108.158 |
| 79.65 | hysteria2 | 296.9 | 695.0 | 20.91 | 0.0 | 10.0 | 13.75 | 17.56 | Au1rxx-base64 | 129.213.91.185 |
| 79.46 | vless | 265.6 | 614.0 | 21.63 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 45.32.69.110 |
| 79.08 | shadowsocks | 267.9 | 598.8 | 21.58 | 0.0 | 10.0 | 13.34 | 18.16 | mheidari-all | 156.146.38.170 |
| 78.27 | shadowsocks | 264.8 | 598.6 | 21.65 | 0.0 | 10.0 | 13.34 | 17.28 | Surfboard-tg-mixed | 156.146.38.169 |
| 77.99 | shadowsocks | 244.2 | 628.6 | 22.13 | 0.0 | 8.96 | 13.34 | 17.56 | Au1rxx-base64 | 156.146.38.167 |
| 77.16 | vless | 280.6 | 649.9 | 21.28 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 144.202.126.147 |
| 76.29 | hysteria2 | 349.1 | 649.4 | 19.7 | 0.0 | 8.98 | 13.75 | 17.56 | Au1rxx-base64 | 66.94.121.46 |
| 75.09 | vless | 297.7 | 585.6 | 20.89 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 44.248.233.99 |
| 75.02 | trojan | 323.9 | 824.2 | 20.28 | 0.0 | 9.03 | 12.67 | 17.56 | Au1rxx-base64 | 66.23.203.21 |
| 74.91 | shadowsocks | 269.9 | 564.8 | 21.53 | 0.0 | 10.0 | 13.34 | 17.56 | Au1rxx-base64 | 173.244.56.6 |
| 74.55 | shadowsocks | 289.3 | 765.8 | 21.08 | 0.0 | 8.92 | 13.34 | 17.56 | Au1rxx-base64 | 156.146.38.168 |
| 74.38 | vless | 273.3 | 615.8 | 21.45 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 45.63.53.81 |
| 74.21 | shadowsocks | 329.3 | 736.3 | 20.15 | 0.0 | 10.0 | 13.34 | 18.16 | mheidari-all | 37.19.198.160 |
| 73.46 | vless | 373.0 | 784.3 | 19.14 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 66.70.179.198 |
| 73.46 | vless | 381.6 | 605.4 | 18.94 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 154.12.38.202 |
| 73.35 | shadowsocks | 291.6 | 648.7 | 21.03 | 0.0 | 10.0 | 13.34 | 18.16 | mheidari-all | 216.105.168.18 |
| 73.26 | vless | 374.6 | 767.1 | 19.11 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 5.34.178.120 |
| 72.95 | vless | 365.3 | 752.8 | 19.32 | 0.0 | 10.0 | 11.35 | 17.56 | Au1rxx-base64 | 167.17.69.171 |
| 72.71 | shadowsocks | 309.3 | 299.7 | 20.62 | 3.76 | 8.91 | 13.34 | 17.56 | Au1rxx-base64 | 149.22.87.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.955 | 0.901 | 213 | 1439 | prefer |
| Surfboard-tg-mixed | 0.931 | 0.859 | 85 | 7115 | prefer |
| mheidari-all | 0.559 | 0.479 | 211 | 23653 | observe |
| zhangkai | 0.501 | 0.5 | 20 | 31 | observe |
| ermaozi-get_subscribe | 0.496 | 0.474 | 38 | 516 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| DeltaKronecker-all | 0.255 | 0.222 | 9 | 3519 | observe |
| Epodonios-all | 0.255 | None | 0 | 7598 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10013 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5552 | observe |
| barry-far-vless | 0.255 | None | 0 | 5764 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 54 |
| 204 | ProxyError | - | 28 |
| geo | ClientOSError | - | 27 |
| speed | ClientOSError | - | 24 |
| speed | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 9 |
| cn-block | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 11:02:10 |
| 运行耗时 | 687.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94094 |
| 去重后节点 | 26431 |
| TCP 可达 | 3000 |
| 真实可用 | 378 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26431 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 44.5 |
| probe | 288.0 |
| real_test | 206.7 |
| generate | 139.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55945 |
| vmess | 16905 |
| shadowsocks | 11192 |
| trojan | 8368 |
| hysteria2 | 1119 |
| http | 278 |
| shadowsocksr | 165 |
| socks | 65 |
| anytls | 34 |
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
| 80.35 | hysteria2 | 239.3 | 523.2 | 22.24 | 0.0 | 10.0 | 14.21 | 19.28 | Surfboard-tg-mixed | 179.255.104.98 |
| 80.11 | shadowsocks | 255.3 | 601.3 | 21.87 | 0.0 | 10.0 | 13.96 | 19.28 | Surfboard-tg-mixed | 156.146.38.169 |
| 78.75 | shadowsocks | 303.4 | 753.8 | 20.75 | 0.0 | 10.0 | 13.96 | 18.04 | Au1rxx-base64 | 37.19.198.243 |
| 78.18 | trojan | 340.5 | 882.6 | 19.9 | 0.0 | 10.0 | 13.24 | 18.04 | Au1rxx-base64 | 66.23.203.21 |
| 77.89 | vless | 265.3 | 656.3 | 21.64 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 195.211.98.43 |
| 77.68 | shadowsocks | 309.2 | 768.9 | 20.62 | 0.0 | 10.0 | 13.96 | 18.04 | Au1rxx-base64 | 37.19.198.160 |
| 75.81 | shadowsocks | 409.1 | 940.3 | 18.31 | 0.0 | 10.0 | 13.96 | 18.04 | Au1rxx-base64 | 15.204.233.41 |
| 74.18 | vless | 324.1 | 721.9 | 20.27 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 137.184.218.169 |
| 74.13 | vless | 296.0 | 647.2 | 20.93 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 195.123.235.183 |
| 74.01 | vless | 270.3 | 663.1 | 21.52 | 0.0 | 10.0 | 8.21 | 19.28 | Surfboard-tg-mixed | 147.45.60.160 |
| 73.71 | shadowsocks | 305.3 | 754.7 | 20.71 | 0.0 | 10.0 | 13.96 | 18.04 | Au1rxx-base64 | 37.19.198.244 |
| 73.39 | shadowsocks | 286.1 | 578.7 | 21.16 | 0.0 | 10.0 | 13.96 | 18.04 | Au1rxx-base64 | 173.244.56.9 |
| 73.39 | vless | 361.6 | 870.6 | 19.41 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 169.40.42.235 |
| 73.22 | trojan | 457.5 | 1128.1 | 17.19 | 0.0 | 10.0 | 13.24 | 18.04 | Au1rxx-base64 | 69.164.240.85 |
| 73.18 | vless | 252.8 | 640.7 | 21.93 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 212.134.252.249 |
| 73.04 | vless | 335.3 | 763.1 | 20.02 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 159.89.87.21 |
| 72.98 | vless | 291.6 | 591.5 | 21.03 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 45.63.53.81 |
| 72.95 | vless | 284.3 | 674.5 | 21.2 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 69.48.201.136 |
| 72.88 | vless | 272.4 | 556.1 | 21.47 | 0.0 | 10.0 | 8.21 | 18.04 | Au1rxx-base64 | 47.251.108.158 |
| 72.73 | http | 300.7 | 607.4 | 20.82 | 0.0 | 10.0 | 10.1 | 19.12 | zhangkai | 138.199.35.209 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | 0.87 | 54 | 23400 | prefer |
| zhangkai | 0.91 | 0.95 | 20 | 27 | prefer |
| Au1rxx-base64 | 0.86 | 0.815 | 292 | 1180 | prefer |
| Surfboard-tg-mixed | 0.705 | 0.628 | 86 | 6911 | prefer |
| ermaozi-get_subscribe | 0.378 | 0.352 | 54 | 510 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| Epodonios-all | 0.255 | None | 0 | 7377 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9888 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5733 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| DeltaKronecker-all | 0.24 | 0.25 | 4 | 3519 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 38 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 9 |
| geo | ClientOSError | - | 8 |
| 204 | ProxyConnectionError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

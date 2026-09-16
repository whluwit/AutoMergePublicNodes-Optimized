# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 20:57:36 |
| 运行耗时 | 618.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89382 |
| 去重后节点 | 24518 |
| TCP 可达 | 3000 |
| 真实可用 | 411 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24518 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 42.7 |
| probe | 282.3 |
| real_test | 211.0 |
| generate | 77.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52961 |
| vmess | 14377 |
| shadowsocks | 10701 |
| trojan | 9074 |
| hysteria2 | 1471 |
| http | 592 |
| shadowsocksr | 129 |
| socks | 65 |
| hysteria | 8 |
| tuic | 2 |
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
| 82.49 | hysteria2 | 292.4 | 700.0 | 21.01 | 0.0 | 10.0 | 14.32 | 19.7 | mheidari-all | 159.223.157.129 |
| 81.22 | hysteria2 | 234.2 | 522.7 | 22.36 | 0.0 | 10.0 | 14.32 | 19.7 | mheidari-all | 45.149.172.74 |
| 80.89 | hysteria2 | 271.8 | 585.3 | 21.49 | 0.0 | 10.0 | 14.32 | 18.36 | Au1rxx-base64 | 66.94.121.46 |
| 80.04 | shadowsocks | 256.9 | 659.9 | 21.83 | 0.0 | 10.0 | 13.97 | 18.36 | Au1rxx-base64 | 156.146.38.168 |
| 79.85 | shadowsocks | 255.6 | 628.0 | 21.86 | 0.0 | 10.0 | 13.97 | 18.02 | Surfboard-tg-mixed | 156.146.38.167 |
| 78.95 | vless | 361.9 | 718.4 | 19.4 | 0.0 | 10.0 | 11.19 | 18.36 | Au1rxx-base64 | 38.180.242.205 |
| 78.72 | shadowsocks | 301.1 | 704.5 | 20.81 | 0.0 | 10.0 | 13.97 | 19.7 | mheidari-all | 37.19.198.236 |
| 78.66 | shadowsocks | 303.7 | 758.6 | 20.75 | 0.0 | 10.0 | 13.97 | 18.36 | Au1rxx-base64 | 156.146.38.170 |
| 78.63 | vless | 295.1 | 656.2 | 20.95 | 0.0 | 10.0 | 11.19 | 18.36 | Au1rxx-base64 | 216.152.147.28 |
| 78.02 | shadowsocks | 252.1 | 665.1 | 21.94 | 0.0 | 10.0 | 13.97 | 18.02 | Surfboard-tg-mixed | 23.150.248.20 |
| 78.02 | vless | 294.5 | 667.8 | 20.96 | 0.0 | 10.0 | 11.19 | 18.36 | Au1rxx-base64 | 198.251.78.29 |
| 77.07 | vless | 212.6 | 582.3 | 22.86 | 0.0 | 10.0 | 11.19 | 18.02 | Surfboard-tg-mixed | 88.216.57.128 |
| 76.96 | shadowsocks | 300.1 | 692.7 | 20.83 | 0.0 | 10.0 | 13.97 | 19.7 | mheidari-all | 37.19.198.244 |
| 76.88 | hysteria2 | 260.6 | 552.4 | 21.74 | 0.0 | 10.0 | 14.32 | 19.7 | mheidari-all | 45.149.172.80 |
| 76.73 | shadowsocks | 245.0 | 591.1 | 22.11 | 0.0 | 10.0 | 13.97 | 18.36 | Au1rxx-base64 | 156.146.38.169 |
| 76.71 | vless | 335.6 | 709.9 | 20.01 | 0.0 | 10.0 | 11.19 | 18.36 | Au1rxx-base64 | 169.40.42.90 |
| 76.47 | vless | 321.7 | 720.8 | 20.33 | 0.0 | 10.0 | 11.19 | 18.36 | Au1rxx-base64 | 137.184.218.169 |
| 76.46 | shadowsocks | 409.9 | 1060.9 | 18.29 | 0.0 | 10.0 | 13.97 | 19.7 | mheidari-all | 15.204.247.206 |
| 76.23 | vless | 324.4 | 672.9 | 20.27 | 0.0 | 10.0 | 11.19 | 18.36 | Au1rxx-base64 | 195.123.235.177 |
| 75.96 | vless | 293.9 | 571.9 | 20.97 | 0.0 | 10.0 | 11.19 | 18.36 | Au1rxx-base64 | 144.172.104.26 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.91 | 0.847 | 268 | 1651 | prefer |
| mheidari-all | 0.891 | 0.819 | 72 | 17985 | prefer |
| Surfboard-tg-mixed | 0.819 | 0.742 | 132 | 7470 | prefer |
| ermaozi | 0.558 | 0.818 | 11 | 353 | observe |
| DeltaKronecker-all | 0.547 | 0.464 | 28 | 6081 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4234 | observe |
| tg-oneclickvpnkeys | 0.274 | 0.667 | 3 | 140 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7934 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8999 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5979 | observe |
| barry-far-vless | 0.255 | None | 0 | 6197 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 28 |
| cn-block | TimeoutError | - | 23 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 8 |
| geo | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 4 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

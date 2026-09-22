# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 16:18:51 |
| 运行耗时 | 612.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 87920 |
| 去重后节点 | 25306 |
| TCP 可达 | 3000 |
| 真实可用 | 483 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25306 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.5 |
| tcp | 43.3 |
| probe | 248.4 |
| real_test | 231.1 |
| generate | 82.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51736 |
| vmess | 14667 |
| shadowsocks | 10497 |
| trojan | 8882 |
| hysteria2 | 1315 |
| http | 576 |
| shadowsocksr | 135 |
| socks | 81 |
| hysteria | 14 |
| anytls | 11 |
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
| 83.44 | hysteria2 | 255.8 | 589.4 | 21.86 | 0.0 | 10.0 | 13.42 | 19.16 | Au1rxx-base64 | 66.94.121.46 |
| 79.26 | shadowsocks | 257.5 | 609.5 | 21.82 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 23.150.248.20 |
| 76.53 | shadowsocks | 301.5 | 657.5 | 20.8 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 198.98.53.130 |
| 75.25 | shadowsocks | 347.7 | 778.3 | 19.73 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 37.19.198.236 |
| 75.04 | shadowsocks | 348.9 | 787.4 | 19.7 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 37.19.198.244 |
| 74.93 | shadowsocks | 348.6 | 787.1 | 19.71 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 37.19.198.160 |
| 74.88 | shadowsocks | 346.7 | 778.0 | 19.75 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 37.19.198.243 |
| 74.79 | hysteria2 | 331.6 | 738.8 | 20.1 | 0.0 | 10.0 | 13.42 | 19.16 | Au1rxx-base64 | 159.223.157.129 |
| 73.62 | vless | 342.6 | 809.6 | 19.85 | 0.0 | 10.0 | 7.56 | 19.16 | Au1rxx-base64 | 15.204.97.216 |
| 73.3 | vless | 279.5 | 591.9 | 21.31 | 0.0 | 10.0 | 7.56 | 19.16 | Au1rxx-base64 | 195.123.240.65 |
| 73.22 | shadowsocks | 363.8 | 774.6 | 19.36 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 108.181.57.93 |
| 72.88 | vless | 284.8 | 613.7 | 21.19 | 0.0 | 10.0 | 7.56 | 19.16 | Au1rxx-base64 | 51.81.203.63 |
| 72.74 | shadowsocks | 240.3 | 612.2 | 22.22 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 156.146.38.168 |
| 72.69 | shadowsocks | 247.5 | 636.7 | 22.05 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 71.42 | vless | 375.9 | 888.2 | 19.08 | 0.0 | 10.0 | 7.56 | 19.16 | Au1rxx-base64 | 195.211.98.43 |
| 71.4 | shadowsocks | 517.4 | 1311.6 | 15.8 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 185.156.47.97 |
| 71.11 | shadowsocks | 357.5 | 451.3 | 19.5 | 0.0 | 9.74 | 14.25 | 19.16 | Au1rxx-base64 | 149.22.87.241 |
| 70.65 | shadowsocks | 280.5 | 558.3 | 21.29 | 0.0 | 10.0 | 14.25 | 19.16 | Au1rxx-base64 | 129.146.122.81 |
| 70.54 | vless | 381.2 | 810.8 | 18.95 | 0.0 | 10.0 | 7.56 | 19.16 | Au1rxx-base64 | 66.70.179.198 |
| 70.14 | shadowsocks | 403.5 | 597.8 | 18.44 | 0.0 | 9.79 | 14.25 | 19.16 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.986 | 0.933 | 30 | 16289 | prefer |
| Au1rxx-base64 | 0.919 | 0.856 | 298 | 1636 | prefer |
| ermaozi | 0.737 | 0.741 | 27 | 325 | prefer |
| Surfboard-tg-mixed | 0.6 | 0.52 | 177 | 7076 | observe |
| DeltaKronecker-all | 0.586 | 0.507 | 152 | 6324 | observe |
| xiaoji235-airport-v2ray-all | 0.543 | 0.615 | 13 | 4242 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 132 | observe |
| Epodonios-all | 0.255 | None | 0 | 7611 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8744 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5712 | observe |
| barry-far-vless | 0.255 | None | 0 | 6010 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 68 |
| geo | ClientOSError | - | 34 |
| 204 | TimeoutError | - | 27 |
| geo | TimeoutError | - | 26 |
| 204 | ProxyError | - | 20 |
| cn-block | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 10 |
| speed | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-06 13:57:44 |
| 运行耗时 | 226.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 89497 |
| 去重后节点 | 24511 |
| TCP 可达 | 3000 |
| 真实可用 | 454 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24511 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 36.8 |
| probe | 48.6 |
| real_test | 93.4 |
| generate | 40.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52290 |
| vmess | 13271 |
| trojan | 12009 |
| shadowsocks | 10161 |
| hysteria2 | 1472 |
| socks | 127 |
| shadowsocksr | 78 |
| anytls | 30 |
| http | 24 |
| hysteria | 21 |
| tuic | 14 |

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
| 82.51 | hysteria2 | 285.9 | 688.4 | 21.16 | 0.0 | 8.7 | 13.75 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.17 | hysteria2 | 304.8 | 717.8 | 20.72 | 0.0 | 8.7 | 13.75 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 81.85 | hysteria2 | 289.4 | 728.3 | 21.08 | 0.0 | 8.02 | 13.75 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 80.68 | shadowsocks | 247.8 | 610.5 | 22.04 | 0.0 | 8.76 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.64 | shadowsocks | 249.5 | 617.8 | 22.0 | 0.0 | 8.76 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 79.39 | shadowsocks | 303.7 | 781.0 | 20.75 | 0.0 | 8.76 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 78.14 | shadowsocks | 293.9 | 693.0 | 20.97 | 0.0 | 8.77 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 77.97 | shadowsocks | 284.3 | 666.0 | 21.2 | 0.0 | 8.76 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 77.69 | vless | 271.0 | 604.0 | 21.5 | 0.0 | 10.0 | 8.18 | 20.0 | Au1rxx-base64 | 64.49.38.6 |
| 76.98 | trojan | 377.1 | 910.7 | 19.05 | 0.0 | 8.99 | 14.19 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 76.69 | trojan | 351.6 | 826.5 | 19.64 | 0.0 | 8.99 | 14.19 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 75.98 | trojan | 303.6 | 558.9 | 20.75 | 0.0 | 8.98 | 14.19 | 20.0 | Au1rxx-base64 | 35.91.251.124 |
| 75.69 | shadowsocks | 305.5 | 733.5 | 20.71 | 0.0 | 8.76 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 75.62 | shadowsocks | 246.2 | 596.3 | 22.08 | 0.0 | 8.76 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 75.51 | shadowsocks | 306.3 | 736.7 | 20.69 | 0.0 | 8.76 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 75.29 | shadowsocks | 300.8 | 633.7 | 20.82 | 0.0 | 8.75 | 13.88 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 74.87 | shadowsocks | 292.9 | 581.9 | 21.0 | 0.0 | 8.75 | 13.88 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 74.53 | vless | 337.6 | 622.3 | 19.96 | 0.0 | 10.0 | 8.18 | 20.0 | Au1rxx-base64 | 176.122.164.194 |
| 74.48 | vless | 306.8 | 619.2 | 20.68 | 0.0 | 10.0 | 8.18 | 20.0 | Au1rxx-base64 | 167.17.68.205 |
| 74.18 | trojan | 379.1 | 783.5 | 19.0 | 0.0 | 8.98 | 14.19 | 20.0 | Au1rxx-base64 | 44.246.163.102 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | 0.919 | 382 | 1538 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| mheidari-all | 0.622 | 0.667 | 15 | 20767 | observe |
| Surfboard-tg-mixed | 0.613 | 0.534 | 118 | 5922 | observe |
| DeltaKronecker-all | 0.543 | 0.615 | 13 | 5897 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 5184 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5219 | observe |
| Epodonios-all | 0.255 | None | 0 | 6534 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7365 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4784 | observe |
| barry-far-vless | 0.255 | None | 0 | 5092 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5212 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1538 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 24 |
| geo | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 9 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

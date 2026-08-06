# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-06 08:30:40 |
| 运行耗时 | 227.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 89018 |
| 去重后节点 | 24407 |
| TCP 可达 | 3000 |
| 真实可用 | 459 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24407 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.0 |
| tcp | 36.2 |
| probe | 51.7 |
| real_test | 99.7 |
| generate | 33.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51934 |
| vmess | 13349 |
| trojan | 11875 |
| shadowsocks | 10148 |
| hysteria2 | 1443 |
| socks | 101 |
| shadowsocksr | 79 |
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
| 84.97 | hysteria2 | 266.1 | 683.1 | 21.62 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 84.89 | hysteria2 | 269.4 | 699.9 | 21.54 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 84.84 | hysteria2 | 267.4 | 678.1 | 21.59 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 81.88 | shadowsocks | 250.1 | 623.4 | 21.99 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.82 | shadowsocks | 252.6 | 623.2 | 21.93 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.24 | shadowsocks | 250.0 | 613.0 | 21.99 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.19 | shadowsocks | 279.7 | 708.0 | 21.3 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 80.88 | trojan | 307.4 | 739.6 | 20.66 | 0.0 | 10.0 | 13.73 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 80.26 | shadowsocks | 320.2 | 829.5 | 20.37 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 77.34 | shadowsocks | 277.3 | 697.1 | 21.36 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 76.97 | shadowsocks | 280.7 | 571.1 | 21.28 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.77 | shadowsocks | 285.1 | 579.8 | 21.18 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 76.53 | shadowsocks | 315.4 | 708.2 | 20.48 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 76.27 | hysteria2 | 372.0 | 696.1 | 19.17 | 0.0 | 9.88 | 14.35 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 76.19 | trojan | 291.3 | 708.2 | 21.04 | 0.0 | 10.0 | 13.73 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 76.05 | shadowsocks | 288.6 | 545.6 | 21.1 | 0.0 | 10.0 | 13.89 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 75.67 | trojan | 480.8 | 1243.3 | 16.65 | 0.0 | 10.0 | 13.73 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 75.04 | trojan | 339.7 | 591.4 | 19.91 | 0.0 | 10.0 | 13.73 | 20.0 | Au1rxx-base64 | 44.242.235.129 |
| 74.74 | hysteria2 | 453.6 | 896.4 | 17.28 | 0.0 | 9.96 | 14.35 | 20.0 | Au1rxx-base64 | 5.255.102.165 |
| 74.72 | trojan | 347.0 | 613.0 | 19.75 | 0.0 | 9.94 | 13.73 | 20.0 | Au1rxx-base64 | pet-ghost.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.955 | 358 | 1409 | prefer |
| zhangkai | 0.819 | 0.85 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.693 | 0.615 | 135 | 5904 | observe |
| mheidari-all | 0.423 | 0.333 | 33 | 20781 | observe |
| DeltaKronecker-all | 0.32 | 0.217 | 23 | 5897 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 5214 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5219 | observe |
| Epodonios-all | 0.255 | None | 0 | 6505 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7196 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4739 | observe |
| barry-far-vless | 0.255 | None | 0 | 5049 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5212 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.24 | None | 0 | 1621 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 36 |
| geo | ClientOSError | - | 17 |
| 204 | ProxyError | - | 13 |
| speed | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 6 |
| speed | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

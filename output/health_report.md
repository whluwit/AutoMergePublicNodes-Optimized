# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 16:08:21 |
| 运行耗时 | 599.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96963 |
| 去重后节点 | 26519 |
| TCP 可达 | 3000 |
| 真实可用 | 421 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26519 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 43.0 |
| probe | 283.1 |
| real_test | 181.5 |
| generate | 85.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59817 |
| vmess | 14820 |
| shadowsocks | 11176 |
| trojan | 8761 |
| hysteria2 | 1525 |
| http | 565 |
| shadowsocksr | 174 |
| socks | 74 |
| anytls | 25 |
| hysteria | 18 |
| tuic | 8 |

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
| 79.17 | shadowsocks | 233.2 | 532.1 | 22.38 | 0.0 | 9.2 | 13.61 | 17.98 | Au1rxx-base64 | 173.244.56.6 |
| 78.84 | vless | 208.0 | 542.6 | 22.96 | 0.0 | 9.11 | 8.79 | 17.98 | Au1rxx-base64 | 172.235.43.210 |
| 78.59 | shadowsocks | 195.1 | 516.8 | 23.26 | 0.0 | 10.0 | 13.61 | 16.22 | mheidari-all | 192.3.247.109 |
| 78.46 | shadowsocks | 194.8 | 514.6 | 23.27 | 0.0 | 9.1 | 13.61 | 17.98 | Au1rxx-base64 | 129.146.124.141 |
| 78.25 | vless | 232.8 | 538.6 | 22.39 | 0.0 | 9.09 | 8.79 | 17.98 | Au1rxx-base64 | 195.123.240.65 |
| 77.95 | hysteria2 | 356.3 | 877.7 | 19.53 | 0.0 | 9.17 | 13.57 | 17.98 | Au1rxx-base64 | 66.94.121.46 |
| 77.71 | vless | 219.2 | 501.4 | 22.7 | 0.0 | 10.0 | 8.79 | 16.22 | mheidari-all | 47.251.108.158 |
| 77.25 | vless | 196.1 | 503.8 | 23.24 | 0.0 | 10.0 | 8.79 | 16.22 | mheidari-all | 172.233.139.46 |
| 75.56 | shadowsocks | 276.9 | 650.6 | 21.37 | 0.0 | 9.18 | 13.61 | 17.98 | Au1rxx-base64 | 23.150.248.20 |
| 75.32 | shadowsocks | 264.1 | 646.1 | 21.67 | 0.0 | 9.12 | 13.61 | 17.98 | Au1rxx-base64 | 156.146.38.169 |
| 75.25 | shadowsocks | 262.1 | 636.2 | 21.71 | 0.0 | 9.1 | 13.61 | 17.98 | Au1rxx-base64 | 156.146.38.167 |
| 75.21 | hysteria2 | 278.0 | 652.4 | 21.34 | 0.0 | 8.32 | 13.57 | 17.98 | Au1rxx-base64 | newstate.vihodest.net |
| 74.88 | shadowsocks | 194.6 | 476.1 | 23.27 | 0.0 | 10.0 | 13.61 | 12.5 | Surfboard-tg-mixed | 108.181.0.177 |
| 74.69 | shadowsocks | 208.8 | 505.0 | 22.94 | 0.0 | 10.0 | 13.61 | 16.22 | mheidari-all | 108.181.118.10 |
| 74.01 | vless | 225.2 | 514.2 | 22.56 | 0.0 | 9.18 | 8.79 | 17.98 | Au1rxx-base64 | 104.18.39.218 |
| 73.98 | vless | 225.7 | 496.5 | 22.55 | 0.0 | 9.16 | 8.79 | 17.98 | Au1rxx-base64 | 104.18.46.234 |
| 73.8 | vless | 265.4 | 536.1 | 21.63 | 0.0 | 9.07 | 8.79 | 17.98 | Au1rxx-base64 | 31.58.50.200 |
| 73.68 | vless | 291.7 | 662.4 | 21.02 | 0.0 | 9.16 | 8.79 | 17.98 | Au1rxx-base64 | 15.204.97.216 |
| 72.88 | vless | 274.1 | 482.0 | 21.43 | 0.0 | 9.18 | 8.79 | 17.98 | Au1rxx-base64 | 172.64.42.85 |
| 72.71 | trojan | 290.7 | 788.8 | 21.05 | 0.0 | 10.0 | 7.94 | 16.22 | mheidari-all | 34.94.125.227 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.925 | 253 | 1629 | prefer |
| ermaozi | 0.812 | 0.821 | 28 | 291 | prefer |
| Surfboard-tg-mixed | 0.785 | 0.714 | 42 | 7138 | prefer |
| mheidari-all | 0.631 | 0.551 | 234 | 22163 | observe |
| tg-oneclickvpnkeys | 0.405 | 1.0 | 4 | 117 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| Epodonios-all | 0.255 | None | 0 | 7512 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9221 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5827 | observe |
| barry-far-vless | 0.255 | None | 0 | 6042 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4187 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1629 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 40 |
| geo | ClientOSError | - | 32 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 14 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 6 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

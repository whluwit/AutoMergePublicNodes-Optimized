# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 19:11:38 |
| 运行耗时 | 274.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79443 |
| 去重后节点 | 22697 |
| TCP 可达 | 3000 |
| 真实可用 | 497 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22697 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 32.4 |
| probe | 57.1 |
| real_test | 135.2 |
| generate | 42.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46621 |
| vmess | 10927 |
| trojan | 10596 |
| shadowsocks | 10540 |
| hysteria2 | 523 |
| http | 73 |
| shadowsocksr | 70 |
| socks | 52 |
| anytls | 26 |
| hysteria | 12 |
| tuic | 3 |

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
| 79.13 | shadowsocks | 190.9 | 497.4 | 23.36 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 149.22.95.183 |
| 75.76 | vless | 310.4 | 804.8 | 20.59 | 0.0 | 10.0 | 8.69 | 17.48 | Au1rxx-base64 | 52.43.158.158 |
| 75.6 | vless | 230.9 | 517.0 | 22.43 | 0.0 | 10.0 | 8.69 | 17.48 | Au1rxx-base64 | 47.251.25.74 |
| 74.41 | shadowsocks | 241.7 | 522.3 | 22.18 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 108.181.118.10 |
| 74.15 | shadowsocks | 253.4 | 507.0 | 21.91 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 108.181.0.177 |
| 73.34 | hysteria2 | 346.8 | 713.6 | 19.75 | 0.0 | 10.0 | 11.47 | 17.48 | Au1rxx-base64 | 159.223.157.129 |
| 72.98 | shadowsocks | 276.2 | 323.4 | 21.38 | 2.87 | 9.85 | 12.29 | 17.48 | Au1rxx-base64 | 149.22.87.204 |
| 72.94 | shadowsocks | 231.0 | 502.8 | 22.43 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 185.236.200.210 |
| 72.75 | vless | 211.1 | 490.8 | 22.89 | 0.0 | 10.0 | 8.69 | 12.36 | DeltaKronecker-all | 104.16.9.20 |
| 72.52 | shadowsocks | 281.9 | 331.2 | 21.25 | 2.58 | 9.85 | 12.29 | 17.48 | Au1rxx-base64 | 149.22.87.241 |
| 71.93 | vless | 238.9 | 532.7 | 22.25 | 0.0 | 10.0 | 8.69 | 17.48 | Au1rxx-base64 | 154.19.184.40 |
| 71.55 | vless | 235.1 | 496.5 | 22.34 | 0.0 | 10.0 | 8.69 | 12.36 | DeltaKronecker-all | 104.17.90.246 |
| 71.16 | shadowsocks | 324.9 | 678.3 | 20.26 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 156.146.38.170 |
| 70.98 | trojan | 339.0 | 677.5 | 19.93 | 0.0 | 10.0 | 11.7 | 17.48 | Au1rxx-base64 | 64.94.95.117 |
| 70.46 | shadowsocks | 320.8 | 597.0 | 20.35 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 173.244.56.6 |
| 70.16 | shadowsocks | 352.1 | 754.9 | 19.63 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 156.146.38.167 |
| 70.11 | vless | 238.5 | 504.1 | 22.26 | 0.0 | 10.0 | 8.69 | 12.36 | DeltaKronecker-all | 172.67.209.126 |
| 69.77 | shadowsocks | 333.1 | 590.0 | 20.07 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 173.244.56.9 |
| 69.61 | shadowsocks | 359.7 | 725.3 | 19.45 | 0.0 | 10.0 | 12.29 | 17.48 | Au1rxx-base64 | 37.19.198.244 |
| 69.5 | trojan | 396.1 | 850.8 | 18.61 | 0.0 | 10.0 | 11.7 | 17.48 | Au1rxx-base64 | 163.245.196.68 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 70 | 84 | prefer |
| Au1rxx-base64 | 0.826 | 0.772 | 276 | 1415 | prefer |
| DeltaKronecker-all | 0.747 | 0.668 | 214 | 5519 | prefer |
| Surfboard-tg-mixed | 0.64 | 0.561 | 123 | 5754 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| mheidari-all | 0.287 | 0.5 | 2 | 16105 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5118 | observe |
| Epodonios-all | 0.255 | None | 0 | 6491 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6737 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4513 | observe |
| barry-far-vless | 0.255 | None | 0 | 4922 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5076 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.246 | None | 0 | 1774 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 50 |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 30 |
| speed | TimeoutError | - | 27 |
| geo | ClientOSError | - | 17 |
| 204 | ProxyError | - | 12 |
| 204 | ClientOSError | - | 11 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-12 19:02:26 |
| 运行耗时 | 200.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77603 |
| 去重后节点 | 24151 |
| TCP 可达 | 3000 |
| 真实可用 | 158 |
| Verified 输出 | 158 |
| Global 输出 | 176 |
| All 输出 | 24151 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 32.1 |
| probe | 52.2 |
| real_test | 65.4 |
| generate | 44.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45010 |
| trojan | 11723 |
| vmess | 10653 |
| shadowsocks | 9569 |
| hysteria2 | 322 |
| shadowsocksr | 147 |
| http | 137 |
| socks | 30 |
| hysteria | 8 |
| tuic | 4 |

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
| 70.22 | trojan | 282.5 | 391.0 | 21.24 | 0.34 | 10.0 | 9.91 | 16.2 | Surfboard-tg-mixed | 162.159.38.62 |
| 68.34 | trojan | 352.7 | 492.9 | 19.61 | 0.0 | 10.0 | 9.91 | 12.82 | mheidari-all | 5.10.215.9 |
| 66.46 | vless | 220.9 | 601.0 | 22.66 | 0.0 | 10.0 | 1.98 | 12.82 | mheidari-all | 104.16.9.20 |
| 66.11 | trojan | 320.7 | 370.7 | 20.35 | 1.1 | 10.0 | 9.91 | 16.2 | Surfboard-tg-mixed | 45.131.5.9 |
| 66.09 | trojan | 353.8 | 788.1 | 19.59 | 0.0 | 10.0 | 9.91 | 13.6 | DeltaKronecker-all | 45.32.198.247 |
| 65.77 | trojan | 234.9 | 494.4 | 22.34 | 0.0 | 10.0 | 9.91 | 16.2 | Surfboard-tg-mixed | 104.21.52.100 |
| 65.68 | trojan | 353.2 | 360.3 | 19.6 | 1.49 | 10.0 | 9.91 | 16.2 | Surfboard-tg-mixed | 104.24.212.83 |
| 65.57 | trojan | 401.0 | 933.9 | 18.5 | 0.0 | 10.0 | 9.91 | 13.6 | DeltaKronecker-all | 64.94.95.114 |
| 65.26 | trojan | 397.6 | 926.5 | 18.58 | 0.0 | 10.0 | 9.91 | 13.6 | DeltaKronecker-all | 64.94.95.115 |
| 64.94 | trojan | 367.1 | 401.6 | 19.28 | 0.0 | 10.0 | 9.91 | 16.2 | Surfboard-tg-mixed | 108.162.194.119 |
| 64.9 | trojan | 406.5 | 962.1 | 18.37 | 0.0 | 10.0 | 9.91 | 13.6 | DeltaKronecker-all | 64.94.95.117 |
| 64.73 | trojan | 420.5 | 351.5 | 18.04 | 1.82 | 9.48 | 9.91 | 16.2 | Surfboard-tg-mixed | 119.246.1.143 |
| 63.69 | trojan | 322.6 | 713.5 | 20.31 | 0.0 | 10.0 | 9.91 | 12.82 | mheidari-all | 64.94.95.118 |
| 62.79 | shadowsocks | 347.7 | 343.0 | 19.73 | 2.14 | 9.61 | 12.47 | 16.2 | Surfboard-tg-mixed | 36.224.169.242 |
| 62.22 | trojan | 370.7 | 359.2 | 19.2 | 1.53 | 10.0 | 9.91 | 16.2 | Surfboard-tg-mixed | 172.64.53.65 |
| 62.18 | shadowsocks | 483.0 | 745.6 | 16.6 | 0.0 | 9.58 | 12.47 | 16.2 | Surfboard-tg-mixed | 104.156.233.234 |
| 60.83 | shadowsocks | 557.2 | 862.6 | 14.88 | 0.0 | 9.36 | 12.47 | 16.2 | Surfboard-tg-mixed | 82.38.31.29 |
| 60.66 | shadowsocks | 421.2 | 404.9 | 18.03 | 0.0 | 9.25 | 12.47 | 13.6 | DeltaKronecker-all | 167.150.100.115 |
| 60.61 | shadowsocks | 562.5 | 875.4 | 14.76 | 0.0 | 9.36 | 12.47 | 16.2 | Surfboard-tg-mixed | 82.38.31.57 |
| 60.39 | shadowsocks | 557.4 | 859.1 | 14.87 | 0.0 | 9.36 | 12.47 | 16.2 | Surfboard-tg-mixed | 82.38.31.3 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.705 | 0.628 | 94 | 5591 | prefer |
| mheidari-all | 0.629 | 0.551 | 49 | 16307 | observe |
| DeltaKronecker-all | 0.448 | 0.366 | 93 | 8141 | observe |
| xiaoji235-airport-v2ray-all | 0.315 | 1.0 | 1 | 1508 | observe |
| Au1rxx-base64 | 0.26 | 1.0 | 1 | 124 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4003 | observe |
| Epodonios-all | 0.255 | None | 0 | 6622 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6588 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4292 | observe |
| barry-far-vless | 0.255 | None | 0 | 4906 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5438 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.233 | None | 0 | 1439 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 29 |
| speed | ClientOSError | - | 22 |
| 204 | ProxyError | - | 14 |
| cn-block | ClientOSError | - | 11 |
| geo | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 7 |
| cn-block | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 6 |
| geo | ClientOSError | - | 4 |
| speed | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 268 | 158 | - |
| global | False | 285 | 176 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

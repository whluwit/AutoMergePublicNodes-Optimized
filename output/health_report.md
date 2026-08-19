# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 12:41:39 |
| 运行耗时 | 325.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82517 |
| 去重后节点 | 22537 |
| TCP 可达 | 3000 |
| 真实可用 | 1129 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22537 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.2 |
| tcp | 37.0 |
| probe | 65.5 |
| real_test | 187.4 |
| generate | 28.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44840 |
| trojan | 17700 |
| shadowsocks | 10042 |
| vmess | 8466 |
| hysteria2 | 1072 |
| http | 165 |
| socks | 120 |
| shadowsocksr | 93 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 4 |

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
| 81.72 | shadowsocks | 262.0 | 679.2 | 21.71 | 0.0 | 10.0 | 14.01 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 79.95 | hysteria2 | 241.7 | 527.9 | 22.18 | 0.0 | 10.0 | 11.59 | 17.18 | Surfboard-tg-mixed | 150.241.102.127 |
| 78.96 | shadowsocks | 259.4 | 673.7 | 21.77 | 0.0 | 10.0 | 14.01 | 17.18 | Surfboard-tg-mixed | 156.146.38.169 |
| 78.19 | vless | 291.8 | 578.2 | 21.02 | 0.0 | 10.0 | 10.71 | 20.0 | Au1rxx-base64 | 150.241.102.202 |
| 77.95 | trojan | 298.3 | 583.3 | 20.87 | 0.0 | 10.0 | 14.74 | 20.0 | mheidari-all | 44.246.163.102 |
| 77.93 | shadowsocks | 284.0 | 564.2 | 21.2 | 0.0 | 10.0 | 14.01 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 77.88 | shadowsocks | 259.4 | 536.5 | 21.77 | 0.0 | 10.0 | 14.01 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 77.64 | shadowsocks | 363.6 | 986.7 | 19.36 | 0.0 | 10.0 | 14.01 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.6 | shadowsocks | 265.0 | 565.9 | 21.64 | 0.0 | 10.0 | 14.01 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 77.56 | trojan | 312.0 | 622.0 | 20.56 | 0.0 | 10.0 | 14.74 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 77.5 | vless | 306.7 | 670.6 | 20.68 | 0.0 | 10.0 | 10.71 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 77.21 | trojan | 322.8 | 624.6 | 20.31 | 0.0 | 10.0 | 14.74 | 20.0 | mheidari-all | 35.91.138.234 |
| 77.04 | trojan | 352.7 | 754.2 | 19.61 | 0.0 | 10.0 | 14.74 | 20.0 | mheidari-all | 44.249.55.18 |
| 76.98 | shadowsocks | 262.9 | 548.5 | 21.69 | 0.0 | 10.0 | 14.01 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 76.83 | trojan | 351.2 | 745.7 | 19.65 | 0.0 | 10.0 | 14.74 | 20.0 | mheidari-all | 44.251.158.80 |
| 76.38 | shadowsocks | 293.9 | 587.7 | 20.97 | 0.0 | 10.0 | 14.01 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.37 | vless | 387.5 | 911.5 | 18.81 | 0.0 | 10.0 | 10.71 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 75.65 | hysteria2 | 248.6 | 241.4 | 22.02 | 5.95 | 8.33 | 11.59 | 20.0 | Au1rxx-base64 | 45.32.252.144 |
| 75.52 | shadowsocks | 303.9 | 307.6 | 20.74 | 3.46 | 9.79 | 14.01 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 75.29 | trojan | 330.5 | 649.9 | 20.13 | 0.0 | 10.0 | 14.74 | 20.0 | mheidari-all | 35.88.120.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.985 | 614 | 1765 | prefer |
| mheidari-all | 1.0 | 0.924 | 314 | 16605 | prefer |
| zhangkai | 0.971 | 0.973 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.911 | 0.836 | 140 | 6360 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3330 | observe |
| DeltaKronecker-all | 0.382 | 0.357 | 14 | 6390 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7081 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7049 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4918 | observe |
| barry-far-vless | 0.255 | None | 0 | 5240 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3995 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1765 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 10 |
| geo | ClientOSError | - | 9 |
| speed | TimeoutError | - | 7 |
| geo | TimeoutError | - | 7 |
| 204 | ProxyError | - | 7 |
| cn-block | ProxyError | - | 6 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

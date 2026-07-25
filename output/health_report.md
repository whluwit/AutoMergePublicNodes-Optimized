# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 19:05:39 |
| 运行耗时 | 302.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80407 |
| 去重后节点 | 22481 |
| TCP 可达 | 3000 |
| 真实可用 | 678 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22481 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.3 |
| tcp | 31.4 |
| probe | 67.6 |
| real_test | 168.8 |
| generate | 27.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45442 |
| trojan | 14269 |
| vmess | 10185 |
| shadowsocks | 9832 |
| hysteria2 | 426 |
| http | 81 |
| shadowsocksr | 76 |
| socks | 69 |
| hysteria | 15 |
| tuic | 11 |
| anytls | 1 |

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
| 79.84 | shadowsocks | 195.8 | 477.9 | 23.25 | 0.0 | 10.0 | 12.81 | 18.28 | Au1rxx-base64 | 108.181.0.177 |
| 79.78 | shadowsocks | 198.3 | 486.7 | 23.19 | 0.0 | 10.0 | 12.81 | 18.28 | Au1rxx-base64 | 108.181.118.10 |
| 79.42 | shadowsocks | 235.5 | 558.4 | 22.33 | 0.0 | 10.0 | 12.81 | 18.28 | Au1rxx-base64 | 149.22.95.183 |
| 75.47 | shadowsocks | 292.0 | 659.1 | 21.02 | 0.0 | 10.0 | 12.81 | 18.28 | Au1rxx-base64 | 156.146.38.169 |
| 74.87 | shadowsocks | 294.4 | 668.5 | 20.96 | 0.0 | 10.0 | 12.81 | 18.28 | Au1rxx-base64 | 156.146.38.170 |
| 74.63 | shadowsocks | 427.0 | 1188.5 | 17.89 | 0.0 | 10.0 | 12.81 | 18.28 | Au1rxx-base64 | 173.244.56.9 |
| 74.35 | vless | 172.8 | 454.5 | 23.78 | 0.0 | 10.0 | 5.37 | 16.2 | mheidari-all | 104.16.9.20 |
| 73.8 | shadowsocks | 327.7 | 765.9 | 20.19 | 0.0 | 10.0 | 12.81 | 18.28 | Au1rxx-base64 | 156.146.38.167 |
| 73.4 | vless | 213.7 | 584.5 | 22.83 | 0.0 | 10.0 | 5.37 | 16.2 | mheidari-all | 198.41.209.87 |
| 73.34 | trojan | 352.8 | 806.4 | 19.61 | 0.0 | 10.0 | 11.68 | 18.28 | Au1rxx-base64 | 64.94.95.117 |
| 73.13 | shadowsocks | 291.7 | 339.6 | 21.03 | 2.26 | 9.94 | 12.81 | 18.28 | Au1rxx-base64 | 149.22.87.241 |
| 72.83 | trojan | 327.5 | 330.3 | 20.2 | 2.61 | 9.93 | 11.68 | 18.28 | Au1rxx-base64 | 95.85.94.199 |
| 72.81 | shadowsocks | 295.4 | 347.8 | 20.94 | 1.96 | 9.94 | 12.81 | 18.28 | Au1rxx-base64 | 149.22.87.204 |
| 72.7 | trojan | 327.8 | 333.6 | 20.19 | 2.49 | 9.93 | 11.68 | 18.28 | Au1rxx-base64 | 31.223.184.82 |
| 72.66 | shadowsocks | 300.5 | 348.7 | 20.82 | 1.93 | 9.94 | 12.81 | 18.28 | Au1rxx-base64 | 149.22.87.240 |
| 72.65 | trojan | 325.5 | 333.6 | 20.24 | 2.49 | 9.94 | 11.68 | 18.28 | Au1rxx-base64 | 95.85.94.112 |
| 72.62 | trojan | 326.7 | 336.5 | 20.21 | 2.38 | 9.93 | 11.68 | 18.28 | Au1rxx-base64 | 95.85.94.165 |
| 72.41 | trojan | 328.7 | 339.9 | 20.17 | 2.26 | 9.92 | 11.68 | 18.28 | Au1rxx-base64 | 31.223.184.58 |
| 72.25 | trojan | 328.6 | 673.9 | 20.17 | 0.0 | 10.0 | 11.68 | 18.28 | Au1rxx-base64 | 163.245.196.68 |
| 72.11 | trojan | 400.7 | 947.7 | 18.5 | 0.0 | 10.0 | 11.68 | 18.28 | Au1rxx-base64 | 64.94.95.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.979 | 0.987 | 77 | 119 | prefer |
| Au1rxx-base64 | 0.894 | 0.853 | 409 | 1064 | prefer |
| Surfboard-tg-mixed | 0.825 | 0.755 | 53 | 5471 | prefer |
| mheidari-all | 0.747 | 0.668 | 262 | 17275 | prefer |
| DeltaKronecker-all | 0.517 | 0.435 | 85 | 5838 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4879 | observe |
| Epodonios-all | 0.255 | None | 0 | 6622 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6579 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4269 | observe |
| barry-far-vless | 0.255 | None | 0 | 4959 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2974 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 66 |
| 204 | TimeoutError | - | 44 |
| speed | ClientOSError | - | 35 |
| cn-block | TimeoutError | - | 33 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 7 |
| 204 | ProxyError | - | 5 |
| geo | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-23 19:13:09 |
| 运行耗时 | 322.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83097 |
| 去重后节点 | 22696 |
| TCP 可达 | 3000 |
| 真实可用 | 659 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22696 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.3 |
| tcp | 32.8 |
| probe | 68.0 |
| real_test | 172.9 |
| generate | 42.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48109 |
| trojan | 14311 |
| vmess | 10086 |
| shadowsocks | 9951 |
| hysteria2 | 427 |
| shadowsocksr | 75 |
| socks | 58 |
| http | 50 |
| hysteria | 14 |
| tuic | 13 |
| anytls | 3 |

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
| 78.23 | trojan | 237.2 | 555.7 | 22.29 | 0.0 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 54.201.96.21 |
| 76.33 | trojan | 232.8 | 522.5 | 22.39 | 0.0 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 44.247.232.119 |
| 75.55 | trojan | 304.7 | 317.0 | 20.72 | 3.11 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 95.85.94.199 |
| 75.27 | trojan | 278.6 | 708.4 | 21.33 | 0.0 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 44.255.209.248 |
| 75.16 | trojan | 283.1 | 691.3 | 21.22 | 0.0 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 34.219.189.213 |
| 75.13 | trojan | 284.7 | 726.2 | 21.19 | 0.0 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 16.147.206.1 |
| 74.66 | vless | 213.5 | 490.2 | 22.84 | 0.0 | 10.0 | 4.92 | 17.9 | DeltaKronecker-all | 104.17.90.246 |
| 74.59 | vless | 216.3 | 494.7 | 22.77 | 0.0 | 10.0 | 4.92 | 17.9 | DeltaKronecker-all | 172.67.209.126 |
| 74.23 | trojan | 256.2 | 604.5 | 21.85 | 0.0 | 10.0 | 13.54 | 14.34 | mheidari-all | 44.255.92.71 |
| 73.98 | vless | 217.9 | 502.7 | 22.73 | 0.0 | 10.0 | 4.92 | 17.9 | DeltaKronecker-all | 198.41.209.87 |
| 73.65 | trojan | 281.1 | 704.2 | 21.27 | 0.0 | 10.0 | 13.54 | 14.34 | mheidari-all | 35.163.152.150 |
| 72.76 | trojan | 304.1 | 312.9 | 20.74 | 3.27 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 31.223.184.149 |
| 72.61 | trojan | 304.9 | 314.3 | 20.72 | 3.21 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 31.223.184.82 |
| 72.29 | trojan | 253.7 | 626.0 | 21.91 | 0.0 | 10.0 | 13.54 | 14.34 | mheidari-all | 34.222.117.208 |
| 72.08 | shadowsocks | 233.4 | 526.4 | 22.37 | 0.0 | 10.0 | 11.47 | 14.34 | mheidari-all | 107.172.219.230 |
| 71.57 | trojan | 336.8 | 412.4 | 19.98 | 0.0 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 95.85.94.148 |
| 71.5 | trojan | 228.1 | 552.8 | 22.5 | 0.0 | 10.0 | 13.54 | 14.34 | mheidari-all | 35.89.240.174 |
| 71.36 | vless | 204.6 | 463.8 | 23.04 | 0.0 | 10.0 | 4.92 | 17.9 | DeltaKronecker-all | 92.223.71.246 |
| 71.14 | trojan | 360.4 | 477.4 | 19.43 | 0.0 | 10.0 | 13.54 | 17.9 | DeltaKronecker-all | 95.85.94.90 |
| 70.55 | vless | 248.4 | 513.5 | 22.03 | 0.0 | 10.0 | 4.92 | 17.9 | DeltaKronecker-all | 104.25.161.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.969 | 0.891 | 322 | 19362 | prefer |
| zhangkai | 0.95 | 0.972 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.78 | 0.705 | 88 | 5412 | prefer |
| DeltaKronecker-all | 0.521 | 0.441 | 612 | 5572 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4399 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| Epodonios-all | 0.255 | None | 0 | 6563 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6800 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4259 | observe |
| barry-far-vless | 0.255 | None | 0 | 4890 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4971 | observe |
| nscl5-all | 0.255 | None | 0 | 2435 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 185 |
| geo | TimeoutError | - | 75 |
| 204 | ProxyError | - | 33 |
| geo | ClientOSError | - | 31 |
| cn-block | TimeoutError | - | 30 |
| 204 | TimeoutError | - | 27 |
| speed | TimeoutError | - | 7 |
| geo | ProxyError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

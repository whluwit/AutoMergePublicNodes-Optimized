# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-23 02:26:06 |
| 运行耗时 | 301.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81619 |
| 去重后节点 | 22921 |
| TCP 可达 | 3000 |
| 真实可用 | 642 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22921 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.2 |
| tcp | 31.6 |
| probe | 69.8 |
| real_test | 171.8 |
| generate | 21.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46934 |
| trojan | 13328 |
| shadowsocks | 10554 |
| vmess | 10191 |
| hysteria2 | 411 |
| shadowsocksr | 76 |
| http | 50 |
| socks | 42 |
| tuic | 17 |
| hysteria | 13 |
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
| 72.99 | vless | 221.4 | 609.1 | 22.65 | 0.0 | 10.0 | 5.04 | 16.3 | mheidari-all | 104.16.9.20 |
| 71.55 | vless | 197.2 | 514.1 | 23.21 | 0.0 | 10.0 | 5.04 | 16.3 | mheidari-all | 167.17.68.205 |
| 70.7 | trojan | 315.8 | 768.0 | 20.47 | 0.0 | 10.0 | 13.45 | 16.3 | mheidari-all | 34.222.117.208 |
| 69.13 | vless | 237.1 | 626.4 | 22.29 | 0.0 | 10.0 | 5.04 | 16.3 | mheidari-all | 104.18.42.163 |
| 68.0 | trojan | 327.7 | 331.2 | 20.19 | 2.58 | 9.92 | 13.45 | 14.06 | DeltaKronecker-all | 95.85.94.90 |
| 67.79 | trojan | 329.7 | 339.9 | 20.15 | 2.26 | 9.95 | 13.45 | 14.06 | DeltaKronecker-all | 94.177.131.30 |
| 67.44 | trojan | 533.2 | 1289.6 | 15.43 | 0.0 | 10.0 | 13.45 | 16.3 | mheidari-all | 163.245.196.68 |
| 67.22 | shadowsocks | 181.2 | 490.3 | 23.58 | 0.0 | 10.0 | 8.68 | 14.06 | DeltaKronecker-all | 107.172.219.230 |
| 67.04 | trojan | 500.2 | 851.9 | 16.2 | 0.0 | 9.44 | 13.45 | 16.3 | mheidari-all | 91.107.145.13 |
| 65.97 | vless | 328.1 | 621.2 | 20.18 | 0.0 | 10.0 | 5.04 | 16.3 | mheidari-all | 198.23.238.35 |
| 65.22 | trojan | 350.2 | 399.4 | 19.67 | 0.02 | 9.94 | 13.45 | 14.06 | DeltaKronecker-all | 95.85.94.199 |
| 64.75 | vless | 353.8 | 699.3 | 19.59 | 0.0 | 10.0 | 5.04 | 16.3 | mheidari-all | 154.193.55.183 |
| 64.67 | trojan | 373.7 | 474.6 | 19.13 | 0.0 | 9.94 | 13.45 | 14.06 | DeltaKronecker-all | 95.85.94.148 |
| 64.67 | trojan | 485.5 | 999.0 | 16.54 | 0.0 | 10.0 | 13.45 | 14.06 | DeltaKronecker-all | 64.74.163.118 |
| 64.62 | trojan | 515.7 | 696.2 | 15.84 | 0.0 | 9.58 | 13.45 | 16.3 | mheidari-all | 82.117.225.20 |
| 64.36 | trojan | 429.5 | 356.8 | 17.83 | 1.62 | 9.48 | 13.45 | 12.68 | Surfboard-tg-mixed | 119.246.1.143 |
| 64.33 | trojan | 603.4 | 905.0 | 13.81 | 0.0 | 10.0 | 13.45 | 16.3 | mheidari-all | 104.19.64.105 |
| 64.31 | trojan | 603.9 | 915.3 | 13.8 | 0.0 | 10.0 | 13.45 | 16.3 | mheidari-all | 185.18.250.245 |
| 64.23 | trojan | 604.7 | 908.9 | 13.78 | 0.0 | 10.0 | 13.45 | 16.3 | mheidari-all | 45.130.125.160 |
| 64.07 | trojan | 534.5 | 756.6 | 15.41 | 0.0 | 9.57 | 13.45 | 16.3 | mheidari-all | 82.117.225.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.994 | 0.926 | 68 | 5286 | prefer |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.749 | 0.671 | 170 | 5212 | prefer |
| mheidari-all | 0.626 | 0.546 | 777 | 19024 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4399 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4613 | observe |
| Epodonios-all | 0.255 | None | 0 | 6359 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3965 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6916 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4008 | observe |
| barry-far-vless | 0.255 | None | 0 | 4602 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4954 | observe |
| nscl5-all | 0.255 | None | 0 | 2435 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 188 |
| speed | ClientOSError | - | 103 |
| speed | TimeoutError | - | 44 |
| geo | ClientOSError | - | 34 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 16 |
| 204 | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 13:31:40 |
| 运行耗时 | 288.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82965 |
| 去重后节点 | 22672 |
| TCP 可达 | 3000 |
| 真实可用 | 638 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22672 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.3 |
| tcp | 32.0 |
| probe | 64.7 |
| real_test | 146.5 |
| generate | 39.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47007 |
| trojan | 15326 |
| vmess | 10156 |
| shadowsocks | 9860 |
| hysteria2 | 405 |
| shadowsocksr | 75 |
| socks | 59 |
| http | 51 |
| hysteria | 15 |
| tuic | 9 |
| anytls | 2 |

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
| 82.17 | trojan | 248.9 | 679.6 | 22.02 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 153.75.250.171 |
| 76.86 | trojan | 307.8 | 667.0 | 20.65 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 163.245.196.68 |
| 74.18 | vmess | 350.0 | 1012.0 | 19.68 | 0.0 | 10.0 | 10.0 | 19.0 | mheidari-all | 67.220.95.3 |
| 73.65 | vless | 316.8 | 598.0 | 20.44 | 0.0 | 10.0 | 4.21 | 19.0 | mheidari-all | 47.89.186.170 |
| 73.38 | trojan | 386.4 | 727.7 | 18.83 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 91.107.145.13 |
| 73.25 | vless | 284.6 | 673.9 | 21.19 | 0.0 | 10.0 | 4.21 | 19.0 | mheidari-all | 45.206.5.122 |
| 71.45 | trojan | 340.5 | 862.4 | 19.9 | 0.0 | 10.0 | 14.15 | 10.4 | DeltaKronecker-all | 64.74.163.118 |
| 70.91 | trojan | 452.8 | 814.2 | 17.3 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 79.133.126.111 |
| 70.78 | trojan | 465.9 | 773.7 | 16.99 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 193.169.239.76 |
| 70.11 | trojan | 467.0 | 795.2 | 16.97 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 8.6.112.6 |
| 69.84 | trojan | 509.6 | 974.5 | 15.98 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 193.169.239.214 |
| 69.5 | trojan | 519.2 | 947.8 | 15.76 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 79.133.126.237 |
| 69.24 | trojan | 528.2 | 1049.1 | 15.55 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 79.133.126.137 |
| 69.03 | trojan | 538.3 | 1045.1 | 15.32 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 79.133.126.190 |
| 69.02 | trojan | 534.8 | 1041.0 | 15.4 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 89.39.70.222 |
| 68.82 | trojan | 546.2 | 1069.3 | 15.13 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 13.39.127.43 |
| 68.81 | trojan | 539.9 | 1059.1 | 15.28 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 89.39.70.49 |
| 68.66 | trojan | 546.2 | 1031.6 | 15.14 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 79.133.126.108 |
| 68.51 | trojan | 515.1 | 1014.8 | 15.85 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 85.234.65.26 |
| 68.38 | trojan | 439.3 | 760.8 | 17.61 | 0.0 | 10.0 | 14.15 | 19.0 | mheidari-all | 13.39.161.149 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.818 | 0.738 | 665 | 19570 | prefer |
| Surfboard-tg-mixed | 0.729 | 0.657 | 35 | 5218 | prefer |
| DeltaKronecker-all | 0.711 | 0.633 | 120 | 5559 | prefer |
| Au1rxx-base64 | 0.601 | 1.0 | 9 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 3847 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6521 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6965 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4143 | observe |
| barry-far-vless | 0.255 | None | 0 | 4809 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| nscl5-all | 0.255 | None | 0 | 3124 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 68 |
| speed | ClientOSError | - | 42 |
| 204 | ProxyError | - | 29 |
| cn-block | TimeoutError | - | 25 |
| geo | ClientOSError | - | 20 |
| 204 | TimeoutError | - | 12 |
| cn-block | ProxyError | - | 11 |
| speed | TimeoutError | - | 9 |
| geo | ProxyError | - | 6 |
| speed | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

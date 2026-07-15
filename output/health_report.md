# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-15 08:03:33 |
| 运行耗时 | 225.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 75501 |
| 去重后节点 | 22798 |
| TCP 可达 | 3000 |
| 真实可用 | 368 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22798 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.3 |
| tcp | 31.4 |
| probe | 50.5 |
| real_test | 107.7 |
| generate | 30.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 41988 |
| trojan | 11812 |
| vmess | 11105 |
| shadowsocks | 9940 |
| hysteria2 | 345 |
| http | 138 |
| shadowsocksr | 124 |
| socks | 31 |
| hysteria | 10 |
| anytls | 5 |
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
| 81.89 | shadowsocks | 238.2 | 638.2 | 22.26 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 37.19.198.160 |
| 81.83 | shadowsocks | 240.9 | 647.8 | 22.2 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 37.19.198.243 |
| 81.72 | shadowsocks | 245.6 | 663.0 | 22.09 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 37.19.198.244 |
| 81.65 | shadowsocks | 248.8 | 675.9 | 22.02 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 37.19.198.236 |
| 79.21 | shadowsocks | 276.2 | 639.8 | 21.38 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 156.146.38.168 |
| 78.13 | shadowsocks | 298.7 | 654.4 | 20.86 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 156.146.38.167 |
| 77.89 | shadowsocks | 321.9 | 775.7 | 20.33 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 156.146.38.170 |
| 76.67 | shadowsocks | 276.7 | 632.4 | 21.37 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 156.146.38.169 |
| 76.08 | hysteria2 | 267.7 | 527.2 | 21.58 | 0.0 | 10.0 | 12.5 | 19.74 | Au1rxx-base64 | 38.148.249.252 |
| 76.03 | trojan | 297.7 | 640.8 | 20.89 | 0.0 | 10.0 | 14.14 | 16.78 | DeltaKronecker-all | 64.94.95.115 |
| 75.08 | hysteria2 | 366.2 | 666.0 | 19.3 | 0.0 | 10.0 | 12.5 | 19.74 | Au1rxx-base64 | 62.210.124.146 |
| 74.53 | shadowsocks | 329.4 | 567.2 | 20.15 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 173.244.56.6 |
| 74.12 | shadowsocks | 331.1 | 563.2 | 20.11 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 173.244.56.9 |
| 74.01 | shadowsocks | 322.1 | 553.2 | 20.32 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 108.181.0.177 |
| 73.84 | shadowsocks | 330.7 | 595.4 | 20.12 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 149.22.95.183 |
| 73.83 | vmess | 399.7 | 1104.7 | 18.53 | 0.0 | 10.0 | 12.0 | 17.8 | Surfboard-tg-mixed | 67.220.85.46 |
| 73.77 | shadowsocks | 360.0 | 885.1 | 19.44 | 0.0 | 10.0 | 13.89 | 16.78 | DeltaKronecker-all | 185.196.61.82 |
| 73.14 | shadowsocks | 303.3 | 813.4 | 20.76 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 72.15 | shadowsocks | 404.7 | 850.0 | 18.41 | 0.0 | 10.0 | 13.89 | 19.74 | Au1rxx-base64 | 108.181.118.10 |
| 71.29 | trojan | 365.2 | 584.0 | 19.32 | 0.0 | 10.0 | 14.14 | 17.8 | Surfboard-tg-mixed | 104.18.45.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.802 | 0.802 | 106 | 149 | prefer |
| mheidari-all | 0.787 | 0.711 | 97 | 16158 | prefer |
| Surfboard-tg-mixed | 0.758 | 0.681 | 119 | 5625 | prefer |
| DeltaKronecker-all | 0.684 | 0.605 | 157 | 6421 | observe |
| nscl5-all | 0.307 | 1.0 | 1 | 1300 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3759 | observe |
| Epodonios-all | 0.255 | None | 0 | 6608 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6441 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4133 | observe |
| barry-far-vless | 0.255 | None | 0 | 4712 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5187 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 54 |
| speed | ClientOSError | - | 45 |
| 204 | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| speed | TimeoutError | - | 7 |
| cn-block | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| geo | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

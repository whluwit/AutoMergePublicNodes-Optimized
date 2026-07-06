# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-06 10:12:24 |
| 运行耗时 | 195.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 79123 |
| 去重后节点 | 24389 |
| TCP 可达 | 3000 |
| 真实可用 | 368 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24389 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.3 |
| tcp | 30.9 |
| probe | 45.8 |
| real_test | 84.6 |
| generate | 28.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45512 |
| trojan | 12931 |
| vmess | 10454 |
| shadowsocks | 9438 |
| hysteria2 | 441 |
| shadowsocksr | 148 |
| http | 139 |
| socks | 44 |
| tuic | 10 |
| hysteria | 6 |

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
| 79.43 | shadowsocks | 226.7 | 624.3 | 22.53 | 0.0 | 10.0 | 13.58 | 17.32 | Au1rxx-base64 | 37.19.198.243 |
| 79.38 | shadowsocks | 228.9 | 632.0 | 22.48 | 0.0 | 10.0 | 13.58 | 17.32 | Au1rxx-base64 | 37.19.198.244 |
| 79.3 | shadowsocks | 232.4 | 642.5 | 22.4 | 0.0 | 10.0 | 13.58 | 17.32 | Au1rxx-base64 | 37.19.198.160 |
| 77.04 | shadowsocks | 250.4 | 666.0 | 21.98 | 0.0 | 10.0 | 13.58 | 15.98 | mheidari-all | 108.181.57.93 |
| 76.31 | shadowsocks | 278.7 | 638.3 | 21.33 | 0.0 | 10.0 | 13.58 | 17.32 | Au1rxx-base64 | 156.146.38.168 |
| 76.3 | shadowsocks | 232.5 | 635.6 | 22.4 | 0.0 | 10.0 | 13.58 | 17.32 | Au1rxx-base64 | 37.19.198.236 |
| 76.24 | shadowsocks | 228.8 | 615.8 | 22.48 | 0.0 | 10.0 | 13.58 | 15.98 | mheidari-all | 198.98.53.130 |
| 76.04 | shadowsocks | 276.4 | 639.3 | 21.38 | 0.0 | 10.0 | 13.58 | 17.32 | Au1rxx-base64 | 156.146.38.167 |
| 75.9 | shadowsocks | 284.2 | 659.3 | 21.2 | 0.0 | 10.0 | 13.58 | 17.32 | Au1rxx-base64 | 156.146.38.170 |
| 75.48 | trojan | 329.2 | 757.3 | 20.16 | 0.0 | 10.0 | 13.9 | 16.28 | DeltaKronecker-all | 45.32.198.247 |
| 74.84 | trojan | 343.8 | 759.7 | 19.82 | 0.0 | 10.0 | 13.9 | 16.28 | DeltaKronecker-all | 45.32.195.168 |
| 74.71 | trojan | 331.9 | 768.0 | 20.1 | 0.0 | 10.0 | 13.9 | 16.28 | DeltaKronecker-all | 149.28.241.235 |
| 74.43 | trojan | 325.7 | 635.1 | 20.24 | 0.0 | 10.0 | 13.9 | 15.98 | mheidari-all | 64.94.95.118 |
| 74.35 | shadowsocks | 340.0 | 853.3 | 19.91 | 0.0 | 10.0 | 13.58 | 15.98 | mheidari-all | 185.196.61.82 |
| 73.95 | trojan | 344.1 | 801.6 | 19.81 | 0.0 | 10.0 | 13.9 | 16.28 | DeltaKronecker-all | 64.94.95.117 |
| 73.78 | trojan | 375.5 | 895.4 | 19.09 | 0.0 | 10.0 | 13.9 | 16.28 | DeltaKronecker-all | 64.94.95.115 |
| 73.07 | trojan | 376.4 | 900.4 | 19.06 | 0.0 | 10.0 | 13.9 | 16.28 | DeltaKronecker-all | 64.94.95.114 |
| 72.51 | trojan | 461.6 | 760.4 | 17.09 | 0.0 | 10.0 | 13.9 | 19.9 | Surfboard-tg-mixed | 104.18.152.207 |
| 72.32 | trojan | 473.9 | 812.5 | 16.81 | 0.0 | 10.0 | 13.9 | 19.9 | Surfboard-tg-mixed | 104.18.152.233 |
| 72.2 | trojan | 481.0 | 798.4 | 16.64 | 0.0 | 10.0 | 13.9 | 19.9 | Surfboard-tg-mixed | 91.193.58.77 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.896 | 0.822 | 101 | 16255 | prefer |
| Au1rxx-base64 | 0.866 | 0.889 | 27 | 110 | prefer |
| DeltaKronecker-all | 0.848 | 0.771 | 188 | 8330 | prefer |
| Surfboard-tg-mixed | 0.783 | 0.706 | 109 | 5925 | prefer |
| nscl5-all | 0.377 | 1.0 | 2 | 1651 | observe |
| ermaozi | 0.256 | 1.0 | 1 | 27 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4358 | observe |
| Epodonios-all | 0.255 | None | 0 | 6980 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6861 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4334 | observe |
| barry-far-vless | 0.255 | None | 0 | 5043 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5349 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 24 |
| speed | ClientOSError | - | 21 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 8 |
| geo | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 01:32:50 |
| 运行耗时 | 335.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79314 |
| 去重后节点 | 21292 |
| TCP 可达 | 3000 |
| 真实可用 | 988 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21292 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.1 |
| tcp | 32.7 |
| probe | 62.8 |
| real_test | 198.5 |
| generate | 34.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44152 |
| vmess | 13483 |
| trojan | 10677 |
| shadowsocks | 9626 |
| hysteria2 | 1058 |
| http | 152 |
| socks | 80 |
| shadowsocksr | 70 |
| tuic | 8 |
| hysteria | 7 |
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
| 84.97 | hysteria2 | 240.3 | 661.3 | 22.22 | 0.0 | 10.0 | 14.35 | 19.5 | Au1rxx-base64 | 159.223.157.129 |
| 84.18 | http | 236.0 | 630.9 | 22.32 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 84.14 | http | 237.5 | 628.7 | 22.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 84.08 | http | 240.3 | 641.7 | 22.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 84.06 | http | 240.8 | 635.9 | 22.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 84.02 | http | 242.7 | 647.9 | 22.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 83.93 | http | 246.4 | 651.7 | 22.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.87 | http | 249.3 | 656.6 | 22.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.85 | hysteria2 | 292.9 | 813.3 | 21.0 | 0.0 | 10.0 | 14.35 | 19.5 | Au1rxx-base64 | 138.124.68.188 |
| 83.79 | http | 252.4 | 682.5 | 21.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.73 | http | 255.1 | 686.1 | 21.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.68 | http | 257.4 | 681.7 | 21.82 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 83.62 | http | 260.0 | 688.9 | 21.76 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.58 | http | 261.5 | 686.5 | 21.72 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.47 | http | 266.5 | 702.6 | 21.61 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 82.76 | vless | 242.8 | 657.4 | 22.16 | 0.0 | 10.0 | 11.1 | 19.5 | Au1rxx-base64 | 204.48.20.223 |
| 82.54 | http | 306.5 | 842.1 | 20.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.52 | http | 307.5 | 835.9 | 20.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 82.52 | http | 307.6 | 804.5 | 20.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 82.34 | http | 315.4 | 866.5 | 20.48 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.94 | 712 | 1951 | prefer |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| DeltaKronecker-all | 0.922 | 0.861 | 36 | 3656 | prefer |
| Surfboard-tg-mixed | 0.882 | 0.807 | 109 | 5942 | prefer |
| mheidari-all | 0.442 | 0.36 | 197 | 16929 | observe |
| Epodonios-all | 0.255 | None | 0 | 6600 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7491 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4695 | observe |
| barry-far-vless | 0.255 | None | 0 | 5056 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| Au1rxx-clash | 0.253 | None | 0 | 1951 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| nscl5-all | 0.217 | 0.2 | 5 | 1768 | downweight |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 56 |
| speed | TimeoutError | - | 49 |
| cn-block | TimeoutError | - | 33 |
| 204 | TimeoutError | - | 16 |
| speed | ClientOSError | - | 16 |
| geo | ClientOSError | - | 15 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

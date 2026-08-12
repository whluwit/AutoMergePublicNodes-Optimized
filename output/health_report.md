# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 01:30:56 |
| 运行耗时 | 298.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80666 |
| 去重后节点 | 22917 |
| TCP 可达 | 3000 |
| 真实可用 | 698 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22917 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.3 |
| tcp | 33.8 |
| probe | 61.7 |
| real_test | 172.8 |
| generate | 21.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46110 |
| vmess | 13122 |
| trojan | 10280 |
| shadowsocks | 9622 |
| hysteria2 | 1209 |
| http | 159 |
| shadowsocksr | 72 |
| socks | 67 |
| tuic | 15 |
| hysteria | 10 |

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
| 83.91 | hysteria2 | 233.6 | 636.7 | 22.37 | 0.0 | 10.0 | 13.7 | 18.94 | Au1rxx-base64 | 159.223.157.129 |
| 83.87 | http | 248.2 | 670.2 | 22.03 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.8 |
| 83.84 | http | 249.6 | 669.5 | 22.0 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.23 |
| 83.83 | http | 249.9 | 670.3 | 21.99 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.5 |
| 83.82 | http | 250.6 | 675.4 | 21.98 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.21 |
| 83.67 | http | 257.0 | 691.1 | 21.83 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.33 |
| 83.65 | http | 257.8 | 699.4 | 21.81 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.25 |
| 82.43 | http | 310.6 | 845.6 | 20.59 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.41 |
| 81.37 | shadowsocks | 223.4 | 616.9 | 22.61 | 0.0 | 10.0 | 13.82 | 18.94 | Au1rxx-base64 | 37.19.198.243 |
| 81.36 | shadowsocks | 223.6 | 601.1 | 22.6 | 0.0 | 10.0 | 13.82 | 18.94 | Au1rxx-base64 | 198.98.53.130 |
| 81.07 | http | 239.7 | 642.2 | 22.23 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.31 |
| 81.01 | http | 242.2 | 644.5 | 22.17 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.27 |
| 80.98 | shadowsocks | 239.9 | 658.7 | 22.22 | 0.0 | 10.0 | 13.82 | 18.94 | Au1rxx-base64 | 37.19.198.160 |
| 80.94 | http | 245.2 | 657.5 | 22.1 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.4 |
| 80.86 | http | 248.8 | 672.6 | 22.02 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.15 |
| 80.85 | http | 249.0 | 665.4 | 22.01 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.34 |
| 80.8 | http | 251.5 | 679.7 | 21.96 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.10 |
| 80.76 | http | 253.0 | 681.6 | 21.92 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.9 |
| 80.73 | http | 254.5 | 682.9 | 21.89 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.39 |
| 80.42 | http | 267.7 | 721.7 | 21.58 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 156.146.59.11 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.94 | 0.875 | 465 | 1659 | prefer |
| Surfboard-tg-mixed | 0.64 | 0.565 | 23 | 6013 | observe |
| mheidari-all | 0.455 | 0.364 | 22 | 16697 | observe |
| nscl5-all | 0.328 | 0.667 | 3 | 1481 | observe |
| DeltaKronecker-all | 0.315 | 0.234 | 599 | 5522 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5419 | observe |
| Epodonios-all | 0.255 | None | 0 | 6635 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7384 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4913 | observe |
| barry-far-vless | 0.255 | None | 0 | 5220 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1659 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 261 |
| geo | ClientOSError | - | 122 |
| speed | TimeoutError | - | 68 |
| speed | ClientOSError | - | 67 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

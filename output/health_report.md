# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-16 06:37:45 |
| 运行耗时 | 362.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 78622 |
| 去重后节点 | 21798 |
| TCP 可达 | 3000 |
| 真实可用 | 1160 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21798 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 32.7 |
| probe | 65.6 |
| real_test | 220.4 |
| generate | 36.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43196 |
| trojan | 13586 |
| vmess | 10761 |
| shadowsocks | 9714 |
| hysteria2 | 1023 |
| http | 170 |
| shadowsocksr | 77 |
| socks | 76 |
| tuic | 10 |
| hysteria | 7 |
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
| 84.13 | http | 237.9 | 642.5 | 22.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 84.09 | http | 239.6 | 643.6 | 22.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 84.09 | http | 239.6 | 638.0 | 22.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 84.08 | http | 240.2 | 644.7 | 22.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.99 | http | 243.9 | 661.1 | 22.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.86 | http | 249.5 | 668.7 | 22.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.83 | http | 251.1 | 673.4 | 21.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.79 | http | 252.5 | 674.1 | 21.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 83.79 | http | 252.7 | 691.3 | 21.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.72 | http | 255.8 | 685.7 | 21.86 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.62 | http | 260.0 | 709.6 | 21.76 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.61 | http | 260.5 | 706.4 | 21.75 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.56 | http | 262.8 | 712.4 | 21.7 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.54 | http | 263.3 | 709.3 | 21.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.54 | http | 263.5 | 718.9 | 21.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 83.53 | http | 263.9 | 711.3 | 21.67 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.48 | http | 265.9 | 701.7 | 21.62 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.62 | http | 303.2 | 829.3 | 20.76 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 81.92 | hysteria2 | 265.8 | 530.5 | 21.63 | 0.0 | 9.23 | 14.12 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 80.88 | trojan | 369.6 | 937.3 | 19.22 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 64.74.163.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.975 | 795 | 1997 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.787 | 0.71 | 145 | 16464 | prefer |
| Surfboard-tg-mixed | 0.751 | 0.673 | 211 | 5651 | prefer |
| nscl5-all | 0.349 | 0.667 | 3 | 2601 | observe |
| DeltaKronecker-all | 0.347 | 0.256 | 43 | 5092 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1997 | observe |
| Epodonios-all | 0.255 | None | 0 | 6328 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3984 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7355 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4394 | observe |
| barry-far-vless | 0.255 | None | 0 | 4736 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3950 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 54 |
| speed | TimeoutError | - | 39 |
| geo | ClientOSError | - | 20 |
| speed | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

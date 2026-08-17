# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-17 06:49:20 |
| 运行耗时 | 397.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83055 |
| 去重后节点 | 23057 |
| TCP 可达 | 3000 |
| 真实可用 | 1350 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23057 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 34.3 |
| probe | 75.2 |
| real_test | 246.1 |
| generate | 34.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45823 |
| trojan | 15236 |
| vmess | 10996 |
| shadowsocks | 9582 |
| hysteria2 | 1075 |
| http | 160 |
| socks | 87 |
| shadowsocksr | 73 |
| tuic | 10 |
| hysteria | 7 |
| anytls | 6 |

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
| 84.21 | http | 234.5 | 623.0 | 22.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 84.16 | http | 236.8 | 624.3 | 22.3 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 84.1 | http | 239.3 | 636.3 | 22.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.9 | hysteria2 | 243.5 | 666.7 | 22.14 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.86 | http | 249.6 | 664.2 | 22.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.86 | http | 249.6 | 669.4 | 22.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.85 | http | 250.2 | 655.0 | 21.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.84 | http | 250.3 | 664.4 | 21.98 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.83 | http | 250.8 | 674.1 | 21.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 83.83 | http | 251.0 | 682.9 | 21.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.81 | http | 251.9 | 683.4 | 21.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.8 | http | 252.0 | 685.0 | 21.94 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.78 | http | 252.9 | 678.3 | 21.92 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.78 | http | 252.9 | 677.5 | 21.92 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.68 | http | 257.5 | 669.7 | 21.82 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.61 | http | 260.2 | 711.0 | 21.75 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.59 | http | 261.1 | 706.0 | 21.73 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 83.38 | http | 270.4 | 721.3 | 21.52 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.76 | http | 246.5 | 658.3 | 22.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 82.69 | shadowsocks | 237.9 | 654.6 | 22.27 | 0.0 | 10.0 | 14.42 | 20.0 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.958 | 865 | 1991 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.904 | 0.833 | 72 | 5937 | prefer |
| mheidari-all | 0.896 | 0.818 | 395 | 17400 | prefer |
| nscl5-all | 0.335 | 1.0 | 1 | 3043 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 150 | observe |
| DeltaKronecker-all | 0.256 | 0.163 | 49 | 6368 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 6602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3983 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7808 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4658 | observe |
| barry-far-vless | 0.255 | None | 0 | 4994 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4046 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 53 |
| cn-block | TimeoutError | - | 28 |
| speed | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 17 |
| geo | ClientOSError | - | 14 |
| speed | ClientOSError | - | 14 |
| 204 | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

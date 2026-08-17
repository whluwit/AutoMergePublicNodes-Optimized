# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-17 01:04:31 |
| 运行耗时 | 363.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 80840 |
| 去重后节点 | 22199 |
| TCP 可达 | 3000 |
| 真实可用 | 1315 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22199 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 0.9 |
| tcp | 33.0 |
| probe | 67.8 |
| real_test | 229.2 |
| generate | 25.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44360 |
| trojan | 14844 |
| vmess | 10753 |
| shadowsocks | 9485 |
| hysteria2 | 1060 |
| http | 159 |
| socks | 87 |
| shadowsocksr | 73 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 4 |

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
| 84.19 | http | 235.4 | 635.9 | 22.33 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 84.01 | http | 243.0 | 646.2 | 22.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.96 | http | 245.3 | 654.1 | 22.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 83.91 | http | 247.3 | 668.5 | 22.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 83.82 | http | 251.1 | 678.7 | 21.96 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.81 | http | 251.8 | 678.5 | 21.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.81 | http | 252.0 | 675.0 | 21.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.79 | http | 252.8 | 678.7 | 21.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 83.72 | http | 255.7 | 671.7 | 21.86 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.71 | http | 256.2 | 686.0 | 21.85 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.7 | http | 256.5 | 693.0 | 21.84 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 83.69 | http | 257.1 | 700.5 | 21.83 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.66 | http | 258.2 | 702.9 | 21.8 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.59 | vless | 245.1 | 653.0 | 22.1 | 0.0 | 10.0 | 11.49 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 83.59 | vless | 245.4 | 687.1 | 22.1 | 0.0 | 10.0 | 11.49 | 20.0 | Au1rxx-base64 | 47.89.186.170 |
| 83.52 | http | 264.1 | 713.1 | 21.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.52 | http | 264.3 | 714.0 | 21.66 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.46 | vless | 250.8 | 655.7 | 21.97 | 0.0 | 10.0 | 11.49 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 83.37 | http | 270.8 | 715.3 | 21.51 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.02 | vless | 270.1 | 626.7 | 21.53 | 0.0 | 10.0 | 11.49 | 20.0 | Au1rxx-base64 | 169.40.42.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.955 | 911 | 1994 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.84 | 0.763 | 169 | 17074 | prefer |
| Surfboard-tg-mixed | 0.814 | 0.736 | 242 | 5936 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4990 | observe |
| nscl5-all | 0.32 | 0.5 | 4 | 3043 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 129 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1994 | observe |
| Epodonios-all | 0.255 | None | 0 | 6595 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7537 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4561 | observe |
| barry-far-vless | 0.255 | None | 0 | 4890 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4025 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 74 |
| speed | TimeoutError | - | 32 |
| cn-block | TimeoutError | - | 26 |
| geo | ClientOSError | - | 24 |
| speed | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

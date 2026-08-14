# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 07:22:50 |
| 运行耗时 | 355.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 81304 |
| 去重后节点 | 23172 |
| TCP 可达 | 3000 |
| 真实可用 | 963 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23172 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 34.9 |
| probe | 73.2 |
| real_test | 210.5 |
| generate | 29.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44345 |
| vmess | 13351 |
| trojan | 11757 |
| shadowsocks | 10104 |
| hysteria2 | 1436 |
| http | 149 |
| socks | 79 |
| shadowsocksr | 67 |
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
| 83.69 | http | 256.8 | 668.0 | 21.83 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.55 | http | 263.1 | 673.0 | 21.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 83.54 | http | 263.6 | 671.5 | 21.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 83.53 | http | 264.0 | 675.8 | 21.67 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.5 | http | 265.2 | 688.8 | 21.64 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 83.4 | http | 269.4 | 707.3 | 21.54 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.34 | http | 272.2 | 693.3 | 21.48 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 83.28 | http | 274.6 | 700.7 | 21.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.21 | http | 277.8 | 721.2 | 21.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.2 | http | 278.3 | 734.7 | 21.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 82.45 | hysteria2 | 255.8 | 662.9 | 21.86 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.1 | http | 325.8 | 815.4 | 20.24 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 82.05 | http | 327.9 | 847.9 | 20.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.05 | http | 327.9 | 855.8 | 20.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 82.03 | http | 328.5 | 866.2 | 20.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 82.0 | http | 330.0 | 867.2 | 20.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 81.97 | http | 331.1 | 863.1 | 20.11 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 81.91 | http | 333.9 | 878.2 | 20.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 81.3 | http | 328.5 | 853.9 | 20.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 81.08 | hysteria2 | 262.3 | 697.0 | 21.71 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 138.124.68.188 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 126 | 159 | prefer |
| Au1rxx-base64 | 0.989 | 0.923 | 691 | 1671 | prefer |
| Surfboard-tg-mixed | 0.71 | 0.64 | 25 | 5896 | prefer |
| DeltaKronecker-all | 0.448 | 0.368 | 476 | 5969 | observe |
| mheidari-all | 0.441 | 0.462 | 13 | 16991 | observe |
| nscl5-all | 0.326 | 1.0 | 1 | 1768 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5157 | observe |
| Epodonios-all | 0.255 | None | 0 | 6586 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7698 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4633 | observe |
| barry-far-vless | 0.255 | None | 0 | 4975 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5332 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1671 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 145 |
| geo | ClientOSError | - | 76 |
| speed | ClientOSError | - | 46 |
| speed | TimeoutError | - | 33 |
| 204 | TimeoutError | - | 30 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| speed | ClientPayloadError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

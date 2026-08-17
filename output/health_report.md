# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-17 18:39:20 |
| 运行耗时 | 484.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 80682 |
| 去重后节点 | 22980 |
| TCP 可达 | 3000 |
| 真实可用 | 1377 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22980 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 13.8 |
| geo | 1.4 |
| tcp | 36.5 |
| probe | 90.2 |
| real_test | 301.7 |
| generate | 40.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46509 |
| trojan | 14418 |
| shadowsocks | 9856 |
| vmess | 8221 |
| hysteria2 | 1240 |
| http | 195 |
| socks | 135 |
| shadowsocksr | 80 |
| tuic | 19 |
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
| 83.54 | http | 263.2 | 666.5 | 21.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 83.51 | http | 264.7 | 653.3 | 21.65 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 83.5 | http | 265.1 | 666.7 | 21.64 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 83.49 | http | 265.7 | 667.3 | 21.63 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 83.47 | http | 266.3 | 670.4 | 21.61 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 83.42 | http | 268.5 | 645.5 | 21.56 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 83.39 | http | 270.1 | 666.1 | 21.53 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 83.38 | http | 270.1 | 669.3 | 21.52 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 83.36 | http | 271.0 | 674.0 | 21.5 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 83.32 | http | 272.9 | 683.3 | 21.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 83.12 | hysteria2 | 274.4 | 718.2 | 21.43 | 0.0 | 10.0 | 12.69 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.01 | hysteria2 | 274.5 | 718.2 | 21.42 | 0.0 | 10.0 | 12.69 | 20.0 | mheidari-all | 159.223.157.129 |
| 82.42 | vless | 258.9 | 673.2 | 21.78 | 0.0 | 10.0 | 10.64 | 20.0 | Au1rxx-base64 | 204.48.20.223 |
| 82.33 | http | 315.6 | 806.2 | 20.47 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.32 | http | 316.0 | 833.2 | 20.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.32 | http | 316.3 | 827.8 | 20.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 82.26 | vless | 266.0 | 700.0 | 21.62 | 0.0 | 10.0 | 10.64 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 82.17 | http | 322.7 | 831.4 | 20.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 82.11 | http | 325.0 | 849.2 | 20.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 82.04 | http | 328.0 | 851.7 | 20.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.944 | 286 | 15619 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Au1rxx-base64 | 0.979 | 0.9 | 964 | 1983 | prefer |
| Surfboard-tg-mixed | 0.925 | 0.85 | 127 | 6186 | prefer |
| MatinGhanbari-all-sub | 0.335 | 1.0 | 1 | 3987 | observe |
| DeltaKronecker-all | 0.263 | 0.25 | 8 | 6368 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 192 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5085 | observe |
| Epodonios-all | 0.255 | None | 0 | 6790 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6707 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4808 | observe |
| barry-far-vless | 0.255 | None | 0 | 5131 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4027 | observe |
| nscl5-all | 0.255 | None | 0 | 3043 | observe |
| Au1rxx-clash | 0.254 | None | 0 | 1983 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 41 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 16 |
| geo | TimeoutError | - | 13 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

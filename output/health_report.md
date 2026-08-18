# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 06:41:10 |
| 运行耗时 | 408.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 91014 |
| 去重后节点 | 23825 |
| TCP 可达 | 3000 |
| 真实可用 | 1327 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23825 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.1 |
| tcp | 35.9 |
| probe | 72.6 |
| real_test | 257.4 |
| generate | 35.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51757 |
| trojan | 17415 |
| shadowsocks | 10390 |
| vmess | 9452 |
| hysteria2 | 1462 |
| http | 186 |
| socks | 147 |
| shadowsocksr | 128 |
| anytls | 44 |
| tuic | 20 |
| hysteria | 13 |

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
| 83.72 | hysteria2 | 270.9 | 709.2 | 21.51 | 0.0 | 10.0 | 14.21 | 19.0 | mheidari-all | 138.124.68.188 |
| 83.71 | hysteria2 | 267.1 | 666.4 | 21.6 | 0.0 | 10.0 | 14.21 | 19.0 | mheidari-all | 159.223.157.129 |
| 83.17 | http | 279.6 | 676.6 | 21.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 82.98 | http | 287.7 | 684.5 | 21.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 82.97 | http | 287.5 | 693.6 | 21.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 82.89 | http | 276.1 | 668.9 | 21.39 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 82.8 | http | 289.7 | 697.2 | 21.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |
| 82.76 | http | 286.1 | 687.9 | 21.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 82.74 | http | 285.2 | 697.1 | 21.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 82.52 | http | 281.2 | 674.7 | 21.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.34 |
| 82.48 | http | 277.7 | 664.6 | 21.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.31 |
| 82.47 | http | 288.4 | 691.7 | 21.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 82.18 | http | 276.4 | 673.1 | 21.38 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 81.99 | http | 296.6 | 725.4 | 20.91 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 81.97 | http | 295.9 | 718.1 | 20.93 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 81.88 | http | 279.7 | 680.9 | 21.3 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 81.12 | http | 301.6 | 722.6 | 20.8 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 81.08 | shadowsocks | 245.5 | 609.3 | 22.1 | 0.0 | 10.0 | 13.98 | 19.0 | mheidari-all | 156.146.38.168 |
| 80.93 | shadowsocks | 251.7 | 616.1 | 21.95 | 0.0 | 10.0 | 13.98 | 19.0 | mheidari-all | 156.146.38.170 |
| 80.71 | shadowsocks | 261.3 | 660.3 | 21.73 | 0.0 | 10.0 | 13.98 | 19.0 | mheidari-all | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.998 | 0.923 | 168 | 6109 | prefer |
| Au1rxx-base64 | 0.879 | 0.823 | 837 | 1408 | prefer |
| mheidari-all | 0.742 | 0.662 | 524 | 21284 | prefer |
| nscl5-all | 0.438 | 1.0 | 3 | 2992 | observe |
| DeltaKronecker-all | 0.37 | 0.312 | 16 | 5725 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6329 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6729 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6856 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4779 | observe |
| barry-far-vless | 0.255 | None | 0 | 5077 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4045 | observe |
| Au1rxx-clash | 0.231 | None | 0 | 1408 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 108 |
| speed | TimeoutError | - | 101 |
| geo | ClientOSError | - | 53 |
| speed | ClientOSError | - | 26 |
| 204 | ProxyError | - | 22 |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 02:27:28 |
| 运行耗时 | 293.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78339 |
| 去重后节点 | 23008 |
| TCP 可达 | 3000 |
| 真实可用 | 593 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23008 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 32.9 |
| probe | 60.5 |
| real_test | 157.1 |
| generate | 36.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45496 |
| vmess | 11400 |
| trojan | 10282 |
| shadowsocks | 10259 |
| hysteria2 | 595 |
| http | 116 |
| shadowsocksr | 74 |
| socks | 57 |
| anytls | 26 |
| tuic | 20 |
| hysteria | 14 |

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
| 80.16 | hysteria2 | 273.9 | 748.1 | 21.44 | 0.0 | 10.0 | 12.5 | 17.32 | Au1rxx-base64 | 159.223.157.129 |
| 79.94 | http | 329.5 | 890.7 | 20.15 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.20 |
| 79.88 | http | 331.9 | 889.3 | 20.09 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.25 |
| 79.87 | http | 332.3 | 893.6 | 20.08 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.7 |
| 79.82 | http | 334.7 | 890.0 | 20.03 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.8 |
| 79.7 | http | 339.9 | 914.0 | 19.91 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.21 |
| 79.66 | http | 341.7 | 914.1 | 19.87 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.50 |
| 79.01 | http | 340.1 | 916.6 | 19.91 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.23 |
| 78.9 | http | 331.1 | 889.2 | 20.11 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.16 |
| 78.86 | http | 333.0 | 885.6 | 20.07 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.33 |
| 78.34 | hysteria2 | 282.3 | 764.7 | 21.24 | 0.0 | 8.28 | 12.5 | 17.32 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 77.81 | http | 346.3 | 924.7 | 19.76 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.5 |
| 77.45 | shadowsocks | 241.1 | 641.8 | 22.2 | 0.0 | 10.0 | 11.93 | 17.32 | Au1rxx-base64 | 37.19.198.244 |
| 77.43 | shadowsocks | 241.7 | 647.5 | 22.18 | 0.0 | 10.0 | 11.93 | 17.32 | Au1rxx-base64 | 37.19.198.160 |
| 77.31 | shadowsocks | 246.9 | 664.0 | 22.06 | 0.0 | 10.0 | 11.93 | 17.32 | Au1rxx-base64 | 37.19.198.236 |
| 77.29 | shadowsocks | 247.8 | 666.8 | 22.04 | 0.0 | 10.0 | 11.93 | 17.32 | Au1rxx-base64 | 37.19.198.243 |
| 76.45 | trojan | 342.1 | 927.3 | 19.86 | 0.0 | 10.0 | 12.27 | 17.32 | Au1rxx-base64 | 153.75.250.171 |
| 75.0 | hysteria2 | 285.0 | 781.1 | 21.18 | 0.0 | 10.0 | 12.5 | 17.32 | Au1rxx-base64 | 138.124.68.188 |
| 73.94 | shadowsocks | 284.2 | 651.0 | 21.2 | 0.0 | 10.0 | 11.93 | 17.32 | Au1rxx-base64 | 156.146.38.169 |
| 73.81 | shadowsocks | 282.9 | 642.7 | 21.23 | 0.0 | 10.0 | 11.93 | 17.32 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 113 | 129 | prefer |
| Au1rxx-base64 | 0.976 | 0.929 | 238 | 1272 | prefer |
| Surfboard-tg-mixed | 0.721 | 0.642 | 204 | 5393 | prefer |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| DeltaKronecker-all | 0.328 | 0.247 | 503 | 5759 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 43 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5342 | observe |
| Epodonios-all | 0.255 | None | 0 | 6141 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6717 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4267 | observe |
| barry-far-vless | 0.255 | None | 0 | 4647 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5047 | observe |
| mheidari-all | 0.231 | 0.143 | 14 | 16264 | downweight |
| Au1rxx-clash | 0.226 | None | 0 | 1272 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 267 |
| speed | ClientOSError | - | 64 |
| geo | ClientOSError | - | 54 |
| speed | TimeoutError | - | 53 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

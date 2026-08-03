# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 09:38:53 |
| 运行耗时 | 262.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83341 |
| 去重后节点 | 24485 |
| TCP 可达 | 3000 |
| 真实可用 | 579 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24485 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 36.8 |
| probe | 55.0 |
| real_test | 134.1 |
| generate | 28.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50633 |
| vmess | 12732 |
| shadowsocks | 10481 |
| trojan | 8415 |
| hysteria2 | 732 |
| http | 176 |
| shadowsocksr | 77 |
| socks | 71 |
| hysteria | 12 |
| anytls | 7 |
| tuic | 5 |

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
| 82.47 | hysteria2 | 294.5 | 828.0 | 20.96 | 0.0 | 10.0 | 13.57 | 19.04 | Au1rxx-base64 | 159.223.157.129 |
| 81.42 | shadowsocks | 231.9 | 645.1 | 22.41 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 37.19.198.244 |
| 81.27 | shadowsocks | 238.4 | 665.6 | 22.26 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 37.19.198.236 |
| 81.18 | http | 367.1 | 1013.8 | 19.28 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.20 |
| 81.13 | http | 369.3 | 1024.4 | 19.23 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.23 |
| 81.09 | http | 370.9 | 1037.6 | 19.19 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.21 |
| 81.08 | http | 371.3 | 1033.9 | 19.18 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.8 |
| 81.02 | http | 374.0 | 1047.5 | 19.12 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.25 |
| 80.98 | http | 375.8 | 1033.2 | 19.08 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.5 |
| 80.87 | http | 380.5 | 1052.9 | 18.97 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.7 |
| 79.92 | shadowsocks | 296.8 | 837.8 | 20.91 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 37.19.198.243 |
| 78.86 | vless | 287.9 | 718.9 | 21.11 | 0.0 | 10.0 | 8.71 | 19.04 | Au1rxx-base64 | 159.195.12.98 |
| 78.15 | shadowsocks | 243.6 | 678.1 | 22.14 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 37.19.198.160 |
| 78.07 | shadowsocks | 354.9 | 864.6 | 19.56 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 68.168.222.210 |
| 77.94 | vless | 241.3 | 644.6 | 22.19 | 0.0 | 10.0 | 8.71 | 19.04 | Au1rxx-base64 | 137.184.218.169 |
| 77.83 | shadowsocks | 275.1 | 621.7 | 21.41 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 156.146.38.170 |
| 77.67 | shadowsocks | 283.3 | 658.2 | 21.22 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 156.146.38.168 |
| 77.47 | vless | 348.2 | 883.8 | 19.72 | 0.0 | 10.0 | 8.71 | 19.04 | Au1rxx-base64 | 216.152.147.28 |
| 77.44 | shadowsocks | 353.1 | 873.9 | 19.6 | 0.0 | 10.0 | 13.97 | 19.04 | Au1rxx-base64 | 185.196.61.82 |
| 76.63 | vless | 384.3 | 874.6 | 18.88 | 0.0 | 10.0 | 8.71 | 19.04 | Au1rxx-base64 | 169.40.42.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 143 | 344 | prefer |
| Au1rxx-base64 | 0.796 | 0.732 | 526 | 1629 | prefer |
| mheidari-all | 0.555 | 0.529 | 17 | 18806 | observe |
| Surfboard-tg-mixed | 0.397 | 0.313 | 99 | 5244 | observe |
| DeltaKronecker-all | 0.361 | 0.267 | 30 | 6205 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3833 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 54 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5285 | observe |
| Epodonios-all | 0.255 | None | 0 | 5831 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6567 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4132 | observe |
| barry-far-vless | 0.255 | None | 0 | 4467 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 105 |
| speed | TimeoutError | - | 44 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| geo | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

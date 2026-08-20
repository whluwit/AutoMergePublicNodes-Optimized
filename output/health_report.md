# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 01:03:28 |
| 运行耗时 | 385.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 91268 |
| 去重后节点 | 23525 |
| TCP 可达 | 3000 |
| 真实可用 | 1285 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23525 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 0.7 |
| tcp | 37.8 |
| probe | 76.6 |
| real_test | 226.9 |
| generate | 37.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51105 |
| trojan | 17508 |
| shadowsocks | 10752 |
| vmess | 9661 |
| hysteria2 | 1688 |
| shadowsocksr | 203 |
| http | 165 |
| socks | 128 |
| anytls | 33 |
| hysteria | 15 |
| tuic | 10 |

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
| 82.24 | shadowsocks | 255.6 | 685.7 | 21.86 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 82.07 | vless | 266.1 | 694.0 | 21.62 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 82.0 | vless | 268.9 | 684.1 | 21.55 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 81.81 | shadowsocks | 255.3 | 686.9 | 21.87 | 0.0 | 10.0 | 14.38 | 19.56 | Surfboard-tg-mixed | 37.19.198.243 |
| 81.5 | shadowsocks | 225.6 | 588.6 | 22.56 | 0.0 | 10.0 | 14.38 | 19.56 | Surfboard-tg-mixed | 198.98.53.130 |
| 81.41 | vless | 276.3 | 710.0 | 21.38 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 81.31 | vless | 298.7 | 702.4 | 20.86 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 80.87 | shadowsocks | 315.0 | 830.2 | 20.49 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 80.84 | vless | 276.4 | 651.9 | 21.38 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 80.66 | vless | 327.1 | 846.9 | 20.21 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 80.21 | vless | 297.2 | 630.7 | 20.9 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.173 |
| 80.21 | vless | 346.3 | 858.6 | 19.76 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 80.19 | vless | 330.4 | 870.3 | 20.13 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 80.06 | vless | 272.8 | 650.3 | 21.46 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 80.05 | shadowsocks | 267.1 | 722.4 | 21.59 | 0.0 | 10.0 | 14.38 | 18.08 | mheidari-all | 37.19.198.160 |
| 79.63 | shadowsocks | 327.8 | 852.7 | 20.19 | 0.0 | 10.0 | 14.38 | 19.56 | Surfboard-tg-mixed | 38.180.135.156 |
| 79.63 | vless | 371.4 | 856.0 | 19.18 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 79.61 | vless | 372.4 | 958.9 | 19.16 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 79.34 | vless | 309.3 | 732.9 | 20.62 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 79.28 | vless | 272.6 | 696.0 | 21.47 | 0.0 | 10.0 | 10.45 | 20.0 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.986 | 732 | 1789 | prefer |
| zhangkai | 0.988 | 0.991 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.869 | 0.792 | 264 | 6465 | prefer |
| mheidari-all | 0.808 | 0.729 | 329 | 20672 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5974 | observe |
| Epodonios-all | 0.255 | None | 0 | 7184 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7380 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5081 | observe |
| barry-far-vless | 0.255 | None | 0 | 5402 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4086 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |
| DeltaKronecker-all | 0.226 | 0.2 | 5 | 4713 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 51 |
| speed | TimeoutError | - | 44 |
| geo | ClientOSError | - | 33 |
| cn-block | TimeoutError | - | 11 |
| speed | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

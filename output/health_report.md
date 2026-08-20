# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 06:43:48 |
| 运行耗时 | 421.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 93913 |
| 去重后节点 | 25115 |
| TCP 可达 | 3000 |
| 真实可用 | 1326 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25115 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 0.6 |
| tcp | 37.2 |
| probe | 74.7 |
| real_test | 260.6 |
| generate | 40.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52555 |
| trojan | 18355 |
| shadowsocks | 10569 |
| vmess | 10203 |
| hysteria2 | 1677 |
| shadowsocksr | 197 |
| http | 165 |
| socks | 132 |
| anytls | 33 |
| hysteria | 15 |
| tuic | 12 |

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
| 81.79 | vless | 255.1 | 661.2 | 21.87 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 81.71 | vless | 258.7 | 624.8 | 21.79 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 81.7 | vless | 259.1 | 687.7 | 21.78 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 81.56 | vless | 265.1 | 626.8 | 21.64 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 81.44 | vless | 256.5 | 622.1 | 21.84 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 81.3 | vless | 276.2 | 733.8 | 21.38 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 81.21 | vless | 280.5 | 623.5 | 21.29 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 81.11 | vless | 284.6 | 757.5 | 21.19 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 80.6 | vless | 306.4 | 764.2 | 20.68 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 80.35 | vless | 274.4 | 722.1 | 21.43 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.35 |
| 79.95 | shadowsocks | 354.4 | 1012.8 | 19.57 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.92 | shadowsocks | 356.0 | 970.0 | 19.54 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 79.87 | shadowsocks | 304.1 | 805.9 | 20.74 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 79.87 | vless | 338.2 | 917.5 | 19.95 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.212 |
| 79.47 | vless | 276.0 | 671.3 | 21.39 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.90 |
| 79.38 | vless | 359.4 | 851.0 | 19.46 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.225 |
| 79.35 | vless | 355.1 | 905.6 | 19.56 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 79.33 | vless | 361.6 | 957.0 | 19.41 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 79.13 | vless | 250.5 | 653.4 | 21.98 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 78.67 | vless | 303.7 | 871.7 | 20.75 | 0.0 | 10.0 | 9.92 | 20.0 | Au1rxx-base64 | 209.50.241.126 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.984 | 702 | 1789 | prefer |
| mheidari-all | 1.0 | 0.931 | 333 | 21143 | prefer |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.872 | 0.794 | 262 | 6395 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5974 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7111 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3984 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7230 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5079 | observe |
| barry-far-vless | 0.255 | None | 0 | 5404 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| nscl5-all | 0.255 | None | 0 | 2418 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |
| DeltaKronecker-all | 0.247 | 0.136 | 22 | 6781 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 39 |
| speed | TimeoutError | - | 16 |
| geo | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 5 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46180: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

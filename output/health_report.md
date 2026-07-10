# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-10 14:15:01 |
| 运行耗时 | 205.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 75854 |
| 去重后节点 | 23671 |
| TCP 可达 | 3000 |
| 真实可用 | 208 |
| Verified 输出 | 208 |
| Global 输出 | 227 |
| All 输出 | 23671 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 31.6 |
| probe | 50.1 |
| real_test | 80.5 |
| generate | 37.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42952 |
| trojan | 12274 |
| vmess | 10817 |
| shadowsocks | 9132 |
| hysteria2 | 285 |
| shadowsocksr | 150 |
| http | 135 |
| socks | 94 |
| hysteria | 8 |
| anytls | 6 |
| tuic | 1 |

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
| 79.51 | shadowsocks | 248.3 | 669.0 | 22.03 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 108.181.57.93 |
| 76.58 | shadowsocks | 237.6 | 639.9 | 22.28 | 0.0 | 10.0 | 13.5 | 14.8 | Surfboard-tg-mixed | 37.19.198.244 |
| 76.54 | shadowsocks | 239.4 | 652.6 | 22.24 | 0.0 | 10.0 | 13.5 | 14.8 | Surfboard-tg-mixed | 37.19.198.236 |
| 76.53 | shadowsocks | 239.6 | 650.9 | 22.23 | 0.0 | 10.0 | 13.5 | 14.8 | Surfboard-tg-mixed | 37.19.198.160 |
| 76.43 | shadowsocks | 282.6 | 648.3 | 21.24 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 156.146.38.168 |
| 76.36 | shadowsocks | 290.0 | 628.0 | 21.06 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 156.146.38.167 |
| 75.76 | shadowsocks | 285.6 | 654.5 | 21.17 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 156.146.38.170 |
| 75.36 | shadowsocks | 290.2 | 815.9 | 21.06 | 0.0 | 10.0 | 13.5 | 14.8 | Surfboard-tg-mixed | 37.19.198.243 |
| 74.62 | shadowsocks | 289.1 | 665.4 | 21.08 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 156.146.38.169 |
| 74.59 | trojan | 344.0 | 762.2 | 19.81 | 0.0 | 10.0 | 13.2 | 16.86 | DeltaKronecker-all | 45.32.198.247 |
| 74.55 | trojan | 346.3 | 806.7 | 19.76 | 0.0 | 10.0 | 13.2 | 16.86 | DeltaKronecker-all | 45.32.195.168 |
| 74.0 | trojan | 323.7 | 726.7 | 20.28 | 0.0 | 10.0 | 13.2 | 16.86 | DeltaKronecker-all | 64.94.95.115 |
| 73.84 | trojan | 315.3 | 686.7 | 20.48 | 0.0 | 10.0 | 13.2 | 16.86 | DeltaKronecker-all | 64.94.95.117 |
| 72.88 | vmess | 332.6 | 922.2 | 20.08 | 0.0 | 10.0 | 12.5 | 14.8 | Surfboard-tg-mixed | 67.220.85.46 |
| 72.52 | shadowsocks | 324.2 | 566.1 | 20.27 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 108.181.0.177 |
| 72.35 | shadowsocks | 317.9 | 612.4 | 20.42 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 108.181.118.10 |
| 72.21 | shadowsocks | 324.3 | 579.3 | 20.27 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 173.244.56.9 |
| 72.07 | shadowsocks | 329.3 | 576.5 | 20.16 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 173.244.56.6 |
| 71.27 | shadowsocks | 342.4 | 655.9 | 19.85 | 0.0 | 10.0 | 13.5 | 18.48 | Au1rxx-base64 | 149.22.95.183 |
| 71.13 | shadowsocks | 293.4 | 802.7 | 20.99 | 0.0 | 10.0 | 13.5 | 14.8 | Surfboard-tg-mixed | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.877 | 0.947 | 19 | 52 | prefer |
| Surfboard-tg-mixed | 0.725 | 0.648 | 122 | 5542 | prefer |
| nscl5-all | 0.404 | 1.0 | 3 | 1148 | observe |
| DeltaKronecker-all | 0.369 | 0.287 | 237 | 7600 | observe |
| mheidari-all | 0.361 | 0.4 | 10 | 16259 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4165 | observe |
| Epodonios-all | 0.255 | None | 0 | 6344 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6483 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4182 | observe |
| barry-far-vless | 0.255 | None | 0 | 4670 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5391 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.228 | None | 0 | 1319 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 56 |
| geo | TimeoutError | - | 47 |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 21 |
| cn-block | ProxyError | - | 18 |
| geo | ClientOSError | - | 14 |
| cn-block | ClientOSError | - | 14 |
| 204 | ClientOSError | - | 7 |
| cn-block | TimeoutError | - | 7 |
| speed | TimeoutError | - | 7 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 208 | - |
| global | False | 300 | 227 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

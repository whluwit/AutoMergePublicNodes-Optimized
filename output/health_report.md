# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-08 19:21:09 |
| 运行耗时 | 179.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83161 |
| 去重后节点 | 24948 |
| TCP 可达 | 3000 |
| 真实可用 | 177 |
| Verified 输出 | 177 |
| Global 输出 | 184 |
| All 输出 | 24948 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.6 |
| tcp | 32.2 |
| probe | 41.3 |
| real_test | 60.7 |
| generate | 38.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48789 |
| trojan | 13204 |
| vmess | 10557 |
| shadowsocks | 9434 |
| hysteria2 | 829 |
| shadowsocksr | 140 |
| http | 140 |
| socks | 55 |
| hysteria | 8 |
| anytls | 3 |
| tuic | 2 |

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
| 76.75 | shadowsocks | 263.9 | 639.4 | 21.67 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 37.19.198.243 |
| 76.58 | shadowsocks | 271.1 | 660.2 | 21.5 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 37.19.198.244 |
| 76.13 | shadowsocks | 265.7 | 653.7 | 21.63 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 37.19.198.160 |
| 76.01 | shadowsocks | 288.6 | 714.1 | 21.1 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 37.19.198.236 |
| 73.36 | shadowsocks | 368.2 | 942.5 | 19.25 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 108.181.57.93 |
| 72.54 | shadowsocks | 274.7 | 667.6 | 21.42 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 147.90.234.133 |
| 71.84 | shadowsocks | 286.7 | 571.2 | 21.14 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 149.22.95.183 |
| 71.61 | shadowsocks | 252.3 | 627.5 | 21.94 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 198.98.53.130 |
| 70.44 | trojan | 270.4 | 613.4 | 21.52 | 0.0 | 10.0 | 10.41 | 11.64 | DeltaKronecker-all | 64.94.95.117 |
| 70.2 | shadowsocks | 309.0 | 600.5 | 20.63 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 108.181.118.10 |
| 70.16 | shadowsocks | 258.5 | 633.8 | 21.8 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 156.146.38.169 |
| 70.01 | trojan | 262.6 | 615.2 | 21.7 | 0.0 | 10.0 | 10.41 | 11.64 | DeltaKronecker-all | 64.94.95.114 |
| 69.96 | shadowsocks | 366.0 | 721.6 | 19.31 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 173.244.56.6 |
| 69.91 | shadowsocks | 266.2 | 601.4 | 21.61 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 156.146.38.168 |
| 69.82 | shadowsocks | 339.6 | 673.8 | 19.92 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 108.181.0.177 |
| 69.8 | shadowsocks | 262.3 | 631.8 | 21.71 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 156.146.38.170 |
| 68.86 | shadowsocks | 258.0 | 628.2 | 21.81 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | 156.146.38.167 |
| 68.27 | hysteria2 | 393.8 | 716.2 | 18.66 | 0.0 | 9.89 | 10.71 | 16.54 | Au1rxx-base64 | 62.210.124.146 |
| 68.06 | trojan | 354.8 | 891.6 | 19.57 | 0.0 | 10.0 | 10.41 | 11.64 | DeltaKronecker-all | 64.94.95.115 |
| 67.91 | shadowsocks | 278.2 | 674.5 | 21.34 | 0.0 | 10.0 | 12.54 | 16.54 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.77 | 0.773 | 66 | 129 | prefer |
| Surfboard-tg-mixed | 0.66 | 0.582 | 79 | 5884 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 3640 | observe |
| DeltaKronecker-all | 0.399 | 0.316 | 114 | 8321 | observe |
| mheidari-all | 0.382 | 0.357 | 14 | 18123 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4408 | observe |
| Epodonios-all | 0.255 | None | 0 | 6761 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3966 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6878 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4406 | observe |
| barry-far-vless | 0.255 | None | 0 | 4940 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5361 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.237 | None | 0 | 1561 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 49 |
| geo | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 7 |
| cn-block | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 3 |
| geo | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 229 | 177 | - |
| global | False | 242 | 184 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

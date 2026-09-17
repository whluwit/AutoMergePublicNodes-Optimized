# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 11:02:13 |
| 运行耗时 | 662.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84508 |
| 去重后节点 | 22939 |
| TCP 可达 | 3000 |
| 真实可用 | 433 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22939 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 37.8 |
| probe | 277.6 |
| real_test | 253.6 |
| generate | 85.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50798 |
| vmess | 13389 |
| shadowsocks | 9902 |
| trojan | 8200 |
| hysteria2 | 1387 |
| http | 627 |
| shadowsocksr | 120 |
| socks | 73 |
| hysteria | 8 |
| tuic | 2 |
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
| 82.3 | hysteria2 | 240.9 | 661.0 | 22.2 | 0.0 | 10.0 | 12.12 | 19.08 | Au1rxx-base64 | 159.223.157.129 |
| 79.26 | vless | 253.7 | 668.5 | 21.9 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 137.184.218.169 |
| 78.68 | shadowsocks | 316.2 | 827.9 | 20.46 | 0.0 | 10.0 | 13.64 | 19.08 | Au1rxx-base64 | 38.180.135.156 |
| 78.38 | vless | 292.1 | 828.5 | 21.02 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 79.141.172.154 |
| 77.56 | vless | 327.2 | 739.7 | 20.2 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.16 |
| 77.56 | vless | 327.4 | 862.3 | 20.2 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.202 |
| 77.45 | shadowsocks | 369.3 | 1041.5 | 19.23 | 0.0 | 10.0 | 13.64 | 19.08 | Au1rxx-base64 | 15.204.247.206 |
| 77.43 | vless | 333.1 | 846.0 | 20.07 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 66.70.179.198 |
| 77.33 | shadowsocks | 230.2 | 601.1 | 22.45 | 0.0 | 10.0 | 13.64 | 15.24 | Surfboard-tg-mixed | 198.98.53.130 |
| 76.92 | vless | 355.2 | 945.6 | 19.56 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.35 |
| 76.87 | vless | 341.0 | 831.5 | 19.88 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 158.69.112.254 |
| 76.67 | vless | 366.0 | 921.3 | 19.31 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.104 |
| 76.56 | vless | 370.7 | 1014.8 | 19.2 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 185.95.231.156 |
| 76.46 | vless | 375.0 | 1007.7 | 19.1 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.223 |
| 76.39 | vless | 371.6 | 990.1 | 19.18 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.229 |
| 76.25 | vless | 384.0 | 899.3 | 18.89 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.232 |
| 76.11 | vless | 361.2 | 961.3 | 19.42 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.95 |
| 75.96 | vless | 306.2 | 682.0 | 20.69 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 198.251.78.29 |
| 75.95 | vless | 396.8 | 1008.6 | 18.59 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 169.40.42.173 |
| 75.9 | vless | 361.7 | 913.8 | 19.41 | 0.0 | 10.0 | 8.28 | 19.08 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.881 | 0.817 | 289 | 1671 | prefer |
| mheidari-all | 0.838 | 0.766 | 64 | 16008 | prefer |
| ermaozi | 0.735 | 0.727 | 55 | 396 | prefer |
| DeltaKronecker-all | 0.667 | 0.591 | 44 | 5931 | observe |
| Surfboard-tg-mixed | 0.616 | 0.536 | 138 | 7408 | observe |
| ermaozi-get_subscribe | 0.325 | 0.292 | 24 | 431 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 189 | observe |
| Epodonios-all | 0.255 | None | 0 | 7867 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8876 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5925 | observe |
| barry-far-vless | 0.255 | None | 0 | 6149 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4179 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1671 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 41 |
| 204 | TimeoutError | - | 33 |
| geo | ClientOSError | - | 22 |
| geo | TimeoutError | - | 19 |
| speed | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 15 |
| cn-block | ClientOSError | - | 11 |
| cn-block | ProxyError | - | 4 |
| 204 | ServerDisconnectedError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-22 19:11:18 |
| 运行耗时 | 244.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82193 |
| 去重后节点 | 22546 |
| TCP 可达 | 3000 |
| 真实可用 | 454 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22546 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.1 |
| tcp | 31.4 |
| probe | 55.4 |
| real_test | 106.1 |
| generate | 44.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48389 |
| trojan | 12845 |
| vmess | 10222 |
| shadowsocks | 10097 |
| hysteria2 | 417 |
| shadowsocksr | 73 |
| socks | 51 |
| http | 50 |
| tuic | 31 |
| hysteria | 16 |
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
| 75.04 | vless | 186.1 | 494.2 | 23.47 | 0.0 | 10.0 | 3.91 | 17.66 | Surfboard-tg-mixed | 86.109.75.147 |
| 74.22 | trojan | 262.1 | 596.4 | 21.71 | 0.0 | 10.0 | 13.42 | 13.98 | mheidari-all | 35.89.240.174 |
| 70.9 | trojan | 215.2 | 473.8 | 22.8 | 0.0 | 10.0 | 13.42 | 13.98 | mheidari-all | 34.222.117.208 |
| 70.08 | trojan | 287.3 | 668.6 | 21.13 | 0.0 | 10.0 | 13.42 | 13.98 | mheidari-all | 44.255.92.71 |
| 69.59 | vless | 219.5 | 588.0 | 22.7 | 0.0 | 10.0 | 3.91 | 13.98 | mheidari-all | 104.16.9.20 |
| 69.58 | vless | 174.9 | 464.2 | 23.73 | 0.0 | 10.0 | 3.91 | 12.94 | DeltaKronecker-all | 104.17.90.246 |
| 69.53 | vless | 177.2 | 464.2 | 23.68 | 0.0 | 10.0 | 3.91 | 12.94 | DeltaKronecker-all | 172.67.209.126 |
| 69.46 | trojan | 369.2 | 403.7 | 19.23 | 0.0 | 10.0 | 13.42 | 17.66 | Surfboard-tg-mixed | 172.66.45.6 |
| 69.46 | trojan | 424.9 | 355.6 | 17.94 | 1.66 | 9.48 | 13.42 | 17.66 | Surfboard-tg-mixed | 119.246.1.143 |
| 69.05 | vless | 185.5 | 515.3 | 23.48 | 0.0 | 10.0 | 3.91 | 17.66 | Surfboard-tg-mixed | 66.33.22.113 |
| 68.71 | trojan | 447.1 | 627.1 | 17.43 | 0.0 | 10.0 | 13.42 | 17.66 | Surfboard-tg-mixed | 151.101.56.7 |
| 66.99 | trojan | 392.5 | 830.0 | 18.69 | 0.0 | 10.0 | 13.42 | 13.98 | mheidari-all | 163.245.196.68 |
| 66.25 | trojan | 327.3 | 329.2 | 20.2 | 2.65 | 9.95 | 13.42 | 12.94 | DeltaKronecker-all | 94.177.131.30 |
| 65.88 | trojan | 566.4 | 674.5 | 14.67 | 0.0 | 10.0 | 13.42 | 17.66 | Surfboard-tg-mixed | 151.101.1.194 |
| 65.87 | trojan | 332.9 | 335.7 | 20.07 | 2.41 | 9.95 | 13.42 | 12.94 | DeltaKronecker-all | 94.177.131.191 |
| 64.87 | trojan | 452.4 | 531.8 | 17.31 | 0.0 | 10.0 | 13.42 | 17.66 | Surfboard-tg-mixed | 199.232.222.178 |
| 64.39 | shadowsocks | 213.3 | 594.1 | 22.84 | 0.0 | 10.0 | 6.67 | 13.98 | mheidari-all | 107.172.219.230 |
| 64.35 | trojan | 586.0 | 928.6 | 14.21 | 0.0 | 9.62 | 13.42 | 17.66 | Surfboard-tg-mixed | 34.249.41.208 |
| 64.32 | trojan | 587.6 | 922.0 | 14.18 | 0.0 | 9.66 | 13.42 | 17.66 | Surfboard-tg-mixed | 34.242.69.173 |
| 64.13 | trojan | 596.7 | 915.3 | 13.97 | 0.0 | 9.64 | 13.42 | 17.66 | Surfboard-tg-mixed | 3.255.100.31 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.975 | 1.0 | 35 | 61 | prefer |
| mheidari-all | 0.815 | 0.736 | 349 | 19265 | prefer |
| DeltaKronecker-all | 0.703 | 0.627 | 67 | 5212 | prefer |
| Surfboard-tg-mixed | 0.634 | 0.555 | 211 | 5383 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 4246 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4613 | observe |
| Epodonios-all | 0.255 | None | 0 | 6453 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6975 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4231 | observe |
| barry-far-vless | 0.255 | None | 0 | 4830 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4954 | observe |
| nscl5-all | 0.255 | None | 0 | 2197 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 74 |
| speed | ClientOSError | - | 72 |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 19 |
| geo | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

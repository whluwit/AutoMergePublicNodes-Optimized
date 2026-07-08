# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-08 08:23:29 |
| 运行耗时 | 210.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83152 |
| 去重后节点 | 24718 |
| TCP 可达 | 3000 |
| 真实可用 | 362 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24718 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 31.7 |
| probe | 44.0 |
| real_test | 95.6 |
| generate | 33.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48674 |
| trojan | 13219 |
| vmess | 10477 |
| shadowsocks | 9623 |
| hysteria2 | 823 |
| shadowsocksr | 143 |
| http | 140 |
| socks | 39 |
| hysteria | 8 |
| anytls | 4 |
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
| 79.64 | trojan | 336.1 | 816.2 | 20.0 | 0.0 | 10.0 | 14.13 | 19.22 | Surfboard-tg-mixed | 64.94.95.118 |
| 75.52 | vless | 304.7 | 773.8 | 20.72 | 0.0 | 10.0 | 5.58 | 19.22 | Surfboard-tg-mixed | 47.253.226.114 |
| 75.22 | vmess | 449.0 | 1189.2 | 17.38 | 0.0 | 10.0 | 13.12 | 19.22 | Surfboard-tg-mixed | 67.220.85.46 |
| 75.16 | trojan | 279.0 | 671.6 | 21.32 | 0.0 | 10.0 | 14.13 | 12.88 | DeltaKronecker-all | 64.94.95.117 |
| 75.02 | shadowsocks | 255.0 | 624.4 | 21.87 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 156.146.38.168 |
| 75.02 | shadowsocks | 255.2 | 632.4 | 21.87 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 156.146.38.169 |
| 74.76 | shadowsocks | 266.4 | 664.4 | 21.61 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 37.19.198.244 |
| 74.71 | shadowsocks | 268.7 | 663.5 | 21.56 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 37.19.198.243 |
| 74.57 | shadowsocks | 274.6 | 686.2 | 21.42 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 37.19.198.160 |
| 74.48 | shadowsocks | 278.7 | 698.1 | 21.33 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 37.19.198.236 |
| 74.22 | shadowsocks | 252.2 | 615.7 | 21.94 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 156.146.38.170 |
| 73.76 | shadowsocks | 309.8 | 797.7 | 20.61 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 198.98.53.130 |
| 72.8 | trojan | 352.4 | 883.1 | 19.62 | 0.0 | 10.0 | 14.13 | 12.88 | DeltaKronecker-all | 64.94.95.115 |
| 72.39 | shadowsocks | 323.9 | 839.3 | 20.28 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 185.196.61.82 |
| 70.97 | trojan | 506.2 | 845.9 | 16.06 | 0.0 | 10.0 | 14.13 | 19.22 | Surfboard-tg-mixed | 104.18.152.97 |
| 70.77 | vmess | 641.5 | 1775.7 | 12.93 | 0.0 | 10.0 | 13.12 | 19.22 | Surfboard-tg-mixed | 67.220.95.3 |
| 70.69 | trojan | 495.8 | 810.7 | 16.3 | 0.0 | 10.0 | 14.13 | 19.22 | Surfboard-tg-mixed | 104.18.152.219 |
| 70.62 | trojan | 511.6 | 806.9 | 15.94 | 0.0 | 10.0 | 14.13 | 19.22 | Surfboard-tg-mixed | 188.114.97.6 |
| 70.47 | shadowsocks | 394.0 | 986.0 | 18.66 | 0.0 | 10.0 | 12.77 | 14.38 | Au1rxx-base64 | 108.181.57.93 |
| 70.16 | trojan | 512.2 | 837.3 | 15.92 | 0.0 | 10.0 | 14.13 | 19.22 | Surfboard-tg-mixed | 91.193.58.77 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.826 | 0.831 | 65 | 134 | prefer |
| DeltaKronecker-all | 0.826 | 0.75 | 136 | 8321 | prefer |
| Surfboard-tg-mixed | 0.623 | 0.543 | 302 | 5828 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3640 | observe |
| mheidari-all | 0.297 | 0.19 | 21 | 17974 | observe |
| Epodonios-all | 0.255 | None | 0 | 6817 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6807 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4349 | observe |
| barry-far-vless | 0.255 | None | 0 | 4981 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5352 | observe |
| nscl5-all | 0.237 | None | 0 | 1561 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 81 |
| geo | TimeoutError | - | 50 |
| geo | ClientOSError | - | 22 |
| 204 | TimeoutError | - | 16 |
| speed | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 4 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

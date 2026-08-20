# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 18:37:57 |
| 运行耗时 | 380.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 95088 |
| 去重后节点 | 25211 |
| TCP 可达 | 3000 |
| 真实可用 | 1125 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25211 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 38.0 |
| probe | 75.6 |
| real_test | 234.1 |
| generate | 26.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53138 |
| trojan | 18723 |
| shadowsocks | 10549 |
| vmess | 10453 |
| hysteria2 | 1671 |
| shadowsocksr | 201 |
| http | 164 |
| socks | 130 |
| anytls | 32 |
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
| 85.95 | hysteria2 | 221.2 | 224.6 | 22.66 | 6.58 | 9.94 | 13.5 | 20.0 | Au1rxx-base64 | 45.32.252.144 |
| 84.77 | trojan | 231.2 | 528.8 | 22.43 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 35.160.249.189 |
| 84.68 | trojan | 235.1 | 541.7 | 22.34 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 34.210.213.17 |
| 84.62 | trojan | 237.6 | 539.8 | 22.28 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 34.221.30.108 |
| 84.48 | trojan | 243.8 | 570.2 | 22.14 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 35.92.245.6 |
| 84.47 | trojan | 243.8 | 568.2 | 22.13 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 100.22.163.167 |
| 83.58 | trojan | 240.7 | 560.0 | 22.2 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 54.213.46.211 |
| 83.56 | trojan | 283.3 | 689.1 | 21.22 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 35.88.120.18 |
| 83.41 | trojan | 289.7 | 700.0 | 21.07 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 82.99 | trojan | 293.5 | 714.6 | 20.98 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 34.220.224.252 |
| 82.79 | shadowsocks | 161.5 | 451.7 | 24.04 | 0.0 | 10.0 | 14.0 | 20.0 | Au1rxx-base64 | 209.38.142.23 |
| 82.77 | trojan | 242.8 | 566.7 | 22.16 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 35.91.138.234 |
| 82.08 | trojan | 339.2 | 854.2 | 19.93 | 0.0 | 10.0 | 14.84 | 20.0 | Au1rxx-base64 | 34.223.2.163 |
| 82.03 | shadowsocks | 248.5 | 606.0 | 22.03 | 0.0 | 10.0 | 14.0 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 81.54 | trojan | 238.4 | 549.7 | 22.26 | 0.0 | 10.0 | 14.84 | 16.94 | mheidari-all | 54.188.176.255 |
| 81.34 | trojan | 201.3 | 523.8 | 23.12 | 0.0 | 10.0 | 14.84 | 16.38 | Surfboard-tg-mixed | 128.14.181.220 |
| 81.12 | shadowsocks | 244.2 | 568.1 | 22.12 | 0.0 | 10.0 | 14.0 | 20.0 | Au1rxx-base64 | 154.12.242.150 |
| 81.0 | trojan | 231.3 | 522.0 | 22.42 | 0.0 | 10.0 | 14.84 | 16.94 | mheidari-all | 44.243.85.47 |
| 80.73 | trojan | 240.3 | 560.2 | 22.22 | 0.0 | 10.0 | 14.84 | 16.94 | mheidari-all | 35.90.27.143 |
| 80.71 | trojan | 239.6 | 551.5 | 22.23 | 0.0 | 10.0 | 14.84 | 16.38 | Surfboard-tg-mixed | 35.88.210.26 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.966 | 563 | 1789 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Surfboard-tg-mixed | 0.985 | 0.91 | 145 | 6460 | prefer |
| mheidari-all | 0.909 | 0.831 | 402 | 22064 | prefer |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 6781 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7182 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7349 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5173 | observe |
| barry-far-vless | 0.255 | None | 0 | 5501 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| nscl5-all | 0.255 | None | 0 | 2418 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 40 |
| speed | TimeoutError | - | 14 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 9 |
| speed | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

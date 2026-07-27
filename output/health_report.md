# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 02:35:20 |
| 运行耗时 | 343.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83767 |
| 去重后节点 | 22035 |
| TCP 可达 | 3000 |
| 真实可用 | 1022 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22035 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 31.3 |
| probe | 69.7 |
| real_test | 210.3 |
| generate | 24.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46520 |
| trojan | 15549 |
| shadowsocks | 10539 |
| vmess | 10230 |
| hysteria2 | 611 |
| shadowsocksr | 106 |
| http | 84 |
| socks | 81 |
| anytls | 22 |
| hysteria | 13 |
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
| 79.74 | shadowsocks | 205.4 | 517.8 | 23.02 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 173.244.56.9 |
| 79.49 | shadowsocks | 194.7 | 480.9 | 23.27 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 108.181.118.10 |
| 79.33 | shadowsocks | 201.8 | 494.9 | 23.11 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 108.181.0.177 |
| 78.95 | shadowsocks | 239.6 | 579.8 | 22.23 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 149.22.95.183 |
| 78.9 | shadowsocks | 198.5 | 532.2 | 23.18 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 216.105.168.19 |
| 78.29 | vless | 172.9 | 469.1 | 23.78 | 0.0 | 10.0 | 5.23 | 19.28 | Au1rxx-base64 | 64.23.143.23 |
| 76.69 | shadowsocks | 207.8 | 530.7 | 22.97 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 173.244.56.6 |
| 76.17 | trojan | 324.3 | 324.0 | 20.27 | 2.85 | 9.94 | 13.73 | 19.28 | Au1rxx-base64 | 31.223.184.164 |
| 76.03 | trojan | 328.1 | 324.7 | 20.18 | 2.82 | 9.93 | 13.73 | 19.28 | Au1rxx-base64 | 95.85.94.142 |
| 75.89 | trojan | 324.7 | 330.7 | 20.26 | 2.6 | 9.94 | 13.73 | 19.28 | Au1rxx-base64 | 95.85.94.199 |
| 75.86 | trojan | 326.8 | 330.2 | 20.21 | 2.62 | 9.94 | 13.73 | 19.28 | Au1rxx-base64 | 31.223.184.82 |
| 75.83 | trojan | 332.4 | 327.8 | 20.08 | 2.71 | 9.93 | 13.73 | 19.28 | Au1rxx-base64 | 31.223.184.249 |
| 75.78 | trojan | 326.6 | 333.3 | 20.22 | 2.5 | 9.93 | 13.73 | 19.28 | Au1rxx-base64 | 95.85.94.165 |
| 75.72 | trojan | 326.2 | 334.4 | 20.23 | 2.46 | 9.94 | 13.73 | 19.28 | Au1rxx-base64 | 31.223.184.238 |
| 75.65 | trojan | 326.1 | 335.8 | 20.23 | 2.41 | 9.93 | 13.73 | 19.28 | Au1rxx-base64 | 95.85.94.51 |
| 75.63 | trojan | 327.8 | 336.2 | 20.19 | 2.39 | 9.95 | 13.73 | 19.28 | Au1rxx-base64 | 31.223.184.149 |
| 74.99 | shadowsocks | 194.8 | 521.2 | 23.27 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 216.105.168.18 |
| 74.82 | trojan | 325.3 | 332.7 | 20.25 | 2.53 | 9.95 | 13.73 | 19.28 | Au1rxx-base64 | 95.85.94.185 |
| 74.8 | trojan | 334.5 | 353.4 | 20.03 | 1.75 | 9.93 | 13.73 | 19.28 | Au1rxx-base64 | 95.85.94.96 |
| 74.65 | shadowsocks | 291.0 | 658.7 | 21.04 | 0.0 | 10.0 | 11.44 | 19.28 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.947 | 525 | 1478 | prefer |
| zhangkai | 0.991 | 1.0 | 78 | 86 | prefer |
| Surfboard-tg-mixed | 0.825 | 0.755 | 53 | 5558 | prefer |
| DeltaKronecker-all | 0.815 | 0.738 | 160 | 4320 | prefer |
| mheidari-all | 0.569 | 0.489 | 575 | 19312 | observe |
| tg-oneclickvpnkeys | 0.483 | 1.0 | 6 | 149 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3959 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6493 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3969 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6295 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4334 | observe |
| barry-far-vless | 0.255 | None | 0 | 4841 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5003 | observe |
| Au1rxx-clash | 0.234 | None | 0 | 1478 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 160 |
| speed | ClientOSError | - | 85 |
| speed | TimeoutError | - | 58 |
| geo | ClientOSError | - | 38 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

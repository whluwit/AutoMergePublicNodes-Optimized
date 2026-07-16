# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-16 02:11:49 |
| 运行耗时 | 199.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 75825 |
| 去重后节点 | 22908 |
| TCP 可达 | 3000 |
| 真实可用 | 459 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22908 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 32.2 |
| probe | 45.0 |
| real_test | 94.7 |
| generate | 21.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43290 |
| trojan | 11489 |
| vmess | 10988 |
| shadowsocks | 9481 |
| hysteria2 | 290 |
| shadowsocksr | 135 |
| http | 97 |
| socks | 41 |
| hysteria | 10 |
| tuic | 4 |

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
| 75.35 | shadowsocks | 234.2 | 648.1 | 22.36 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 37.19.198.244 |
| 74.17 | shadowsocks | 263.6 | 712.2 | 21.68 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 108.181.57.93 |
| 73.99 | shadowsocks | 232.8 | 623.5 | 22.39 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 73.95 | shadowsocks | 294.7 | 802.1 | 20.96 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 198.98.53.130 |
| 73.05 | shadowsocks | 244.0 | 644.8 | 22.13 | 0.0 | 10.0 | 12.55 | 19.32 | mheidari-all | 147.90.234.133 |
| 72.54 | hysteria2 | 287.0 | 552.2 | 21.14 | 0.0 | 10.0 | 12.0 | 14.44 | Au1rxx-base64 | 38.148.249.252 |
| 72.53 | shadowsocks | 329.0 | 869.5 | 20.16 | 0.0 | 10.0 | 12.55 | 19.32 | mheidari-all | 50.114.177.235 |
| 71.92 | shadowsocks | 280.1 | 641.3 | 21.29 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 156.146.38.169 |
| 71.78 | trojan | 484.9 | 1212.4 | 16.55 | 0.0 | 10.0 | 12.14 | 19.32 | mheidari-all | 64.94.95.118 |
| 71.37 | vless | 279.4 | 673.4 | 21.31 | 0.0 | 10.0 | 2.74 | 19.32 | mheidari-all | 104.19.87.194 |
| 71.26 | shadowsocks | 282.9 | 648.5 | 21.23 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 156.146.38.168 |
| 71.17 | trojan | 440.3 | 778.0 | 17.59 | 0.0 | 10.0 | 12.14 | 19.32 | mheidari-all | 104.18.152.208 |
| 71.12 | trojan | 442.1 | 775.9 | 17.54 | 0.0 | 10.0 | 12.14 | 19.32 | mheidari-all | 172.64.155.209 |
| 70.79 | trojan | 448.0 | 771.8 | 17.41 | 0.0 | 10.0 | 12.14 | 19.32 | mheidari-all | 104.19.64.105 |
| 70.76 | trojan | 450.1 | 794.8 | 17.36 | 0.0 | 10.0 | 12.14 | 19.32 | mheidari-all | 104.17.121.9 |
| 70.66 | shadowsocks | 291.9 | 670.5 | 21.02 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 156.146.38.167 |
| 70.64 | trojan | 448.6 | 777.5 | 17.39 | 0.0 | 10.0 | 12.14 | 19.32 | mheidari-all | 104.17.131.88 |
| 70.44 | shadowsocks | 230.2 | 628.8 | 22.45 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 37.19.198.236 |
| 70.38 | trojan | 452.4 | 774.9 | 17.31 | 0.0 | 10.0 | 12.14 | 19.32 | mheidari-all | 104.16.174.121 |
| 70.32 | shadowsocks | 235.2 | 646.4 | 22.33 | 0.0 | 10.0 | 12.55 | 14.44 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.983 | 0.912 | 91 | 5425 | prefer |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.963 | 0.967 | 92 | 149 | prefer |
| DeltaKronecker-all | 0.749 | 0.671 | 152 | 6421 | prefer |
| mheidari-all | 0.536 | 0.456 | 318 | 16454 | observe |
| xiaoji235-airport-v2ray-all | 0.382 | 1.0 | 2 | 1757 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| Epodonios-all | 0.255 | None | 0 | 6430 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6740 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4194 | observe |
| barry-far-vless | 0.255 | None | 0 | 4781 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5183 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 89 |
| geo | TimeoutError | - | 79 |
| speed | TimeoutError | - | 37 |
| geo | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | parse | TimeoutError | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-22 02:14:17 |
| 运行耗时 | 308.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81716 |
| 去重后节点 | 22508 |
| TCP 可达 | 3000 |
| 真实可用 | 626 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22508 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.3 |
| tcp | 30.6 |
| probe | 60.7 |
| real_test | 170.6 |
| generate | 40.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47855 |
| trojan | 12583 |
| vmess | 10686 |
| shadowsocks | 9980 |
| hysteria2 | 416 |
| shadowsocksr | 73 |
| http | 51 |
| socks | 49 |
| hysteria | 16 |
| tuic | 5 |
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
| 75.16 | shadowsocks | 235.7 | 654.3 | 22.32 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 37.19.198.160 |
| 75.16 | shadowsocks | 235.9 | 652.5 | 22.32 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 37.19.198.244 |
| 75.14 | shadowsocks | 236.5 | 651.7 | 22.3 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 37.19.198.243 |
| 73.85 | shadowsocks | 292.6 | 816.3 | 21.01 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 198.98.53.130 |
| 73.15 | shadowsocks | 301.0 | 823.2 | 20.81 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 108.181.57.93 |
| 72.48 | vless | 243.9 | 678.2 | 22.13 | 0.0 | 10.0 | 3.21 | 17.14 | Surfboard-tg-mixed | 47.89.186.170 |
| 72.44 | trojan | 351.1 | 787.9 | 19.65 | 0.0 | 10.0 | 13.36 | 15.7 | Au1rxx-base64 | 64.94.95.115 |
| 72.32 | shadowsocks | 229.0 | 630.1 | 22.48 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 37.19.198.236 |
| 72.02 | shadowsocks | 279.4 | 633.1 | 21.31 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 156.146.38.170 |
| 71.68 | shadowsocks | 355.7 | 876.9 | 19.54 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 185.196.61.82 |
| 71.32 | trojan | 513.2 | 1352.8 | 15.9 | 0.0 | 10.0 | 13.36 | 15.7 | Au1rxx-base64 | 148.72.168.35 |
| 71.25 | trojan | 395.6 | 918.9 | 18.62 | 0.0 | 10.0 | 13.36 | 15.7 | Au1rxx-base64 | 64.94.95.118 |
| 70.97 | shadowsocks | 277.1 | 631.4 | 21.36 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 156.146.38.167 |
| 70.95 | shadowsocks | 287.6 | 654.6 | 21.12 | 0.0 | 10.0 | 11.14 | 15.7 | Au1rxx-base64 | 156.146.38.169 |
| 70.92 | trojan | 410.9 | 962.8 | 18.27 | 0.0 | 10.0 | 13.36 | 15.7 | Au1rxx-base64 | 64.94.95.117 |
| 70.47 | trojan | 398.5 | 767.3 | 18.55 | 0.0 | 10.0 | 13.36 | 17.14 | Surfboard-tg-mixed | 3.255.100.31 |
| 70.36 | trojan | 436.1 | 774.0 | 17.68 | 0.0 | 10.0 | 13.36 | 17.14 | Surfboard-tg-mixed | 212.183.88.136 |
| 70.23 | trojan | 404.2 | 778.9 | 18.42 | 0.0 | 10.0 | 13.36 | 17.14 | Surfboard-tg-mixed | 34.249.41.208 |
| 70.17 | trojan | 434.5 | 777.2 | 17.72 | 0.0 | 10.0 | 13.36 | 17.14 | Surfboard-tg-mixed | 198.62.62.23 |
| 70.15 | trojan | 379.2 | 617.9 | 19.0 | 0.0 | 10.0 | 13.36 | 17.14 | Surfboard-tg-mixed | 199.232.78.140 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.75 | 0.735 | 211 | 432 | prefer |
| Surfboard-tg-mixed | 0.743 | 0.664 | 289 | 5420 | prefer |
| mheidari-all | 0.453 | 0.373 | 598 | 18723 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4246 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4482 | observe |
| DeltaKronecker-all | 0.273 | 0.186 | 86 | 5415 | observe |
| Epodonios-all | 0.255 | None | 0 | 6487 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3967 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7011 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4054 | observe |
| barry-far-vless | 0.255 | None | 0 | 4665 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5204 | observe |
| nscl5-all | 0.255 | None | 0 | 2197 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 228 |
| speed | ClientOSError | - | 165 |
| cn-block | TimeoutError | - | 66 |
| geo | ClientOSError | - | 60 |
| speed | TimeoutError | - | 51 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

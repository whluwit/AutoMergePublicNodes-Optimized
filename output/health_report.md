# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-12 02:18:11 |
| 运行耗时 | 230.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 76484 |
| 去重后节点 | 24080 |
| TCP 可达 | 3000 |
| 真实可用 | 509 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24080 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.3 |
| tcp | 31.8 |
| probe | 50.1 |
| real_test | 117.1 |
| generate | 25.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43980 |
| trojan | 11871 |
| vmess | 10584 |
| shadowsocks | 9450 |
| hysteria2 | 268 |
| shadowsocksr | 147 |
| http | 135 |
| socks | 36 |
| hysteria | 8 |
| tuic | 5 |

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
| 74.51 | shadowsocks | 215.9 | 584.5 | 22.78 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 198.98.53.130 |
| 74.26 | shadowsocks | 226.5 | 620.7 | 22.53 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 37.19.198.244 |
| 74.16 | shadowsocks | 231.2 | 638.1 | 22.43 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 37.19.198.160 |
| 74.09 | shadowsocks | 234.1 | 647.3 | 22.36 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 37.19.198.243 |
| 74.03 | shadowsocks | 236.5 | 634.0 | 22.3 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 147.90.234.133 |
| 70.69 | shadowsocks | 251.1 | 700.3 | 21.96 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 37.19.198.236 |
| 69.38 | shadowsocks | 336.7 | 770.3 | 19.98 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 156.146.38.168 |
| 68.87 | socks | 278.9 | 715.0 | 21.32 | 0.0 | 10.0 | 10.31 | 11.74 | Surfboard-tg-mixed | 134.122.1.61 |
| 68.12 | shadowsocks | 344.3 | 827.0 | 19.81 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 156.146.38.167 |
| 66.91 | trojan | 335.7 | 778.4 | 20.01 | 0.0 | 10.0 | 8.35 | 14.06 | Au1rxx-base64 | 149.28.241.235 |
| 66.63 | shadowsocks | 324.6 | 578.0 | 20.26 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 173.244.56.6 |
| 66.5 | shadowsocks | 326.1 | 575.5 | 20.23 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 173.244.56.9 |
| 66.27 | vless | 310.5 | 792.6 | 20.59 | 0.0 | 10.0 | 4.94 | 11.74 | Surfboard-tg-mixed | 104.16.75.234 |
| 66.17 | vless | 242.2 | 654.2 | 22.17 | 0.0 | 10.0 | 4.94 | 14.06 | Au1rxx-base64 | 159.89.87.21 |
| 66.12 | http | 623.4 | 955.6 | 13.35 | 0.0 | 9.77 | 14.61 | 19.52 | snakem982 | 193.176.84.32 |
| 65.89 | shadowsocks | 333.0 | 601.6 | 20.07 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 108.181.0.177 |
| 65.86 | shadowsocks | 297.6 | 634.8 | 20.89 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 156.146.38.170 |
| 65.48 | shadowsocks | 360.3 | 640.6 | 19.44 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | 149.22.95.183 |
| 65.41 | http | 644.8 | 971.4 | 12.85 | 0.0 | 9.68 | 14.61 | 19.52 | snakem982 | 84.239.49.154 |
| 65.4 | shadowsocks | 290.9 | 806.2 | 21.04 | 0.0 | 10.0 | 11.67 | 14.06 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.786 | 0.79 | 62 | 125 | prefer |
| Surfboard-tg-mixed | 0.756 | 0.677 | 322 | 5400 | prefer |
| mheidari-all | 0.603 | 0.523 | 279 | 16350 | observe |
| DeltaKronecker-all | 0.537 | 0.456 | 125 | 7969 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 3953 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6385 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6420 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4135 | observe |
| barry-far-vless | 0.255 | None | 0 | 4725 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5416 | observe |
| nscl5-all | 0.233 | None | 0 | 1439 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 126 |
| geo | TimeoutError | - | 94 |
| speed | TimeoutError | - | 38 |
| geo | ClientOSError | - | 29 |
| cn-block | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 292 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

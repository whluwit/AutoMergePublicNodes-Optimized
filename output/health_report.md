# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-20 02:37:12 |
| 运行耗时 | 266.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86121 |
| 去重后节点 | 24160 |
| TCP 可达 | 3000 |
| 真实可用 | 624 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24160 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.0 |
| tcp | 34.5 |
| probe | 61.5 |
| real_test | 132.2 |
| generate | 31.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50425 |
| trojan | 14214 |
| vmess | 10887 |
| shadowsocks | 10008 |
| hysteria2 | 399 |
| shadowsocksr | 71 |
| http | 52 |
| socks | 38 |
| hysteria | 15 |
| tuic | 11 |
| anytls | 1 |

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
| 77.16 | shadowsocks | 249.7 | 618.5 | 22.0 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 156.146.38.168 |
| 77.08 | shadowsocks | 253.0 | 623.7 | 21.92 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 156.146.38.170 |
| 76.75 | shadowsocks | 267.4 | 658.6 | 21.59 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 37.19.198.244 |
| 76.66 | shadowsocks | 268.8 | 678.1 | 21.56 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 37.19.198.160 |
| 76.6 | shadowsocks | 273.7 | 685.1 | 21.44 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 37.19.198.243 |
| 75.26 | shadowsocks | 331.6 | 865.3 | 20.1 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 37.19.198.236 |
| 75.2 | shadowsocks | 334.2 | 860.6 | 20.04 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 198.98.53.130 |
| 75.17 | shadowsocks | 279.2 | 689.0 | 21.32 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 108.181.57.93 |
| 75.01 | shadowsocks | 321.0 | 838.3 | 20.35 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 185.196.61.82 |
| 74.75 | shadowsocks | 332.1 | 887.9 | 20.09 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 50.114.177.235 |
| 74.42 | shadowsocks | 368.2 | 970.3 | 19.26 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 156.146.38.169 |
| 73.74 | shadowsocks | 397.5 | 1055.1 | 18.58 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 156.146.38.167 |
| 73.05 | shadowsocks | 405.6 | 771.2 | 18.39 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 68.168.222.210 |
| 71.83 | shadowsocks | 295.6 | 610.2 | 20.94 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 149.22.95.183 |
| 71.42 | trojan | 421.2 | 1077.0 | 18.03 | 0.0 | 10.0 | 11.2 | 17.2 | Au1rxx-base64 | 64.94.95.118 |
| 71.41 | shadowsocks | 288.2 | 568.1 | 21.11 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 173.244.56.9 |
| 71.37 | shadowsocks | 318.5 | 623.5 | 20.41 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 108.181.0.177 |
| 70.62 | shadowsocks | 361.3 | 770.5 | 19.41 | 0.0 | 10.0 | 11.96 | 17.2 | Au1rxx-base64 | 172.245.235.84 |
| 69.72 | hysteria2 | 431.7 | 852.6 | 17.78 | 0.0 | 9.95 | 12.0 | 17.2 | Au1rxx-base64 | 62.210.124.146 |
| 69.7 | trojan | 400.2 | 999.0 | 18.51 | 0.0 | 10.0 | 11.2 | 17.2 | Au1rxx-base64 | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | 0.949 | 254 | 1061 | prefer |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.697 | 0.619 | 160 | 6235 | observe |
| mheidari-all | 0.663 | 0.584 | 197 | 19448 | observe |
| Surfboard-tg-mixed | 0.572 | 0.492 | 238 | 5229 | observe |
| chromego_merge | 0.479 | 1.0 | 6 | 54 | observe |
| nscl5-all | 0.335 | 1.0 | 1 | 2755 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4478 | observe |
| Epodonios-all | 0.255 | None | 0 | 6589 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6990 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4170 | observe |
| barry-far-vless | 0.255 | None | 0 | 4960 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5229 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 136 |
| geo | TimeoutError | - | 73 |
| 204 | TimeoutError | - | 52 |
| geo | ClientOSError | - | 33 |
| speed | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

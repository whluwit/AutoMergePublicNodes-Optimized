# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-29 19:55:20 |
| 运行耗时 | 267.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 75437 |
| 去重后节点 | 22984 |
| TCP 可达 | 3000 |
| 真实可用 | 434 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22984 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.4 |
| tcp | 30.6 |
| probe | 59.9 |
| real_test | 127.9 |
| generate | 43.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42124 |
| trojan | 13127 |
| vmess | 10320 |
| shadowsocks | 9254 |
| hysteria2 | 267 |
| shadowsocksr | 151 |
| http | 136 |
| socks | 51 |
| hysteria | 6 |
| tuic | 1 |

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
| 79.28 | vless | 266.5 | 754.6 | 21.61 | 0.0 | 10.0 | 10.27 | 17.4 | mheidari-all | 47.253.226.114 |
| 77.26 | shadowsocks | 242.1 | 652.6 | 22.17 | 0.0 | 10.0 | 12.19 | 17.4 | mheidari-all | 108.181.57.93 |
| 76.92 | shadowsocks | 236.3 | 652.8 | 22.31 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 37.19.198.244 |
| 76.9 | shadowsocks | 237.2 | 648.0 | 22.29 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 37.19.198.243 |
| 76.89 | shadowsocks | 237.6 | 647.5 | 22.28 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 37.19.198.160 |
| 76.84 | shadowsocks | 239.6 | 640.9 | 22.23 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 37.19.198.236 |
| 75.68 | shadowsocks | 331.9 | 699.1 | 20.09 | 0.0 | 10.0 | 12.19 | 17.4 | mheidari-all | 198.98.53.130 |
| 72.76 | shadowsocks | 287.2 | 648.1 | 21.13 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 156.146.38.169 |
| 72.61 | shadowsocks | 282.9 | 660.2 | 21.23 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 156.146.38.167 |
| 72.39 | vless | 265.3 | 655.1 | 21.64 | 0.0 | 10.0 | 10.27 | 11.48 | DeltaKronecker-all | 104.17.90.246 |
| 71.91 | shadowsocks | 330.2 | 783.7 | 20.13 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 156.146.38.168 |
| 71.12 | trojan | 369.2 | 883.2 | 19.23 | 0.0 | 10.0 | 10.99 | 17.4 | mheidari-all | 64.94.95.118 |
| 71.06 | vless | 270.2 | 661.5 | 21.52 | 0.0 | 10.0 | 10.27 | 11.48 | DeltaKronecker-all | 198.41.209.87 |
| 70.61 | hysteria2 | 353.7 | 682.6 | 19.59 | 0.0 | 10.0 | 11.25 | 16.42 | Au1rxx-base64 | 62.210.124.146 |
| 70.16 | vless | 294.6 | 732.5 | 20.96 | 0.0 | 10.0 | 10.27 | 17.4 | mheidari-all | 162.159.18.241 |
| 70.14 | shadowsocks | 315.2 | 581.3 | 20.48 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 173.244.56.6 |
| 69.96 | shadowsocks | 237.0 | 645.9 | 22.29 | 0.0 | 10.0 | 12.19 | 11.48 | DeltaKronecker-all | 147.90.234.133 |
| 69.31 | shadowsocks | 313.6 | 544.9 | 20.52 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 108.181.118.10 |
| 69.14 | shadowsocks | 461.3 | 1012.1 | 17.1 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 172.234.202.34 |
| 69.09 | shadowsocks | 298.7 | 559.7 | 20.86 | 0.0 | 10.0 | 12.19 | 16.42 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.798 | 0.719 | 260 | 15724 | prefer |
| Au1rxx-base64 | 0.753 | 0.765 | 34 | 79 | prefer |
| Surfboard-tg-mixed | 0.745 | 0.667 | 231 | 5497 | prefer |
| DeltaKronecker-all | 0.535 | 0.453 | 64 | 7004 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 170 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4653 | observe |
| Epodonios-all | 0.255 | None | 0 | 6449 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3980 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6727 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3986 | observe |
| barry-far-vless | 0.255 | None | 0 | 4569 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5353 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 93 |
| 204 | ProxyError | - | 20 |
| 204 | TimeoutError | - | 17 |
| 204 | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| geo | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 7 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

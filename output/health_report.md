# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-29 15:43:22 |
| 运行耗时 | 251.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 77444 |
| 去重后节点 | 23262 |
| TCP 可达 | 3000 |
| 真实可用 | 497 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23262 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.4 |
| tcp | 31.0 |
| probe | 49.9 |
| real_test | 126.2 |
| generate | 38.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43645 |
| trojan | 12987 |
| vmess | 10951 |
| shadowsocks | 9264 |
| hysteria2 | 247 |
| shadowsocksr | 156 |
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
| 79.02 | vless | 309.7 | 775.5 | 20.61 | 0.0 | 10.0 | 11.17 | 17.24 | mheidari-all | 47.253.226.114 |
| 74.75 | shadowsocks | 269.1 | 626.5 | 21.55 | 0.0 | 10.0 | 10.62 | 17.24 | mheidari-all | 198.98.53.130 |
| 74.31 | shadowsocks | 262.2 | 648.5 | 21.71 | 0.0 | 10.0 | 10.62 | 15.98 | Au1rxx-base64 | 156.146.38.169 |
| 74.3 | shadowsocks | 258.1 | 639.9 | 21.8 | 0.0 | 10.0 | 10.62 | 15.98 | Au1rxx-base64 | 156.146.38.168 |
| 73.63 | shadowsocks | 258.2 | 619.1 | 21.8 | 0.0 | 10.0 | 10.62 | 15.98 | Au1rxx-base64 | 156.146.38.170 |
| 73.04 | shadowsocks | 273.9 | 692.1 | 21.44 | 0.0 | 10.0 | 10.62 | 15.98 | Au1rxx-base64 | 37.19.198.160 |
| 72.87 | shadowsocks | 282.0 | 687.9 | 21.25 | 0.0 | 10.0 | 10.62 | 15.98 | Au1rxx-base64 | 37.19.198.243 |
| 72.63 | shadowsocks | 280.0 | 678.6 | 21.3 | 0.0 | 10.0 | 10.62 | 17.24 | mheidari-all | 108.181.57.93 |
| 72.04 | shadowsocks | 277.6 | 661.6 | 21.35 | 0.0 | 10.0 | 10.62 | 15.98 | Au1rxx-base64 | 37.19.198.244 |
| 71.94 | vless | 281.7 | 671.6 | 21.26 | 0.0 | 10.0 | 11.17 | 12.3 | DeltaKronecker-all | 198.41.209.87 |
| 71.11 | vless | 280.2 | 655.6 | 21.29 | 0.0 | 10.0 | 11.17 | 12.3 | DeltaKronecker-all | 104.17.238.33 |
| 70.91 | vless | 344.4 | 655.2 | 19.8 | 0.0 | 10.0 | 11.17 | 17.24 | mheidari-all | 38.244.20.164 |
| 70.81 | vless | 305.9 | 729.0 | 20.7 | 0.0 | 10.0 | 11.17 | 12.3 | DeltaKronecker-all | 162.159.252.15 |
| 70.81 | shadowsocks | 311.8 | 803.5 | 20.56 | 0.0 | 10.0 | 10.62 | 15.98 | Au1rxx-base64 | 37.19.198.236 |
| 70.52 | vless | 412.1 | 794.2 | 18.24 | 0.0 | 10.0 | 11.17 | 17.24 | mheidari-all | 34.213.172.16 |
| 70.41 | vless | 290.0 | 689.7 | 21.07 | 0.0 | 10.0 | 11.17 | 12.3 | DeltaKronecker-all | 104.17.90.246 |
| 70.41 | vless | 312.7 | 600.8 | 20.54 | 0.0 | 10.0 | 11.17 | 15.06 | Surfboard-tg-mixed | 64.23.143.23 |
| 70.31 | vless | 347.8 | 592.9 | 19.73 | 0.0 | 10.0 | 11.17 | 17.24 | mheidari-all | 162.159.18.241 |
| 70.09 | vless | 317.9 | 592.7 | 20.42 | 0.0 | 10.0 | 11.17 | 17.24 | mheidari-all | 104.18.42.68 |
| 69.88 | vless | 430.0 | 950.0 | 17.82 | 0.0 | 10.0 | 11.17 | 15.98 | Au1rxx-base64 | 15.204.97.214 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.87 | 0.792 | 269 | 15881 | prefer |
| Au1rxx-base64 | 0.821 | 0.839 | 31 | 80 | prefer |
| Surfboard-tg-mixed | 0.769 | 0.691 | 262 | 5497 | prefer |
| DeltaKronecker-all | 0.574 | 0.494 | 77 | 7004 | observe |
| nscl5-all | 0.302 | 1.0 | 1 | 1166 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4653 | observe |
| Epodonios-all | 0.255 | None | 0 | 7616 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7472 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3986 | observe |
| barry-far-vless | 0.255 | None | 0 | 4553 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5278 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 86 |
| geo | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| geo | ClientOSError | - | 8 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

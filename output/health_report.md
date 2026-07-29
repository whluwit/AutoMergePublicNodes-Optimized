# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 02:12:16 |
| 运行耗时 | 266.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 76519 |
| 去重后节点 | 21563 |
| TCP 可达 | 3000 |
| 真实可用 | 670 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21563 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.4 |
| tcp | 31.3 |
| probe | 55.1 |
| real_test | 143.5 |
| generate | 29.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43971 |
| trojan | 10976 |
| shadowsocks | 10518 |
| vmess | 10316 |
| hysteria2 | 494 |
| http | 100 |
| shadowsocksr | 74 |
| socks | 59 |
| hysteria | 8 |
| tuic | 3 |

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
| 80.16 | shadowsocks | 217.8 | 523.1 | 22.74 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 173.244.56.6 |
| 80.06 | shadowsocks | 200.4 | 491.0 | 23.14 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 108.181.118.10 |
| 79.9 | shadowsocks | 228.7 | 517.2 | 22.48 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 173.244.56.9 |
| 79.43 | shadowsocks | 240.0 | 570.9 | 22.22 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 149.22.95.183 |
| 77.93 | shadowsocks | 287.1 | 750.9 | 21.13 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 108.181.0.177 |
| 77.85 | shadowsocks | 187.7 | 480.6 | 23.43 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 216.105.168.18 |
| 75.05 | shadowsocks | 290.0 | 649.0 | 21.06 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 156.146.38.170 |
| 75.02 | shadowsocks | 298.4 | 654.2 | 20.87 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 156.146.38.168 |
| 74.82 | shadowsocks | 289.6 | 634.6 | 21.07 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 156.146.38.169 |
| 74.38 | shadowsocks | 288.9 | 652.8 | 21.09 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 156.146.38.167 |
| 74.25 | hysteria2 | 348.1 | 721.3 | 19.72 | 0.0 | 10.0 | 11.25 | 18.64 | Au1rxx-base64 | 159.223.157.129 |
| 73.59 | vless | 269.4 | 629.0 | 21.54 | 0.0 | 10.0 | 8.02 | 18.64 | Au1rxx-base64 | 52.43.158.158 |
| 73.24 | shadowsocks | 293.5 | 338.9 | 20.98 | 2.29 | 9.94 | 12.78 | 18.64 | Au1rxx-base64 | 149.22.87.204 |
| 73.13 | shadowsocks | 296.6 | 347.0 | 20.91 | 1.99 | 9.94 | 12.78 | 18.64 | Au1rxx-base64 | 149.22.87.240 |
| 72.17 | vless | 271.0 | 650.0 | 21.51 | 0.0 | 10.0 | 8.02 | 18.64 | Au1rxx-base64 | web-production-bc324.up.railway.app |
| 71.42 | shadowsocks | 349.6 | 691.4 | 19.69 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 198.98.53.130 |
| 71.0 | vless | 167.6 | 455.5 | 23.9 | 0.0 | 10.0 | 8.02 | 10.08 | DeltaKronecker-all | 104.16.9.20 |
| 70.89 | shadowsocks | 372.6 | 735.8 | 19.15 | 0.0 | 10.0 | 12.78 | 18.64 | Au1rxx-base64 | 37.19.198.244 |
| 70.88 | vless | 172.8 | 458.1 | 23.78 | 0.0 | 10.0 | 8.02 | 10.08 | DeltaKronecker-all | 104.25.161.29 |
| 70.8 | vless | 176.1 | 472.9 | 23.7 | 0.0 | 10.0 | 8.02 | 10.08 | DeltaKronecker-all | 104.17.90.246 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 64 | 173 | prefer |
| Au1rxx-base64 | 0.972 | 0.928 | 305 | 1167 | prefer |
| DeltaKronecker-all | 0.803 | 0.725 | 262 | 4038 | prefer |
| Surfboard-tg-mixed | 0.687 | 0.608 | 176 | 5746 | observe |
| mheidari-all | 0.474 | 0.391 | 64 | 17232 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6752 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6316 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4508 | observe |
| barry-far-vless | 0.255 | None | 0 | 5026 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5059 | observe |
| nscl5-all | 0.246 | None | 0 | 1774 | observe |
| Au1rxx-clash | 0.222 | None | 0 | 1167 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 74 |
| cn-block | TimeoutError | - | 35 |
| geo | ClientOSError | - | 30 |
| speed | TimeoutError | - | 27 |
| speed | ClientOSError | - | 23 |
| 204 | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

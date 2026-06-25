# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-25 08:58:14 |
| 运行耗时 | 244.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 82391 |
| 去重后节点 | 22466 |
| TCP 可达 | 3000 |
| 真实可用 | 388 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22466 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.3 |
| tcp | 29.2 |
| probe | 56.0 |
| real_test | 111.3 |
| generate | 42.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46345 |
| trojan | 14134 |
| vmess | 11163 |
| shadowsocks | 10161 |
| hysteria2 | 230 |
| shadowsocksr | 154 |
| http | 129 |
| socks | 67 |
| hysteria | 6 |
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
| 74.87 | shadowsocks | 254.3 | 639.4 | 21.89 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 156.146.38.167 |
| 74.75 | shadowsocks | 256.5 | 626.2 | 21.84 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 156.146.38.168 |
| 74.69 | shadowsocks | 262.1 | 644.6 | 21.71 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 37.19.198.244 |
| 74.61 | shadowsocks | 265.5 | 671.7 | 21.63 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 37.19.198.160 |
| 74.42 | shadowsocks | 273.5 | 675.4 | 21.45 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 37.19.198.236 |
| 73.79 | shadowsocks | 273.7 | 683.1 | 21.44 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 37.19.198.243 |
| 72.62 | shadowsocks | 278.6 | 671.5 | 21.33 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 108.181.57.93 |
| 72.33 | vless | 281.2 | 668.9 | 21.27 | 0.0 | 10.0 | 6.75 | 17.04 | Surfboard-tg-mixed | 104.16.9.20 |
| 72.0 | shadowsocks | 333.9 | 519.0 | 20.05 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 198.98.53.130 |
| 71.61 | vless | 304.0 | 774.2 | 20.74 | 0.0 | 10.0 | 6.75 | 14.12 | mheidari-all | 47.253.226.114 |
| 71.42 | vless | 366.2 | 910.1 | 19.3 | 0.0 | 10.0 | 6.75 | 17.04 | Surfboard-tg-mixed | 15.223.121.250 |
| 70.23 | vless | 293.3 | 691.9 | 20.99 | 0.0 | 10.0 | 6.75 | 17.04 | Surfboard-tg-mixed | 137.184.218.169 |
| 70.04 | shadowsocks | 247.2 | 610.2 | 22.06 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 156.146.38.170 |
| 69.96 | shadowsocks | 250.3 | 617.5 | 21.98 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 156.146.38.169 |
| 69.95 | trojan | 437.0 | 1129.1 | 17.66 | 0.0 | 10.0 | 12.33 | 14.12 | mheidari-all | 64.94.95.118 |
| 69.8 | trojan | 369.2 | 586.2 | 19.23 | 0.0 | 10.0 | 12.33 | 17.04 | Surfboard-tg-mixed | 151.101.56.6 |
| 69.41 | shadowsocks | 293.5 | 565.0 | 20.98 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 173.244.56.9 |
| 69.37 | shadowsocks | 306.1 | 623.7 | 20.69 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 149.22.95.183 |
| 68.69 | shadowsocks | 355.1 | 912.0 | 19.56 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 147.90.234.133 |
| 68.58 | shadowsocks | 336.8 | 734.2 | 19.98 | 0.0 | 10.0 | 13.04 | 13.94 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Surfboard-tg-mixed | 0.749 | 0.671 | 237 | 5184 | prefer |
| Au1rxx-base64 | 0.693 | 0.695 | 59 | 111 | observe |
| mheidari-all | 0.671 | 0.592 | 157 | 15925 | observe |
| DeltaKronecker-all | 0.594 | 0.514 | 109 | 12590 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| nscl5-all | 0.3 | 1.0 | 1 | 1136 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4787 | observe |
| Epodonios-all | 0.255 | None | 0 | 7823 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7164 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3909 | observe |
| barry-far-vless | 0.255 | None | 0 | 4701 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5133 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 95 |
| geo | TimeoutError | - | 26 |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyError | - | 12 |
| geo | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| speed | TimeoutError | - | 6 |
| speed | ProxyError | - | 5 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

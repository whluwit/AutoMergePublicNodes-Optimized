# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-29 10:53:05 |
| 运行耗时 | 288.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 75732 |
| 去重后节点 | 22987 |
| TCP 可达 | 3000 |
| 真实可用 | 497 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22987 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.3 |
| tcp | 30.6 |
| probe | 60.9 |
| real_test | 149.2 |
| generate | 41.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42304 |
| trojan | 12612 |
| vmess | 10928 |
| shadowsocks | 9321 |
| hysteria2 | 227 |
| shadowsocksr | 153 |
| http | 136 |
| socks | 44 |
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
| 77.56 | shadowsocks | 279.2 | 621.7 | 21.31 | 0.0 | 10.0 | 13.14 | 18.08 | mheidari-all | 198.98.53.130 |
| 76.94 | trojan | 269.1 | 670.4 | 21.55 | 0.0 | 10.0 | 11.5 | 18.08 | mheidari-all | 64.94.95.118 |
| 75.01 | vless | 327.8 | 792.5 | 20.19 | 0.0 | 10.0 | 7.82 | 18.08 | mheidari-all | 47.253.226.114 |
| 73.53 | shadowsocks | 247.3 | 626.4 | 22.05 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 156.146.38.169 |
| 73.41 | shadowsocks | 252.5 | 628.0 | 21.93 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 156.146.38.168 |
| 73.33 | shadowsocks | 256.1 | 632.4 | 21.85 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 156.146.38.170 |
| 73.19 | shadowsocks | 261.9 | 647.2 | 21.71 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 156.146.38.167 |
| 72.72 | shadowsocks | 310.4 | 666.5 | 20.59 | 0.0 | 10.0 | 13.14 | 18.08 | mheidari-all | 108.181.57.93 |
| 70.95 | vless | 317.9 | 584.6 | 20.42 | 0.0 | 10.0 | 7.82 | 18.08 | mheidari-all | 34.213.172.16 |
| 70.7 | shadowsocks | 298.1 | 698.3 | 20.88 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 37.19.198.244 |
| 70.13 | vless | 262.3 | 542.4 | 21.71 | 0.0 | 10.0 | 7.82 | 15.98 | Surfboard-tg-mixed | 64.23.143.23 |
| 69.94 | shadowsocks | 292.0 | 698.8 | 21.02 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 37.19.198.243 |
| 69.17 | vless | 293.8 | 576.0 | 20.98 | 0.0 | 10.0 | 7.82 | 18.08 | mheidari-all | 38.244.20.164 |
| 68.44 | shadowsocks | 278.3 | 542.6 | 21.33 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 173.244.56.9 |
| 68.23 | trojan | 354.2 | 644.5 | 19.58 | 0.0 | 10.0 | 11.5 | 15.98 | Surfboard-tg-mixed | 94.140.0.100 |
| 68.13 | shadowsocks | 310.3 | 717.9 | 20.6 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 37.19.198.236 |
| 67.92 | shadowsocks | 337.7 | 724.3 | 19.96 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 173.244.56.6 |
| 67.88 | shadowsocks | 292.4 | 659.3 | 21.01 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 37.19.198.160 |
| 67.28 | shadowsocks | 337.9 | 751.7 | 19.96 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 108.181.0.177 |
| 66.38 | shadowsocks | 310.1 | 622.4 | 20.6 | 0.0 | 10.0 | 13.14 | 12.34 | Au1rxx-base64 | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.862 | 0.784 | 273 | 15787 | prefer |
| Au1rxx-base64 | 0.799 | 0.811 | 37 | 95 | prefer |
| Surfboard-tg-mixed | 0.753 | 0.675 | 252 | 5150 | prefer |
| DeltaKronecker-all | 0.615 | 0.536 | 84 | 7004 | observe |
| nscl5-all | 0.358 | 1.0 | 2 | 1166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4653 | observe |
| Epodonios-all | 0.255 | None | 0 | 7391 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6789 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3760 | observe |
| barry-far-vless | 0.255 | None | 0 | 4344 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5278 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.226 | None | 0 | 1269 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 70 |
| cn-block | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 24 |
| 204 | ClientOSError | - | 18 |
| geo | TimeoutError | - | 12 |
| speed | TimeoutError | - | 11 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 6 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

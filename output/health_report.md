# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-23 14:44:33 |
| 运行耗时 | 319.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 77162 |
| 去重后节点 | 22028 |
| TCP 可达 | 3000 |
| 真实可用 | 517 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22028 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.5 |
| tcp | 29.4 |
| probe | 65.5 |
| real_test | 177.8 |
| generate | 40.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46489 |
| trojan | 10492 |
| shadowsocks | 9783 |
| vmess | 9774 |
| hysteria2 | 237 |
| shadowsocksr | 162 |
| http | 151 |
| socks | 65 |
| hysteria | 6 |
| tuic | 2 |
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
| 76.91 | shadowsocks | 234.9 | 592.3 | 22.34 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 156.146.38.170 |
| 76.83 | shadowsocks | 238.3 | 607.7 | 22.26 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 156.146.38.168 |
| 76.82 | shadowsocks | 238.8 | 612.1 | 22.25 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 156.146.38.169 |
| 75.87 | shadowsocks | 236.5 | 609.5 | 22.3 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 156.146.38.167 |
| 73.11 | vless | 230.4 | 517.8 | 22.44 | 0.0 | 10.0 | 8.05 | 13.28 | DeltaKronecker-all | 64.23.143.23 |
| 72.63 | shadowsocks | 268.9 | 538.1 | 21.55 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 173.244.56.9 |
| 71.56 | vless | 342.3 | 822.3 | 19.85 | 0.0 | 10.0 | 8.05 | 15.22 | Au1rxx-base64 | 15.204.97.214 |
| 71.27 | shadowsocks | 281.7 | 565.2 | 21.26 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 108.181.0.177 |
| 71.17 | shadowsocks | 268.2 | 529.3 | 21.57 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 108.181.118.10 |
| 71.04 | shadowsocks | 303.1 | 671.7 | 20.76 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 173.244.56.6 |
| 70.81 | shadowsocks | 260.8 | 536.0 | 21.74 | 0.0 | 10.0 | 13.35 | 13.28 | DeltaKronecker-all | 107.172.219.230 |
| 70.67 | vless | 354.8 | 858.5 | 19.56 | 0.0 | 10.0 | 8.05 | 15.22 | Au1rxx-base64 | 15.204.97.219 |
| 70.45 | shadowsocks | 327.3 | 712.0 | 20.2 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 37.19.198.236 |
| 70.4 | shadowsocks | 312.6 | 633.7 | 20.54 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 149.22.95.183 |
| 70.29 | shadowsocks | 328.0 | 711.5 | 20.18 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 37.19.198.160 |
| 70.15 | shadowsocks | 329.2 | 716.4 | 20.16 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 37.19.198.243 |
| 69.34 | shadowsocks | 328.5 | 675.9 | 20.17 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 198.98.53.130 |
| 68.74 | shadowsocks | 377.6 | 858.8 | 19.04 | 0.0 | 10.0 | 13.35 | 15.22 | Au1rxx-base64 | 37.19.198.244 |
| 68.07 | shadowsocks | 326.7 | 372.3 | 20.22 | 1.04 | 9.77 | 13.35 | 15.22 | Au1rxx-base64 | 149.22.87.240 |
| 67.32 | shadowsocks | 332.3 | 387.9 | 20.09 | 0.45 | 9.78 | 13.35 | 15.22 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | 1.0 | 50 | 73 | prefer |
| Au1rxx-base64 | 0.802 | 0.806 | 72 | 124 | prefer |
| mheidari-all | 0.747 | 0.679 | 28 | 15591 | prefer |
| Surfboard-tg-mixed | 0.7 | 0.621 | 219 | 5438 | observe |
| DeltaKronecker-all | 0.474 | 0.394 | 642 | 6437 | observe |
| Epodonios-all | 0.255 | None | 0 | 8099 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7501 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4204 | observe |
| barry-far-vless | 0.255 | None | 0 | 5009 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4477 | observe |
| nscl5-all | 0.237 | None | 0 | 1559 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| xiaoji235-airport-v2ray-all | 0.218 | None | 0 | 1064 | observe |
| Barabama-yudou | 0.214 | 0.5 | 2 | 166 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 255 |
| geo | ClientOSError | - | 102 |
| 204 | TimeoutError | - | 40 |
| cn-block | TimeoutError | - | 35 |
| 204 | ProxyError | - | 21 |
| speed | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 9 |
| geo | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-23 02:52:58 |
| 运行耗时 | 288.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 78573 |
| 去重后节点 | 22837 |
| TCP 可达 | 3000 |
| 真实可用 | 429 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22837 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.3 |
| tcp | 30.6 |
| probe | 68.6 |
| real_test | 161.0 |
| generate | 22.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47624 |
| trojan | 10666 |
| shadowsocks | 9871 |
| vmess | 9760 |
| hysteria2 | 257 |
| http | 170 |
| shadowsocksr | 153 |
| socks | 63 |
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
| 79.32 | vless | 313.1 | 817.4 | 20.53 | 0.0 | 10.0 | 12.07 | 16.72 | Au1rxx-base64 | 15.204.97.214 |
| 79.14 | vless | 320.9 | 840.9 | 20.35 | 0.0 | 10.0 | 12.07 | 16.72 | Au1rxx-base64 | 15.204.97.219 |
| 78.33 | shadowsocks | 183.6 | 482.1 | 23.53 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 216.105.168.18 |
| 77.35 | shadowsocks | 225.7 | 510.4 | 22.55 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 173.244.56.9 |
| 77.12 | vless | 187.4 | 480.3 | 23.44 | 0.0 | 9.89 | 12.07 | 16.72 | Au1rxx-base64 | fh1.freechatup2.com |
| 77.04 | shadowsocks | 217.6 | 538.4 | 22.74 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 108.181.118.10 |
| 77.02 | vless | 205.1 | 468.2 | 23.03 | 0.0 | 10.0 | 12.07 | 11.92 | DeltaKronecker-all | 172.252.125.77 |
| 75.79 | shadowsocks | 257.3 | 641.3 | 21.82 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 173.244.56.6 |
| 75.71 | vless | 228.6 | 469.1 | 22.49 | 0.0 | 10.0 | 12.07 | 16.72 | Au1rxx-base64 | 173.245.59.35 |
| 75.59 | shadowsocks | 280.2 | 727.0 | 21.29 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 108.181.0.177 |
| 75.13 | vless | 409.9 | 1048.1 | 18.29 | 0.0 | 10.0 | 12.07 | 17.28 | mheidari-all | 34.213.172.16 |
| 74.41 | vless | 188.2 | 493.0 | 23.42 | 0.0 | 10.0 | 12.07 | 11.92 | DeltaKronecker-all | 144.34.235.155 |
| 73.03 | trojan | 284.3 | 752.8 | 21.2 | 0.0 | 10.0 | 7.61 | 16.72 | Au1rxx-base64 | 45.61.52.243 |
| 72.33 | shadowsocks | 294.0 | 658.8 | 20.97 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 156.146.38.170 |
| 72.19 | trojan | 320.6 | 724.3 | 20.36 | 0.0 | 10.0 | 7.61 | 16.72 | Au1rxx-base64 | 207.126.167.241 |
| 72.04 | shadowsocks | 320.3 | 737.6 | 20.36 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 156.146.38.169 |
| 71.69 | shadowsocks | 322.1 | 733.2 | 20.32 | 0.0 | 10.0 | 12.08 | 16.72 | Au1rxx-base64 | 156.146.38.168 |
| 70.33 | shadowsocks | 296.7 | 346.6 | 20.91 | 2.0 | 9.85 | 12.08 | 16.72 | Au1rxx-base64 | 149.22.87.241 |
| 70.29 | shadowsocks | 298.8 | 346.0 | 20.86 | 2.03 | 9.85 | 12.08 | 16.72 | Au1rxx-base64 | 149.22.87.204 |
| 70.25 | vless | 423.3 | 355.1 | 17.98 | 1.68 | 9.49 | 12.07 | 17.28 | mheidari-all | 64.49.44.87 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.987 | 1.0 | 58 | 95 | prefer |
| Surfboard-tg-mixed | 0.805 | 0.875 | 16 | 5421 | prefer |
| Au1rxx-base64 | 0.746 | 0.745 | 94 | 149 | prefer |
| mheidari-all | 0.647 | 0.568 | 192 | 15546 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| DeltaKronecker-all | 0.305 | 0.224 | 784 | 7452 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4466 | observe |
| Epodonios-all | 0.255 | None | 0 | 8267 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7735 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4156 | observe |
| barry-far-vless | 0.255 | None | 0 | 5140 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4547 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.237 | None | 0 | 1559 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 311 |
| geo | TimeoutError | - | 241 |
| 204 | TimeoutError | - | 57 |
| speed | TimeoutError | - | 40 |
| geo | ClientOSError | - | 39 |
| cn-block | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 7 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

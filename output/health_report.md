# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-10 18:54:35 |
| 运行耗时 | 246.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84978 |
| 去重后节点 | 24647 |
| TCP 可达 | 3000 |
| 真实可用 | 452 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24647 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.3 |
| tcp | 36.5 |
| probe | 52.6 |
| real_test | 115.8 |
| generate | 35.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50333 |
| vmess | 13226 |
| trojan | 10306 |
| shadowsocks | 9535 |
| hysteria2 | 1329 |
| http | 72 |
| shadowsocksr | 67 |
| socks | 63 |
| anytls | 26 |
| hysteria | 13 |
| tuic | 8 |

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
| 84.4 | vless | 194.5 | 505.6 | 23.28 | 0.0 | 10.0 | 11.62 | 19.5 | Au1rxx-base64 | 167.17.68.205 |
| 83.99 | vless | 212.1 | 505.5 | 22.87 | 0.0 | 10.0 | 11.62 | 19.5 | Au1rxx-base64 | 64.23.143.23 |
| 83.89 | vless | 184.4 | 478.2 | 23.51 | 0.0 | 9.26 | 11.62 | 19.5 | Au1rxx-base64 | 179.255.148.66 |
| 83.77 | vless | 189.2 | 484.3 | 23.4 | 0.0 | 9.25 | 11.62 | 19.5 | Au1rxx-base64 | 179.253.240.24 |
| 81.67 | vless | 276.3 | 733.0 | 21.38 | 0.0 | 10.0 | 11.62 | 19.5 | Au1rxx-base64 | 172.247.109.66 |
| 81.43 | shadowsocks | 192.3 | 517.1 | 23.33 | 0.0 | 9.37 | 13.23 | 19.5 | Au1rxx-base64 | 173.244.56.9 |
| 80.45 | shadowsocks | 234.5 | 644.4 | 22.35 | 0.0 | 9.37 | 13.23 | 19.5 | Au1rxx-base64 | 173.244.56.6 |
| 79.65 | trojan | 261.8 | 526.2 | 21.72 | 0.0 | 10.0 | 14.07 | 19.5 | Au1rxx-base64 | 44.244.3.114 |
| 79.23 | vless | 218.5 | 486.9 | 22.72 | 0.0 | 10.0 | 11.62 | 19.5 | Au1rxx-base64 | 70.39.178.231 |
| 79.09 | vless | 229.4 | 518.1 | 22.47 | 0.0 | 10.0 | 11.62 | 19.5 | Au1rxx-base64 | 104.26.1.195 |
| 79.08 | trojan | 285.3 | 637.1 | 21.17 | 0.0 | 10.0 | 14.07 | 19.5 | Au1rxx-base64 | 64.94.95.114 |
| 79.06 | trojan | 272.7 | 547.4 | 21.47 | 0.0 | 10.0 | 14.07 | 19.5 | Au1rxx-base64 | 44.242.235.129 |
| 78.83 | trojan | 279.7 | 590.3 | 21.3 | 0.0 | 10.0 | 14.07 | 19.5 | Au1rxx-base64 | 44.246.163.102 |
| 78.53 | trojan | 313.9 | 722.3 | 20.51 | 0.0 | 10.0 | 14.07 | 19.5 | Au1rxx-base64 | 64.94.95.115 |
| 78.37 | vless | 206.6 | 498.4 | 23.0 | 0.0 | 9.25 | 11.62 | 19.5 | Au1rxx-base64 | 143.110.147.74 |
| 78.2 | shadowsocks | 310.3 | 805.6 | 20.6 | 0.0 | 9.37 | 13.23 | 19.5 | Au1rxx-base64 | 108.181.0.177 |
| 77.95 | vless | 272.2 | 483.6 | 21.48 | 0.0 | 10.0 | 11.62 | 19.5 | Au1rxx-base64 | 70.39.198.183 |
| 77.94 | vless | 298.1 | 633.1 | 20.88 | 0.0 | 10.0 | 11.62 | 19.5 | Au1rxx-base64 | 216.227.161.95 |
| 77.73 | vless | 237.1 | 242.5 | 22.29 | 5.91 | 9.84 | 11.62 | 19.5 | Au1rxx-base64 | 18.179.40.96 |
| 77.59 | trojan | 305.4 | 666.0 | 20.71 | 0.0 | 9.23 | 14.07 | 19.5 | Au1rxx-base64 | 35.86.90.51 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | 1.0 | 49 | 67 | prefer |
| Au1rxx-base64 | 0.939 | 0.876 | 396 | 1614 | prefer |
| DeltaKronecker-all | 0.515 | 0.434 | 106 | 5881 | observe |
| Surfboard-tg-mixed | 0.461 | 0.545 | 11 | 6152 | observe |
| mheidari-all | 0.324 | 0.375 | 8 | 20189 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 6803 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7537 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5085 | observe |
| barry-far-vless | 0.255 | None | 0 | 5417 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1614 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 18 |
| geo | ClientOSError | - | 12 |
| geo | TimeoutError | - | 5 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

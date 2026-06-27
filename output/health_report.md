# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-27 19:18:22 |
| 运行耗时 | 254.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 76872 |
| 去重后节点 | 23153 |
| TCP 可达 | 3000 |
| 真实可用 | 376 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23153 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.4 |
| tcp | 31.1 |
| probe | 61.4 |
| real_test | 108.0 |
| generate | 46.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42806 |
| trojan | 12833 |
| vmess | 11255 |
| shadowsocks | 9345 |
| hysteria2 | 275 |
| shadowsocksr | 168 |
| http | 135 |
| socks | 46 |
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
| 77.54 | shadowsocks | 192.4 | 513.8 | 23.32 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 108.181.118.10 |
| 77.33 | shadowsocks | 223.2 | 503.1 | 22.61 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 173.244.56.9 |
| 77.1 | shadowsocks | 229.7 | 545.3 | 22.46 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 149.22.95.183 |
| 76.45 | shadowsocks | 239.6 | 611.2 | 22.23 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 108.181.0.177 |
| 76.09 | vless | 309.5 | 814.1 | 20.61 | 0.0 | 10.0 | 9.72 | 15.76 | Au1rxx-base64 | 15.204.97.214 |
| 75.86 | vless | 319.8 | 846.1 | 20.38 | 0.0 | 10.0 | 9.72 | 15.76 | Au1rxx-base64 | 15.204.97.219 |
| 75.65 | vless | 330.6 | 819.6 | 20.12 | 0.0 | 10.0 | 9.72 | 16.66 | mheidari-all | 34.213.172.16 |
| 74.25 | vless | 212.0 | 545.6 | 22.87 | 0.0 | 10.0 | 9.72 | 16.66 | mheidari-all | 38.244.20.47 |
| 73.52 | vless | 204.5 | 522.4 | 23.04 | 0.0 | 10.0 | 9.72 | 15.76 | Au1rxx-base64 | 38.244.20.69 |
| 73.52 | vless | 226.8 | 551.0 | 22.53 | 0.0 | 10.0 | 9.72 | 16.66 | mheidari-all | 38.244.21.164 |
| 73.42 | shadowsocks | 258.9 | 646.6 | 21.79 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 173.244.56.6 |
| 73.15 | trojan | 269.3 | 648.2 | 21.54 | 0.0 | 10.0 | 8.35 | 15.76 | Au1rxx-base64 | 45.61.52.243 |
| 73.12 | trojan | 289.8 | 603.4 | 21.07 | 0.0 | 10.0 | 8.35 | 16.7 | Surfboard-tg-mixed | 94.140.0.100 |
| 72.82 | shadowsocks | 284.9 | 640.5 | 21.18 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 156.146.38.167 |
| 72.64 | trojan | 264.1 | 655.6 | 21.66 | 0.0 | 10.0 | 8.35 | 15.76 | Au1rxx-base64 | 207.126.167.150 |
| 72.38 | shadowsocks | 292.6 | 650.9 | 21.01 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 156.146.38.170 |
| 72.23 | shadowsocks | 298.4 | 666.9 | 20.87 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 156.146.38.168 |
| 68.3 | vless | 426.9 | 876.2 | 17.9 | 0.0 | 10.0 | 9.72 | 16.66 | mheidari-all | 47.253.226.114 |
| 68.05 | shadowsocks | 373.4 | 753.6 | 19.13 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 37.19.198.160 |
| 67.91 | shadowsocks | 377.4 | 757.2 | 19.04 | 0.0 | 10.0 | 12.96 | 15.76 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.8 | 0.722 | 198 | 5150 | prefer |
| Au1rxx-base64 | 0.733 | 0.739 | 46 | 95 | prefer |
| mheidari-all | 0.701 | 0.623 | 167 | 16142 | prefer |
| DeltaKronecker-all | 0.623 | 0.544 | 103 | 6822 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| nscl5-all | 0.302 | 1.0 | 1 | 1186 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4579 | observe |
| Epodonios-all | 0.255 | None | 0 | 7776 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3981 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7287 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3804 | observe |
| barry-far-vless | 0.255 | None | 0 | 4576 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5287 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 92 |
| 204 | TimeoutError | - | 21 |
| 204 | ClientOSError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| geo | TimeoutError | - | 10 |
| 204 | ProxyError | - | 8 |
| geo | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

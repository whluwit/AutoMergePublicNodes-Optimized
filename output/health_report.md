# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-28 08:31:49 |
| 运行耗时 | 358.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86104 |
| 去重后节点 | 23298 |
| TCP 可达 | 3000 |
| 真实可用 | 803 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23298 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 32.1 |
| probe | 68.9 |
| real_test | 214.8 |
| generate | 35.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48733 |
| trojan | 16077 |
| vmess | 10306 |
| shadowsocks | 10158 |
| hysteria2 | 560 |
| shadowsocksr | 95 |
| http | 73 |
| socks | 72 |
| hysteria | 15 |
| anytls | 10 |
| tuic | 5 |

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
| 83.56 | shadowsocks | 202.0 | 542.2 | 23.1 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 79.89 | shadowsocks | 260.1 | 267.5 | 21.76 | 4.97 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 79.74 | shadowsocks | 251.3 | 517.8 | 21.96 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 79.62 | shadowsocks | 247.8 | 512.2 | 22.04 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 79.48 | shadowsocks | 251.4 | 547.7 | 21.96 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 78.87 | shadowsocks | 252.8 | 560.3 | 21.93 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 77.37 | shadowsocks | 300.7 | 312.5 | 20.82 | 3.28 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 149.22.87.241 |
| 76.75 | shadowsocks | 322.5 | 679.7 | 20.31 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 76.29 | shadowsocks | 316.4 | 683.7 | 20.45 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 76.28 | trojan | 332.0 | 674.2 | 20.09 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 76.14 | shadowsocks | 315.9 | 661.3 | 20.46 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 75.03 | shadowsocks | 316.5 | 686.3 | 20.45 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 74.82 | shadowsocks | 372.7 | 874.2 | 19.15 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 172.245.235.84 |
| 74.33 | shadowsocks | 366.8 | 745.1 | 19.29 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 74.31 | shadowsocks | 361.6 | 740.3 | 19.41 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 73.56 | shadowsocks | 331.5 | 411.5 | 20.1 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 149.22.87.204 |
| 73.55 | shadowsocks | 400.0 | 859.6 | 18.52 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 73.49 | shadowsocks | 380.5 | 791.3 | 18.97 | 0.0 | 10.0 | 14.46 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 73.17 | vless | 220.3 | 535.8 | 22.68 | 0.0 | 10.0 | 5.49 | 20.0 | Au1rxx-base64 | 52.43.158.158 |
| 73.12 | trojan | 411.8 | 816.9 | 18.24 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 153.75.250.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 69 | 81 | prefer |
| Au1rxx-base64 | 0.977 | 0.925 | 426 | 1345 | prefer |
| mheidari-all | 0.874 | 0.8 | 100 | 18776 | prefer |
| Surfboard-tg-mixed | 0.53 | 0.7 | 10 | 5743 | observe |
| DeltaKronecker-all | 0.519 | 0.439 | 572 | 5965 | observe |
| ninja-vless | 0.279 | 0.5 | 2 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4972 | observe |
| Epodonios-all | 0.255 | None | 0 | 6749 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6579 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4586 | observe |
| barry-far-vless | 0.255 | None | 0 | 5112 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4991 | observe |
| Au1rxx-clash | 0.229 | None | 0 | 1345 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 168 |
| geo | ClientOSError | - | 58 |
| speed | ClientOSError | - | 50 |
| speed | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 17 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

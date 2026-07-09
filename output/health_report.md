# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-09 02:35:12 |
| 运行耗时 | 224.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79955 |
| 去重后节点 | 24829 |
| TCP 可达 | 3000 |
| 真实可用 | 457 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24829 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 33.1 |
| probe | 48.1 |
| real_test | 100.7 |
| generate | 36.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45897 |
| trojan | 12865 |
| vmess | 10528 |
| shadowsocks | 9443 |
| hysteria2 | 844 |
| http | 140 |
| shadowsocksr | 138 |
| socks | 85 |
| hysteria | 8 |
| anytls | 5 |
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
| 75.75 | shadowsocks | 221.4 | 547.7 | 22.65 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 108.181.118.10 |
| 75.74 | shadowsocks | 243.7 | 588.5 | 22.14 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 149.22.95.183 |
| 75.43 | shadowsocks | 225.4 | 492.8 | 22.56 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 173.244.56.6 |
| 73.1 | shadowsocks | 228.2 | 498.6 | 22.5 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 173.244.56.9 |
| 72.4 | shadowsocks | 274.9 | 277.9 | 21.41 | 4.58 | 9.94 | 12.2 | 15.4 | Au1rxx-base64 | 149.22.87.240 |
| 71.97 | shadowsocks | 277.8 | 287.3 | 21.35 | 4.23 | 9.95 | 12.2 | 15.4 | Au1rxx-base64 | 149.22.87.204 |
| 71.49 | shadowsocks | 296.9 | 672.6 | 20.9 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 156.146.38.168 |
| 71.31 | shadowsocks | 290.1 | 647.9 | 21.06 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 156.146.38.170 |
| 71.23 | shadowsocks | 294.2 | 655.8 | 20.97 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 156.146.38.167 |
| 71.1 | shadowsocks | 294.4 | 663.2 | 20.96 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 156.146.38.169 |
| 70.2 | shadowsocks | 461.2 | 1272.0 | 17.1 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 108.181.0.177 |
| 69.03 | shadowsocks | 297.9 | 344.0 | 20.88 | 2.1 | 9.95 | 12.2 | 15.4 | Au1rxx-base64 | 149.22.87.241 |
| 67.66 | shadowsocks | 351.6 | 693.9 | 19.64 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 198.98.53.130 |
| 67.05 | shadowsocks | 364.9 | 727.8 | 19.33 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 37.19.198.243 |
| 66.96 | shadowsocks | 376.4 | 752.6 | 19.06 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 37.19.198.160 |
| 66.77 | shadowsocks | 382.8 | 784.6 | 18.92 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 37.19.198.236 |
| 66.35 | shadowsocks | 383.2 | 770.9 | 18.91 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 37.19.198.244 |
| 66.06 | hysteria2 | 454.7 | 760.6 | 17.25 | 0.0 | 9.49 | 12.5 | 15.4 | Au1rxx-base64 | 62.210.124.146 |
| 65.82 | shadowsocks | 399.1 | 739.6 | 18.54 | 0.0 | 10.0 | 12.2 | 15.4 | Au1rxx-base64 | 108.181.57.93 |
| 65.2 | vmess | 197.9 | 504.4 | 23.2 | 0.0 | 10.0 | 12.86 | 3.64 | Barabama-yudou | 82.198.246.233 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.805 | 0.808 | 78 | 129 | prefer |
| DeltaKronecker-all | 0.76 | 0.682 | 170 | 8321 | prefer |
| Surfboard-tg-mixed | 0.687 | 0.608 | 324 | 5759 | observe |
| mheidari-all | 0.661 | 0.583 | 60 | 17104 | observe |
| xiaoji235-airport-v2ray-all | 0.606 | 0.889 | 9 | 2703 | observe |
| nscl5-all | 0.26 | 0.5 | 2 | 1319 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4408 | observe |
| Epodonios-all | 0.255 | None | 0 | 6606 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3969 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6629 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4275 | observe |
| barry-far-vless | 0.255 | None | 0 | 4589 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5361 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 93 |
| geo | TimeoutError | - | 78 |
| geo | ClientOSError | - | 17 |
| speed | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 177 | 300 | - |
| global | False | 184 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

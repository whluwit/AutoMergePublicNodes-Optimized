# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-09 09:33:52 |
| 运行耗时 | 196.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79180 |
| 去重后节点 | 23776 |
| TCP 可达 | 3000 |
| 真实可用 | 308 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23776 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.3 |
| tcp | 31.7 |
| probe | 46.4 |
| real_test | 72.8 |
| generate | 39.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45320 |
| trojan | 12745 |
| vmess | 10315 |
| shadowsocks | 9598 |
| hysteria2 | 830 |
| shadowsocksr | 139 |
| http | 136 |
| socks | 83 |
| hysteria | 8 |
| anytls | 4 |
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
| 78.36 | shadowsocks | 244.5 | 652.7 | 22.12 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 37.19.198.160 |
| 78.32 | shadowsocks | 246.2 | 664.7 | 22.08 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 37.19.198.243 |
| 78.29 | shadowsocks | 247.6 | 668.2 | 22.05 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 37.19.198.236 |
| 77.78 | shadowsocks | 248.0 | 644.6 | 22.04 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 108.181.57.93 |
| 76.11 | trojan | 317.5 | 751.2 | 20.43 | 0.0 | 10.0 | 13.75 | 16.1 | Au1rxx-base64 | 149.28.241.235 |
| 75.91 | shadowsocks | 225.8 | 589.4 | 22.55 | 0.0 | 10.0 | 14.14 | 13.22 | mheidari-all | 198.98.53.130 |
| 75.52 | shadowsocks | 280.0 | 647.7 | 21.3 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 156.146.38.169 |
| 75.52 | trojan | 313.8 | 747.2 | 20.51 | 0.0 | 10.0 | 13.75 | 15.2 | DeltaKronecker-all | 45.32.198.247 |
| 75.18 | shadowsocks | 279.1 | 638.5 | 21.32 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 156.146.38.167 |
| 74.72 | shadowsocks | 279.6 | 646.0 | 21.31 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 156.146.38.168 |
| 74.31 | shadowsocks | 278.7 | 747.0 | 21.33 | 0.0 | 10.0 | 14.14 | 13.22 | mheidari-all | 147.90.234.133 |
| 72.49 | trojan | 321.6 | 771.2 | 20.33 | 0.0 | 10.0 | 13.75 | 13.22 | mheidari-all | 45.32.195.168 |
| 72.4 | shadowsocks | 235.7 | 630.1 | 22.32 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 37.19.198.244 |
| 71.33 | shadowsocks | 343.8 | 845.8 | 19.82 | 0.0 | 10.0 | 14.14 | 13.22 | mheidari-all | 185.196.61.82 |
| 71.11 | shadowsocks | 322.6 | 584.0 | 20.31 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 173.244.56.6 |
| 70.71 | shadowsocks | 322.6 | 566.9 | 20.31 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 108.181.118.10 |
| 70.55 | vmess | 391.6 | 1070.7 | 18.71 | 0.0 | 10.0 | 13.12 | 13.22 | mheidari-all | 67.220.85.46 |
| 70.07 | trojan | 366.8 | 854.4 | 19.29 | 0.0 | 10.0 | 13.75 | 13.22 | mheidari-all | 64.94.95.118 |
| 69.57 | shadowsocks | 305.0 | 827.7 | 20.72 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 69.13 | shadowsocks | 322.3 | 544.6 | 20.32 | 0.0 | 10.0 | 14.14 | 16.1 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.809 | 0.735 | 83 | 17088 | prefer |
| Surfboard-tg-mixed | 0.74 | 0.663 | 98 | 5778 | prefer |
| Au1rxx-base64 | 0.723 | 0.724 | 76 | 128 | prefer |
| DeltaKronecker-all | 0.598 | 0.518 | 168 | 7533 | observe |
| xiaoji235-airport-v2ray-all | 0.48 | 1.0 | 4 | 2703 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4306 | observe |
| Epodonios-all | 0.255 | None | 0 | 6686 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6293 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4286 | observe |
| barry-far-vless | 0.255 | None | 0 | 4851 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5440 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.228 | None | 0 | 1319 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 41 |
| 204 | ProxyError | - | 29 |
| geo | TimeoutError | - | 24 |
| 204 | ClientOSError | - | 16 |
| cn-block | ProxyError | - | 10 |
| geo | ProxyError | - | 9 |
| geo | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 6 |
| speed | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 3 |
| speed | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

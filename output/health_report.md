# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 10:08:56 |
| 运行耗时 | 671.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83041 |
| 去重后节点 | 22802 |
| TCP 可达 | 3000 |
| 真实可用 | 454 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22802 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 38.7 |
| probe | 292.3 |
| real_test | 252.3 |
| generate | 80.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50381 |
| vmess | 12614 |
| shadowsocks | 9770 |
| trojan | 7811 |
| hysteria2 | 1628 |
| http | 634 |
| shadowsocksr | 128 |
| socks | 51 |
| hysteria | 11 |
| tuic | 11 |
| anytls | 2 |

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
| 81.11 | shadowsocks | 241.3 | 617.8 | 22.19 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 156.146.38.169 |
| 80.83 | shadowsocks | 253.4 | 596.1 | 21.91 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 156.146.38.170 |
| 80.73 | shadowsocks | 257.9 | 616.4 | 21.81 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 156.146.38.168 |
| 76.96 | shadowsocks | 312.8 | 681.6 | 20.54 | 0.0 | 10.0 | 14.26 | 16.66 | Surfboard-tg-mixed | 23.150.248.20 |
| 76.0 | shadowsocks | 302.4 | 667.9 | 20.78 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 198.98.53.130 |
| 75.78 | shadowsocks | 342.5 | 758.8 | 19.85 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 173.244.56.6 |
| 75.1 | shadowsocks | 315.6 | 651.5 | 20.47 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 149.22.95.183 |
| 74.39 | vless | 313.9 | 737.2 | 20.51 | 0.0 | 10.0 | 6.65 | 18.66 | Au1rxx-base64 | 79.141.172.154 |
| 73.44 | vless | 286.5 | 587.4 | 21.14 | 0.0 | 10.0 | 6.65 | 18.66 | Au1rxx-base64 | 172.235.38.85 |
| 73.29 | vless | 353.7 | 858.6 | 19.59 | 0.0 | 10.0 | 6.65 | 18.66 | Au1rxx-base64 | 15.204.97.216 |
| 73.19 | vless | 279.2 | 573.0 | 21.31 | 0.0 | 10.0 | 6.65 | 18.66 | Au1rxx-base64 | 172.233.139.46 |
| 72.86 | shadowsocks | 378.9 | 797.3 | 19.01 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 51.222.155.113 |
| 72.68 | http | 249.8 | 561.9 | 22.0 | 0.0 | 10.0 | 10.45 | 14.64 | ermaozi | 138.199.35.218 |
| 72.45 | http | 252.5 | 564.4 | 21.93 | 0.0 | 10.0 | 10.45 | 14.64 | ermaozi | 138.199.35.208 |
| 72.34 | http | 255.3 | 567.7 | 21.87 | 0.0 | 10.0 | 10.45 | 14.64 | ermaozi | 138.199.35.214 |
| 72.29 | http | 249.0 | 547.6 | 22.01 | 0.0 | 10.0 | 10.45 | 14.64 | ermaozi | 138.199.35.204 |
| 72.25 | shadowsocks | 333.3 | 373.7 | 20.06 | 0.99 | 9.76 | 14.26 | 18.66 | Au1rxx-base64 | 149.22.87.204 |
| 72.12 | vless | 352.3 | 786.9 | 19.62 | 0.0 | 10.0 | 6.65 | 18.66 | Au1rxx-base64 | 172.235.43.210 |
| 71.82 | shadowsocks | 464.6 | 1143.2 | 17.02 | 0.0 | 10.0 | 14.26 | 18.66 | Au1rxx-base64 | 15.204.247.206 |
| 71.33 | shadowsocks | 371.4 | 859.8 | 19.18 | 0.0 | 7.19 | 14.26 | 18.66 | Au1rxx-base64 | ca225.vpnbook.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.92 | 0.857 | 287 | 1636 | prefer |
| mheidari-all | 0.747 | 0.671 | 82 | 15628 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.656 | 128 | 7232 | prefer |
| ermaozi | 0.591 | 0.577 | 52 | 434 | observe |
| DeltaKronecker-all | 0.547 | 0.466 | 73 | 5970 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Surfboard-tg-vless | 0.287 | 0.5 | 2 | 5899 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7695 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8653 | observe |
| barry-far-vless | 0.255 | None | 0 | 6084 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4207 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1636 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 53 |
| 204 | ProxyError | - | 28 |
| cn-block | TimeoutError | - | 21 |
| speed | ClientOSError | - | 16 |
| geo | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyConnectionError | - | 12 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 6 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

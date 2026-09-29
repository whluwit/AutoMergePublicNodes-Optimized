# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 12:10:11 |
| 运行耗时 | 597.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97025 |
| 去重后节点 | 26954 |
| TCP 可达 | 3000 |
| 真实可用 | 473 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26954 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 44.5 |
| probe | 268.4 |
| real_test | 189.0 |
| generate | 87.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59106 |
| vmess | 14826 |
| shadowsocks | 11439 |
| trojan | 9293 |
| hysteria2 | 1422 |
| http | 644 |
| shadowsocksr | 165 |
| socks | 83 |
| anytls | 24 |
| hysteria | 15 |
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
| 77.58 | hysteria2 | 286.6 | 587.2 | 21.14 | 0.0 | 10.0 | 14.09 | 17.38 | Au1rxx-base64 | 192.255.128.123 |
| 77.57 | shadowsocks | 265.4 | 722.4 | 21.63 | 0.0 | 9.02 | 13.54 | 17.38 | Au1rxx-base64 | 37.19.198.244 |
| 75.91 | shadowsocks | 312.8 | 840.5 | 20.54 | 0.0 | 8.95 | 13.54 | 17.38 | Au1rxx-base64 | 38.180.135.156 |
| 75.37 | shadowsocks | 251.9 | 704.5 | 21.95 | 0.0 | 10.0 | 13.54 | 17.38 | Au1rxx-base64 | 47.90.153.88 |
| 74.83 | vless | 249.4 | 687.3 | 22.0 | 0.0 | 9.01 | 6.44 | 17.38 | Au1rxx-base64 | 47.90.153.88 |
| 74.73 | vless | 252.3 | 707.2 | 21.94 | 0.0 | 8.97 | 6.44 | 17.38 | Au1rxx-base64 | 79.141.172.154 |
| 74.45 | shadowsocks | 376.4 | 974.7 | 19.06 | 0.0 | 8.97 | 13.54 | 17.38 | Au1rxx-base64 | 185.156.47.97 |
| 74.29 | hysteria2 | 371.0 | 694.4 | 19.19 | 0.0 | 10.0 | 14.09 | 17.38 | Au1rxx-base64 | 66.94.121.46 |
| 73.93 | vless | 290.0 | 675.3 | 21.06 | 0.0 | 9.05 | 6.44 | 17.38 | Au1rxx-base64 | 169.40.42.224 |
| 73.9 | shadowsocks | 400.7 | 975.1 | 18.5 | 0.0 | 8.98 | 13.54 | 17.38 | Au1rxx-base64 | 15.204.246.132 |
| 73.7 | shadowsocks | 271.2 | 717.5 | 21.5 | 0.0 | 10.0 | 13.54 | 12.66 | Surfboard-tg-mixed | 37.19.198.160 |
| 73.35 | vless | 313.6 | 695.4 | 20.52 | 0.0 | 9.01 | 6.44 | 17.38 | Au1rxx-base64 | 169.40.42.225 |
| 73.24 | hysteria2 | 398.7 | 665.2 | 18.55 | 0.0 | 10.0 | 14.09 | 17.38 | Au1rxx-base64 | 62.210.124.146 |
| 73.14 | vless | 305.2 | 663.8 | 20.71 | 0.0 | 9.04 | 6.44 | 17.38 | Au1rxx-base64 | 169.40.42.95 |
| 72.8 | vless | 379.9 | 1027.5 | 18.98 | 0.0 | 10.0 | 6.44 | 17.38 | Au1rxx-base64 | 185.95.231.156 |
| 72.71 | vless | 340.7 | 725.8 | 19.89 | 0.0 | 9.0 | 6.44 | 17.38 | Au1rxx-base64 | 169.40.42.35 |
| 72.54 | vless | 391.4 | 982.6 | 18.72 | 0.0 | 10.0 | 6.44 | 17.38 | Au1rxx-base64 | 169.40.42.179 |
| 72.51 | vless | 308.1 | 756.8 | 20.65 | 0.0 | 9.0 | 6.44 | 17.38 | Au1rxx-base64 | 195.211.98.43 |
| 72.51 | vless | 341.1 | 906.4 | 19.88 | 0.0 | 9.01 | 6.44 | 17.38 | Au1rxx-base64 | 169.40.42.104 |
| 72.47 | vless | 368.6 | 922.8 | 19.25 | 0.0 | 10.0 | 6.44 | 17.38 | Au1rxx-base64 | 169.40.42.163 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.903 | 0.841 | 340 | 1599 | prefer |
| mheidari-all | 0.839 | 0.768 | 56 | 22883 | prefer |
| Surfboard-tg-mixed | 0.729 | 0.651 | 152 | 7053 | prefer |
| ermaozi | 0.681 | 0.673 | 55 | 354 | observe |
| DeltaKronecker-all | 0.543 | 0.615 | 13 | 5528 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5314 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9541 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5690 | observe |
| barry-far-vless | 0.255 | None | 0 | 5869 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1599 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 31 |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 27 |
| geo | TimeoutError | - | 15 |
| 204 | ProxyError | - | 13 |
| 204 | ProxyConnectionError | - | 12 |
| speed | TimeoutError | - | 6 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

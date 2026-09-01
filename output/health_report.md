# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-01 20:31:24 |
| 运行耗时 | 296.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 81525 |
| 去重后节点 | 23511 |
| TCP 可达 | 3000 |
| 真实可用 | 641 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23511 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 39.0 |
| probe | 78.3 |
| real_test | 134.0 |
| generate | 37.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50796 |
| vmess | 11230 |
| shadowsocks | 9979 |
| trojan | 7621 |
| hysteria2 | 1530 |
| http | 145 |
| shadowsocksr | 130 |
| socks | 76 |
| tuic | 11 |
| hysteria | 7 |

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
| 83.71 | hysteria2 | 239.9 | 542.0 | 22.23 | 0.0 | 10.0 | 13.64 | 19.64 | Au1rxx-base64 | 66.94.121.46 |
| 81.29 | trojan | 262.4 | 599.8 | 21.7 | 0.0 | 10.0 | 12.95 | 19.64 | Au1rxx-base64 | 64.94.95.118 |
| 80.47 | vless | 276.1 | 590.0 | 21.39 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 38.127.121.44 |
| 80.39 | vless | 269.3 | 572.0 | 21.54 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 172.239.67.156 |
| 80.24 | vless | 268.1 | 566.6 | 21.57 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 172.233.156.123 |
| 79.83 | vless | 281.3 | 596.2 | 21.27 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 172.235.38.85 |
| 79.67 | trojan | 252.7 | 589.9 | 21.93 | 0.0 | 10.0 | 12.95 | 19.64 | Au1rxx-base64 | 64.94.95.114 |
| 79.61 | vless | 279.1 | 586.5 | 21.32 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 172.239.67.231 |
| 79.57 | vless | 282.0 | 603.3 | 21.25 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 172.233.156.118 |
| 79.53 | vless | 302.7 | 666.9 | 20.77 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 195.211.99.49 |
| 79.45 | vless | 278.7 | 555.9 | 21.33 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 172.233.139.46 |
| 79.38 | vless | 299.1 | 651.4 | 20.85 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 195.211.99.45 |
| 79.33 | vless | 309.1 | 674.5 | 20.62 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 195.211.98.214 |
| 79.25 | shadowsocks | 240.3 | 603.5 | 22.22 | 0.0 | 10.0 | 13.97 | 17.06 | mheidari-all | 156.146.38.169 |
| 79.21 | vless | 294.0 | 638.8 | 20.97 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 172.236.252.35 |
| 78.7 | vless | 288.2 | 583.2 | 21.11 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 45.79.103.108 |
| 78.64 | vless | 289.0 | 581.7 | 21.09 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 192.155.87.188 |
| 78.46 | vless | 305.0 | 633.1 | 20.72 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 74.207.245.124 |
| 78.44 | vless | 288.1 | 580.6 | 21.11 | 0.0 | 10.0 | 12.11 | 19.64 | Au1rxx-base64 | 45.33.62.226 |
| 78.06 | shadowsocks | 244.1 | 626.2 | 22.13 | 0.0 | 10.0 | 13.97 | 15.96 | Surfboard-tg-mixed | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 1.0 | 0.969 | 32 | 7294 | prefer |
| Au1rxx-base64 | 0.978 | 0.912 | 408 | 1703 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| mheidari-all | 0.908 | 0.833 | 126 | 15436 | prefer |
| Surfboard-tg-mixed | 0.81 | 0.733 | 150 | 6974 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4708 | observe |
| Epodonios-all | 0.255 | None | 0 | 7385 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7585 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5805 | observe |
| barry-far-vless | 0.255 | None | 0 | 5987 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4159 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1703 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 23 |
| 204 | ProxyError | - | 11 |
| cn-block | ClientOSError | - | 8 |
| speed | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 8 |
| geo | ClientOSError | - | 6 |
| speed | TimeoutError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

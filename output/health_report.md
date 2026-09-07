# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 11:29:27 |
| 运行耗时 | 294.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94672 |
| 去重后节点 | 24923 |
| TCP 可达 | 3000 |
| 真实可用 | 475 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24923 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 41.1 |
| probe | 95.5 |
| real_test | 106.6 |
| generate | 42.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59136 |
| vmess | 12762 |
| shadowsocks | 11082 |
| trojan | 9215 |
| hysteria2 | 2093 |
| http | 138 |
| shadowsocksr | 130 |
| socks | 61 |
| anytls | 22 |
| hysteria | 19 |
| tuic | 14 |

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
| 82.67 | hysteria2 | 257.0 | 549.3 | 21.83 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 80.79 | shadowsocks | 273.7 | 655.8 | 21.44 | 0.0 | 10.0 | 14.37 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 79.5 | shadowsocks | 290.4 | 684.4 | 21.06 | 0.0 | 10.0 | 14.37 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 78.93 | trojan | 297.9 | 559.7 | 20.88 | 0.0 | 10.0 | 12.12 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 78.13 | trojan | 378.6 | 809.4 | 19.01 | 0.0 | 10.0 | 12.12 | 20.0 | Au1rxx-base64 | 64.94.95.114 |
| 77.63 | shadowsocks | 284.4 | 576.6 | 21.19 | 0.0 | 10.0 | 14.37 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.6 | shadowsocks | 302.4 | 589.3 | 20.78 | 0.0 | 10.0 | 14.37 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 76.06 | trojan | 248.6 | 623.0 | 22.02 | 0.0 | 10.0 | 12.12 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 75.8 | vless | 320.5 | 688.0 | 20.36 | 0.0 | 10.0 | 7.33 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 75.28 | vless | 309.0 | 698.1 | 20.63 | 0.0 | 10.0 | 7.33 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 74.9 | trojan | 298.2 | 726.6 | 20.87 | 0.0 | 10.0 | 12.12 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 74.66 | vless | 290.3 | 551.1 | 21.06 | 0.0 | 10.0 | 7.33 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 74.48 | vless | 327.9 | 741.0 | 20.19 | 0.0 | 10.0 | 7.33 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 74.41 | vless | 283.6 | 565.5 | 21.21 | 0.0 | 10.0 | 7.33 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 74.41 | shadowsocks | 431.9 | 1024.2 | 17.78 | 0.0 | 10.0 | 14.37 | 20.0 | Au1rxx-base64 | 51.222.200.165 |
| 74.34 | shadowsocks | 408.2 | 960.7 | 18.33 | 0.0 | 10.0 | 14.37 | 20.0 | Au1rxx-base64 | 15.204.246.189 |
| 74.23 | shadowsocks | 398.9 | 965.3 | 18.54 | 0.0 | 10.0 | 14.37 | 20.0 | Au1rxx-base64 | 51.79.64.198 |
| 74.19 | vless | 339.9 | 785.6 | 19.91 | 0.0 | 10.0 | 7.33 | 20.0 | Au1rxx-base64 | 169.40.42.168 |
| 73.91 | vless | 346.5 | 739.4 | 19.76 | 0.0 | 10.0 | 7.33 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 73.85 | shadowsocks | 298.6 | 656.8 | 20.87 | 0.0 | 10.0 | 14.37 | 16.92 | Surfboard-tg-mixed | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | 0.926 | 311 | 1781 | prefer |
| Surfboard-tg-mixed | 0.766 | 0.689 | 151 | 7247 | prefer |
| mheidari-all | 0.646 | 0.568 | 111 | 21631 | observe |
| zhangkai | 0.646 | 0.652 | 23 | 144 | observe |
| DeltaKronecker-all | 0.4 | 0.75 | 4 | 6417 | observe |
| tg-oneclickvpnkeys | 0.275 | 0.667 | 3 | 151 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| Epodonios-all | 0.255 | None | 0 | 7707 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8442 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1781 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 33 |
| 204 | TimeoutError | - | 30 |
| 204 | ProxyConnectionError | - | 14 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

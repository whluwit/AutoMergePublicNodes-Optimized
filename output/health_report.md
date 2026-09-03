# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-03 10:39:37 |
| 运行耗时 | 299.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82545 |
| 去重后节点 | 22920 |
| TCP 可达 | 3000 |
| 真实可用 | 550 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22920 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.6 |
| tcp | 36.6 |
| probe | 83.8 |
| real_test | 126.7 |
| generate | 44.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51677 |
| vmess | 11435 |
| shadowsocks | 9819 |
| trojan | 7659 |
| hysteria2 | 1587 |
| http | 138 |
| shadowsocksr | 125 |
| socks | 84 |
| tuic | 11 |
| hysteria | 10 |

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
| 83.06 | http | 236.7 | 631.8 | 22.3 | 0.0 | 10.0 | 14.44 | 19.32 | zhangkai | 138.199.35.216 |
| 82.81 | shadowsocks | 196.3 | 483.1 | 23.23 | 0.0 | 10.0 | 14.34 | 19.74 | Au1rxx-base64 | 108.181.0.177 |
| 82.81 | http | 247.4 | 659.5 | 22.05 | 0.0 | 10.0 | 14.44 | 19.32 | zhangkai | 138.199.35.198 |
| 82.33 | hysteria2 | 364.7 | 993.4 | 19.34 | 0.0 | 10.0 | 14.25 | 19.74 | Au1rxx-base64 | 66.94.121.46 |
| 82.31 | shadowsocks | 218.2 | 538.1 | 22.73 | 0.0 | 10.0 | 14.34 | 19.74 | Au1rxx-base64 | 108.181.118.10 |
| 82.21 | vless | 193.3 | 500.1 | 23.3 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.235.38.85 |
| 82.1 | vless | 198.2 | 516.4 | 23.19 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.239.67.156 |
| 82.09 | shadowsocks | 249.0 | 601.1 | 22.01 | 0.0 | 10.0 | 14.34 | 19.74 | Au1rxx-base64 | 149.22.95.183 |
| 82.03 | vless | 201.4 | 513.9 | 23.12 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.233.156.123 |
| 81.98 | vless | 199.3 | 516.6 | 23.16 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.239.67.231 |
| 81.95 | vless | 204.7 | 529.7 | 23.04 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.233.139.46 |
| 81.79 | vless | 211.6 | 554.5 | 22.88 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.233.156.118 |
| 81.75 | shadowsocks | 264.0 | 608.6 | 21.67 | 0.0 | 10.0 | 14.34 | 19.74 | Au1rxx-base64 | 173.244.56.9 |
| 81.74 | vless | 213.7 | 551.9 | 22.83 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.235.43.210 |
| 81.45 | vless | 226.2 | 601.0 | 22.54 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 172.236.252.35 |
| 80.42 | shadowsocks | 321.3 | 734.8 | 20.34 | 0.0 | 10.0 | 14.34 | 19.74 | Au1rxx-base64 | 173.244.56.6 |
| 80.08 | vless | 199.0 | 520.7 | 23.17 | 0.0 | 10.0 | 9.17 | 19.74 | Au1rxx-base64 | 31.58.50.200 |
| 78.76 | vless | 213.0 | 524.9 | 22.85 | 0.0 | 10.0 | 9.17 | 16.74 | Surfboard-tg-mixed | 38.127.121.44 |
| 77.39 | vless | 203.7 | 525.0 | 23.06 | 0.0 | 10.0 | 9.17 | 16.74 | Surfboard-tg-mixed | 172.233.156.42 |
| 77.05 | shadowsocks | 303.0 | 658.4 | 20.76 | 0.0 | 10.0 | 14.34 | 19.74 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | 0.909 | 328 | 1751 | prefer |
| mheidari-all | 0.965 | 0.917 | 24 | 16145 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| DeltaKronecker-all | 0.823 | 0.747 | 99 | 6335 | prefer |
| Surfboard-tg-mixed | 0.787 | 0.709 | 189 | 7139 | prefer |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 87 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4671 | observe |
| Epodonios-all | 0.255 | None | 0 | 7527 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8132 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6006 | observe |
| barry-far-vless | 0.255 | None | 0 | 6217 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 28 |
| geo | ClientOSError | - | 17 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

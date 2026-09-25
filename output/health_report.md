# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 03:18:55 |
| 运行耗时 | 726.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98026 |
| 去重后节点 | 26569 |
| TCP 可达 | 3000 |
| 真实可用 | 476 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26569 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.5 |
| tcp | 43.6 |
| probe | 290.5 |
| real_test | 354.6 |
| generate | 30.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59477 |
| vmess | 15072 |
| shadowsocks | 11843 |
| trojan | 9043 |
| hysteria2 | 1648 |
| http | 648 |
| shadowsocksr | 174 |
| socks | 74 |
| anytls | 24 |
| hysteria | 16 |
| tuic | 7 |

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
| 81.81 | vless | 211.7 | 515.9 | 22.88 | 0.0 | 9.15 | 11.16 | 19.66 | Au1rxx-base64 | 195.123.240.65 |
| 80.68 | vless | 199.9 | 505.6 | 23.15 | 0.0 | 9.13 | 11.16 | 19.66 | Au1rxx-base64 | 172.235.43.210 |
| 80.35 | vless | 274.5 | 605.7 | 21.42 | 0.0 | 10.0 | 11.16 | 19.66 | Au1rxx-base64 | 15.204.97.216 |
| 80.28 | vless | 202.2 | 526.1 | 23.1 | 0.0 | 10.0 | 11.16 | 16.02 | Surfboard-tg-mixed | 172.235.38.85 |
| 80.0 | shadowsocks | 227.2 | 527.5 | 22.52 | 0.0 | 9.12 | 12.7 | 19.66 | Au1rxx-base64 | 173.244.56.9 |
| 79.27 | shadowsocks | 258.7 | 639.8 | 21.79 | 0.0 | 9.12 | 12.7 | 19.66 | Au1rxx-base64 | 156.146.38.170 |
| 78.79 | hysteria2 | 329.0 | 726.3 | 20.16 | 0.0 | 10.0 | 13.5 | 19.66 | Au1rxx-base64 | 159.223.157.129 |
| 78.41 | vless | 197.5 | 518.3 | 23.21 | 0.0 | 10.0 | 11.16 | 14.04 | mheidari-all | 172.233.139.46 |
| 78.27 | vless | 194.5 | 516.3 | 23.27 | 0.0 | 9.15 | 11.16 | 19.66 | Au1rxx-base64 | 192.3.247.109 |
| 77.89 | vless | 331.4 | 759.0 | 20.11 | 0.0 | 9.13 | 11.16 | 19.66 | Au1rxx-base64 | 79.141.172.154 |
| 77.14 | shadowsocks | 320.1 | 822.4 | 20.37 | 0.0 | 9.12 | 12.7 | 19.66 | Au1rxx-base64 | 156.146.38.167 |
| 77.09 | vless | 302.8 | 496.0 | 20.77 | 0.0 | 10.0 | 11.16 | 19.66 | Au1rxx-base64 | 172.64.229.2 |
| 76.57 | shadowsocks | 278.4 | 615.1 | 21.33 | 0.0 | 9.1 | 12.7 | 19.66 | Au1rxx-base64 | 23.150.248.20 |
| 75.98 | vless | 307.4 | 446.8 | 20.66 | 0.0 | 10.0 | 11.16 | 19.66 | Au1rxx-base64 | 162.159.0.53 |
| 75.98 | vless | 421.5 | 1063.1 | 18.02 | 0.0 | 9.15 | 11.16 | 19.66 | Au1rxx-base64 | 5.78.159.214 |
| 75.97 | shadowsocks | 260.3 | 667.6 | 21.75 | 0.0 | 10.0 | 12.7 | 16.02 | Surfboard-tg-mixed | 108.181.0.177 |
| 75.96 | shadowsocks | 260.7 | 639.6 | 21.74 | 0.0 | 10.0 | 12.7 | 16.02 | Surfboard-tg-mixed | 108.181.118.10 |
| 75.43 | shadowsocks | 198.2 | 522.5 | 23.19 | 0.0 | 10.0 | 12.7 | 14.04 | mheidari-all | 192.3.247.109 |
| 75.16 | shadowsocks | 317.1 | 798.8 | 20.44 | 0.0 | 10.0 | 12.7 | 16.02 | Surfboard-tg-mixed | 156.146.38.168 |
| 74.83 | shadowsocks | 262.9 | 638.8 | 21.69 | 0.0 | 10.0 | 12.7 | 16.02 | Surfboard-tg-mixed | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | 0.905 | 296 | 1702 | prefer |
| Surfboard-tg-mixed | 0.782 | 0.704 | 189 | 7399 | prefer |
| ermaozi | 0.643 | 0.64 | 25 | 338 | observe |
| ermaozi-get_subscribe | 0.38 | 0.8 | 5 | 359 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| mheidari-all | 0.298 | 0.216 | 241 | 22554 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 65 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7876 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9222 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5862 | observe |
| barry-far-vless | 0.255 | None | 0 | 6091 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1702 | observe |
| DeltaKronecker-all | 0.226 | 0.2 | 5 | 5845 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 116 |
| speed | TimeoutError | - | 48 |
| geo | ClientOSError | - | 36 |
| speed | ClientOSError | - | 31 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 11 |
| cn-block | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

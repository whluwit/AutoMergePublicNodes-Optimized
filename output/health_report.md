# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 18:26:22 |
| 运行耗时 | 308.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 77721 |
| 去重后节点 | 21470 |
| TCP 可达 | 3000 |
| 真实可用 | 708 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21470 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 13.6 |
| geo | 1.4 |
| tcp | 34.7 |
| probe | 59.8 |
| real_test | 158.4 |
| generate | 40.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47954 |
| shadowsocks | 10199 |
| vmess | 10150 |
| trojan | 7837 |
| hysteria2 | 1182 |
| http | 165 |
| shadowsocksr | 125 |
| socks | 100 |
| hysteria | 7 |
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
| 82.76 | vless | 301.8 | 681.0 | 20.79 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 154.40.137.160 |
| 82.42 | vless | 288.8 | 703.7 | 21.09 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 216.152.147.28 |
| 82.18 | vless | 250.4 | 680.6 | 21.98 | 0.0 | 8.05 | 12.45 | 19.7 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 82.06 | vless | 340.0 | 948.9 | 19.91 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 79.127.243.217 |
| 81.85 | vless | 349.2 | 809.6 | 19.7 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 169.40.42.179 |
| 81.49 | shadowsocks | 259.2 | 724.3 | 21.78 | 0.0 | 10.0 | 14.01 | 19.7 | Au1rxx-base64 | 37.19.198.236 |
| 81.4 | vless | 368.5 | 1038.3 | 19.25 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 137.184.218.169 |
| 81.22 | vless | 289.7 | 720.8 | 21.07 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 66.70.179.198 |
| 81.17 | shadowsocks | 229.9 | 631.0 | 22.46 | 0.0 | 10.0 | 14.01 | 19.7 | Au1rxx-base64 | 37.19.198.244 |
| 80.83 | vless | 391.6 | 993.4 | 18.71 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 130.107.73.148 |
| 80.74 | vless | 300.8 | 678.4 | 20.82 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 198.251.78.29 |
| 80.6 | vless | 402.8 | 881.7 | 18.45 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 169.40.42.229 |
| 80.44 | vless | 258.6 | 625.6 | 21.79 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 195.211.99.49 |
| 80.43 | hysteria2 | 231.2 | 642.6 | 22.43 | 0.0 | 10.0 | 13.5 | 15.6 | mheidari-all | 159.223.157.129 |
| 80.11 | vless | 376.4 | 1034.2 | 19.06 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 45.138.100.226 |
| 79.83 | shadowsocks | 309.2 | 816.3 | 20.62 | 0.0 | 10.0 | 14.01 | 19.7 | Au1rxx-base64 | 38.180.135.156 |
| 79.8 | vless | 437.4 | 1147.3 | 17.65 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 158.69.112.254 |
| 79.61 | vless | 359.5 | 795.9 | 19.46 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 169.40.42.75 |
| 79.03 | vless | 312.9 | 714.9 | 20.54 | 0.0 | 10.0 | 12.45 | 19.7 | Au1rxx-base64 | 169.40.42.232 |
| 78.99 | shadowsocks | 283.8 | 646.6 | 21.21 | 0.0 | 10.0 | 14.01 | 19.7 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | 0.93 | 399 | 1729 | prefer |
| mheidari-all | 0.997 | 0.941 | 34 | 14516 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Surfboard-tg-mixed | 0.737 | 0.659 | 138 | 6307 | prefer |
| DeltaKronecker-all | 0.609 | 0.529 | 189 | 5415 | observe |
| nscl5-all | 0.298 | 1.0 | 1 | 1082 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 177 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4989 | observe |
| Epodonios-all | 0.255 | None | 0 | 6874 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3990 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6995 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5215 | observe |
| barry-far-vless | 0.255 | None | 0 | 5492 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4085 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 39 |
| cn-block | TimeoutError | - | 37 |
| 204 | TimeoutError | - | 21 |
| geo | ClientOSError | - | 17 |
| 204 | ProxyError | - | 14 |
| speed | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 8 |
| speed | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

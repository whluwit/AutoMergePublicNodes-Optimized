# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 06:43:26 |
| 运行耗时 | 379.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 94187 |
| 去重后节点 | 24566 |
| TCP 可达 | 3000 |
| 真实可用 | 1214 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24566 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.5 |
| tcp | 38.1 |
| probe | 69.1 |
| real_test | 225.5 |
| generate | 39.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52133 |
| trojan | 18298 |
| vmess | 10842 |
| shadowsocks | 10735 |
| hysteria2 | 1633 |
| shadowsocksr | 195 |
| http | 166 |
| socks | 125 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 84.67 | trojan | 227.5 | 520.4 | 22.51 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 44.251.158.80 |
| 83.77 | trojan | 266.3 | 632.0 | 21.61 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 44.255.190.116 |
| 83.62 | trojan | 272.8 | 659.5 | 21.46 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 35.91.138.234 |
| 83.58 | trojan | 274.5 | 659.7 | 21.42 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 35.91.98.35 |
| 83.54 | trojan | 276.2 | 666.0 | 21.38 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 34.223.2.163 |
| 83.03 | shadowsocks | 195.6 | 481.7 | 23.25 | 0.0 | 10.0 | 14.28 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 83.01 | shadowsocks | 174.9 | 491.9 | 23.73 | 0.0 | 10.0 | 14.28 | 20.0 | Au1rxx-base64 | 167.99.103.190 |
| 82.48 | shadowsocks | 230.2 | 631.1 | 22.45 | 0.0 | 10.0 | 14.28 | 20.0 | Au1rxx-base64 | 209.38.142.23 |
| 82.41 | shadowsocks | 243.9 | 592.1 | 22.13 | 0.0 | 10.0 | 14.28 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 82.28 | trojan | 198.8 | 470.6 | 23.18 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 128.14.181.220 |
| 82.17 | trojan | 225.1 | 514.4 | 22.57 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 54.244.169.225 |
| 82.05 | trojan | 230.1 | 519.9 | 22.45 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 34.210.213.17 |
| 81.82 | hysteria2 | 230.4 | 541.1 | 22.44 | 0.0 | 10.0 | 14.14 | 16.24 | mheidari-all | 150.241.102.127 |
| 81.79 | trojan | 241.4 | 545.2 | 22.19 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 34.220.224.252 |
| 81.77 | trojan | 242.4 | 555.8 | 22.17 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 54.188.176.255 |
| 81.68 | trojan | 211.3 | 474.2 | 22.89 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 35.88.120.18 |
| 81.59 | trojan | 274.4 | 660.3 | 21.43 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 35.160.249.189 |
| 81.35 | trojan | 223.2 | 499.8 | 22.61 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 35.90.27.143 |
| 80.64 | trojan | 285.3 | 692.4 | 21.17 | 0.0 | 10.0 | 14.66 | 17.44 | Surfboard-tg-mixed | 100.22.163.167 |
| 80.58 | trojan | 274.7 | 664.7 | 21.42 | 0.0 | 10.0 | 14.66 | 20.0 | Au1rxx-base64 | 34.221.30.108 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.961 | 646 | 1607 | prefer |
| zhangkai | 0.997 | 1.0 | 111 | 144 | prefer |
| mheidari-all | 0.956 | 0.879 | 313 | 21864 | prefer |
| Surfboard-tg-mixed | 0.879 | 0.802 | 252 | 6375 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| DeltaKronecker-all | 0.262 | 0.15 | 20 | 6250 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5148 | observe |
| Epodonios-all | 0.255 | None | 0 | 7077 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7024 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5092 | observe |
| barry-far-vless | 0.255 | None | 0 | 5415 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4647 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1607 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 40 |
| speed | TimeoutError | - | 28 |
| geo | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 14 |
| speed | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 9 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

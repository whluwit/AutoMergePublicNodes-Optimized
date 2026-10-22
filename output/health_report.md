# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 11:10:04 |
| 运行耗时 | 502.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 95606 |
| 去重后节点 | 26580 |
| TCP 可达 | 3000 |
| 真实可用 | 254 |
| Verified 输出 | 254 |
| Global 输出 | 270 |
| All 输出 | 26580 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 44.4 |
| probe | 176.9 |
| real_test | 190.8 |
| generate | 81.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56663 |
| vmess | 17073 |
| shadowsocks | 12033 |
| trojan | 8110 |
| hysteria2 | 1275 |
| http | 193 |
| shadowsocksr | 161 |
| socks | 54 |
| anytls | 21 |
| hysteria | 17 |
| tuic | 6 |

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
| 82.35 | shadowsocks | 239.2 | 604.5 | 22.24 | 0.0 | 10.0 | 14.11 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 81.32 | hysteria2 | 311.4 | 745.9 | 20.57 | 0.0 | 10.0 | 13.75 | 20.0 | Au1rxx-base64 | clash2.deep-links.com |
| 76.56 | shadowsocks | 305.8 | 307.7 | 20.7 | 3.46 | 9.79 | 14.11 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 75.93 | vless | 264.3 | 610.0 | 21.66 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 45.32.69.110 |
| 75.54 | vless | 268.9 | 618.3 | 21.55 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 144.202.126.147 |
| 75.23 | shadowsocks | 345.8 | 749.8 | 19.77 | 0.0 | 10.0 | 14.11 | 19.52 | Surfboard-tg-mixed | 15.204.233.41 |
| 74.22 | vless | 237.0 | 528.4 | 22.29 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 45.76.172.197 |
| 72.59 | vless | 290.2 | 586.4 | 21.06 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 44.248.233.99 |
| 72.14 | vless | 305.9 | 644.8 | 20.7 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 154.29.145.196 |
| 71.84 | vless | 277.8 | 576.2 | 21.35 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 195.123.240.65 |
| 71.7 | hysteria2 | 470.3 | 775.9 | 16.89 | 0.0 | 9.58 | 13.75 | 19.52 | Surfboard-tg-mixed | 130.49.161.70 |
| 71.04 | shadowsocks | 394.0 | 986.0 | 18.66 | 0.0 | 10.0 | 14.11 | 19.52 | Surfboard-tg-mixed | 185.215.132.9 |
| 71.01 | vless | 288.8 | 610.8 | 21.09 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 156.229.164.4 |
| 70.21 | vless | 289.4 | 587.6 | 21.08 | 0.0 | 7.77 | 5.1 | 20.0 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 70.15 | hysteria2 | 507.4 | 606.3 | 16.03 | 0.0 | 9.24 | 13.75 | 20.0 | Au1rxx-base64 | 38.175.202.26 |
| 70.11 | vless | 283.2 | 554.3 | 21.22 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 104.36.69.180 |
| 69.89 | vless | 363.6 | 771.1 | 19.36 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 5.34.178.120 |
| 69.75 | vless | 274.8 | 612.0 | 21.42 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 15.204.97.209 |
| 69.56 | vless | 373.0 | 800.0 | 19.14 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 69.49 | vless | 364.1 | 764.1 | 19.35 | 0.0 | 10.0 | 5.1 | 20.0 | Au1rxx-base64 | 167.17.69.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.828 | 0.857 | 21 | 45 | prefer |
| Au1rxx-base64 | 0.809 | 0.75 | 216 | 1526 | prefer |
| Surfboard-tg-mixed | 0.777 | 0.701 | 87 | 6970 | prefer |
| mheidari-all | 0.547 | 0.778 | 9 | 23951 | observe |
| DeltaKronecker-all | 0.446 | 0.625 | 8 | 3641 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7460 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10066 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5452 | observe |
| barry-far-vless | 0.255 | None | 0 | 5666 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.236 | None | 0 | 1526 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| geo | ClientOSError | - | 8 |
| geo | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 254 | - |
| global | False | 300 | 270 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 08:32:13 |
| 运行耗时 | 245.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85538 |
| 去重后节点 | 23899 |
| TCP 可达 | 3000 |
| 真实可用 | 519 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23899 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 35.8 |
| probe | 55.0 |
| real_test | 113.8 |
| generate | 33.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49973 |
| vmess | 13064 |
| trojan | 10675 |
| shadowsocks | 10250 |
| hysteria2 | 1293 |
| socks | 80 |
| http | 76 |
| shadowsocksr | 73 |
| anytls | 21 |
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
| 84.94 | hysteria2 | 232.1 | 643.8 | 22.4 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 84.67 | hysteria2 | 248.4 | 685.8 | 22.03 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 84.45 | hysteria2 | 241.7 | 677.0 | 22.18 | 0.0 | 9.63 | 13.64 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 82.86 | http | 244.0 | 657.6 | 22.13 | 0.0 | 10.0 | 14.43 | 19.3 | zhangkai | 156.146.59.33 |
| 82.38 | shadowsocks | 231.6 | 645.3 | 22.42 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 81.71 | trojan | 256.9 | 700.8 | 21.83 | 0.0 | 10.0 | 12.88 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 81.35 | shadowsocks | 232.5 | 648.1 | 22.39 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.15 | shadowsocks | 284.4 | 803.3 | 21.19 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.46 | shadowsocks | 272.4 | 619.9 | 21.47 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 79.19 | shadowsocks | 277.0 | 640.6 | 21.37 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 79.08 | shadowsocks | 278.5 | 643.1 | 21.33 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 78.58 | shadowsocks | 374.2 | 1029.3 | 19.12 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 68.168.222.210 |
| 78.23 | shadowsocks | 366.8 | 915.0 | 19.29 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 185.196.61.82 |
| 77.47 | shadowsocks | 227.6 | 629.9 | 22.51 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 77.46 | shadowsocks | 319.7 | 762.9 | 20.38 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 76.68 | trojan | 308.5 | 669.3 | 20.64 | 0.0 | 10.0 | 12.88 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 76.62 | shadowsocks | 313.2 | 704.7 | 20.53 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 75.96 | hysteria2 | 388.8 | 698.8 | 18.78 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 75.36 | hysteria2 | 418.4 | 866.9 | 18.09 | 0.0 | 10.0 | 13.64 | 20.0 | Au1rxx-base64 | 5.255.102.165 |
| 75.01 | shadowsocks | 314.9 | 602.2 | 20.49 | 0.0 | 10.0 | 13.96 | 20.0 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | 0.941 | 407 | 1403 | prefer |
| zhangkai | 0.967 | 0.981 | 53 | 72 | prefer |
| Surfboard-tg-mixed | 0.612 | 0.533 | 122 | 5560 | observe |
| tg-LonUp_M | 0.365 | 1.0 | 3 | 176 | observe |
| mheidari-all | 0.363 | 0.273 | 44 | 20226 | observe |
| DeltaKronecker-all | 0.267 | 0.167 | 18 | 5316 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6163 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6818 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4397 | observe |
| barry-far-vless | 0.255 | None | 0 | 4823 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5147 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 4655 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 48 |
| 204 | TimeoutError | - | 18 |
| speed | TimeoutError | - | 16 |
| 204 | ProxyError | - | 15 |
| speed | ClientOSError | - | 9 |
| geo | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 6 |
| cn-block | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-26 14:17:36 |
| 运行耗时 | 218.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 76309 |
| 去重后节点 | 22702 |
| TCP 可达 | 3000 |
| 真实可用 | 401 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22702 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 30.0 |
| probe | 58.2 |
| real_test | 91.1 |
| generate | 31.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43588 |
| trojan | 11502 |
| vmess | 11138 |
| shadowsocks | 9469 |
| hysteria2 | 262 |
| shadowsocksr | 159 |
| http | 110 |
| socks | 71 |
| hysteria | 8 |
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
| 75.45 | vless | 329.2 | 913.9 | 20.16 | 0.0 | 10.0 | 9.83 | 15.46 | mheidari-all | 47.253.226.114 |
| 75.09 | shadowsocks | 239.1 | 644.8 | 22.24 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 37.19.198.244 |
| 74.02 | shadowsocks | 285.4 | 767.6 | 21.17 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 37.19.198.160 |
| 72.55 | shadowsocks | 343.8 | 917.7 | 19.82 | 0.0 | 10.0 | 11.77 | 15.46 | mheidari-all | 108.181.57.93 |
| 72.13 | shadowsocks | 282.2 | 653.0 | 21.25 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 156.146.38.170 |
| 72.1 | shadowsocks | 275.7 | 637.2 | 21.4 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 156.146.38.167 |
| 70.93 | shadowsocks | 330.1 | 798.3 | 20.14 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 156.146.38.169 |
| 70.82 | shadowsocks | 275.7 | 636.0 | 21.4 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 156.146.38.168 |
| 70.64 | vless | 406.9 | 988.1 | 18.36 | 0.0 | 10.0 | 9.83 | 15.94 | Surfboard-tg-mixed | 15.223.121.250 |
| 70.02 | shadowsocks | 242.1 | 646.4 | 22.17 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 37.19.198.236 |
| 70.0 | shadowsocks | 243.3 | 644.9 | 22.15 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 37.19.198.243 |
| 69.8 | hysteria2 | 361.9 | 699.1 | 19.4 | 0.0 | 10.0 | 12.0 | 15.08 | Au1rxx-base64 | 62.210.124.146 |
| 69.13 | shadowsocks | 388.8 | 1032.1 | 18.78 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 172.234.202.34 |
| 68.19 | vless | 274.5 | 663.7 | 21.42 | 0.0 | 10.0 | 9.83 | 10.32 | DeltaKronecker-all | 104.19.142.226 |
| 67.81 | shadowsocks | 321.1 | 580.8 | 20.35 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 173.244.56.9 |
| 67.48 | vless | 278.4 | 671.5 | 21.33 | 0.0 | 10.0 | 9.83 | 10.32 | DeltaKronecker-all | 104.17.238.33 |
| 67.11 | vless | 390.6 | 714.6 | 18.74 | 0.0 | 10.0 | 9.83 | 15.94 | Surfboard-tg-mixed | 104.16.9.20 |
| 67.08 | shadowsocks | 344.9 | 644.0 | 19.79 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 108.181.0.177 |
| 66.79 | shadowsocks | 345.4 | 647.3 | 19.78 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 108.181.118.10 |
| 66.76 | shadowsocks | 352.5 | 665.0 | 19.62 | 0.0 | 10.0 | 11.77 | 15.08 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Au1rxx-base64 | 0.83 | 0.841 | 44 | 95 | prefer |
| mheidari-all | 0.799 | 0.721 | 201 | 16250 | prefer |
| Surfboard-tg-mixed | 0.78 | 0.701 | 211 | 5176 | prefer |
| DeltaKronecker-all | 0.42 | 0.337 | 98 | 6283 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4567 | observe |
| Epodonios-all | 0.255 | None | 0 | 7885 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3983 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7254 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3834 | observe |
| barry-far-vless | 0.255 | None | 0 | 4612 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5185 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 85 |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 22 |
| 204 | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 13 |
| geo | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 6 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

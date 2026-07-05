# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-05 02:42:56 |
| 运行耗时 | 232.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 78851 |
| 去重后节点 | 23827 |
| TCP 可达 | 3000 |
| 真实可用 | 508 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23827 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 31.0 |
| probe | 46.4 |
| real_test | 102.4 |
| generate | 46.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45400 |
| trojan | 12685 |
| vmess | 10433 |
| shadowsocks | 9507 |
| hysteria2 | 468 |
| shadowsocksr | 147 |
| http | 135 |
| socks | 67 |
| hysteria | 6 |
| tuic | 3 |

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
| 74.28 | shadowsocks | 226.0 | 533.9 | 22.55 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 149.22.95.183 |
| 74.24 | shadowsocks | 206.0 | 496.6 | 23.01 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 108.181.118.10 |
| 73.88 | shadowsocks | 221.7 | 542.7 | 22.65 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 108.181.0.177 |
| 68.78 | shadowsocks | 326.3 | 757.5 | 20.22 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 156.146.38.168 |
| 68.38 | shadowsocks | 349.4 | 831.2 | 19.69 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 156.146.38.169 |
| 68.02 | shadowsocks | 339.2 | 753.3 | 19.93 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 156.146.38.167 |
| 67.93 | vless | 319.0 | 845.8 | 20.39 | 0.0 | 10.0 | 3.24 | 14.3 | Au1rxx-base64 | 15.204.97.214 |
| 67.13 | shadowsocks | 297.1 | 352.3 | 20.9 | 1.79 | 9.9 | 11.43 | 14.3 | Au1rxx-base64 | 149.22.87.241 |
| 66.22 | shadowsocks | 335.4 | 614.6 | 20.01 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 173.244.56.9 |
| 66.16 | vless | 294.8 | 647.1 | 20.95 | 0.0 | 10.0 | 3.24 | 13.82 | Surfboard-tg-mixed | 91.196.33.216 |
| 65.78 | vless | 175.2 | 478.7 | 23.72 | 0.0 | 10.0 | 3.24 | 13.82 | Surfboard-tg-mixed | 64.23.143.23 |
| 65.44 | shadowsocks | 366.0 | 720.9 | 19.3 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 173.244.56.6 |
| 65.27 | shadowsocks | 366.2 | 736.6 | 19.3 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 37.19.198.160 |
| 65.22 | shadowsocks | 370.3 | 750.2 | 19.21 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 37.19.198.236 |
| 64.85 | trojan | 243.8 | 453.6 | 22.14 | 0.0 | 10.0 | 6.99 | 13.82 | Surfboard-tg-mixed | 172.67.172.95 |
| 64.68 | shadowsocks | 287.3 | 646.7 | 21.13 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 156.146.38.170 |
| 64.42 | trojan | 243.7 | 560.1 | 22.14 | 0.0 | 10.0 | 6.99 | 14.3 | Au1rxx-base64 | pro-tortoise.rooster465.autos |
| 64.37 | shadowsocks | 352.1 | 351.6 | 19.63 | 1.81 | 9.59 | 11.43 | 14.3 | Au1rxx-base64 | 61.231.25.172 |
| 64.11 | shadowsocks | 419.0 | 896.2 | 18.08 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 37.19.198.244 |
| 64.06 | shadowsocks | 414.3 | 875.5 | 18.19 | 0.0 | 10.0 | 11.43 | 14.3 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.856 | 0.779 | 208 | 7309 | prefer |
| Au1rxx-base64 | 0.802 | 0.807 | 57 | 127 | prefer |
| mheidari-all | 0.761 | 0.689 | 45 | 16452 | prefer |
| Surfboard-tg-mixed | 0.71 | 0.631 | 363 | 6073 | prefer |
| tg-ConfigV2rayNG | 0.319 | 1.0 | 2 | 200 | observe |
| nscl5-all | 0.308 | 1.0 | 1 | 1323 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6981 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6984 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4518 | observe |
| barry-far-vless | 0.255 | None | 0 | 5089 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5366 | observe |
| xiaoji235-airport-v2ray-all | 0.227 | None | 0 | 1288 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 106 |
| geo | TimeoutError | - | 41 |
| speed | TimeoutError | - | 16 |
| geo | ClientOSError | - | 15 |
| 204 | ClientOSError | - | 9 |
| cn-block | TimeoutError | - | 8 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| speed | ClientPayloadError | - | 2 |
| 204 | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 165 | 300 | - |
| global | False | 175 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

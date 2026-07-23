# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-23 08:27:54 |
| 运行耗时 | 308.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83068 |
| 去重后节点 | 22722 |
| TCP 可达 | 3000 |
| 真实可用 | 744 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22722 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.3 |
| tcp | 32.6 |
| probe | 61.2 |
| real_test | 180.9 |
| generate | 28.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47811 |
| trojan | 13996 |
| shadowsocks | 10445 |
| vmess | 10196 |
| hysteria2 | 421 |
| shadowsocksr | 72 |
| http | 50 |
| socks | 43 |
| tuic | 17 |
| hysteria | 14 |
| anytls | 3 |

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
| 77.12 | vless | 187.1 | 476.1 | 23.45 | 0.0 | 10.0 | 3.79 | 19.88 | Surfboard-tg-mixed | 64.23.143.23 |
| 71.77 | trojan | 283.9 | 656.6 | 21.21 | 0.0 | 10.0 | 14.1 | 14.98 | DeltaKronecker-all | 54.201.96.21 |
| 71.64 | vless | 168.6 | 454.8 | 23.87 | 0.0 | 10.0 | 3.79 | 14.98 | DeltaKronecker-all | 104.25.161.29 |
| 71.59 | vless | 170.9 | 458.8 | 23.82 | 0.0 | 10.0 | 3.79 | 14.98 | DeltaKronecker-all | 172.67.209.126 |
| 70.75 | trojan | 325.9 | 334.7 | 20.23 | 2.45 | 9.93 | 14.1 | 14.98 | DeltaKronecker-all | 95.85.94.148 |
| 70.64 | trojan | 243.1 | 543.8 | 22.15 | 0.0 | 10.0 | 14.1 | 12.52 | mheidari-all | 44.255.92.71 |
| 69.75 | trojan | 283.7 | 660.4 | 21.21 | 0.0 | 10.0 | 14.1 | 12.52 | mheidari-all | 54.70.42.11 |
| 69.12 | trojan | 339.9 | 371.5 | 19.91 | 1.07 | 9.95 | 14.1 | 14.98 | DeltaKronecker-all | 95.85.94.199 |
| 69.09 | vless | 172.5 | 468.8 | 23.78 | 0.0 | 10.0 | 3.79 | 12.52 | mheidari-all | 198.41.209.87 |
| 68.39 | vless | 157.9 | 447.8 | 24.12 | 0.0 | 10.0 | 3.79 | 14.98 | DeltaKronecker-all | 92.223.71.246 |
| 67.97 | trojan | 404.1 | 514.1 | 18.42 | 0.0 | 10.0 | 14.1 | 19.88 | Surfboard-tg-mixed | 104.16.72.50 |
| 67.7 | vless | 341.5 | 348.1 | 19.87 | 1.95 | 9.91 | 3.79 | 19.88 | Surfboard-tg-mixed | 43.165.186.226 |
| 67.38 | trojan | 390.5 | 849.8 | 18.74 | 0.0 | 10.0 | 14.1 | 12.52 | mheidari-all | 163.245.196.68 |
| 67.13 | trojan | 323.4 | 327.8 | 20.29 | 2.71 | 9.95 | 14.1 | 14.98 | DeltaKronecker-all | 31.223.184.43 |
| 66.99 | trojan | 327.0 | 329.4 | 20.21 | 2.65 | 9.94 | 14.1 | 14.98 | DeltaKronecker-all | 31.223.184.164 |
| 66.84 | trojan | 239.9 | 545.8 | 22.22 | 0.0 | 0.0 | 14.1 | 19.88 | Surfboard-tg-mixed | sincere-man.rooster465.autos |
| 66.69 | trojan | 329.8 | 331.8 | 20.14 | 2.56 | 9.94 | 14.1 | 14.98 | DeltaKronecker-all | 31.223.184.238 |
| 66.53 | trojan | 678.1 | 969.4 | 12.08 | 0.0 | 10.0 | 14.1 | 19.88 | Surfboard-tg-mixed | 198.62.62.23 |
| 66.52 | trojan | 605.3 | 895.4 | 13.77 | 0.0 | 9.45 | 14.1 | 19.88 | Surfboard-tg-mixed | 63.178.193.196 |
| 66.35 | trojan | 611.0 | 905.9 | 13.63 | 0.0 | 9.42 | 14.1 | 19.88 | Surfboard-tg-mixed | 3.64.62.54 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.929 | 0.85 | 381 | 19639 | prefer |
| Surfboard-tg-mixed | 0.617 | 0.537 | 244 | 5330 | observe |
| DeltaKronecker-all | 0.608 | 0.528 | 470 | 5572 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4399 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| Epodonios-all | 0.255 | None | 0 | 6489 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3968 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6912 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4154 | observe |
| barry-far-vless | 0.255 | None | 0 | 4690 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4954 | observe |
| nscl5-all | 0.255 | None | 0 | 2435 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 183 |
| speed | ClientOSError | - | 70 |
| geo | ClientOSError | - | 47 |
| cn-block | TimeoutError | - | 39 |
| speed | TimeoutError | - | 22 |
| 204 | ProxyError | - | 18 |
| 204 | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

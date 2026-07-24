# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 08:23:39 |
| 运行耗时 | 325.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83095 |
| 去重后节点 | 22604 |
| TCP 可达 | 3000 |
| 真实可用 | 748 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22604 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 32.4 |
| probe | 63.4 |
| real_test | 181.4 |
| generate | 41.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46858 |
| trojan | 15525 |
| vmess | 10141 |
| shadowsocks | 9958 |
| hysteria2 | 403 |
| shadowsocksr | 79 |
| socks | 57 |
| http | 51 |
| hysteria | 17 |
| tuic | 4 |
| anytls | 2 |

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
| 76.38 | vless | 220.8 | 518.6 | 22.67 | 0.0 | 10.0 | 4.31 | 19.4 | Surfboard-tg-mixed | 86.109.75.147 |
| 75.1 | vless | 228.0 | 513.5 | 22.5 | 0.0 | 10.0 | 4.31 | 19.4 | Surfboard-tg-mixed | 64.23.143.23 |
| 72.66 | trojan | 452.8 | 317.5 | 17.3 | 3.09 | 9.56 | 13.98 | 19.4 | Surfboard-tg-mixed | 119.246.1.143 |
| 71.39 | trojan | 305.7 | 313.2 | 20.7 | 3.25 | 10.0 | 13.98 | 13.26 | mheidari-all | 95.85.94.148 |
| 70.64 | trojan | 459.7 | 564.4 | 17.14 | 0.0 | 10.0 | 13.98 | 19.4 | Surfboard-tg-mixed | 151.101.1.194 |
| 70.56 | trojan | 303.6 | 312.7 | 20.75 | 3.27 | 10.0 | 13.98 | 13.26 | mheidari-all | 31.223.184.43 |
| 70.51 | trojan | 304.6 | 314.4 | 20.73 | 3.21 | 10.0 | 13.98 | 13.26 | mheidari-all | 31.223.184.149 |
| 70.38 | trojan | 305.5 | 314.1 | 20.71 | 3.22 | 10.0 | 13.98 | 13.26 | mheidari-all | 31.223.184.178 |
| 70.33 | trojan | 306.5 | 316.7 | 20.68 | 3.12 | 10.0 | 13.98 | 13.26 | mheidari-all | 31.223.184.82 |
| 70.21 | vless | 213.8 | 490.7 | 22.83 | 0.0 | 10.0 | 4.31 | 15.46 | DeltaKronecker-all | 172.67.209.126 |
| 69.85 | trojan | 306.7 | 325.1 | 20.68 | 2.81 | 10.0 | 13.98 | 13.26 | mheidari-all | 31.223.184.238 |
| 69.67 | trojan | 531.2 | 1265.8 | 15.48 | 0.0 | 10.0 | 13.98 | 19.4 | Surfboard-tg-mixed | 163.245.196.68 |
| 69.4 | trojan | 333.7 | 293.9 | 20.05 | 3.98 | 10.0 | 13.98 | 13.26 | mheidari-all | 31.223.184.164 |
| 68.68 | trojan | 266.8 | 635.8 | 21.6 | 0.0 | 10.0 | 13.98 | 10.62 | Au1rxx-base64 | 44.249.231.131 |
| 68.67 | trojan | 307.5 | 313.1 | 20.66 | 3.26 | 10.0 | 13.98 | 15.46 | DeltaKronecker-all | 95.85.94.96 |
| 68.6 | trojan | 307.1 | 313.9 | 20.67 | 3.23 | 10.0 | 13.98 | 15.46 | DeltaKronecker-all | 31.223.184.172 |
| 67.71 | trojan | 375.9 | 404.4 | 19.08 | 0.0 | 10.0 | 13.98 | 19.4 | Surfboard-tg-mixed | 104.16.72.50 |
| 67.54 | trojan | 327.5 | 379.2 | 20.2 | 0.78 | 10.0 | 13.98 | 13.26 | mheidari-all | 95.85.94.165 |
| 67.28 | trojan | 465.8 | 962.8 | 17.0 | 0.0 | 10.0 | 13.98 | 15.46 | DeltaKronecker-all | 64.74.163.118 |
| 67.25 | trojan | 322.1 | 656.6 | 20.32 | 0.0 | 10.0 | 13.98 | 10.62 | Au1rxx-base64 | 64.94.95.115 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.95 | 0.871 | 428 | 19618 | prefer |
| zhangkai | 0.95 | 0.972 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.708 | 0.629 | 232 | 5335 | prefer |
| DeltaKronecker-all | 0.52 | 0.44 | 423 | 5559 | observe |
| Au1rxx-base64 | 0.467 | 0.7 | 10 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3847 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6546 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6796 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4186 | observe |
| barry-far-vless | 0.255 | None | 0 | 4836 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| nscl5-all | 0.255 | None | 0 | 3124 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 181 |
| geo | ClientOSError | - | 50 |
| speed | ClientOSError | - | 45 |
| cn-block | TimeoutError | - | 35 |
| 204 | ProxyError | - | 28 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

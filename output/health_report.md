# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 03:30:17 |
| 运行耗时 | 888.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98610 |
| 去重后节点 | 27423 |
| TCP 可达 | 3000 |
| 真实可用 | 514 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27423 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 47.4 |
| probe | 333.1 |
| real_test | 428.0 |
| generate | 72.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58083 |
| vmess | 16125 |
| shadowsocks | 11864 |
| trojan | 10459 |
| hysteria2 | 1304 |
| http | 485 |
| shadowsocksr | 171 |
| socks | 70 |
| anytls | 25 |
| hysteria | 18 |
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
| 84.62 | vless | 210.2 | 524.6 | 22.91 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 144.202.126.147 |
| 84.41 | vless | 219.6 | 530.6 | 22.7 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 195.123.240.65 |
| 84.2 | vless | 228.3 | 552.8 | 22.49 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 154.9.241.170 |
| 82.73 | vless | 275.3 | 563.5 | 21.41 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 154.29.145.196 |
| 82.54 | hysteria2 | 247.2 | 584.0 | 22.05 | 0.0 | 10.0 | 12.19 | 19.3 | Au1rxx-base64 | 66.94.121.46 |
| 82.46 | vless | 219.1 | 514.5 | 22.71 | 0.0 | 10.0 | 12.41 | 19.84 | mheidari-all | 47.251.108.158 |
| 81.72 | shadowsocks | 219.4 | 547.8 | 22.7 | 0.0 | 10.0 | 13.72 | 19.3 | Au1rxx-base64 | 173.244.56.6 |
| 81.55 | shadowsocks | 226.5 | 543.6 | 22.54 | 0.0 | 10.0 | 13.72 | 19.3 | Au1rxx-base64 | 173.244.56.9 |
| 81.39 | vless | 220.1 | 520.2 | 22.68 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 140.82.50.205 |
| 81.34 | vless | 263.2 | 490.8 | 21.68 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 95.111.212.241 |
| 80.85 | shadowsocks | 257.0 | 624.1 | 21.83 | 0.0 | 10.0 | 13.72 | 19.3 | Au1rxx-base64 | 156.146.38.170 |
| 80.26 | vless | 307.4 | 749.2 | 20.66 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 147.45.60.160 |
| 79.58 | shadowsocks | 262.5 | 634.1 | 21.7 | 0.0 | 10.0 | 13.72 | 19.3 | Au1rxx-base64 | 156.146.38.167 |
| 79.57 | http | 339.4 | 920.3 | 19.92 | 0.0 | 10.0 | 13.33 | 19.32 | zhangkai | 138.199.35.198 |
| 79.43 | shadowsocks | 257.0 | 622.7 | 21.83 | 0.0 | 10.0 | 13.72 | 19.3 | Au1rxx-base64 | 156.146.38.169 |
| 78.68 | vless | 360.5 | 689.9 | 19.43 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 154.40.55.185 |
| 78.65 | http | 379.3 | 1029.4 | 19.0 | 0.0 | 10.0 | 13.33 | 19.32 | zhangkai | 138.199.35.216 |
| 78.52 | vless | 289.2 | 600.8 | 21.08 | 0.0 | 10.0 | 12.41 | 19.3 | Au1rxx-base64 | 44.248.233.99 |
| 78.32 | shadowsocks | 260.3 | 632.7 | 21.75 | 0.0 | 10.0 | 13.72 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 78.03 | hysteria2 | 316.9 | 732.3 | 20.44 | 0.0 | 10.0 | 12.19 | 19.3 | Au1rxx-base64 | 129.213.91.185 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | 0.952 | 42 | 7113 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.963 | 0.894 | 340 | 1781 | prefer |
| ermaozi-get_subscribe | 0.574 | 0.553 | 38 | 598 | observe |
| mheidari-all | 0.489 | 0.409 | 301 | 24076 | observe |
| DeltaKronecker-all | 0.291 | 0.25 | 12 | 5076 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5086 | observe |
| Epodonios-all | 0.255 | None | 0 | 7613 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9824 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5621 | observe |
| barry-far-vless | 0.255 | None | 0 | 5866 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 113 |
| geo | ClientOSError | - | 31 |
| speed | ClientOSError | - | 31 |
| 204 | ProxyError | - | 24 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 13 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

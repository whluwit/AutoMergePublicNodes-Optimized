# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 11:09:57 |
| 运行耗时 | 634.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 94216 |
| 去重后节点 | 25182 |
| TCP 可达 | 3000 |
| 真实可用 | 422 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25182 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.4 |
| tcp | 41.1 |
| probe | 307.1 |
| real_test | 246.5 |
| generate | 30.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57892 |
| vmess | 13478 |
| shadowsocks | 10876 |
| trojan | 8895 |
| hysteria2 | 2204 |
| http | 640 |
| shadowsocksr | 129 |
| socks | 61 |
| hysteria | 15 |
| anytls | 14 |
| tuic | 12 |

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
| 84.79 | hysteria2 | 202.0 | 497.9 | 23.1 | 0.0 | 10.0 | 13.75 | 18.94 | Au1rxx-base64 | 66.94.121.46 |
| 78.91 | hysteria2 | 326.4 | 904.2 | 20.22 | 0.0 | 10.0 | 13.75 | 18.94 | Au1rxx-base64 | 107.175.219.48 |
| 77.94 | vless | 201.2 | 512.4 | 23.12 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 172.235.43.210 |
| 77.42 | vless | 223.8 | 502.6 | 22.6 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 150.241.102.181 |
| 76.35 | vless | 270.1 | 672.2 | 21.53 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 172.235.38.85 |
| 74.34 | vless | 262.5 | 552.2 | 21.7 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 144.172.104.26 |
| 74.18 | shadowsocks | 329.6 | 757.2 | 20.15 | 0.0 | 10.0 | 14.33 | 18.74 | Surfboard-tg-mixed | 156.146.38.167 |
| 73.4 | http | 194.0 | 484.1 | 23.29 | 0.0 | 10.0 | 8.91 | 14.2 | ermaozi | 138.199.35.214 |
| 73.39 | vless | 190.6 | 479.0 | 23.37 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 172.236.233.59 |
| 73.32 | http | 197.1 | 499.5 | 23.21 | 0.0 | 10.0 | 8.91 | 14.2 | ermaozi | 138.199.35.200 |
| 72.91 | vless | 202.6 | 523.0 | 23.09 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 31.58.50.200 |
| 72.85 | vless | 190.7 | 477.0 | 23.36 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 104.18.39.218 |
| 72.57 | hysteria2 | 261.5 | 595.0 | 21.73 | 0.0 | 10.0 | 13.75 | 18.94 | Au1rxx-base64 | 108.59.244.158 |
| 72.03 | vless | 273.1 | 715.7 | 21.46 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 172.64.229.2 |
| 71.45 | vless | 287.2 | 444.0 | 21.13 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 172.64.53.55 |
| 71.34 | http | 196.5 | 481.6 | 23.23 | 0.0 | 10.0 | 8.91 | 14.2 | ermaozi | 138.199.35.198 |
| 71.33 | vless | 486.6 | 1287.3 | 16.51 | 0.0 | 10.0 | 5.88 | 18.94 | Au1rxx-base64 | 51.81.203.63 |
| 71.32 | shadowsocks | 432.1 | 942.5 | 17.78 | 0.0 | 10.0 | 14.33 | 18.74 | Surfboard-tg-mixed | 198.98.53.130 |
| 70.68 | http | 225.0 | 561.6 | 22.57 | 0.0 | 10.0 | 8.91 | 14.2 | ermaozi | 138.199.35.215 |
| 70.63 | shadowsocks | 429.1 | 919.7 | 17.85 | 0.0 | 10.0 | 14.33 | 18.74 | Surfboard-tg-mixed | 38.180.135.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.922 | 0.849 | 93 | 20485 | prefer |
| Au1rxx-base64 | 0.855 | 0.792 | 250 | 1633 | prefer |
| Surfboard-tg-mixed | 0.815 | 0.739 | 134 | 7439 | prefer |
| ermaozi | 0.677 | 0.667 | 45 | 436 | observe |
| DeltaKronecker-all | 0.65 | 0.647 | 17 | 5892 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5301 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 102 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7887 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8937 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6075 | observe |
| barry-far-vless | 0.255 | None | 0 | 6291 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4221 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| speed | ClientOSError | - | 23 |
| 204 | ProxyError | - | 18 |
| geo | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 15 |
| 204 | ProxyConnectionError | - | 8 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-11 18:59:28 |
| 运行耗时 | 261.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 75124 |
| 去重后节点 | 24063 |
| TCP 可达 | 3000 |
| 真实可用 | 292 |
| Verified 输出 | 292 |
| Global 输出 | 300 |
| All 输出 | 24063 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.8 |
| geo | 1.4 |
| tcp | 31.8 |
| probe | 59.3 |
| real_test | 122.9 |
| generate | 42.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42647 |
| trojan | 11920 |
| vmess | 10641 |
| shadowsocks | 9314 |
| hysteria2 | 265 |
| shadowsocksr | 149 |
| http | 135 |
| socks | 44 |
| hysteria | 8 |
| tuic | 1 |

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
| 80.32 | shadowsocks | 211.7 | 492.1 | 22.88 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 173.244.56.6 |
| 80.24 | shadowsocks | 214.8 | 496.7 | 22.8 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 173.244.56.9 |
| 80.02 | shadowsocks | 203.1 | 494.5 | 23.08 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 108.181.0.177 |
| 79.22 | shadowsocks | 259.2 | 624.6 | 21.78 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 156.146.38.170 |
| 79.16 | shadowsocks | 252.0 | 616.0 | 21.94 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 156.146.38.167 |
| 79.02 | shadowsocks | 267.9 | 617.6 | 21.58 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 156.146.38.168 |
| 78.54 | shadowsocks | 266.8 | 692.5 | 21.6 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 108.181.118.10 |
| 76.69 | vless | 208.0 | 492.1 | 22.96 | 0.0 | 10.0 | 7.27 | 16.46 | Surfboard-tg-mixed | 64.23.143.23 |
| 75.64 | shadowsocks | 280.4 | 284.6 | 21.29 | 4.33 | 9.85 | 12.86 | 18.58 | Au1rxx-base64 | 149.22.87.204 |
| 75.42 | shadowsocks | 288.1 | 626.1 | 21.11 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 149.22.95.183 |
| 72.72 | shadowsocks | 330.2 | 674.9 | 20.13 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 198.98.53.130 |
| 72.36 | shadowsocks | 305.9 | 357.2 | 20.7 | 1.6 | 9.85 | 12.86 | 18.58 | Au1rxx-base64 | 149.22.87.241 |
| 71.85 | shadowsocks | 351.8 | 735.7 | 19.63 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 37.19.198.243 |
| 71.74 | trojan | 401.9 | 995.7 | 18.47 | 0.0 | 10.0 | 8.32 | 18.58 | Au1rxx-base64 | 149.28.241.235 |
| 71.69 | shadowsocks | 355.3 | 707.9 | 19.55 | 0.0 | 10.0 | 12.86 | 18.58 | Au1rxx-base64 | 37.19.198.244 |
| 71.56 | vless | 248.7 | 535.8 | 22.02 | 0.0 | 10.0 | 7.27 | 18.58 | Au1rxx-base64 | ans-channel-production-b262.up.railway.app |
| 71.54 | vless | 213.0 | 485.6 | 22.85 | 0.0 | 10.0 | 7.27 | 13.64 | mheidari-all | 104.16.9.20 |
| 69.64 | trojan | 272.5 | 483.6 | 21.47 | 0.0 | 10.0 | 8.32 | 16.46 | Surfboard-tg-mixed | 162.159.38.62 |
| 68.9 | vless | 206.7 | 520.3 | 22.99 | 0.0 | 10.0 | 7.27 | 13.64 | mheidari-all | 38.244.20.203 |
| 68.9 | hysteria2 | 439.2 | 758.1 | 17.61 | 0.0 | 9.59 | 11.25 | 18.58 | Au1rxx-base64 | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.703 | 0.705 | 61 | 117 | prefer |
| Surfboard-tg-mixed | 0.587 | 0.507 | 207 | 5204 | observe |
| mheidari-all | 0.533 | 0.453 | 190 | 16311 | observe |
| DeltaKronecker-all | 0.366 | 0.28 | 75 | 7969 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3953 | observe |
| Epodonios-all | 0.255 | None | 0 | 6185 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6322 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3946 | observe |
| barry-far-vless | 0.255 | None | 0 | 4540 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5416 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.229 | None | 0 | 1340 | observe |
| nscl5-all | 0.223 | None | 0 | 1207 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 131 |
| 204 | ProxyError | - | 32 |
| geo | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 13 |
| geo | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 10 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 6 |
| speed | ProxyError | - | 4 |
| geo | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 293 | 292 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

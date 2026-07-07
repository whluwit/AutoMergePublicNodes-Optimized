# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-07 02:44:18 |
| 运行耗时 | 278.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82307 |
| 去重后节点 | 24669 |
| TCP 可达 | 3000 |
| 真实可用 | 578 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24669 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.3 |
| tcp | 32.1 |
| probe | 57.0 |
| real_test | 140.7 |
| generate | 41.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48511 |
| trojan | 12617 |
| vmess | 10567 |
| shadowsocks | 9528 |
| hysteria2 | 728 |
| shadowsocksr | 146 |
| http | 139 |
| socks | 55 |
| hysteria | 8 |
| tuic | 6 |
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
| 75.77 | shadowsocks | 182.6 | 472.4 | 23.55 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 108.181.0.177 |
| 75.38 | shadowsocks | 199.6 | 484.9 | 23.16 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 108.181.118.10 |
| 74.91 | shadowsocks | 241.4 | 498.0 | 22.19 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 173.244.56.6 |
| 73.57 | shadowsocks | 246.6 | 584.6 | 22.07 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 149.22.95.183 |
| 72.17 | vless | 226.5 | 559.4 | 22.53 | 0.0 | 10.0 | 4.02 | 15.62 | Au1rxx-base64 | 15.204.97.214 |
| 71.13 | shadowsocks | 349.0 | 815.7 | 19.7 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 172.245.235.84 |
| 71.1 | shadowsocks | 280.5 | 280.5 | 21.28 | 4.48 | 9.89 | 11.1 | 15.62 | Au1rxx-base64 | 149.22.87.240 |
| 70.56 | trojan | 242.3 | 556.7 | 22.17 | 0.0 | 10.0 | 9.42 | 15.62 | Au1rxx-base64 | pro-tortoise.rooster465.autos |
| 70.51 | shadowsocks | 293.3 | 652.5 | 20.99 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 156.146.38.167 |
| 70.26 | trojan | 310.9 | 393.7 | 20.58 | 0.23 | 10.0 | 9.42 | 15.54 | Surfboard-tg-mixed | 89.116.250.135 |
| 70.05 | shadowsocks | 235.4 | 481.7 | 22.33 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 173.244.56.9 |
| 69.62 | shadowsocks | 293.6 | 656.6 | 20.98 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 156.146.38.170 |
| 68.34 | shadowsocks | 291.9 | 651.5 | 21.02 | 0.0 | 10.0 | 11.1 | 15.62 | Au1rxx-base64 | 156.146.38.169 |
| 68.29 | vless | 174.9 | 466.1 | 23.73 | 0.0 | 10.0 | 4.02 | 15.54 | Surfboard-tg-mixed | 64.23.143.23 |
| 67.93 | shadowsocks | 304.2 | 354.4 | 20.74 | 1.71 | 9.85 | 11.1 | 15.62 | Au1rxx-base64 | 149.22.87.241 |
| 67.43 | shadowsocks | 310.4 | 360.0 | 20.59 | 1.5 | 9.88 | 11.1 | 15.62 | Au1rxx-base64 | 149.22.87.204 |
| 66.93 | trojan | 309.2 | 553.0 | 20.62 | 0.0 | 10.0 | 9.42 | 15.54 | Surfboard-tg-mixed | 140.248.185.252 |
| 66.91 | trojan | 339.5 | 328.9 | 19.92 | 2.67 | 9.91 | 9.42 | 15.54 | Surfboard-tg-mixed | 103.106.228.187 |
| 66.53 | shadowsocks | 181.8 | 464.8 | 23.57 | 0.0 | 10.0 | 11.1 | 10.96 | DeltaKronecker-all | 107.172.219.230 |
| 65.94 | hysteria2 | 454.8 | 765.2 | 17.25 | 0.0 | 9.49 | 12.5 | 15.62 | Au1rxx-base64 | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.84 | 0.847 | 59 | 110 | prefer |
| Surfboard-tg-mixed | 0.723 | 0.644 | 399 | 6047 | prefer |
| DeltaKronecker-all | 0.646 | 0.567 | 127 | 8330 | observe |
| mheidari-all | 0.631 | 0.552 | 290 | 16411 | observe |
| xiaoji235-airport-v2ray-all | 0.352 | 0.5 | 6 | 3626 | observe |
| Epodonios-all | 0.255 | None | 0 | 7041 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7175 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4526 | observe |
| barry-far-vless | 0.255 | None | 0 | 5184 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5338 | observe |
| nscl5-all | 0.234 | None | 0 | 1478 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 162 |
| geo | TimeoutError | - | 90 |
| speed | TimeoutError | - | 32 |
| geo | ClientOSError | - | 24 |
| 204 | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 6 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 289 | 300 | - |
| global | False | 298 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

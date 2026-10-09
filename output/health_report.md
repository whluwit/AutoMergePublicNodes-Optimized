# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 12:42:32 |
| 运行耗时 | 852.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98196 |
| 去重后节点 | 27443 |
| TCP 可达 | 3000 |
| 真实可用 | 445 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27443 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.8 |
| tcp | 48.5 |
| probe | 338.0 |
| real_test | 375.7 |
| generate | 82.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57714 |
| vmess | 15621 |
| shadowsocks | 11990 |
| trojan | 10644 |
| hysteria2 | 1484 |
| http | 437 |
| shadowsocksr | 166 |
| socks | 80 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 13 |

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
| 82.55 | shadowsocks | 223.5 | 604.9 | 22.61 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 156.146.38.169 |
| 82.45 | shadowsocks | 227.8 | 604.9 | 22.51 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 156.146.38.170 |
| 82.44 | shadowsocks | 228.0 | 612.4 | 22.5 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 156.146.38.167 |
| 80.6 | hysteria2 | 289.1 | 720.0 | 21.09 | 0.0 | 10.0 | 14.46 | 19.92 | Au1rxx-base64 | 129.213.91.185 |
| 78.25 | shadowsocks | 254.1 | 540.3 | 21.9 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 108.181.118.10 |
| 77.64 | shadowsocks | 323.9 | 763.2 | 20.28 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 37.19.198.236 |
| 77.15 | shadowsocks | 325.9 | 769.9 | 20.23 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 37.19.198.244 |
| 77.04 | shadowsocks | 326.0 | 757.7 | 20.23 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 37.19.198.243 |
| 76.76 | shadowsocks | 327.5 | 769.6 | 20.2 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 37.19.198.160 |
| 76.62 | shadowsocks | 361.4 | 671.3 | 19.41 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 108.181.0.177 |
| 75.78 | shadowsocks | 296.3 | 623.5 | 20.92 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 173.244.56.6 |
| 75.4 | shadowsocks | 320.3 | 314.1 | 20.36 | 3.22 | 9.68 | 14.02 | 19.92 | Au1rxx-base64 | 149.22.87.240 |
| 75.37 | vless | 254.6 | 558.4 | 21.88 | 0.0 | 10.0 | 6.18 | 19.92 | Au1rxx-base64 | 144.202.126.147 |
| 74.89 | http | 321.0 | 527.5 | 20.35 | 0.0 | 10.0 | 11.42 | 19.32 | zhangkai | 138.199.35.216 |
| 74.79 | http | 339.1 | 488.7 | 19.93 | 0.0 | 10.0 | 11.42 | 19.32 | zhangkai | 138.199.35.198 |
| 74.14 | vless | 264.1 | 552.9 | 21.66 | 0.0 | 10.0 | 6.18 | 19.92 | Au1rxx-base64 | 47.251.108.158 |
| 73.53 | shadowsocks | 384.6 | 957.6 | 18.87 | 0.0 | 10.0 | 14.02 | 19.92 | Au1rxx-base64 | 66.23.204.214 |
| 73.28 | vless | 316.3 | 732.5 | 20.46 | 0.0 | 10.0 | 6.18 | 19.92 | Au1rxx-base64 | 107.173.237.146 |
| 72.91 | shadowsocks | 335.4 | 366.9 | 20.01 | 1.24 | 9.68 | 14.02 | 19.92 | Au1rxx-base64 | 149.22.87.241 |
| 72.55 | hysteria2 | 485.1 | 810.7 | 16.55 | 0.0 | 9.67 | 14.46 | 19.92 | Au1rxx-base64 | 158.101.148.79 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | 0.919 | 334 | 1810 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| mheidari-all | 0.92 | 0.854 | 48 | 23165 | prefer |
| Surfboard-tg-mixed | 0.701 | 0.624 | 93 | 7139 | prefer |
| DeltaKronecker-all | 0.494 | 0.407 | 27 | 5154 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| Epodonios-all | 0.255 | None | 0 | 7541 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10038 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5578 | observe |
| barry-far-vless | 0.255 | None | 0 | 5830 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1810 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 35 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:39242: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-21 13:33:30 |
| 运行耗时 | 310.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82213 |
| 去重后节点 | 22870 |
| TCP 可达 | 3000 |
| 真实可用 | 491 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22870 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 31.5 |
| probe | 61.6 |
| real_test | 160.2 |
| generate | 51.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48972 |
| trojan | 11349 |
| vmess | 10878 |
| shadowsocks | 10397 |
| hysteria2 | 441 |
| shadowsocksr | 71 |
| http | 51 |
| socks | 36 |
| hysteria | 12 |
| tuic | 5 |
| anytls | 1 |

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
| 74.73 | shadowsocks | 260.1 | 648.0 | 21.76 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 156.146.38.168 |
| 74.28 | shadowsocks | 279.4 | 741.7 | 21.31 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 156.146.38.169 |
| 73.94 | shadowsocks | 294.0 | 761.3 | 20.97 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 156.146.38.170 |
| 72.73 | shadowsocks | 259.9 | 639.8 | 21.76 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 156.146.38.167 |
| 70.88 | shadowsocks | 312.9 | 720.6 | 20.54 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 37.19.198.160 |
| 70.27 | shadowsocks | 310.6 | 731.5 | 20.59 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 37.19.198.243 |
| 69.74 | shadowsocks | 270.1 | 563.8 | 21.53 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 173.244.56.9 |
| 69.58 | shadowsocks | 310.1 | 727.7 | 20.6 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 37.19.198.244 |
| 69.48 | trojan | 542.5 | 1483.7 | 15.22 | 0.0 | 10.0 | 12.18 | 15.08 | Au1rxx-base64 | 64.94.95.117 |
| 69.42 | trojan | 545.3 | 1467.5 | 15.16 | 0.0 | 10.0 | 12.18 | 15.08 | Au1rxx-base64 | 64.94.95.115 |
| 69.23 | shadowsocks | 284.8 | 550.4 | 21.19 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 108.181.0.177 |
| 69.03 | trojan | 519.2 | 1363.7 | 15.76 | 0.0 | 10.0 | 12.18 | 15.08 | Au1rxx-base64 | 64.94.95.118 |
| 68.66 | shadowsocks | 365.2 | 925.5 | 19.32 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 185.196.61.82 |
| 68.42 | shadowsocks | 317.1 | 545.0 | 20.44 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 108.181.118.10 |
| 67.46 | shadowsocks | 393.2 | 934.2 | 18.68 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 108.181.57.93 |
| 67.36 | trojan | 633.9 | 1715.3 | 13.1 | 0.0 | 10.0 | 12.18 | 15.08 | Au1rxx-base64 | 64.94.95.114 |
| 67.26 | shadowsocks | 317.5 | 646.7 | 20.43 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 149.22.95.183 |
| 67.04 | shadowsocks | 303.4 | 579.5 | 20.75 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 173.244.56.6 |
| 66.78 | shadowsocks | 291.4 | 653.6 | 21.03 | 0.0 | 10.0 | 11.89 | 15.08 | Au1rxx-base64 | 37.19.198.236 |
| 66.3 | vmess | 471.2 | 1222.3 | 16.87 | 0.0 | 10.0 | 10.0 | 13.94 | Surfboard-tg-mixed | 67.220.95.3 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.74 | 0.662 | 213 | 19167 | prefer |
| Au1rxx-base64 | 0.725 | 0.715 | 179 | 310 | prefer |
| Surfboard-tg-mixed | 0.614 | 0.535 | 217 | 5464 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4304 | observe |
| DeltaKronecker-all | 0.291 | 0.209 | 325 | 5415 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4482 | observe |
| Epodonios-all | 0.255 | None | 0 | 6557 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6824 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4207 | observe |
| barry-far-vless | 0.255 | None | 0 | 4844 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5247 | observe |
| nscl5-all | 0.255 | None | 0 | 2111 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 179 |
| speed | ClientOSError | - | 107 |
| cn-block | TimeoutError | - | 92 |
| 204 | TimeoutError | - | 30 |
| geo | ClientOSError | - | 27 |
| 204 | ProxyError | - | 16 |
| 204 | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 6 |
| geo | ProxyError | - | 4 |
| speed | ProxyError | - | 4 |
| speed | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42224: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

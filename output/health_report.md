# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-12 08:13:09 |
| 运行耗时 | 227.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 76253 |
| 去重后节点 | 23960 |
| TCP 可达 | 3000 |
| 真实可用 | 345 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23960 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.3 |
| tcp | 31.4 |
| probe | 49.3 |
| real_test | 100.9 |
| generate | 40.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43812 |
| trojan | 11940 |
| vmess | 10591 |
| shadowsocks | 9312 |
| hysteria2 | 266 |
| shadowsocksr | 148 |
| http | 136 |
| socks | 36 |
| hysteria | 8 |
| tuic | 4 |

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
| 78.13 | trojan | 226.8 | 553.7 | 22.53 | 0.0 | 10.0 | 14.48 | 15.12 | Surfboard-tg-mixed | 162.159.38.62 |
| 77.94 | shadowsocks | 189.3 | 484.4 | 23.39 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 108.181.0.177 |
| 77.77 | shadowsocks | 218.6 | 510.0 | 22.72 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 173.244.56.6 |
| 77.74 | shadowsocks | 220.0 | 507.9 | 22.69 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 173.244.56.9 |
| 77.7 | shadowsocks | 200.0 | 490.5 | 23.15 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 108.181.118.10 |
| 77.19 | shadowsocks | 243.4 | 592.3 | 22.14 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 149.22.95.183 |
| 73.01 | shadowsocks | 293.2 | 656.6 | 20.99 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 156.146.38.167 |
| 72.95 | shadowsocks | 288.6 | 633.4 | 21.1 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 156.146.38.170 |
| 72.51 | shadowsocks | 306.0 | 657.8 | 20.7 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 156.146.38.168 |
| 72.15 | trojan | 266.6 | 415.8 | 21.61 | 0.0 | 10.0 | 14.48 | 12.06 | mheidari-all | 5.10.215.9 |
| 71.98 | trojan | 274.7 | 392.9 | 21.42 | 0.26 | 10.0 | 14.48 | 15.12 | Surfboard-tg-mixed | 45.131.5.9 |
| 70.6 | shadowsocks | 298.8 | 349.8 | 20.86 | 1.88 | 9.93 | 13.33 | 15.72 | Au1rxx-base64 | 149.22.87.204 |
| 70.53 | shadowsocks | 296.4 | 351.6 | 20.92 | 1.81 | 9.93 | 13.33 | 15.72 | Au1rxx-base64 | 149.22.87.241 |
| 69.91 | vless | 244.9 | 567.1 | 22.11 | 0.0 | 10.0 | 6.08 | 15.72 | Au1rxx-base64 | ansooyefilter-production-454e.up.railway.app |
| 69.77 | trojan | 301.7 | 636.2 | 20.79 | 0.0 | 10.0 | 14.48 | 10.74 | DeltaKronecker-all | 64.94.95.114 |
| 69.76 | trojan | 356.0 | 805.6 | 19.54 | 0.0 | 10.0 | 14.48 | 12.06 | mheidari-all | 45.32.195.168 |
| 69.21 | trojan | 317.3 | 648.5 | 20.43 | 0.0 | 10.0 | 14.48 | 10.74 | DeltaKronecker-all | 64.94.95.117 |
| 69.19 | trojan | 309.8 | 628.1 | 20.61 | 0.0 | 10.0 | 14.48 | 10.74 | DeltaKronecker-all | 64.94.95.115 |
| 68.71 | trojan | 367.3 | 805.5 | 19.27 | 0.0 | 10.0 | 14.48 | 10.74 | DeltaKronecker-all | 45.32.198.247 |
| 68.5 | shadowsocks | 369.6 | 738.4 | 19.22 | 0.0 | 10.0 | 13.33 | 15.72 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.958 | 0.886 | 88 | 16299 | prefer |
| Surfboard-tg-mixed | 0.837 | 0.762 | 101 | 5277 | prefer |
| DeltaKronecker-all | 0.778 | 0.701 | 157 | 8141 | prefer |
| Au1rxx-base64 | 0.731 | 0.733 | 60 | 118 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4003 | observe |
| Epodonios-all | 0.255 | None | 0 | 6278 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6422 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4046 | observe |
| barry-far-vless | 0.255 | None | 0 | 4645 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5416 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.235 | None | 0 | 1508 | observe |
| nscl5-all | 0.233 | None | 0 | 1439 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 24 |
| geo | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 14 |
| geo | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 9 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

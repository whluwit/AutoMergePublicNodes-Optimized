# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-16 08:08:27 |
| 运行耗时 | 217.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79016 |
| 去重后节点 | 24361 |
| TCP 可达 | 3000 |
| 真实可用 | 464 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24361 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 32.8 |
| probe | 48.2 |
| real_test | 104.1 |
| generate | 26.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45736 |
| trojan | 12325 |
| vmess | 10884 |
| shadowsocks | 9493 |
| hysteria2 | 293 |
| shadowsocksr | 134 |
| http | 97 |
| socks | 40 |
| hysteria | 10 |
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
| 81.66 | shadowsocks | 235.7 | 606.5 | 22.32 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 156.146.38.168 |
| 80.79 | shadowsocks | 273.6 | 709.9 | 21.45 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 156.146.38.170 |
| 80.66 | shadowsocks | 278.8 | 723.3 | 21.32 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 156.146.38.169 |
| 77.59 | shadowsocks | 270.2 | 537.2 | 21.52 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 173.244.56.6 |
| 77.58 | shadowsocks | 241.0 | 614.5 | 22.2 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 156.146.38.167 |
| 77.03 | shadowsocks | 294.6 | 517.0 | 20.96 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 173.244.56.9 |
| 75.94 | shadowsocks | 301.8 | 662.8 | 20.79 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 108.181.118.10 |
| 75.86 | shadowsocks | 315.1 | 678.7 | 20.48 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 108.181.0.177 |
| 75.46 | shadowsocks | 313.2 | 312.5 | 20.53 | 3.28 | 9.8 | 14.08 | 19.26 | Au1rxx-base64 | 149.22.87.204 |
| 75.41 | shadowsocks | 327.1 | 719.4 | 20.21 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 37.19.198.244 |
| 75.29 | shadowsocks | 311.7 | 318.9 | 20.56 | 3.04 | 9.79 | 14.08 | 19.26 | Au1rxx-base64 | 149.22.87.241 |
| 73.74 | trojan | 449.5 | 1183.4 | 17.37 | 0.0 | 10.0 | 14.39 | 14.98 | DeltaKronecker-all | 64.94.95.114 |
| 72.95 | shadowsocks | 324.6 | 366.6 | 20.26 | 1.25 | 9.74 | 14.08 | 19.26 | Au1rxx-base64 | 149.22.87.240 |
| 72.75 | shadowsocks | 360.5 | 752.0 | 19.43 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 108.181.57.93 |
| 72.53 | trojan | 373.6 | 380.4 | 19.13 | 0.73 | 9.3 | 14.39 | 19.26 | Au1rxx-base64 | exciting-grizzly.rooster465.autos |
| 71.92 | trojan | 385.5 | 360.1 | 18.85 | 1.5 | 8.27 | 14.39 | 19.26 | Au1rxx-base64 | star-dodo.rooster465.autos |
| 71.81 | trojan | 395.3 | 425.0 | 18.63 | 0.0 | 9.78 | 14.39 | 19.26 | Au1rxx-base64 | 52.194.192.245 |
| 71.02 | shadowsocks | 394.2 | 939.6 | 18.65 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 50.114.177.235 |
| 70.98 | trojan | 525.6 | 1435.0 | 15.61 | 0.0 | 10.0 | 14.39 | 14.98 | DeltaKronecker-all | 64.94.95.117 |
| 70.71 | shadowsocks | 323.4 | 714.8 | 20.29 | 0.0 | 10.0 | 14.08 | 19.26 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.95 | 0.952 | 105 | 149 | prefer |
| DeltaKronecker-all | 0.82 | 0.742 | 310 | 8462 | prefer |
| Surfboard-tg-mixed | 0.635 | 0.556 | 162 | 5384 | observe |
| mheidari-all | 0.356 | 0.263 | 19 | 16776 | observe |
| xiaoji235-airport-v2ray-all | 0.325 | 1.0 | 1 | 1757 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4470 | observe |
| Epodonios-all | 0.255 | None | 0 | 6507 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6804 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4135 | observe |
| barry-far-vless | 0.255 | None | 0 | 4742 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5262 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 63 |
| speed | ClientOSError | - | 47 |
| geo | ClientOSError | - | 12 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyError | - | 9 |
| cn-block | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 5 |
| 204 | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

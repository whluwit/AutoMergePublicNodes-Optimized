# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 12:14:01 |
| 运行耗时 | 860.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98225 |
| 去重后节点 | 27537 |
| TCP 可达 | 3000 |
| 真实可用 | 484 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27537 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.3 |
| tcp | 48.0 |
| probe | 347.8 |
| real_test | 364.3 |
| generate | 90.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57394 |
| vmess | 15735 |
| shadowsocks | 11907 |
| trojan | 10775 |
| hysteria2 | 1565 |
| http | 553 |
| shadowsocksr | 163 |
| socks | 73 |
| anytls | 37 |
| hysteria | 16 |
| tuic | 7 |

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
| 84.4 | hysteria2 | 265.7 | 214.8 | 21.63 | 6.94 | 9.2 | 13.64 | 19.74 | Au1rxx-base64 | open.2ml.bid |
| 84.08 | hysteria2 | 253.2 | 248.1 | 21.92 | 5.7 | 10.0 | 13.64 | 19.74 | Au1rxx-base64 | 158.101.148.79 |
| 79.67 | hysteria2 | 453.2 | 1165.0 | 17.29 | 0.0 | 10.0 | 13.64 | 19.74 | Au1rxx-base64 | 66.94.121.46 |
| 79.04 | vless | 211.2 | 548.7 | 22.89 | 0.0 | 10.0 | 6.41 | 19.74 | Au1rxx-base64 | 15.204.97.197 |
| 79.01 | vless | 212.4 | 551.2 | 22.86 | 0.0 | 10.0 | 6.41 | 19.74 | Au1rxx-base64 | 15.204.97.216 |
| 78.98 | trojan | 287.0 | 739.1 | 21.13 | 0.0 | 7.72 | 12.89 | 19.74 | Au1rxx-base64 | pro-mako.rooster465.autos |
| 78.32 | hysteria2 | 342.7 | 759.0 | 19.85 | 0.0 | 10.0 | 13.64 | 19.74 | Au1rxx-base64 | 129.213.91.185 |
| 77.6 | shadowsocks | 275.5 | 319.2 | 21.4 | 3.03 | 10.0 | 14.41 | 19.74 | Au1rxx-base64 | 149.22.87.241 |
| 77.42 | shadowsocks | 276.8 | 324.3 | 21.37 | 2.84 | 10.0 | 14.41 | 19.74 | Au1rxx-base64 | 149.22.87.240 |
| 76.91 | http | 269.8 | 578.4 | 21.53 | 0.0 | 10.0 | 12.0 | 19.2 | zhangkai | 138.199.35.198 |
| 76.7 | vless | 237.3 | 531.6 | 22.28 | 0.0 | 10.0 | 6.41 | 19.74 | Au1rxx-base64 | 137.175.82.40 |
| 76.54 | trojan | 275.3 | 703.5 | 21.41 | 0.0 | 10.0 | 12.89 | 19.74 | Au1rxx-base64 | 16.144.66.136 |
| 76.46 | trojan | 231.5 | 574.9 | 22.42 | 0.0 | 8.72 | 12.89 | 19.74 | Au1rxx-base64 | alert-titmouse.rooster465.autos |
| 76.23 | trojan | 313.3 | 315.2 | 20.52 | 3.18 | 10.0 | 12.89 | 19.74 | Au1rxx-base64 | 18.183.212.83 |
| 76.1 | trojan | 310.9 | 322.0 | 20.58 | 2.93 | 10.0 | 12.89 | 19.74 | Au1rxx-base64 | 18.183.167.216 |
| 76.1 | trojan | 313.5 | 323.2 | 20.52 | 2.88 | 10.0 | 12.89 | 19.74 | Au1rxx-base64 | 52.194.251.232 |
| 75.95 | trojan | 314.7 | 327.0 | 20.49 | 2.74 | 10.0 | 12.89 | 19.74 | Au1rxx-base64 | 13.230.76.132 |
| 75.71 | trojan | 313.4 | 321.8 | 20.52 | 2.93 | 10.0 | 12.89 | 19.74 | Au1rxx-base64 | 43.206.225.188 |
| 75.65 | trojan | 314.2 | 318.7 | 20.5 | 3.05 | 9.45 | 12.89 | 19.74 | Au1rxx-base64 | stable-python.rooster465.autos |
| 75.61 | trojan | 331.1 | 312.3 | 20.11 | 3.29 | 9.61 | 12.89 | 19.74 | Au1rxx-base64 | 176.34.5.100 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | 0.905 | 346 | 1835 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.849 | 0.778 | 63 | 23631 | prefer |
| DeltaKronecker-all | 0.79 | 0.724 | 29 | 5372 | prefer |
| Surfboard-tg-mixed | 0.713 | 0.636 | 118 | 7157 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5099 | observe |
| Epodonios-all | 0.255 | None | 0 | 7574 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9580 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5553 | observe |
| barry-far-vless | 0.255 | None | 0 | 5786 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4318 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1835 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 18 |
| speed | ClientOSError | - | 16 |
| geo | ClientOSError | - | 15 |
| geo | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyConnectionError | - | 5 |
| 204 | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

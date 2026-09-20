# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 10:39:49 |
| 运行耗时 | 581.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 87004 |
| 去重后节点 | 25137 |
| TCP 可达 | 3000 |
| 真实可用 | 450 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25137 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.4 |
| tcp | 40.7 |
| probe | 232.3 |
| real_test | 217.4 |
| generate | 81.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51515 |
| vmess | 14019 |
| shadowsocks | 10694 |
| trojan | 8643 |
| hysteria2 | 1252 |
| http | 667 |
| shadowsocksr | 121 |
| socks | 74 |
| hysteria | 12 |
| tuic | 4 |
| anytls | 3 |

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
| 84.65 | hysteria2 | 204.5 | 544.0 | 23.04 | 0.0 | 10.0 | 13.85 | 18.76 | Au1rxx-base64 | 66.94.121.46 |
| 78.83 | vless | 238.0 | 542.1 | 22.27 | 0.0 | 10.0 | 8.18 | 18.76 | Au1rxx-base64 | 198.200.42.129 |
| 77.9 | vless | 294.7 | 799.9 | 20.96 | 0.0 | 10.0 | 8.18 | 18.76 | Au1rxx-base64 | 15.204.97.214 |
| 75.71 | trojan | 256.2 | 542.5 | 21.85 | 0.0 | 10.0 | 8.62 | 18.76 | Au1rxx-base64 | 100.42.228.109 |
| 75.4 | shadowsocks | 313.2 | 674.1 | 20.53 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 156.146.38.168 |
| 75.3 | shadowsocks | 319.0 | 697.4 | 20.39 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 173.244.56.6 |
| 75.19 | shadowsocks | 320.3 | 684.7 | 20.36 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 156.146.38.170 |
| 74.55 | shadowsocks | 314.4 | 659.3 | 20.5 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 156.146.38.169 |
| 72.79 | shadowsocks | 319.4 | 688.9 | 20.38 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 156.146.38.167 |
| 72.74 | shadowsocks | 355.7 | 721.5 | 19.54 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 37.19.198.243 |
| 72.45 | vless | 292.4 | 706.4 | 21.01 | 0.0 | 10.0 | 8.18 | 18.76 | Au1rxx-base64 | 34.19.91.203 |
| 72.32 | vless | 311.6 | 323.3 | 20.56 | 2.88 | 10.0 | 8.18 | 18.76 | Au1rxx-base64 | 154.31.114.248 |
| 72.3 | shadowsocks | 375.9 | 780.6 | 19.08 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 37.19.198.236 |
| 72.25 | http | 262.2 | 559.8 | 21.71 | 0.0 | 10.0 | 11.13 | 15.2 | ermaozi | 138.199.35.196 |
| 72.16 | vless | 542.7 | 1523.6 | 15.22 | 0.0 | 10.0 | 8.18 | 18.76 | Au1rxx-base64 | 51.81.203.63 |
| 72.12 | shadowsocks | 380.6 | 859.4 | 18.97 | 0.0 | 10.0 | 14.1 | 18.76 | Au1rxx-base64 | 23.150.248.20 |
| 71.97 | vless | 243.6 | 544.6 | 22.14 | 0.0 | 10.0 | 8.18 | 18.76 | Au1rxx-base64 | 31.58.50.200 |
| 71.84 | http | 272.7 | 580.9 | 21.47 | 0.0 | 10.0 | 11.13 | 15.2 | ermaozi | 138.199.35.216 |
| 71.84 | http | 274.2 | 588.7 | 21.43 | 0.0 | 10.0 | 11.13 | 15.2 | ermaozi | 138.199.35.198 |
| 71.76 | http | 274.0 | 594.2 | 21.44 | 0.0 | 10.0 | 11.13 | 15.2 | ermaozi | 138.199.35.206 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | 0.824 | 289 | 1589 | prefer |
| ermaozi | 0.792 | 0.788 | 52 | 365 | prefer |
| mheidari-all | 0.73 | 0.654 | 78 | 15979 | prefer |
| Surfboard-tg-mixed | 0.707 | 0.628 | 148 | 7138 | prefer |
| DeltaKronecker-all | 0.655 | 0.579 | 38 | 6092 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3625 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 89 | observe |
| Epodonios-all | 0.255 | None | 0 | 7603 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8786 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5693 | observe |
| barry-far-vless | 0.255 | None | 0 | 5912 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1589 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 36 |
| geo | TimeoutError | - | 36 |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyError | - | 18 |
| cn-block | ClientOSError | - | 18 |
| cn-block | TimeoutError | - | 16 |
| speed | TimeoutError | - | 11 |
| speed | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

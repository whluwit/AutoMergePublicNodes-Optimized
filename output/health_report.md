# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 14:53:59 |
| 运行耗时 | 305.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 93779 |
| 去重后节点 | 24474 |
| TCP 可达 | 3000 |
| 真实可用 | 589 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24474 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 41.1 |
| probe | 80.7 |
| real_test | 147.8 |
| generate | 29.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58260 |
| vmess | 12810 |
| shadowsocks | 11256 |
| trojan | 9045 |
| hysteria2 | 2028 |
| http | 138 |
| shadowsocksr | 127 |
| socks | 64 |
| hysteria | 19 |
| anytls | 18 |
| tuic | 14 |

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
| 83.91 | hysteria2 | 236.7 | 569.5 | 22.3 | 0.0 | 8.99 | 14.32 | 19.3 | Au1rxx-base64 | 66.94.121.46 |
| 79.94 | trojan | 245.5 | 594.4 | 22.09 | 0.0 | 9.05 | 12.5 | 19.3 | Au1rxx-base64 | 64.94.95.114 |
| 79.94 | trojan | 245.7 | 595.5 | 22.09 | 0.0 | 9.05 | 12.5 | 19.3 | Au1rxx-base64 | 64.94.95.117 |
| 79.89 | trojan | 250.2 | 611.1 | 21.99 | 0.0 | 9.1 | 12.5 | 19.3 | Au1rxx-base64 | 64.94.95.118 |
| 79.06 | shadowsocks | 274.5 | 720.7 | 21.42 | 0.0 | 9.13 | 13.21 | 19.3 | Au1rxx-base64 | 156.146.38.167 |
| 79.04 | shadowsocks | 239.5 | 617.5 | 22.23 | 0.0 | 10.0 | 13.21 | 17.6 | Surfboard-tg-mixed | 156.146.38.169 |
| 78.96 | vless | 342.3 | 829.9 | 19.85 | 0.0 | 9.07 | 12.37 | 19.3 | Au1rxx-base64 | 15.204.97.216 |
| 78.54 | shadowsocks | 261.1 | 679.1 | 21.73 | 0.0 | 10.0 | 13.21 | 17.6 | Surfboard-tg-mixed | 156.146.38.168 |
| 78.25 | vless | 281.0 | 586.0 | 21.27 | 0.0 | 8.94 | 12.37 | 19.3 | Au1rxx-base64 | 38.150.33.232 |
| 78.22 | vless | 333.0 | 756.7 | 20.07 | 0.0 | 8.94 | 12.37 | 19.3 | Au1rxx-base64 | 172.233.139.46 |
| 78.17 | shadowsocks | 255.7 | 618.2 | 21.86 | 0.0 | 10.0 | 13.21 | 17.6 | Surfboard-tg-mixed | 23.150.248.20 |
| 78.01 | vless | 300.1 | 658.1 | 20.83 | 0.0 | 8.94 | 12.37 | 19.3 | Au1rxx-base64 | 172.235.38.85 |
| 77.55 | vless | 273.8 | 562.6 | 21.44 | 0.0 | 8.92 | 12.37 | 19.3 | Au1rxx-base64 | 216.167.94.71 |
| 77.34 | http | 278.8 | 629.6 | 21.32 | 0.0 | 10.0 | 13.39 | 17.72 | zhangkai | 138.199.35.216 |
| 77.2 | http | 301.7 | 713.5 | 20.79 | 0.0 | 10.0 | 13.39 | 17.72 | zhangkai | 138.199.35.198 |
| 76.89 | vless | 369.6 | 801.4 | 19.22 | 0.0 | 10.0 | 12.37 | 19.3 | Au1rxx-base64 | 38.180.242.205 |
| 75.36 | vless | 270.2 | 564.3 | 21.52 | 0.0 | 10.0 | 12.37 | 19.3 | Au1rxx-base64 | 104.194.74.73 |
| 75.3 | vless | 280.5 | 581.3 | 21.28 | 0.0 | 10.0 | 12.37 | 16.36 | mheidari-all | 38.246.229.58 |
| 74.84 | trojan | 250.0 | 601.5 | 21.99 | 0.0 | 9.05 | 12.5 | 19.3 | Au1rxx-base64 | 64.94.95.115 |
| 74.77 | vless | 300.2 | 659.0 | 20.83 | 0.0 | 9.1 | 12.37 | 19.3 | Au1rxx-base64 | 198.44.36.41 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | 0.91 | 354 | 1876 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.848 | 0.772 | 162 | 7318 | prefer |
| mheidari-all | 0.662 | 0.583 | 192 | 21148 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 5750 | observe |
| tg-oneclickvpnkeys | 0.363 | 1.0 | 3 | 133 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 5856 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4791 | observe |
| Epodonios-all | 0.255 | None | 0 | 7776 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8207 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6005 | observe |
| barry-far-vless | 0.255 | None | 0 | 6226 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4111 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 37 |
| geo | ClientOSError | - | 35 |
| cn-block | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 25 |
| 204 | ProxyError | - | 8 |
| speed | TimeoutError | - | 7 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

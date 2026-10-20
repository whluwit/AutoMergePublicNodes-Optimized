# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 03:18:55 |
| 运行耗时 | 693.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94696 |
| 去重后节点 | 26184 |
| TCP 可达 | 3000 |
| 真实可用 | 467 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26184 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.5 |
| tcp | 44.7 |
| probe | 243.9 |
| real_test | 318.9 |
| generate | 79.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56664 |
| vmess | 17057 |
| shadowsocks | 11237 |
| trojan | 7968 |
| hysteria2 | 1202 |
| http | 276 |
| shadowsocksr | 168 |
| socks | 67 |
| anytls | 34 |
| hysteria | 17 |
| tuic | 6 |

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
| 82.09 | vless | 198.9 | 505.5 | 23.17 | 0.0 | 10.0 | 10.98 | 17.94 | Au1rxx-base64 | 45.63.53.81 |
| 81.52 | hysteria2 | 280.8 | 555.6 | 21.28 | 0.0 | 9.3 | 14.0 | 17.94 | Au1rxx-base64 | 66.94.121.46 |
| 81.48 | vless | 196.7 | 504.4 | 23.23 | 0.0 | 9.33 | 10.98 | 17.94 | Au1rxx-base64 | 144.202.126.147 |
| 80.62 | vless | 190.6 | 493.6 | 23.37 | 0.0 | 9.33 | 10.98 | 17.94 | Au1rxx-base64 | 131.143.180.87 |
| 80.39 | vless | 272.4 | 693.6 | 21.47 | 0.0 | 10.0 | 10.98 | 17.94 | Au1rxx-base64 | 154.9.241.170 |
| 76.49 | vless | 196.6 | 495.0 | 23.23 | 0.0 | 9.34 | 10.98 | 17.94 | Au1rxx-base64 | 104.225.239.122 |
| 76.21 | hysteria2 | 348.8 | 481.6 | 19.7 | 0.0 | 9.32 | 14.0 | 17.94 | Au1rxx-base64 | 179.255.104.98 |
| 75.89 | shadowsocks | 264.5 | 638.8 | 21.65 | 0.0 | 9.3 | 12.0 | 17.94 | Au1rxx-base64 | 156.146.38.167 |
| 75.11 | hysteria2 | 355.7 | 750.0 | 19.54 | 0.0 | 9.35 | 14.0 | 17.94 | Au1rxx-base64 | 129.213.91.185 |
| 75.1 | shadowsocks | 212.5 | 521.0 | 22.86 | 0.0 | 9.3 | 12.0 | 17.94 | Au1rxx-base64 | 173.244.56.9 |
| 74.81 | shadowsocks | 258.6 | 630.5 | 21.79 | 0.0 | 10.0 | 12.0 | 17.94 | Au1rxx-base64 | 156.146.38.169 |
| 74.58 | vless | 335.9 | 732.7 | 20.0 | 0.0 | 8.96 | 10.98 | 17.94 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 74.52 | shadowsocks | 258.5 | 633.5 | 21.79 | 0.0 | 10.0 | 12.0 | 17.94 | Au1rxx-base64 | 156.146.38.168 |
| 73.79 | shadowsocks | 279.2 | 280.1 | 21.32 | 4.49 | 9.26 | 12.0 | 17.94 | Au1rxx-base64 | 149.22.87.241 |
| 73.76 | vless | 337.7 | 764.9 | 19.96 | 0.0 | 10.0 | 10.98 | 17.94 | Au1rxx-base64 | 181.214.152.137 |
| 73.48 | vless | 444.0 | 1110.2 | 17.5 | 0.0 | 9.33 | 10.98 | 17.94 | Au1rxx-base64 | 51.81.203.63 |
| 73.37 | vless | 370.9 | 779.6 | 19.19 | 0.0 | 10.0 | 10.98 | 17.94 | Au1rxx-base64 | 5.34.178.120 |
| 73.15 | vless | 349.1 | 702.8 | 19.7 | 0.0 | 10.0 | 10.98 | 17.94 | Au1rxx-base64 | 212.104.141.233 |
| 73.02 | http | 198.1 | 508.3 | 23.19 | 0.0 | 10.0 | 9.75 | 13.08 | zhangkai | 138.199.35.209 |
| 73.02 | shadowsocks | 215.9 | 527.2 | 22.78 | 0.0 | 10.0 | 12.0 | 12.24 | mheidari-all | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.964 | 0.893 | 84 | 6911 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 27 | prefer |
| Au1rxx-base64 | 0.902 | 0.848 | 289 | 1420 | prefer |
| mheidari-all | 0.533 | 0.452 | 241 | 23317 | observe |
| ermaozi-get_subscribe | 0.489 | 0.467 | 30 | 510 | observe |
| DeltaKronecker-all | 0.361 | 0.4 | 10 | 3294 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7516 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10158 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5797 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 87 |
| geo | ClientOSError | - | 30 |
| 204 | ProxyError | - | 22 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

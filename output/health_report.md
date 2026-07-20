# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-20 19:43:19 |
| 运行耗时 | 270.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 85844 |
| 去重后节点 | 24243 |
| TCP 可达 | 3000 |
| 真实可用 | 403 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24243 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 0.9 |
| tcp | 34.0 |
| probe | 61.4 |
| real_test | 132.8 |
| generate | 36.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51357 |
| trojan | 12451 |
| vmess | 11046 |
| shadowsocks | 10375 |
| hysteria2 | 410 |
| shadowsocksr | 74 |
| socks | 55 |
| http | 52 |
| hysteria | 16 |
| tuic | 7 |
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
| 77.83 | shadowsocks | 244.4 | 621.9 | 22.12 | 0.0 | 9.15 | 12.58 | 17.98 | Au1rxx-base64 | 156.146.38.170 |
| 77.81 | shadowsocks | 245.5 | 616.9 | 22.1 | 0.0 | 9.15 | 12.58 | 17.98 | Au1rxx-base64 | 156.146.38.168 |
| 74.8 | shadowsocks | 287.8 | 671.7 | 21.12 | 0.0 | 9.15 | 12.58 | 17.98 | Au1rxx-base64 | 37.19.198.160 |
| 74.79 | shadowsocks | 294.0 | 700.8 | 20.97 | 0.0 | 9.15 | 12.58 | 17.98 | Au1rxx-base64 | 37.19.198.243 |
| 74.76 | shadowsocks | 300.0 | 707.8 | 20.83 | 0.0 | 9.15 | 12.58 | 17.98 | Au1rxx-base64 | 37.19.198.236 |
| 73.37 | shadowsocks | 288.5 | 644.4 | 21.1 | 0.0 | 9.14 | 12.58 | 17.98 | Au1rxx-base64 | 198.98.53.130 |
| 73.22 | shadowsocks | 281.9 | 544.7 | 21.25 | 0.0 | 9.13 | 12.58 | 17.98 | Au1rxx-base64 | 173.244.56.9 |
| 72.91 | trojan | 522.1 | 1368.9 | 15.69 | 0.0 | 10.0 | 12.24 | 17.98 | Au1rxx-base64 | 148.72.168.35 |
| 72.41 | shadowsocks | 280.3 | 522.2 | 21.29 | 0.0 | 9.14 | 12.58 | 17.98 | Au1rxx-base64 | 108.181.0.177 |
| 72.21 | trojan | 267.4 | 556.2 | 21.59 | 0.0 | 9.97 | 12.24 | 17.98 | Au1rxx-base64 | jp1.8b1c7c70-ecf1-6891-9fa7-68a86662f902.cheathub.net |
| 71.95 | shadowsocks | 282.1 | 758.0 | 21.25 | 0.0 | 9.14 | 12.58 | 17.98 | Au1rxx-base64 | 156.146.38.167 |
| 71.92 | shadowsocks | 309.4 | 722.8 | 20.62 | 0.0 | 9.14 | 12.58 | 17.98 | Au1rxx-base64 | 108.181.57.93 |
| 71.9 | shadowsocks | 307.2 | 564.8 | 20.67 | 0.0 | 9.14 | 12.58 | 17.98 | Au1rxx-base64 | 108.181.118.10 |
| 70.39 | trojan | 398.1 | 798.8 | 18.56 | 0.0 | 9.45 | 12.24 | 17.98 | Au1rxx-base64 | emerging-hagfish.rooster465.autos |
| 69.73 | shadowsocks | 293.5 | 703.0 | 20.98 | 0.0 | 9.15 | 12.58 | 17.98 | Au1rxx-base64 | 37.19.198.244 |
| 69.46 | trojan | 645.0 | 1755.0 | 12.85 | 0.0 | 10.0 | 12.24 | 17.98 | Au1rxx-base64 | 64.94.95.118 |
| 69.19 | trojan | 387.3 | 787.7 | 18.81 | 0.0 | 9.84 | 12.24 | 17.98 | Au1rxx-base64 | legal-glider.rooster465.autos |
| 68.9 | hysteria2 | 477.9 | 916.6 | 16.72 | 0.0 | 9.11 | 12.5 | 17.98 | Au1rxx-base64 | 5.255.102.165 |
| 68.81 | trojan | 402.9 | 830.0 | 18.45 | 0.0 | 10.0 | 12.24 | 17.98 | Au1rxx-base64 | 52.43.195.42 |
| 68.6 | trojan | 394.5 | 800.2 | 18.65 | 0.0 | 9.57 | 12.24 | 17.98 | Au1rxx-base64 | dashing-possum.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.835 | 0.809 | 230 | 719 | prefer |
| Surfboard-tg-mixed | 0.515 | 0.434 | 175 | 5521 | observe |
| mheidari-all | 0.515 | 0.434 | 159 | 19990 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5035 | observe |
| DeltaKronecker-all | 0.33 | 0.246 | 138 | 5962 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4714 | observe |
| Epodonios-all | 0.255 | None | 0 | 6648 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7049 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4263 | observe |
| barry-far-vless | 0.255 | None | 0 | 4959 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5173 | observe |
| nscl5-all | 0.255 | None | 0 | 2118 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 121 |
| speed | ClientOSError | - | 71 |
| cn-block | TimeoutError | - | 54 |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 22 |
| cn-block | ProxyError | - | 11 |
| cn-block | ClientOSError | - | 11 |
| geo | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 7 |
| speed | ProxyError | - | 6 |
| geo | ProxyError | - | 3 |
| speed | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

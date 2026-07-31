# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 08:46:17 |
| 运行耗时 | 226.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 77155 |
| 去重后节点 | 22419 |
| TCP 可达 | 3000 |
| 真实可用 | 403 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22419 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.3 |
| tcp | 31.7 |
| probe | 53.3 |
| real_test | 102.2 |
| generate | 30.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44551 |
| vmess | 11826 |
| shadowsocks | 10121 |
| trojan | 9781 |
| hysteria2 | 586 |
| http | 98 |
| shadowsocksr | 73 |
| socks | 63 |
| anytls | 26 |
| tuic | 16 |
| hysteria | 14 |

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
| 84.81 | hysteria2 | 235.4 | 638.8 | 22.33 | 0.0 | 10.0 | 14.06 | 19.52 | Au1rxx-base64 | 159.223.157.129 |
| 84.41 | hysteria2 | 256.9 | 699.2 | 21.83 | 0.0 | 10.0 | 14.06 | 19.52 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.97 | shadowsocks | 236.0 | 632.2 | 22.32 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 37.19.198.243 |
| 81.86 | shadowsocks | 240.6 | 598.7 | 22.21 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 198.98.53.130 |
| 81.68 | shadowsocks | 248.4 | 670.1 | 22.03 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 37.19.198.160 |
| 81.61 | shadowsocks | 251.2 | 676.1 | 21.96 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 37.19.198.244 |
| 81.51 | shadowsocks | 255.9 | 691.3 | 21.86 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 37.19.198.236 |
| 81.32 | trojan | 262.3 | 698.1 | 21.71 | 0.0 | 10.0 | 13.09 | 19.52 | Au1rxx-base64 | 153.75.250.171 |
| 79.52 | hysteria2 | 252.1 | 689.2 | 21.94 | 0.0 | 10.0 | 14.06 | 19.52 | Au1rxx-base64 | 138.124.68.188 |
| 79.39 | shadowsocks | 325.5 | 855.8 | 20.24 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 68.168.222.210 |
| 79.17 | shadowsocks | 285.7 | 655.7 | 21.16 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 156.146.38.168 |
| 79.12 | shadowsocks | 269.7 | 620.4 | 21.54 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 156.146.38.170 |
| 78.51 | shadowsocks | 279.6 | 648.1 | 21.31 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 156.146.38.169 |
| 77.92 | trojan | 294.1 | 636.2 | 20.97 | 0.0 | 10.0 | 13.09 | 19.52 | Au1rxx-base64 | 64.94.95.114 |
| 77.74 | trojan | 291.9 | 639.6 | 21.02 | 0.0 | 10.0 | 13.09 | 19.52 | Au1rxx-base64 | 64.94.95.117 |
| 77.39 | trojan | 292.1 | 640.2 | 21.02 | 0.0 | 10.0 | 13.09 | 19.52 | Au1rxx-base64 | 64.94.95.115 |
| 76.95 | http | 501.7 | 1391.9 | 16.16 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.7 |
| 76.79 | shadowsocks | 315.6 | 708.0 | 20.47 | 0.0 | 10.0 | 14.13 | 19.52 | Au1rxx-base64 | 108.181.57.93 |
| 76.78 | http | 509.1 | 1427.3 | 15.99 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.5 |
| 76.73 | http | 511.5 | 1429.3 | 15.94 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 156.146.59.8 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 81 | 110 | prefer |
| Au1rxx-base64 | 0.882 | 0.832 | 197 | 1319 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.656 | 154 | 5242 | prefer |
| mheidari-all | 0.66 | 0.688 | 16 | 16339 | observe |
| DeltaKronecker-all | 0.506 | 0.424 | 99 | 5144 | observe |
| xiaoji235-airport-v2ray-all | 0.282 | 0.5 | 2 | 1861 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 175 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 45 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 5918 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6473 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4146 | observe |
| barry-far-vless | 0.255 | None | 0 | 4510 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5074 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 60 |
| 204 | TimeoutError | - | 26 |
| speed | TimeoutError | - | 19 |
| geo | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 11 |
| speed | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

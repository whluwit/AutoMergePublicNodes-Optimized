# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 10:28:30 |
| 运行耗时 | 748.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98758 |
| 去重后节点 | 27646 |
| TCP 可达 | 3000 |
| 真实可用 | 455 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27646 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.4 |
| tcp | 48.4 |
| probe | 286.2 |
| real_test | 322.2 |
| generate | 86.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57618 |
| vmess | 16516 |
| shadowsocks | 11947 |
| trojan | 9985 |
| hysteria2 | 1655 |
| http | 750 |
| shadowsocksr | 170 |
| socks | 70 |
| anytls | 24 |
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
| 81.7 | shadowsocks | 235.5 | 608.4 | 22.33 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 156.146.38.168 |
| 81.65 | shadowsocks | 237.6 | 603.1 | 22.28 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 156.146.38.169 |
| 81.64 | hysteria2 | 287.7 | 721.4 | 21.12 | 0.0 | 10.0 | 12.86 | 19.16 | Au1rxx-base64 | 129.213.91.185 |
| 81.41 | shadowsocks | 247.8 | 639.6 | 22.04 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 80.82 | trojan | 252.9 | 584.1 | 21.92 | 0.0 | 10.0 | 12.74 | 19.16 | Au1rxx-base64 | 66.23.203.21 |
| 80.08 | shadowsocks | 305.1 | 746.7 | 20.71 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 37.19.198.160 |
| 79.34 | shadowsocks | 247.5 | 641.1 | 22.05 | 0.0 | 10.0 | 14.21 | 17.08 | Surfboard-tg-mixed | 156.146.38.167 |
| 79.05 | shadowsocks | 302.1 | 740.2 | 20.78 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 37.19.198.244 |
| 78.13 | shadowsocks | 303.1 | 745.9 | 20.76 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 37.19.198.243 |
| 77.28 | vless | 274.1 | 694.8 | 21.43 | 0.0 | 10.0 | 8.77 | 17.08 | Surfboard-tg-mixed | 147.45.60.160 |
| 76.14 | shadowsocks | 303.2 | 633.1 | 20.76 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 149.22.95.183 |
| 76.02 | vless | 337.7 | 701.1 | 19.96 | 0.0 | 10.0 | 8.77 | 19.16 | Au1rxx-base64 | 169.40.42.173 |
| 75.81 | vless | 298.1 | 664.2 | 20.88 | 0.0 | 10.0 | 8.77 | 19.16 | Au1rxx-base64 | 212.104.141.233 |
| 75.53 | hysteria2 | 241.5 | 522.0 | 22.19 | 0.0 | 9.99 | 12.86 | 19.16 | Au1rxx-base64 | 179.255.104.98 |
| 75.37 | shadowsocks | 290.8 | 612.4 | 21.05 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 173.244.56.6 |
| 75.37 | vless | 401.6 | 1009.8 | 18.48 | 0.0 | 10.0 | 8.77 | 19.16 | Au1rxx-base64 | 185.95.231.156 |
| 75.23 | vless | 315.4 | 611.2 | 20.48 | 0.0 | 10.0 | 8.77 | 19.16 | Au1rxx-base64 | 67.220.73.204 |
| 75.21 | shadowsocks | 378.5 | 950.5 | 19.02 | 0.0 | 10.0 | 14.21 | 19.16 | Au1rxx-base64 | 198.98.53.130 |
| 74.95 | hysteria2 | 351.0 | 654.6 | 19.65 | 0.0 | 10.0 | 12.86 | 19.16 | Au1rxx-base64 | 66.94.121.46 |
| 74.72 | trojan | 448.6 | 1132.8 | 17.39 | 0.0 | 10.0 | 12.74 | 19.16 | Au1rxx-base64 | 69.164.240.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.902 | 0.827 | 456 | 1920 | prefer |
| ermaozi | 0.553 | 0.525 | 101 | 710 | observe |
| Surfboard-tg-mixed | 0.445 | 0.36 | 50 | 7093 | observe |
| mheidari-all | 0.352 | 0.5 | 6 | 23769 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7561 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10015 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5669 | observe |
| barry-far-vless | 0.255 | None | 0 | 5830 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.252 | None | 0 | 1920 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 60 |
| 204 | ProxyError | - | 54 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 15 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

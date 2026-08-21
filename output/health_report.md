# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 12:42:17 |
| 运行耗时 | 363.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 95291 |
| 去重后节点 | 24832 |
| TCP 可达 | 3000 |
| 真实可用 | 1152 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24832 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 0.8 |
| tcp | 39.9 |
| probe | 68.2 |
| real_test | 221.7 |
| generate | 26.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52541 |
| trojan | 18791 |
| vmess | 10915 |
| shadowsocks | 10847 |
| hysteria2 | 1638 |
| shadowsocksr | 204 |
| http | 166 |
| socks | 129 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 82.65 | shadowsocks | 238.0 | 612.5 | 22.27 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 82.5 | shadowsocks | 244.6 | 593.5 | 22.12 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 82.31 | shadowsocks | 252.4 | 638.7 | 21.93 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.59 | vless | 238.0 | 565.6 | 22.27 | 0.0 | 10.0 | 10.2 | 19.12 | mheidari-all | 216.227.161.95 |
| 81.04 | shadowsocks | 296.6 | 744.4 | 20.91 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 80.94 | shadowsocks | 311.9 | 833.2 | 20.56 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 80.9 | vless | 267.6 | 667.6 | 21.58 | 0.0 | 10.0 | 10.2 | 19.12 | mheidari-all | 195.211.99.45 |
| 80.33 | shadowsocks | 288.0 | 693.3 | 21.11 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 79.39 | shadowsocks | 306.3 | 732.3 | 20.69 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.35 | shadowsocks | 320.2 | 774.6 | 20.37 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 79.08 | shadowsocks | 297.4 | 581.6 | 20.89 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 77.99 | hysteria2 | 287.8 | 708.7 | 21.12 | 0.0 | 10.0 | 13.85 | 19.12 | mheidari-all | 159.223.157.129 |
| 77.67 | trojan | 333.4 | 756.4 | 20.06 | 0.0 | 10.0 | 14.69 | 19.12 | mheidari-all | 128.14.181.220 |
| 77.5 | trojan | 312.9 | 589.3 | 20.54 | 0.0 | 10.0 | 14.69 | 20.0 | Au1rxx-base64 | 44.243.85.47 |
| 77.47 | trojan | 316.3 | 592.9 | 20.46 | 0.0 | 10.0 | 14.69 | 20.0 | Au1rxx-base64 | 44.255.190.116 |
| 77.45 | trojan | 315.5 | 594.1 | 20.48 | 0.0 | 10.0 | 14.69 | 20.0 | Au1rxx-base64 | 35.90.27.143 |
| 77.43 | trojan | 309.4 | 577.8 | 20.62 | 0.0 | 10.0 | 14.69 | 20.0 | Au1rxx-base64 | 35.88.120.18 |
| 77.36 | trojan | 315.0 | 596.1 | 20.49 | 0.0 | 10.0 | 14.69 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 77.33 | trojan | 303.6 | 669.8 | 20.75 | 0.0 | 10.0 | 14.69 | 20.0 | Au1rxx-base64 | 162.221.197.83 |
| 77.32 | trojan | 319.7 | 604.5 | 20.38 | 0.0 | 10.0 | 14.69 | 20.0 | Au1rxx-base64 | 54.244.169.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.955 | 715 | 1897 | prefer |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.915 | 0.841 | 113 | 6408 | prefer |
| mheidari-all | 0.831 | 0.753 | 336 | 22031 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| DeltaKronecker-all | 0.372 | 0.444 | 9 | 6250 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 192 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5148 | observe |
| Epodonios-all | 0.255 | None | 0 | 7104 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7205 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5150 | observe |
| barry-far-vless | 0.255 | None | 0 | 5469 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4647 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 42 |
| geo | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 16 |
| speed | TimeoutError | - | 15 |
| 204 | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 7 |
| speed | ClientOSError | - | 6 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

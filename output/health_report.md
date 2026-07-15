# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-15 02:01:13 |
| 运行耗时 | 168.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 76355 |
| 去重后节点 | 23709 |
| TCP 可达 | 3000 |
| 真实可用 | 396 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23709 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 32.4 |
| probe | 40.0 |
| real_test | 67.8 |
| generate | 22.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43460 |
| trojan | 11302 |
| vmess | 11179 |
| shadowsocks | 9756 |
| hysteria2 | 346 |
| http | 137 |
| shadowsocksr | 125 |
| socks | 32 |
| hysteria | 10 |
| anytls | 5 |
| tuic | 3 |

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
| 72.28 | shadowsocks | 216.7 | 580.5 | 22.76 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 198.98.53.130 |
| 71.99 | trojan | 282.6 | 682.3 | 21.24 | 0.0 | 10.0 | 12.03 | 14.72 | DeltaKronecker-all | 104.16.98.215 |
| 71.66 | shadowsocks | 243.8 | 677.7 | 22.14 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 37.19.198.243 |
| 71.59 | shadowsocks | 246.4 | 674.8 | 22.07 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 37.19.198.160 |
| 71.57 | shadowsocks | 247.5 | 684.1 | 22.05 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 37.19.198.244 |
| 71.15 | trojan | 296.9 | 642.6 | 20.9 | 0.0 | 10.0 | 12.03 | 14.72 | DeltaKronecker-all | 64.94.95.115 |
| 70.99 | shadowsocks | 229.2 | 631.0 | 22.47 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 37.19.198.236 |
| 70.37 | trojan | 300.3 | 640.4 | 20.83 | 0.0 | 10.0 | 12.03 | 14.72 | DeltaKronecker-all | 64.94.95.114 |
| 69.31 | shadowsocks | 323.3 | 893.0 | 20.29 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 108.181.57.93 |
| 68.59 | shadowsocks | 337.1 | 841.1 | 19.98 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 185.196.61.82 |
| 68.24 | trojan | 260.8 | 670.6 | 21.74 | 0.0 | 10.0 | 12.03 | 14.72 | DeltaKronecker-all | 5.10.215.9 |
| 68.04 | shadowsocks | 281.5 | 649.7 | 21.26 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 156.146.38.167 |
| 67.76 | hysteria2 | 350.3 | 685.2 | 19.67 | 0.0 | 10.0 | 12.86 | 11.8 | Au1rxx-base64 | 62.210.124.146 |
| 67.04 | shadowsocks | 322.6 | 772.5 | 20.31 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 156.146.38.168 |
| 67.0 | shadowsocks | 282.5 | 641.4 | 21.24 | 0.0 | 10.0 | 11.72 | 11.8 | Au1rxx-base64 | 156.146.38.170 |
| 66.77 | trojan | 443.2 | 781.2 | 17.52 | 0.0 | 10.0 | 12.03 | 15.12 | mheidari-all | 104.17.121.43 |
| 66.46 | trojan | 449.1 | 765.6 | 17.38 | 0.0 | 10.0 | 12.03 | 15.12 | mheidari-all | 104.17.121.9 |
| 66.45 | trojan | 294.8 | 641.1 | 20.95 | 0.0 | 10.0 | 12.03 | 14.72 | DeltaKronecker-all | 64.94.95.117 |
| 66.2 | trojan | 462.0 | 781.9 | 17.08 | 0.0 | 10.0 | 12.03 | 15.12 | mheidari-all | 185.18.250.245 |
| 65.83 | vmess | 433.9 | 788.0 | 17.73 | 0.0 | 10.0 | 13.12 | 14.72 | DeltaKronecker-all | 159.223.13.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.99 | 105 | 149 | prefer |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.89 | 0.818 | 77 | 5440 | prefer |
| DeltaKronecker-all | 0.839 | 0.763 | 139 | 6421 | prefer |
| mheidari-all | 0.739 | 0.662 | 130 | 18109 | prefer |
| nscl5-all | 0.307 | 1.0 | 1 | 1300 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4019 | observe |
| Epodonios-all | 0.255 | None | 0 | 6322 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6024 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4135 | observe |
| barry-far-vless | 0.255 | None | 0 | 4653 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5187 | observe |
| xiaoji235-airport-v2ray-all | 0.245 | None | 0 | 1741 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 45 |
| geo | TimeoutError | - | 19 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| geo | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 238 | 300 | - |
| global | False | 247 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

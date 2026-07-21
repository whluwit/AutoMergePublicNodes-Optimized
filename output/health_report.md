# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-21 08:24:11 |
| 运行耗时 | 266.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81681 |
| 去重后节点 | 22850 |
| TCP 可达 | 3000 |
| 真实可用 | 524 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22850 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.8 |
| geo | 1.3 |
| tcp | 31.8 |
| probe | 62.0 |
| real_test | 139.5 |
| generate | 28.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48299 |
| trojan | 11496 |
| vmess | 10878 |
| shadowsocks | 10413 |
| hysteria2 | 415 |
| shadowsocksr | 70 |
| http | 51 |
| socks | 43 |
| hysteria | 10 |
| tuic | 5 |
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
| 79.32 | shadowsocks | 239.1 | 592.3 | 22.24 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 156.146.38.169 |
| 79.24 | shadowsocks | 242.8 | 608.9 | 22.16 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 156.146.38.170 |
| 78.63 | shadowsocks | 268.9 | 717.2 | 21.55 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 156.146.38.168 |
| 78.32 | trojan | 274.7 | 688.1 | 21.42 | 0.0 | 10.0 | 12.66 | 17.24 | Au1rxx-base64 | 64.94.95.115 |
| 78.01 | trojan | 280.7 | 732.3 | 21.28 | 0.0 | 10.0 | 12.66 | 17.24 | Au1rxx-base64 | 64.94.95.114 |
| 77.91 | trojan | 292.2 | 709.9 | 21.01 | 0.0 | 10.0 | 12.66 | 17.24 | Au1rxx-base64 | 64.94.95.117 |
| 77.87 | trojan | 272.3 | 662.7 | 21.47 | 0.0 | 10.0 | 12.66 | 17.24 | Au1rxx-base64 | 64.94.95.118 |
| 75.06 | shadowsocks | 290.9 | 682.6 | 21.04 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 37.19.198.243 |
| 74.09 | shadowsocks | 273.1 | 558.1 | 21.46 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 173.244.56.9 |
| 73.89 | shadowsocks | 292.2 | 697.8 | 21.01 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 37.19.198.244 |
| 73.49 | shadowsocks | 353.6 | 881.2 | 19.59 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 37.19.198.160 |
| 73.09 | shadowsocks | 362.1 | 862.6 | 19.4 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 185.196.61.82 |
| 73.02 | shadowsocks | 321.4 | 724.3 | 20.34 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 108.181.57.93 |
| 72.96 | shadowsocks | 384.4 | 1046.4 | 18.88 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 156.146.38.167 |
| 72.64 | shadowsocks | 302.2 | 600.6 | 20.78 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 108.181.0.177 |
| 72.55 | trojan | 261.9 | 537.5 | 21.72 | 0.0 | 8.12 | 12.66 | 17.24 | Au1rxx-base64 | jp1.8b1c7c70-ecf1-6891-9fa7-68a86662f902.cheathub.net |
| 71.74 | shadowsocks | 308.9 | 578.7 | 20.63 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 108.181.118.10 |
| 71.73 | shadowsocks | 335.7 | 325.3 | 20.01 | 2.8 | 9.6 | 13.84 | 17.24 | Au1rxx-base64 | 149.22.87.204 |
| 71.5 | shadowsocks | 447.6 | 826.3 | 17.42 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 68.168.222.210 |
| 70.99 | shadowsocks | 283.7 | 566.9 | 21.21 | 0.0 | 10.0 | 13.84 | 17.24 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.754 | 0.745 | 157 | 290 | prefer |
| Surfboard-tg-mixed | 0.697 | 0.618 | 262 | 5320 | observe |
| DeltaKronecker-all | 0.563 | 0.483 | 230 | 5415 | observe |
| mheidari-all | 0.523 | 0.443 | 219 | 19339 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 4304 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4482 | observe |
| Epodonios-all | 0.255 | None | 0 | 6403 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6715 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4054 | observe |
| barry-far-vless | 0.255 | None | 0 | 4688 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5247 | observe |
| nscl5-all | 0.255 | None | 0 | 2111 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 126 |
| geo | TimeoutError | - | 121 |
| cn-block | TimeoutError | - | 65 |
| geo | ClientOSError | - | 20 |
| 204 | TimeoutError | - | 15 |
| speed | TimeoutError | - | 14 |
| 204 | ProxyError | - | 11 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

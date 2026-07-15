# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-15 13:29:53 |
| 运行耗时 | 202.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 76188 |
| 去重后节点 | 22922 |
| TCP 可达 | 3000 |
| 真实可用 | 258 |
| Verified 输出 | 258 |
| Global 输出 | 266 |
| All 输出 | 22922 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.8 |
| geo | 1.3 |
| tcp | 32.5 |
| probe | 43.9 |
| real_test | 72.3 |
| generate | 43.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43265 |
| trojan | 11547 |
| vmess | 11007 |
| shadowsocks | 9728 |
| hysteria2 | 330 |
| http | 138 |
| shadowsocksr | 125 |
| socks | 29 |
| hysteria | 9 |
| tuic | 5 |
| anytls | 5 |

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
| 76.91 | shadowsocks | 238.8 | 596.5 | 22.25 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 156.146.38.167 |
| 76.74 | shadowsocks | 246.2 | 641.9 | 22.08 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 156.146.38.168 |
| 76.41 | shadowsocks | 260.3 | 632.3 | 21.75 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 156.146.38.170 |
| 75.72 | shadowsocks | 247.2 | 624.8 | 22.06 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 156.146.38.169 |
| 75.43 | hysteria2 | 245.5 | 514.3 | 22.1 | 0.0 | 10.0 | 12.5 | 16.04 | Au1rxx-base64 | 38.148.249.252 |
| 73.26 | shadowsocks | 297.9 | 684.1 | 20.88 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 37.19.198.236 |
| 73.11 | trojan | 353.6 | 902.0 | 19.59 | 0.0 | 10.0 | 12.92 | 15.74 | mheidari-all | 64.94.95.118 |
| 73.04 | shadowsocks | 307.0 | 719.0 | 20.67 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 37.19.198.243 |
| 72.87 | shadowsocks | 295.7 | 710.9 | 20.93 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 37.19.198.160 |
| 71.75 | shadowsocks | 283.8 | 546.3 | 21.21 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 173.244.56.9 |
| 71.65 | shadowsocks | 350.0 | 842.2 | 19.68 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 37.19.198.244 |
| 71.13 | shadowsocks | 276.8 | 512.5 | 21.37 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 108.181.0.177 |
| 71.03 | trojan | 276.6 | 648.7 | 21.37 | 0.0 | 10.0 | 12.92 | 13.68 | DeltaKronecker-all | 64.94.95.115 |
| 70.9 | shadowsocks | 286.0 | 539.2 | 21.16 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 173.244.56.6 |
| 70.45 | shadowsocks | 394.3 | 964.2 | 18.65 | 0.0 | 10.0 | 12.62 | 13.68 | DeltaKronecker-all | 185.196.61.82 |
| 70.44 | shadowsocks | 310.4 | 613.8 | 20.59 | 0.0 | 10.0 | 12.62 | 16.04 | Au1rxx-base64 | 149.22.95.183 |
| 69.98 | trojan | 272.9 | 693.0 | 21.46 | 0.0 | 10.0 | 12.92 | 13.68 | DeltaKronecker-all | 64.94.95.114 |
| 69.76 | vmess | 354.8 | 868.2 | 19.57 | 0.0 | 10.0 | 12.0 | 15.74 | mheidari-all | 67.220.95.3 |
| 69.19 | shadowsocks | 423.2 | 1001.5 | 17.98 | 0.0 | 10.0 | 12.62 | 15.74 | mheidari-all | 108.181.57.93 |
| 69.14 | trojan | 345.8 | 872.6 | 19.77 | 0.0 | 10.0 | 12.92 | 13.68 | DeltaKronecker-all | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.823 | 0.824 | 102 | 149 | prefer |
| DeltaKronecker-all | 0.684 | 0.606 | 99 | 6421 | observe |
| Surfboard-tg-mixed | 0.634 | 0.556 | 72 | 5463 | observe |
| mheidari-all | 0.512 | 0.43 | 86 | 16012 | observe |
| nscl5-all | 0.26 | 0.5 | 2 | 1300 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3759 | observe |
| Epodonios-all | 0.255 | None | 0 | 6619 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7237 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4283 | observe |
| barry-far-vless | 0.255 | None | 0 | 4895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5187 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.245 | None | 0 | 1741 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 49 |
| speed | ClientOSError | - | 44 |
| 204 | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 6 |
| geo | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 258 | - |
| global | False | 300 | 266 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

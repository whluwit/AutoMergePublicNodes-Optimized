# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-21 19:18:09 |
| 运行耗时 | 290.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82316 |
| 去重后节点 | 22946 |
| TCP 可达 | 3000 |
| 真实可用 | 520 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22946 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.3 |
| tcp | 31.3 |
| probe | 65.8 |
| real_test | 142.3 |
| generate | 45.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48923 |
| trojan | 11854 |
| vmess | 10824 |
| shadowsocks | 10127 |
| hysteria2 | 407 |
| shadowsocksr | 70 |
| http | 51 |
| socks | 42 |
| hysteria | 12 |
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
| 74.95 | shadowsocks | 231.1 | 641.1 | 22.43 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 37.19.198.160 |
| 74.74 | shadowsocks | 240.2 | 665.0 | 22.22 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 37.19.198.244 |
| 74.59 | shadowsocks | 246.7 | 686.4 | 22.07 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 37.19.198.243 |
| 74.26 | shadowsocks | 239.1 | 640.1 | 22.24 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 108.181.57.93 |
| 71.59 | shadowsocks | 274.6 | 625.3 | 21.42 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 156.146.38.170 |
| 71.0 | shadowsocks | 361.6 | 915.3 | 19.41 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 185.196.61.82 |
| 70.35 | shadowsocks | 283.3 | 652.5 | 21.22 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 156.146.38.169 |
| 69.86 | vmess | 355.1 | 1034.4 | 19.56 | 0.0 | 10.0 | 10.0 | 14.8 | mheidari-all | 67.220.95.3 |
| 69.8 | shadowsocks | 237.6 | 643.9 | 22.28 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 37.19.198.236 |
| 69.59 | hysteria2 | 358.1 | 681.1 | 19.49 | 0.0 | 10.0 | 12.5 | 14.5 | Au1rxx-base64 | 62.210.124.146 |
| 69.38 | vless | 240.5 | 664.0 | 22.21 | 0.0 | 10.0 | 2.37 | 14.8 | mheidari-all | 47.89.186.170 |
| 68.54 | shadowsocks | 330.2 | 781.8 | 20.13 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 156.146.38.167 |
| 68.39 | hysteria2 | 437.5 | 896.8 | 17.65 | 0.0 | 10.0 | 12.5 | 14.5 | Au1rxx-base64 | 5.255.102.165 |
| 67.77 | trojan | 338.3 | 749.0 | 19.95 | 0.0 | 10.0 | 10.52 | 14.5 | Au1rxx-base64 | 64.94.95.115 |
| 67.73 | trojan | 347.9 | 796.9 | 19.72 | 0.0 | 10.0 | 10.52 | 14.5 | Au1rxx-base64 | 64.94.95.118 |
| 67.0 | trojan | 377.4 | 891.9 | 19.04 | 0.0 | 10.0 | 10.52 | 14.5 | Au1rxx-base64 | 64.94.95.117 |
| 66.92 | shadowsocks | 330.3 | 577.2 | 20.13 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 108.181.118.10 |
| 66.68 | shadowsocks | 340.3 | 647.8 | 19.9 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 149.22.95.183 |
| 66.61 | shadowsocks | 336.9 | 602.9 | 19.98 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 108.181.0.177 |
| 65.63 | shadowsocks | 607.4 | 1344.7 | 13.72 | 0.0 | 10.0 | 12.02 | 14.5 | Au1rxx-base64 | 68.168.222.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.857 | 0.783 | 92 | 5389 | prefer |
| Au1rxx-base64 | 0.785 | 0.77 | 196 | 432 | prefer |
| mheidari-all | 0.599 | 0.519 | 497 | 19482 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4304 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4482 | observe |
| Epodonios-all | 0.255 | None | 0 | 6464 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6710 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4172 | observe |
| barry-far-vless | 0.255 | None | 0 | 4788 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5204 | observe |
| nscl5-all | 0.255 | None | 0 | 2111 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 137 |
| geo | TimeoutError | - | 89 |
| cn-block | TimeoutError | - | 40 |
| 204 | TimeoutError | - | 36 |
| geo | ClientOSError | - | 9 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

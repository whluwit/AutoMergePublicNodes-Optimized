# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-18 07:46:37 |
| 运行耗时 | 302.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 98 |
| 原始节点 | 80045 |
| 去重后节点 | 21570 |
| TCP 可达 | 3000 |
| 真实可用 | 847 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21570 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 0.8 |
| tcp | 30.9 |
| probe | 61.9 |
| real_test | 184.4 |
| generate | 19.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47012 |
| trojan | 11252 |
| vmess | 10740 |
| shadowsocks | 10485 |
| hysteria2 | 310 |
| shadowsocksr | 124 |
| socks | 54 |
| http | 54 |
| hysteria | 9 |
| tuic | 3 |
| anytls | 2 |

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
| 80.45 | shadowsocks | 222.8 | 613.5 | 22.62 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 37.19.198.243 |
| 80.17 | shadowsocks | 235.0 | 644.2 | 22.34 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 37.19.198.160 |
| 79.48 | shadowsocks | 221.4 | 612.0 | 22.65 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 37.19.198.236 |
| 78.78 | shadowsocks | 325.9 | 844.2 | 20.23 | 0.0 | 10.0 | 13.61 | 19.44 | mheidari-all | 50.114.177.235 |
| 78.67 | shadowsocks | 330.9 | 900.1 | 20.12 | 0.0 | 10.0 | 13.61 | 19.44 | mheidari-all | 108.181.57.93 |
| 77.18 | shadowsocks | 234.4 | 650.2 | 22.35 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 37.19.198.244 |
| 76.99 | shadowsocks | 275.4 | 628.0 | 21.4 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 156.146.38.168 |
| 76.37 | shadowsocks | 430.2 | 1228.3 | 17.82 | 0.0 | 10.0 | 13.61 | 19.44 | mheidari-all | 68.168.222.210 |
| 76.31 | shadowsocks | 279.0 | 639.1 | 21.32 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 156.146.38.167 |
| 76.27 | trojan | 378.7 | 882.3 | 19.01 | 0.0 | 10.0 | 14.53 | 19.44 | mheidari-all | 64.94.95.118 |
| 74.74 | shadowsocks | 359.6 | 879.6 | 19.45 | 0.0 | 10.0 | 13.61 | 19.44 | mheidari-all | 185.196.61.82 |
| 74.3 | trojan | 430.8 | 761.6 | 17.81 | 0.0 | 10.0 | 14.53 | 19.76 | Surfboard-tg-mixed | 165.215.250.14 |
| 73.96 | trojan | 432.4 | 765.7 | 17.77 | 0.0 | 10.0 | 14.53 | 19.44 | mheidari-all | 104.19.64.105 |
| 73.81 | shadowsocks | 394.9 | 941.7 | 18.64 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 184.75.221.134 |
| 73.8 | shadowsocks | 277.8 | 637.8 | 21.35 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 156.146.38.169 |
| 73.58 | trojan | 428.2 | 758.7 | 17.87 | 0.0 | 10.0 | 14.53 | 19.44 | mheidari-all | 185.18.250.245 |
| 73.42 | trojan | 431.0 | 748.8 | 17.8 | 0.0 | 10.0 | 14.53 | 19.44 | mheidari-all | 104.17.121.9 |
| 73.24 | shadowsocks | 286.3 | 662.3 | 21.15 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 156.146.38.170 |
| 73.08 | shadowsocks | 300.7 | 576.6 | 20.82 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 173.244.56.6 |
| 72.96 | shadowsocks | 320.4 | 578.7 | 20.36 | 0.0 | 10.0 | 13.61 | 18.22 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.951 | 0.952 | 125 | 150 | prefer |
| DeltaKronecker-all | 0.908 | 0.832 | 161 | 3620 | prefer |
| mheidari-all | 0.726 | 0.647 | 589 | 19158 | prefer |
| Surfboard-tg-mixed | 0.641 | 0.562 | 308 | 5509 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4321 | observe |
| nscl5-all | 0.334 | 1.0 | 1 | 1976 | observe |
| Epodonios-all | 0.255 | None | 0 | 6683 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6902 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4187 | observe |
| barry-far-vless | 0.255 | None | 0 | 4807 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5334 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 193 |
| speed | ClientOSError | - | 105 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 18 |
| geo | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 4 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

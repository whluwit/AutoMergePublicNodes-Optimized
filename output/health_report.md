# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 02:16:32 |
| 运行耗时 | 301.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80522 |
| 去重后节点 | 22888 |
| TCP 可达 | 3000 |
| 真实可用 | 771 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22888 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.1 |
| geo | 1.3 |
| tcp | 32.6 |
| probe | 60.1 |
| real_test | 180.6 |
| generate | 24.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45578 |
| trojan | 14296 |
| vmess | 10195 |
| shadowsocks | 9882 |
| hysteria2 | 340 |
| socks | 87 |
| shadowsocksr | 73 |
| http | 50 |
| hysteria | 15 |
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
| 74.66 | trojan | 300.1 | 763.5 | 20.83 | 0.0 | 10.0 | 14.11 | 12.72 | Au1rxx-base64 | 64.94.95.115 |
| 74.02 | trojan | 459.3 | 1229.2 | 17.15 | 0.0 | 10.0 | 14.11 | 15.76 | mheidari-all | 163.245.196.68 |
| 73.82 | vless | 237.3 | 600.2 | 22.28 | 0.0 | 10.0 | 5.78 | 15.76 | mheidari-all | 154.193.55.183 |
| 72.41 | vless | 323.5 | 735.4 | 20.29 | 0.0 | 10.0 | 5.78 | 18.56 | Surfboard-tg-mixed | 47.89.186.170 |
| 70.92 | vless | 281.1 | 571.9 | 21.27 | 0.0 | 10.0 | 5.78 | 18.56 | Surfboard-tg-mixed | 64.23.143.23 |
| 70.79 | trojan | 337.5 | 867.6 | 19.96 | 0.0 | 10.0 | 14.11 | 12.72 | Au1rxx-base64 | 64.94.95.118 |
| 70.55 | vmess | 419.9 | 1086.7 | 18.06 | 0.0 | 10.0 | 10.0 | 18.56 | Surfboard-tg-mixed | 67.220.95.3 |
| 70.2 | trojan | 447.4 | 577.4 | 17.42 | 0.0 | 10.0 | 14.11 | 18.56 | Surfboard-tg-mixed | 151.101.1.194 |
| 69.65 | shadowsocks | 309.4 | 808.1 | 20.62 | 0.0 | 10.0 | 10.71 | 12.72 | Au1rxx-base64 | 156.146.38.169 |
| 69.49 | trojan | 307.2 | 796.7 | 20.67 | 0.0 | 10.0 | 14.11 | 12.72 | Au1rxx-base64 | 64.94.95.117 |
| 69.43 | trojan | 524.4 | 1316.3 | 15.64 | 0.0 | 10.0 | 14.11 | 15.76 | mheidari-all | 153.75.250.171 |
| 69.35 | trojan | 405.8 | 939.7 | 18.38 | 0.0 | 10.0 | 14.11 | 14.6 | DeltaKronecker-all | 64.74.163.118 |
| 69.23 | shadowsocks | 344.4 | 920.9 | 19.8 | 0.0 | 10.0 | 10.71 | 12.72 | Au1rxx-base64 | 156.146.38.167 |
| 68.64 | hysteria2 | 560.7 | 1216.4 | 14.8 | 0.0 | 9.79 | 12.5 | 18.56 | Surfboard-tg-mixed | 130.49.161.70 |
| 68.47 | vless | 458.5 | 1143.7 | 17.16 | 0.0 | 10.0 | 5.78 | 18.56 | Surfboard-tg-mixed | 130.107.73.148 |
| 68.38 | trojan | 505.1 | 822.6 | 16.09 | 0.0 | 9.82 | 14.11 | 18.56 | Surfboard-tg-mixed | 89.39.70.233 |
| 68.32 | trojan | 580.2 | 854.7 | 14.35 | 0.0 | 10.0 | 14.11 | 18.56 | Surfboard-tg-mixed | 104.18.152.246 |
| 68.24 | trojan | 569.0 | 938.9 | 14.61 | 0.0 | 10.0 | 14.11 | 18.56 | Surfboard-tg-mixed | 104.16.174.44 |
| 67.93 | trojan | 581.9 | 963.6 | 14.31 | 0.0 | 10.0 | 14.11 | 18.56 | Surfboard-tg-mixed | 104.19.229.21 |
| 67.87 | shadowsocks | 311.4 | 656.5 | 20.57 | 0.0 | 10.0 | 10.71 | 15.76 | mheidari-all | 107.172.219.230 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.76 | 0.681 | 320 | 5472 | prefer |
| DeltaKronecker-all | 0.725 | 0.646 | 229 | 5559 | prefer |
| mheidari-all | 0.673 | 0.593 | 602 | 19388 | observe |
| Au1rxx-base64 | 0.58 | 0.9 | 10 | 432 | observe |
| tg-ConfigV2rayNG | 0.263 | 1.0 | 1 | 200 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6656 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3967 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6637 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4180 | observe |
| barry-far-vless | 0.255 | None | 0 | 4847 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 155 |
| speed | ClientOSError | - | 123 |
| geo | ClientOSError | - | 55 |
| speed | TimeoutError | - | 49 |
| cn-block | TimeoutError | - | 40 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

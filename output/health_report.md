# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-03 09:00:36 |
| 运行耗时 | 269.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 77372 |
| 去重后节点 | 22723 |
| TCP 可达 | 3000 |
| 真实可用 | 465 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22723 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.4 |
| tcp | 30.8 |
| probe | 57.4 |
| real_test | 139.6 |
| generate | 35.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44807 |
| trojan | 12312 |
| vmess | 10400 |
| shadowsocks | 9228 |
| hysteria2 | 218 |
| shadowsocksr | 150 |
| http | 135 |
| socks | 115 |
| hysteria | 6 |
| tuic | 1 |

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
| 74.3 | shadowsocks | 210.8 | 499.5 | 22.9 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 173.244.56.9 |
| 73.36 | shadowsocks | 251.2 | 612.6 | 21.96 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 156.146.38.167 |
| 73.36 | shadowsocks | 251.5 | 615.7 | 21.96 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 173.244.56.6 |
| 73.11 | shadowsocks | 262.0 | 640.8 | 21.71 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 156.146.38.168 |
| 72.49 | shadowsocks | 289.1 | 727.9 | 21.09 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 156.146.38.170 |
| 72.45 | shadowsocks | 269.0 | 685.5 | 21.55 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 108.181.118.10 |
| 72.07 | shadowsocks | 339.3 | 680.5 | 19.92 | 0.0 | 10.0 | 12.98 | 18.18 | mheidari-all | 198.98.53.130 |
| 71.98 | shadowsocks | 289.2 | 761.9 | 21.08 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 108.181.0.177 |
| 71.4 | vless | 212.6 | 502.4 | 22.86 | 0.0 | 10.0 | 5.82 | 15.72 | Surfboard-tg-mixed | 64.23.143.23 |
| 71.0 | shadowsocks | 352.8 | 921.2 | 19.61 | 0.0 | 10.0 | 12.98 | 12.42 | Au1rxx-base64 | 156.146.38.169 |
| 70.65 | trojan | 500.3 | 1251.5 | 16.2 | 0.0 | 10.0 | 13.8 | 18.18 | mheidari-all | 64.94.95.118 |
| 70.55 | vless | 326.8 | 708.4 | 20.21 | 0.0 | 10.0 | 5.82 | 18.18 | mheidari-all | 34.213.172.16 |
| 70.45 | shadowsocks | 380.4 | 749.8 | 18.97 | 0.0 | 10.0 | 12.98 | 18.18 | mheidari-all | 108.181.57.93 |
| 68.98 | vless | 274.7 | 425.0 | 21.42 | 0.0 | 10.0 | 5.82 | 18.18 | mheidari-all | 173.245.59.35 |
| 67.83 | vless | 265.6 | 693.8 | 21.63 | 0.0 | 10.0 | 5.82 | 18.18 | mheidari-all | 107.173.237.146 |
| 67.23 | trojan | 454.1 | 543.4 | 17.27 | 0.0 | 10.0 | 13.8 | 15.72 | Surfboard-tg-mixed | 91.193.58.201 |
| 67.18 | trojan | 276.6 | 654.8 | 21.37 | 0.0 | 10.0 | 13.8 | 15.72 | Surfboard-tg-mixed | 94.140.0.40 |
| 66.91 | shadowsocks | 185.0 | 486.3 | 23.49 | 0.0 | 10.0 | 12.98 | 18.18 | mheidari-all | 216.105.168.18 |
| 66.57 | vless | 408.2 | 856.9 | 18.33 | 0.0 | 10.0 | 5.82 | 18.18 | mheidari-all | 47.253.226.114 |
| 66.43 | shadowsocks | 305.9 | 353.2 | 20.7 | 1.76 | 9.87 | 12.98 | 12.42 | Au1rxx-base64 | 149.22.87.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.825 | 0.846 | 26 | 84 | prefer |
| DeltaKronecker-all | 0.767 | 0.691 | 94 | 6997 | prefer |
| Surfboard-tg-mixed | 0.751 | 0.672 | 317 | 6013 | prefer |
| mheidari-all | 0.586 | 0.506 | 251 | 16051 | observe |
| nscl5-all | 0.356 | 1.0 | 2 | 1114 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4368 | observe |
| Epodonios-all | 0.255 | None | 0 | 6902 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6955 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4518 | observe |
| barry-far-vless | 0.255 | None | 0 | 5055 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.227 | None | 0 | 1289 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 123 |
| geo | TimeoutError | - | 65 |
| 204 | TimeoutError | - | 16 |
| 204 | ProxyError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 9 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| geo | ClientOSError | - | 4 |
| speed | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

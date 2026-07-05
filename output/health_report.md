# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-05 13:24:54 |
| 运行耗时 | 206.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80045 |
| 去重后节点 | 23896 |
| TCP 可达 | 3000 |
| 真实可用 | 374 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23896 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 31.0 |
| probe | 50.8 |
| real_test | 84.9 |
| generate | 33.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46658 |
| trojan | 12674 |
| vmess | 10398 |
| shadowsocks | 9501 |
| hysteria2 | 474 |
| shadowsocksr | 143 |
| http | 135 |
| socks | 48 |
| tuic | 8 |
| hysteria | 6 |

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
| 79.82 | shadowsocks | 229.1 | 516.2 | 22.48 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 173.244.56.9 |
| 79.77 | shadowsocks | 230.9 | 537.3 | 22.43 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 149.22.95.183 |
| 78.5 | shadowsocks | 285.9 | 657.1 | 21.16 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 173.244.56.6 |
| 75.81 | trojan | 236.8 | 440.2 | 22.3 | 0.0 | 10.0 | 13.42 | 17.18 | Surfboard-tg-mixed | 104.26.15.137 |
| 75.31 | shadowsocks | 286.5 | 641.4 | 21.15 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 156.146.38.167 |
| 75.26 | shadowsocks | 287.3 | 644.8 | 21.13 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 156.146.38.168 |
| 75.23 | trojan | 350.1 | 787.0 | 19.67 | 0.0 | 10.0 | 13.42 | 18.1 | DeltaKronecker-all | 45.32.195.168 |
| 75.05 | trojan | 344.8 | 781.6 | 19.8 | 0.0 | 10.0 | 13.42 | 18.1 | DeltaKronecker-all | 149.28.241.235 |
| 74.93 | trojan | 358.8 | 809.3 | 19.47 | 0.0 | 10.0 | 13.42 | 18.1 | DeltaKronecker-all | 45.32.198.247 |
| 74.92 | shadowsocks | 419.1 | 1143.6 | 18.08 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 108.181.118.10 |
| 74.83 | shadowsocks | 287.2 | 651.0 | 21.13 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 156.146.38.169 |
| 74.36 | trojan | 264.6 | 457.1 | 21.65 | 0.0 | 10.0 | 13.42 | 17.18 | Surfboard-tg-mixed | 172.67.172.95 |
| 73.67 | shadowsocks | 472.8 | 1305.1 | 16.83 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 108.181.0.177 |
| 73.14 | shadowsocks | 293.5 | 646.8 | 20.98 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 156.146.38.170 |
| 73.07 | shadowsocks | 274.9 | 277.7 | 21.41 | 4.59 | 9.89 | 13.12 | 18.22 | Au1rxx-base64 | 149.22.87.204 |
| 72.48 | shadowsocks | 299.1 | 358.1 | 20.85 | 1.57 | 9.89 | 13.12 | 18.22 | Au1rxx-base64 | 149.22.87.241 |
| 71.07 | shadowsocks | 356.0 | 704.3 | 19.54 | 0.0 | 10.0 | 13.12 | 18.26 | mheidari-all | 198.98.53.130 |
| 70.89 | shadowsocks | 365.6 | 736.0 | 19.32 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 37.19.198.243 |
| 70.67 | shadowsocks | 371.3 | 747.4 | 19.18 | 0.0 | 10.0 | 13.12 | 18.22 | Au1rxx-base64 | 37.19.198.160 |
| 70.45 | shadowsocks | 305.6 | 353.5 | 20.7 | 1.74 | 9.89 | 13.12 | 18.22 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.937 | 0.863 | 117 | 6156 | prefer |
| DeltaKronecker-all | 0.875 | 0.799 | 174 | 7739 | prefer |
| mheidari-all | 0.858 | 0.784 | 97 | 16415 | prefer |
| Au1rxx-base64 | 0.728 | 0.741 | 27 | 109 | prefer |
| nscl5-all | 0.364 | 1.0 | 2 | 1323 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4662 | observe |
| Epodonios-all | 0.255 | None | 0 | 7257 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7136 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4608 | observe |
| barry-far-vless | 0.255 | None | 0 | 5319 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.227 | None | 0 | 1288 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 20 |
| geo | TimeoutError | - | 16 |
| 204 | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

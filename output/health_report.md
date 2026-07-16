# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-16 13:44:24 |
| 运行耗时 | 242.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79344 |
| 去重后节点 | 24507 |
| TCP 可达 | 3000 |
| 真实可用 | 476 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24507 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.0 |
| tcp | 33.0 |
| probe | 50.4 |
| real_test | 118.9 |
| generate | 35.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46226 |
| trojan | 12161 |
| vmess | 10740 |
| shadowsocks | 9637 |
| hysteria2 | 304 |
| shadowsocksr | 126 |
| http | 97 |
| socks | 39 |
| hysteria | 10 |
| tuic | 4 |

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
| 80.16 | shadowsocks | 253.6 | 616.9 | 21.91 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.16 | shadowsocks | 253.6 | 612.6 | 21.91 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 156.146.38.170 |
| 79.77 | shadowsocks | 259.1 | 634.5 | 21.78 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 156.146.38.168 |
| 79.76 | shadowsocks | 249.5 | 610.6 | 22.0 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 156.146.38.167 |
| 78.85 | shadowsocks | 309.9 | 790.9 | 20.6 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 37.19.198.244 |
| 76.77 | shadowsocks | 270.5 | 670.2 | 21.52 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 37.19.198.236 |
| 76.73 | shadowsocks | 272.0 | 663.8 | 21.48 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 37.19.198.160 |
| 76.06 | shadowsocks | 322.7 | 887.9 | 20.31 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 50.114.177.235 |
| 74.62 | shadowsocks | 359.1 | 935.7 | 19.47 | 0.0 | 10.0 | 13.25 | 16.4 | DeltaKronecker-all | 185.196.61.82 |
| 74.3 | shadowsocks | 306.5 | 578.7 | 20.68 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 173.244.56.6 |
| 73.8 | shadowsocks | 303.3 | 567.1 | 20.76 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 173.244.56.9 |
| 73.8 | shadowsocks | 310.9 | 645.9 | 20.58 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 108.181.0.177 |
| 73.24 | vmess | 358.0 | 909.5 | 19.49 | 0.0 | 10.0 | 12.86 | 16.4 | DeltaKronecker-all | 67.220.85.46 |
| 73.23 | shadowsocks | 319.2 | 583.9 | 20.39 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 108.181.118.10 |
| 72.15 | vless | 283.3 | 711.7 | 21.22 | 0.0 | 10.0 | 1.93 | 19.0 | Au1rxx-base64 | 47.253.226.114 |
| 72.11 | shadowsocks | 378.8 | 778.8 | 19.01 | 0.0 | 10.0 | 13.25 | 19.0 | Au1rxx-base64 | 172.245.235.84 |
| 72.09 | shadowsocks | 424.3 | 284.0 | 17.96 | 4.35 | 9.5 | 13.25 | 19.0 | Au1rxx-base64 | 149.22.87.204 |
| 71.83 | shadowsocks | 432.2 | 285.8 | 17.77 | 4.28 | 9.5 | 13.25 | 19.0 | Au1rxx-base64 | 149.22.87.240 |
| 71.62 | hysteria2 | 385.0 | 701.0 | 18.86 | 0.0 | 9.92 | 11.25 | 19.0 | Au1rxx-base64 | 62.210.124.146 |
| 70.83 | shadowsocks | 361.0 | 349.2 | 19.42 | 1.9 | 9.53 | 13.25 | 19.0 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.912 | 0.913 | 126 | 150 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.745 | 98 | 5430 | prefer |
| DeltaKronecker-all | 0.673 | 0.594 | 411 | 8462 | observe |
| mheidari-all | 0.46 | 0.412 | 17 | 16416 | observe |
| xiaoji235-airport-v2ray-all | 0.325 | 1.0 | 1 | 1757 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4470 | observe |
| Epodonios-all | 0.255 | None | 0 | 6545 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7282 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4211 | observe |
| barry-far-vless | 0.255 | None | 0 | 4817 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5262 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.236 | None | 0 | 1519 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 97 |
| geo | TimeoutError | - | 58 |
| geo | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 7 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49901: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

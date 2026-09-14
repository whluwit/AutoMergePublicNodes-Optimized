# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 11:45:25 |
| 运行耗时 | 634.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84316 |
| 去重后节点 | 22916 |
| TCP 可达 | 3000 |
| 真实可用 | 468 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22916 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 37.3 |
| probe | 221.9 |
| real_test | 230.2 |
| generate | 135.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51594 |
| vmess | 12851 |
| shadowsocks | 9638 |
| trojan | 7880 |
| hysteria2 | 1507 |
| http | 638 |
| shadowsocksr | 126 |
| socks | 53 |
| tuic | 15 |
| hysteria | 11 |
| anytls | 3 |

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
| 80.22 | shadowsocks | 247.6 | 607.4 | 22.05 | 0.0 | 10.0 | 14.15 | 18.02 | Au1rxx-base64 | 156.146.38.170 |
| 79.8 | shadowsocks | 265.5 | 663.8 | 21.63 | 0.0 | 10.0 | 14.15 | 18.02 | Au1rxx-base64 | 37.19.198.244 |
| 79.55 | shadowsocks | 251.2 | 605.5 | 21.96 | 0.0 | 10.0 | 14.15 | 18.02 | Au1rxx-base64 | 156.146.38.167 |
| 78.7 | shadowsocks | 271.8 | 676.0 | 21.49 | 0.0 | 10.0 | 14.15 | 17.06 | Surfboard-tg-mixed | 198.98.53.130 |
| 78.45 | vless | 258.0 | 638.7 | 21.81 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 198.251.78.29 |
| 77.9 | vless | 281.7 | 706.0 | 21.26 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 79.141.172.154 |
| 77.78 | vless | 286.9 | 720.5 | 21.14 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 47.253.226.114 |
| 77.72 | shadowsocks | 333.7 | 880.8 | 20.05 | 0.0 | 10.0 | 14.15 | 18.02 | Au1rxx-base64 | 15.204.247.206 |
| 76.99 | vless | 321.1 | 644.5 | 20.35 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 169.40.42.231 |
| 76.95 | shadowsocks | 259.0 | 652.5 | 21.78 | 0.0 | 10.0 | 14.15 | 18.02 | Au1rxx-base64 | 37.19.198.160 |
| 76.64 | vless | 301.9 | 671.1 | 20.79 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 169.40.42.168 |
| 76.57 | vless | 314.4 | 648.6 | 20.5 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 169.40.42.223 |
| 76.52 | vless | 341.4 | 903.3 | 19.88 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 216.152.147.28 |
| 76.33 | vless | 349.5 | 862.4 | 19.69 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 167.17.69.171 |
| 76.05 | shadowsocks | 364.5 | 955.0 | 19.34 | 0.0 | 10.0 | 14.15 | 17.06 | Surfboard-tg-mixed | 15.204.233.41 |
| 75.99 | vless | 343.0 | 742.4 | 19.84 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 169.40.42.182 |
| 75.79 | vless | 372.6 | 954.3 | 19.15 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 185.95.231.156 |
| 75.73 | hysteria2 | 280.6 | 538.9 | 21.28 | 0.0 | 10.0 | 10.0 | 18.02 | Au1rxx-base64 | 66.94.121.46 |
| 75.13 | vless | 336.2 | 835.2 | 20.0 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 195.123.235.177 |
| 75.1 | vless | 386.0 | 981.8 | 18.84 | 0.0 | 10.0 | 8.62 | 18.02 | Au1rxx-base64 | 169.40.42.75 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | 0.87 | 284 | 1623 | prefer |
| Surfboard-tg-mixed | 0.832 | 0.756 | 135 | 7444 | prefer |
| mheidari-all | 0.821 | 0.75 | 56 | 15903 | prefer |
| ermaozi | 0.715 | 0.706 | 51 | 417 | prefer |
| ermaozi-get_subscribe | 0.617 | 0.632 | 19 | 444 | observe |
| DeltaKronecker-all | 0.563 | 0.483 | 58 | 5972 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 131 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 7910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8753 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6094 | observe |
| barry-far-vless | 0.255 | None | 0 | 6310 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 31 |
| 204 | ProxyError | - | 26 |
| speed | ClientOSError | - | 20 |
| geo | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 14 |
| speed | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

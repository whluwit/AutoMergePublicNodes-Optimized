# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 11:12:27 |
| 运行耗时 | 577.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96052 |
| 去重后节点 | 26933 |
| TCP 可达 | 3000 |
| 真实可用 | 352 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26933 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 44.5 |
| probe | 240.1 |
| real_test | 208.2 |
| generate | 78.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57200 |
| vmess | 16926 |
| shadowsocks | 11854 |
| trojan | 8409 |
| hysteria2 | 1215 |
| http | 173 |
| shadowsocksr | 165 |
| socks | 63 |
| anytls | 24 |
| hysteria | 17 |
| tuic | 6 |

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
| 79.95 | shadowsocks | 254.1 | 627.6 | 21.9 | 0.0 | 10.0 | 13.43 | 18.62 | Surfboard-tg-mixed | 156.146.38.169 |
| 79.14 | shadowsocks | 240.8 | 607.8 | 22.2 | 0.0 | 8.41 | 13.43 | 19.1 | Au1rxx-base64 | 156.146.38.170 |
| 78.9 | shadowsocks | 251.3 | 631.5 | 21.96 | 0.0 | 8.41 | 13.43 | 19.1 | Au1rxx-base64 | 156.146.38.167 |
| 78.3 | shadowsocks | 276.2 | 737.3 | 21.38 | 0.0 | 8.39 | 13.43 | 19.1 | Au1rxx-base64 | 156.146.38.168 |
| 77.09 | shadowsocks | 286.1 | 696.8 | 21.16 | 0.0 | 8.41 | 13.43 | 19.1 | Au1rxx-base64 | 37.19.198.160 |
| 76.62 | shadowsocks | 286.9 | 698.9 | 21.14 | 0.0 | 8.41 | 13.43 | 19.1 | Au1rxx-base64 | 37.19.198.244 |
| 75.29 | shadowsocks | 322.7 | 714.3 | 20.31 | 0.0 | 10.0 | 13.43 | 18.62 | Surfboard-tg-mixed | 193.151.163.18 |
| 75.29 | trojan | 464.1 | 1263.7 | 17.03 | 0.0 | 8.43 | 13.73 | 19.1 | Au1rxx-base64 | 66.23.203.21 |
| 74.81 | vless | 295.8 | 749.4 | 20.93 | 0.0 | 7.91 | 7.87 | 19.1 | Au1rxx-base64 | us-4bf85a22b1.shamanapp.online |
| 74.72 | hysteria2 | 264.5 | 682.9 | 21.66 | 0.0 | 8.41 | 12.69 | 19.1 | Au1rxx-base64 | 129.213.91.185 |
| 74.2 | vless | 331.1 | 745.3 | 20.11 | 0.0 | 10.0 | 7.87 | 19.1 | Au1rxx-base64 | 159.89.87.21 |
| 74.13 | vless | 344.5 | 737.7 | 19.8 | 0.0 | 10.0 | 7.87 | 19.1 | Au1rxx-base64 | 167.17.69.171 |
| 73.57 | vless | 318.3 | 666.1 | 20.41 | 0.0 | 10.0 | 7.87 | 19.1 | Au1rxx-base64 | 45.63.53.81 |
| 72.84 | vless | 337.9 | 797.7 | 19.95 | 0.0 | 10.0 | 7.87 | 18.62 | Surfboard-tg-mixed | 195.123.235.177 |
| 72.62 | vless | 287.3 | 727.2 | 21.13 | 0.0 | 10.0 | 7.87 | 18.62 | Surfboard-tg-mixed | 147.45.60.160 |
| 72.4 | shadowsocks | 408.5 | 1027.5 | 18.32 | 0.0 | 8.39 | 13.43 | 19.1 | Au1rxx-base64 | 45.86.51.18 |
| 72.39 | shadowsocks | 397.6 | 961.1 | 18.57 | 0.0 | 10.0 | 13.43 | 18.62 | Surfboard-tg-mixed | 193.151.160.9 |
| 72.38 | shadowsocks | 395.9 | 1011.1 | 18.61 | 0.0 | 8.39 | 13.43 | 19.1 | Au1rxx-base64 | 185.215.132.18 |
| 72.2 | vless | 347.7 | 846.2 | 19.73 | 0.0 | 10.0 | 7.87 | 19.1 | Au1rxx-base64 | 69.48.201.136 |
| 72.2 | vless | 372.5 | 821.1 | 19.15 | 0.0 | 10.0 | 7.87 | 19.1 | Au1rxx-base64 | 169.40.42.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.866 | 0.796 | 54 | 23726 | prefer |
| Au1rxx-base64 | 0.846 | 0.787 | 258 | 1528 | prefer |
| Surfboard-tg-mixed | 0.766 | 0.69 | 100 | 6977 | prefer |
| ermaozi-get_subscribe | 0.592 | 0.575 | 40 | 516 | observe |
| zhangkai | 0.592 | 0.6 | 20 | 31 | observe |
| DeltaKronecker-all | 0.3 | 0.4 | 5 | 4067 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7465 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10264 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5462 | observe |
| barry-far-vless | 0.255 | None | 0 | 5763 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 27 |
| cn-block | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 19 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| geo | ClientOSError | - | 10 |
| geo | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

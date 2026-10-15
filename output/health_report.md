# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 21:04:25 |
| 运行耗时 | 745.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99871 |
| 去重后节点 | 27648 |
| TCP 可达 | 3000 |
| 真实可用 | 372 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27648 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.5 |
| tcp | 49.2 |
| probe | 330.0 |
| real_test | 288.5 |
| generate | 72.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58813 |
| vmess | 16516 |
| shadowsocks | 11996 |
| trojan | 10423 |
| hysteria2 | 1206 |
| http | 649 |
| shadowsocksr | 161 |
| socks | 57 |
| anytls | 27 |
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
| 79.15 | hysteria2 | 295.1 | 722.4 | 20.95 | 0.0 | 10.0 | 13.12 | 16.58 | Au1rxx-base64 | 129.213.91.185 |
| 78.09 | shadowsocks | 238.9 | 626.5 | 22.25 | 0.0 | 10.0 | 13.26 | 16.58 | Au1rxx-base64 | 156.146.38.167 |
| 77.35 | shadowsocks | 270.7 | 721.1 | 21.51 | 0.0 | 10.0 | 13.26 | 16.58 | Au1rxx-base64 | 156.146.38.168 |
| 77.22 | vless | 257.1 | 665.0 | 21.83 | 0.0 | 10.0 | 8.81 | 16.58 | Au1rxx-base64 | 147.45.60.160 |
| 73.05 | shadowsocks | 324.3 | 758.0 | 20.27 | 0.0 | 10.0 | 13.26 | 16.58 | Au1rxx-base64 | 37.19.198.236 |
| 73.0 | shadowsocks | 333.0 | 763.0 | 20.07 | 0.0 | 10.0 | 13.26 | 16.58 | Au1rxx-base64 | 37.19.198.160 |
| 72.64 | shadowsocks | 345.8 | 812.6 | 19.77 | 0.0 | 10.0 | 13.26 | 16.58 | Au1rxx-base64 | 37.19.198.243 |
| 72.55 | shadowsocks | 232.3 | 617.8 | 22.4 | 0.0 | 10.0 | 13.26 | 16.58 | Au1rxx-base64 | 156.146.38.169 |
| 71.99 | vless | 314.7 | 669.6 | 20.49 | 0.0 | 10.0 | 8.81 | 16.58 | Au1rxx-base64 | 195.211.98.43 |
| 71.7 | vless | 323.6 | 683.4 | 20.29 | 0.0 | 10.0 | 8.81 | 16.58 | Au1rxx-base64 | 195.123.235.183 |
| 71.55 | shadowsocks | 318.6 | 313.6 | 20.4 | 3.24 | 9.69 | 13.26 | 16.58 | Au1rxx-base64 | 149.22.87.204 |
| 71.43 | trojan | 316.9 | 825.9 | 20.44 | 0.0 | 10.0 | 8.41 | 16.58 | Au1rxx-base64 | 66.23.203.21 |
| 70.66 | vless | 348.4 | 744.8 | 19.71 | 0.0 | 10.0 | 8.81 | 16.58 | Au1rxx-base64 | 167.17.69.171 |
| 70.57 | shadowsocks | 334.5 | 672.3 | 20.04 | 0.0 | 10.0 | 13.26 | 16.58 | Au1rxx-base64 | 149.22.95.183 |
| 70.19 | vless | 332.7 | 643.2 | 20.08 | 0.0 | 10.0 | 8.81 | 16.58 | Au1rxx-base64 | 44.248.233.99 |
| 70.15 | hysteria2 | 406.3 | 740.4 | 18.37 | 0.0 | 9.74 | 13.12 | 16.58 | Au1rxx-base64 | 62.210.124.146 |
| 68.84 | shadowsocks | 337.6 | 374.5 | 19.96 | 0.96 | 9.67 | 13.26 | 16.58 | Au1rxx-base64 | 149.22.87.240 |
| 68.7 | shadowsocks | 340.2 | 371.0 | 19.9 | 1.09 | 9.5 | 13.26 | 16.58 | Au1rxx-base64 | 149.22.87.241 |
| 68.68 | vless | 476.9 | 1166.9 | 16.74 | 0.0 | 10.0 | 8.81 | 16.58 | Au1rxx-base64 | 185.95.231.156 |
| 68.61 | vless | 421.3 | 934.3 | 18.03 | 0.0 | 10.0 | 8.81 | 16.58 | Au1rxx-base64 | 159.89.87.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.9 | 0.829 | 391 | 1827 | prefer |
| mheidari-all | 0.745 | 0.765 | 17 | 24072 | prefer |
| Surfboard-tg-mixed | 0.507 | 0.75 | 8 | 7281 | observe |
| ermaozi | 0.385 | 0.354 | 65 | 659 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 89 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9885 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5707 | observe |
| barry-far-vless | 0.255 | None | 0 | 5957 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4235 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| DeltaKronecker-all | 0.252 | 0.148 | 27 | 5147 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 45 |
| 204 | TimeoutError | - | 29 |
| speed | TimeoutError | - | 14 |
| geo | ClientOSError | - | 11 |
| speed | ClientOSError | - | 10 |
| geo | TimeoutError | - | 10 |
| cn-block | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 12:05:24 |
| 运行耗时 | 597.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 95360 |
| 去重后节点 | 26130 |
| TCP 可达 | 3000 |
| 真实可用 | 350 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26130 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.6 |
| tcp | 44.5 |
| probe | 255.8 |
| real_test | 210.2 |
| generate | 81.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55510 |
| vmess | 16622 |
| shadowsocks | 11638 |
| trojan | 8982 |
| hysteria2 | 1554 |
| http | 766 |
| shadowsocksr | 172 |
| socks | 64 |
| anytls | 29 |
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
| 81.54 | hysteria2 | 289.4 | 706.6 | 21.08 | 0.0 | 10.0 | 13.24 | 18.72 | Au1rxx-base64 | 129.213.91.185 |
| 79.76 | hysteria2 | 322.3 | 552.0 | 20.32 | 0.0 | 9.72 | 13.24 | 18.72 | Au1rxx-base64 | 66.94.121.46 |
| 79.15 | shadowsocks | 309.3 | 758.9 | 20.62 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 37.19.198.160 |
| 77.59 | shadowsocks | 246.8 | 615.5 | 22.06 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 156.146.38.167 |
| 77.52 | shadowsocks | 250.2 | 616.3 | 21.99 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 156.146.38.170 |
| 76.79 | shadowsocks | 281.7 | 716.3 | 21.26 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 156.146.38.168 |
| 75.41 | shadowsocks | 306.5 | 750.5 | 20.68 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 37.19.198.243 |
| 75.25 | vless | 345.2 | 763.4 | 19.79 | 0.0 | 10.0 | 9.3 | 18.72 | Au1rxx-base64 | 167.17.69.171 |
| 75.09 | trojan | 397.3 | 983.4 | 18.58 | 0.0 | 10.0 | 13.12 | 18.72 | Au1rxx-base64 | 69.164.240.85 |
| 75.01 | shadowsocks | 320.2 | 645.4 | 20.37 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 149.22.95.183 |
| 74.99 | shadowsocks | 380.7 | 967.2 | 18.97 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 15.204.233.41 |
| 74.92 | vless | 295.2 | 597.6 | 20.94 | 0.0 | 10.0 | 9.3 | 18.72 | Au1rxx-base64 | 45.63.53.81 |
| 74.8 | shadowsocks | 285.6 | 579.7 | 21.17 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 173.244.56.6 |
| 74.61 | hysteria2 | 272.6 | 596.6 | 21.47 | 0.0 | 10.0 | 13.24 | 18.72 | Au1rxx-base64 | 179.255.104.98 |
| 74.56 | shadowsocks | 238.9 | 600.6 | 22.25 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 156.146.38.169 |
| 74.35 | vless | 422.7 | 964.9 | 17.99 | 0.0 | 10.0 | 9.3 | 18.72 | Au1rxx-base64 | 185.95.231.156 |
| 74.11 | vless | 289.0 | 725.8 | 21.09 | 0.0 | 10.0 | 9.3 | 18.72 | Au1rxx-base64 | 162.35.126.130 |
| 73.63 | vless | 372.5 | 736.4 | 19.16 | 0.0 | 10.0 | 9.3 | 18.72 | Au1rxx-base64 | 169.40.42.231 |
| 73.47 | vless | 381.5 | 907.4 | 18.95 | 0.0 | 10.0 | 9.3 | 18.72 | Au1rxx-base64 | 159.89.87.21 |
| 73.07 | shadowsocks | 313.0 | 726.6 | 20.53 | 0.0 | 10.0 | 13.81 | 18.72 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | 0.803 | 361 | 1716 | prefer |
| Surfboard-tg-mixed | 0.552 | 0.471 | 51 | 6867 | observe |
| mheidari-all | 0.543 | 0.615 | 13 | 23446 | observe |
| ermaozi | 0.459 | 0.429 | 63 | 696 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7331 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9767 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5407 | observe |
| barry-far-vless | 0.255 | None | 0 | 5622 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1717 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 43 |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 18 |
| geo | ClientOSError | - | 17 |
| speed | ClientOSError | - | 13 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 04:22:17 |
| 运行耗时 | 741.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99282 |
| 去重后节点 | 27674 |
| TCP 可达 | 3000 |
| 真实可用 | 240 |
| Verified 输出 | 240 |
| Global 输出 | 249 |
| All 输出 | 27674 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 46.5 |
| probe | 269.1 |
| real_test | 340.8 |
| generate | 75.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58370 |
| vmess | 15776 |
| shadowsocks | 11945 |
| trojan | 10699 |
| hysteria2 | 1507 |
| http | 676 |
| shadowsocksr | 167 |
| socks | 88 |
| anytls | 29 |
| hysteria | 16 |
| tuic | 9 |

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
| 79.69 | hysteria2 | 254.7 | 698.1 | 21.88 | 0.0 | 10.0 | 13.33 | 18.58 | mheidari-all | 159.223.157.129 |
| 77.18 | vless | 262.5 | 744.2 | 21.7 | 0.0 | 10.0 | 11.84 | 18.64 | Surfboard-tg-mixed | 47.253.226.114 |
| 75.99 | hysteria2 | 327.3 | 306.1 | 20.2 | 3.52 | 8.83 | 13.33 | 18.24 | Au1rxx-base64 | open.2ml.bid |
| 75.85 | shadowsocks | 354.9 | 935.6 | 19.56 | 0.0 | 10.0 | 12.15 | 18.64 | Surfboard-tg-mixed | 51.222.141.125 |
| 75.75 | hysteria2 | 330.6 | 304.4 | 20.12 | 3.59 | 8.76 | 13.33 | 18.24 | Au1rxx-base64 | vp3.yysyy.online |
| 74.83 | hysteria2 | 320.7 | 301.6 | 20.35 | 3.69 | 9.37 | 13.33 | 18.24 | Au1rxx-base64 | 45.32.10.7 |
| 74.5 | hysteria2 | 400.1 | 632.2 | 18.52 | 0.0 | 9.74 | 13.33 | 18.24 | Au1rxx-base64 | 66.94.121.46 |
| 74.17 | hysteria2 | 410.7 | 853.4 | 18.27 | 0.0 | 10.0 | 13.33 | 18.64 | Surfboard-tg-mixed | 130.49.161.70 |
| 73.91 | hysteria2 | 395.6 | 741.5 | 18.62 | 0.0 | 9.98 | 13.33 | 18.58 | mheidari-all | 217.60.33.215 |
| 73.75 | hysteria2 | 391.1 | 671.8 | 18.72 | 0.0 | 10.0 | 13.33 | 18.58 | mheidari-all | 62.210.124.146 |
| 73.64 | vless | 373.1 | 840.9 | 19.14 | 0.0 | 10.0 | 11.84 | 18.58 | mheidari-all | 172.67.152.162 |
| 73.5 | hysteria2 | 389.5 | 738.7 | 18.76 | 0.0 | 9.86 | 13.33 | 18.24 | Au1rxx-base64 | 45.192.12.93 |
| 72.89 | trojan | 440.4 | 767.9 | 17.58 | 0.0 | 10.0 | 14.67 | 18.64 | Surfboard-tg-mixed | 45.205.0.6 |
| 72.73 | trojan | 445.2 | 777.6 | 17.47 | 0.0 | 10.0 | 14.67 | 18.64 | Surfboard-tg-mixed | 188.114.98.0 |
| 72.71 | trojan | 448.8 | 788.8 | 17.39 | 0.0 | 10.0 | 14.67 | 18.64 | Surfboard-tg-mixed | 104.17.121.71 |
| 72.66 | hysteria2 | 449.6 | 911.4 | 17.37 | 0.0 | 10.0 | 13.33 | 18.64 | Surfboard-tg-mixed | 91.196.32.163 |
| 72.36 | trojan | 455.3 | 982.5 | 17.24 | 0.0 | 10.0 | 14.67 | 18.58 | mheidari-all | 34.94.125.227 |
| 72.24 | hysteria2 | 458.3 | 924.7 | 17.17 | 0.0 | 10.0 | 13.33 | 18.58 | mheidari-all | 64.188.98.171 |
| 72.18 | trojan | 454.4 | 783.8 | 17.26 | 0.0 | 10.0 | 14.67 | 18.64 | Surfboard-tg-mixed | 165.215.250.14 |
| 72.18 | shadowsocks | 480.6 | 1128.5 | 16.65 | 0.0 | 10.0 | 12.15 | 18.64 | Surfboard-tg-mixed | 51.222.136.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.974 | 39 | 1821 | prefer |
| Surfboard-tg-mixed | 0.679 | 0.6 | 150 | 7193 | observe |
| ermaozi-get_subscribe | 0.524 | 0.5 | 28 | 592 | observe |
| DeltaKronecker-all | 0.398 | 0.3 | 20 | 5344 | observe |
| ermaozi | 0.397 | 0.361 | 36 | 715 | observe |
| mheidari-all | 0.361 | 0.279 | 276 | 23407 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7663 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9572 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5725 | observe |
| barry-far-vless | 0.255 | None | 0 | 5963 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 149 |
| speed | TimeoutError | - | 45 |
| 204 | ProxyError | - | 40 |
| geo | ClientOSError | - | 28 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 240 | - |
| global | False | 300 | 249 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

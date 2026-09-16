# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 10:54:19 |
| 运行耗时 | 609.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87860 |
| 去重后节点 | 24299 |
| TCP 可达 | 3000 |
| 真实可用 | 471 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24299 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.5 |
| tcp | 41.1 |
| probe | 233.7 |
| real_test | 256.2 |
| generate | 71.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52984 |
| vmess | 13621 |
| shadowsocks | 10049 |
| trojan | 8796 |
| hysteria2 | 1551 |
| http | 653 |
| shadowsocksr | 129 |
| socks | 62 |
| hysteria | 8 |
| tuic | 5 |
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
| 80.1 | shadowsocks | 220.1 | 595.3 | 22.68 | 0.0 | 8.77 | 13.77 | 18.88 | Au1rxx-base64 | 198.98.53.130 |
| 78.01 | hysteria2 | 243.5 | 678.0 | 22.14 | 0.0 | 10.0 | 13.33 | 13.64 | mheidari-all | 159.223.157.129 |
| 77.62 | shadowsocks | 309.4 | 861.1 | 20.61 | 0.0 | 8.86 | 13.77 | 18.88 | Au1rxx-base64 | 38.180.135.156 |
| 77.56 | vless | 231.4 | 598.0 | 22.42 | 0.0 | 8.87 | 7.39 | 18.88 | Au1rxx-base64 | 195.123.235.177 |
| 76.92 | shadowsocks | 236.3 | 655.5 | 22.31 | 0.0 | 8.96 | 13.77 | 18.88 | Au1rxx-base64 | 37.19.198.244 |
| 76.82 | vless | 259.5 | 641.8 | 21.77 | 0.0 | 8.78 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.35 |
| 76.79 | vless | 260.7 | 636.2 | 21.74 | 0.0 | 8.78 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.15 |
| 76.78 | vless | 261.4 | 693.1 | 21.73 | 0.0 | 8.78 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.104 |
| 76.69 | vless | 263.9 | 700.2 | 21.67 | 0.0 | 8.75 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.184 |
| 76.3 | shadowsocks | 283.1 | 644.7 | 21.22 | 0.0 | 8.84 | 13.77 | 18.88 | Au1rxx-base64 | 156.146.38.170 |
| 76.08 | http | 254.9 | 679.5 | 21.88 | 0.0 | 10.0 | 11.56 | 15.14 | ermaozi | 147.182.216.4 |
| 75.98 | vless | 295.9 | 745.9 | 20.93 | 0.0 | 8.78 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.163 |
| 75.8 | shadowsocks | 232.8 | 638.1 | 22.39 | 0.0 | 10.0 | 13.77 | 13.64 | mheidari-all | 37.19.198.236 |
| 75.8 | vless | 305.2 | 825.3 | 20.71 | 0.0 | 8.82 | 7.39 | 18.88 | Au1rxx-base64 | 167.17.69.171 |
| 75.7 | vless | 306.7 | 819.7 | 20.68 | 0.0 | 8.75 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.133 |
| 75.64 | vless | 310.1 | 781.1 | 20.6 | 0.0 | 8.77 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.235 |
| 75.51 | vless | 317.8 | 817.0 | 20.42 | 0.0 | 8.82 | 7.39 | 18.88 | Au1rxx-base64 | 66.70.179.198 |
| 75.24 | vless | 258.3 | 677.5 | 21.8 | 0.0 | 8.78 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.223 |
| 74.97 | vless | 341.1 | 865.0 | 19.88 | 0.0 | 8.82 | 7.39 | 18.88 | Au1rxx-base64 | 216.152.147.28 |
| 74.97 | vless | 341.8 | 932.7 | 19.87 | 0.0 | 8.83 | 7.39 | 18.88 | Au1rxx-base64 | 169.40.42.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | 0.848 | 303 | 1704 | prefer |
| DeltaKronecker-all | 0.818 | 0.75 | 40 | 6081 | prefer |
| ermaozi | 0.78 | 0.774 | 53 | 407 | prefer |
| mheidari-all | 0.776 | 0.701 | 67 | 16003 | prefer |
| Surfboard-tg-mixed | 0.76 | 0.683 | 126 | 7446 | prefer |
| ermaozi-get_subscribe | 0.432 | 0.421 | 19 | 438 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 8003 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9062 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6044 | observe |
| barry-far-vless | 0.255 | None | 0 | 6340 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4206 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 28 |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 14 |
| speed | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 10 |
| geo | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

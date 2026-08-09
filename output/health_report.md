# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 18:36:06 |
| 运行耗时 | 221.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86004 |
| 去重后节点 | 23964 |
| TCP 可达 | 3000 |
| 真实可用 | 456 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23964 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 35.7 |
| probe | 48.4 |
| real_test | 99.8 |
| generate | 30.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51410 |
| vmess | 13182 |
| trojan | 10083 |
| shadowsocks | 9628 |
| hysteria2 | 1482 |
| socks | 69 |
| shadowsocksr | 68 |
| http | 33 |
| anytls | 26 |
| hysteria | 15 |
| tuic | 8 |

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
| 82.57 | hysteria2 | 278.9 | 664.1 | 21.32 | 0.0 | 9.03 | 13.7 | 19.62 | Au1rxx-base64 | 159.223.157.129 |
| 82.5 | hysteria2 | 289.5 | 725.2 | 21.08 | 0.0 | 9.1 | 13.7 | 19.62 | Au1rxx-base64 | 138.124.68.188 |
| 80.17 | hysteria2 | 298.5 | 729.1 | 20.87 | 0.0 | 6.98 | 13.7 | 19.62 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 78.66 | shadowsocks | 304.1 | 649.3 | 20.74 | 0.0 | 10.0 | 13.32 | 19.62 | Au1rxx-base64 | 37.19.198.160 |
| 77.69 | shadowsocks | 286.7 | 668.3 | 21.14 | 0.0 | 10.0 | 13.32 | 19.62 | Au1rxx-base64 | 37.19.198.244 |
| 77.59 | vless | 367.2 | 867.9 | 19.28 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 88.218.44.4 |
| 77.2 | vless | 278.8 | 553.1 | 21.32 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 179.255.148.66 |
| 77.01 | vless | 378.3 | 848.7 | 19.02 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 169.40.42.16 |
| 76.95 | shadowsocks | 295.6 | 720.2 | 20.93 | 0.0 | 9.17 | 13.32 | 19.62 | Au1rxx-base64 | 37.19.198.236 |
| 76.69 | vless | 347.8 | 713.5 | 19.73 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 169.40.42.184 |
| 76.66 | vless | 294.2 | 592.8 | 20.97 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 167.17.68.205 |
| 76.35 | vless | 297.3 | 585.2 | 20.89 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 186.241.106.97 |
| 76.15 | vless | 279.6 | 533.8 | 21.31 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 70.39.198.183 |
| 76.13 | trojan | 251.0 | 585.6 | 21.97 | 0.0 | 10.0 | 12.98 | 19.62 | Au1rxx-base64 | 64.94.95.115 |
| 76.08 | shadowsocks | 303.6 | 573.8 | 20.75 | 0.0 | 10.0 | 13.32 | 19.62 | Au1rxx-base64 | 173.244.56.6 |
| 76.05 | trojan | 273.3 | 691.9 | 21.45 | 0.0 | 10.0 | 12.98 | 19.62 | Au1rxx-base64 | 64.94.95.117 |
| 75.95 | vless | 309.1 | 565.3 | 20.62 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 172.247.109.66 |
| 75.63 | vless | 372.9 | 940.4 | 19.15 | 0.0 | 9.01 | 10.54 | 19.62 | Au1rxx-base64 | 216.152.147.28 |
| 75.3 | shadowsocks | 291.3 | 575.3 | 21.03 | 0.0 | 9.17 | 13.32 | 19.62 | Au1rxx-base64 | 149.22.95.183 |
| 75.28 | vless | 275.3 | 570.5 | 21.4 | 0.0 | 10.0 | 10.54 | 19.62 | Au1rxx-base64 | 179.253.240.24 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | 0.927 | 382 | 1688 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.753 | 0.677 | 99 | 6583 | prefer |
| mheidari-all | 0.334 | 0.246 | 57 | 20206 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 107 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5505 | observe |
| Epodonios-all | 0.255 | None | 0 | 7179 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7585 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5399 | observe |
| barry-far-vless | 0.255 | None | 0 | 5713 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5189 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1688 | observe |
| nscl5-all | 0.235 | None | 0 | 1506 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 31 |
| 204 | TimeoutError | - | 25 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 7 |
| cn-block | TimeoutError | - | 5 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

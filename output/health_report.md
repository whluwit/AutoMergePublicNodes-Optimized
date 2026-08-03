# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 19:29:10 |
| 运行耗时 | 273.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 84760 |
| 去重后节点 | 25157 |
| TCP 可达 | 3000 |
| 真实可用 | 579 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25157 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 37.3 |
| probe | 59.5 |
| real_test | 138.5 |
| generate | 30.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52013 |
| vmess | 12779 |
| shadowsocks | 10399 |
| trojan | 8583 |
| hysteria2 | 742 |
| http | 75 |
| socks | 74 |
| shadowsocksr | 73 |
| hysteria | 11 |
| tuic | 6 |
| anytls | 5 |

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
| 79.14 | hysteria2 | 230.4 | 643.4 | 22.44 | 0.0 | 10.0 | 11.84 | 15.96 | Au1rxx-base64 | 159.223.157.129 |
| 78.61 | trojan | 243.3 | 664.8 | 22.15 | 0.0 | 10.0 | 13.5 | 15.96 | Au1rxx-base64 | 153.75.250.171 |
| 77.08 | vless | 245.8 | 648.5 | 22.09 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 167.17.69.171 |
| 76.67 | shadowsocks | 227.1 | 615.0 | 22.52 | 0.0 | 10.0 | 12.19 | 15.96 | Au1rxx-base64 | 37.19.198.243 |
| 76.37 | shadowsocks | 239.9 | 666.4 | 22.22 | 0.0 | 10.0 | 12.19 | 15.96 | Au1rxx-base64 | 37.19.198.244 |
| 75.93 | vless | 273.1 | 671.1 | 21.46 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 216.152.147.28 |
| 74.08 | vless | 288.8 | 730.8 | 21.09 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 159.195.12.98 |
| 73.99 | vless | 377.7 | 898.1 | 19.03 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 169.40.42.212 |
| 73.9 | shadowsocks | 325.3 | 855.9 | 20.25 | 0.0 | 10.0 | 12.19 | 15.96 | Au1rxx-base64 | 68.168.222.210 |
| 73.89 | hysteria2 | 245.5 | 684.4 | 22.09 | 0.0 | 10.0 | 11.84 | 15.96 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 73.82 | hysteria2 | 248.9 | 690.5 | 22.02 | 0.0 | 10.0 | 11.84 | 15.96 | Au1rxx-base64 | 138.124.68.188 |
| 73.6 | vless | 348.5 | 977.5 | 19.71 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 45.138.100.226 |
| 73.14 | trojan | 301.2 | 640.5 | 20.81 | 0.0 | 10.0 | 13.5 | 15.96 | Au1rxx-base64 | 163.245.196.68 |
| 72.56 | shadowsocks | 282.6 | 646.7 | 21.24 | 0.0 | 10.0 | 12.19 | 15.96 | Au1rxx-base64 | 156.146.38.167 |
| 72.39 | vless | 326.5 | 821.4 | 20.22 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 169.40.42.75 |
| 72.14 | shadowsocks | 276.1 | 634.5 | 21.39 | 0.0 | 10.0 | 12.19 | 15.96 | Au1rxx-base64 | 156.146.38.168 |
| 72.12 | vless | 243.9 | 665.8 | 22.13 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 147.182.212.232 |
| 71.93 | vless | 347.6 | 938.4 | 19.73 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 169.40.42.133 |
| 71.75 | vless | 290.6 | 798.0 | 21.05 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 88.218.44.4 |
| 71.54 | vless | 321.5 | 596.8 | 20.34 | 0.0 | 10.0 | 9.03 | 15.96 | Au1rxx-base64 | 162.159.0.8 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 67 | 92 | prefer |
| Au1rxx-base64 | 0.817 | 0.749 | 553 | 1719 | prefer |
| Surfboard-tg-mixed | 0.735 | 0.667 | 27 | 5168 | prefer |
| mheidari-all | 0.641 | 0.562 | 137 | 18750 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 5127 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 57 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5285 | observe |
| Epodonios-all | 0.255 | None | 0 | 5757 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6825 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4147 | observe |
| barry-far-vless | 0.255 | None | 0 | 4498 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5152 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1719 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 84 |
| 204 | ProxyError | - | 28 |
| speed | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 21 |
| geo | ClientOSError | - | 15 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 14 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

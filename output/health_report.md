# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 08:21:41 |
| 运行耗时 | 287.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78399 |
| 去重后节点 | 22761 |
| TCP 可达 | 3000 |
| 真实可用 | 537 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22761 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 31.7 |
| probe | 58.5 |
| real_test | 147.1 |
| generate | 43.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45952 |
| vmess | 11320 |
| shadowsocks | 10448 |
| trojan | 9828 |
| hysteria2 | 535 |
| http | 121 |
| shadowsocksr | 75 |
| socks | 61 |
| anytls | 26 |
| tuic | 19 |
| hysteria | 14 |

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
| 83.58 | hysteria2 | 262.9 | 664.6 | 21.69 | 0.0 | 10.0 | 13.33 | 19.66 | Au1rxx-base64 | 159.223.157.129 |
| 82.61 | hysteria2 | 272.4 | 699.5 | 21.47 | 0.0 | 9.15 | 13.33 | 19.66 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.14 | shadowsocks | 260.9 | 658.3 | 21.74 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 37.19.198.236 |
| 80.78 | shadowsocks | 276.3 | 698.9 | 21.38 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 37.19.198.243 |
| 80.66 | shadowsocks | 281.7 | 718.2 | 21.26 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 37.19.198.244 |
| 80.18 | trojan | 278.8 | 630.8 | 21.32 | 0.0 | 10.0 | 14.13 | 19.66 | Au1rxx-base64 | 163.245.196.68 |
| 80.07 | shadowsocks | 273.6 | 650.1 | 21.44 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 156.146.38.167 |
| 79.46 | shadowsocks | 309.3 | 765.4 | 20.62 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 156.146.38.170 |
| 79.2 | shadowsocks | 323.2 | 828.4 | 20.3 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 68.168.114.226 |
| 79.04 | shadowsocks | 329.9 | 854.0 | 20.14 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 185.196.61.82 |
| 78.6 | shadowsocks | 349.1 | 863.2 | 19.7 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 185.232.22.28 |
| 78.29 | shadowsocks | 254.4 | 631.3 | 21.89 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 37.19.198.160 |
| 78.25 | shadowsocks | 339.8 | 853.9 | 19.91 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 185.232.22.18 |
| 78.17 | shadowsocks | 280.6 | 653.6 | 21.28 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 156.146.38.169 |
| 77.54 | http | 287.2 | 685.1 | 21.13 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.23 |
| 77.26 | shadowsocks | 372.2 | 898.1 | 19.16 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 146.70.34.226 |
| 76.57 | http | 333.2 | 830.4 | 20.06 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.50 |
| 76.52 | http | 326.1 | 796.5 | 20.23 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.49 |
| 76.48 | http | 339.9 | 830.0 | 19.91 | 0.0 | 10.0 | 14.79 | 19.78 | zhangkai | 156.146.59.21 |
| 76.43 | shadowsocks | 359.0 | 866.1 | 19.47 | 0.0 | 10.0 | 13.74 | 19.66 | Au1rxx-base64 | 156.146.38.195 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.998 | 1.0 | 118 | 157 | prefer |
| Au1rxx-base64 | 0.902 | 0.857 | 244 | 1201 | prefer |
| Surfboard-tg-mixed | 0.687 | 0.608 | 166 | 5473 | observe |
| DeltaKronecker-all | 0.412 | 0.331 | 317 | 5759 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5342 | observe |
| Epodonios-all | 0.255 | None | 0 | 6219 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6833 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4282 | observe |
| barry-far-vless | 0.255 | None | 0 | 4657 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5029 | observe |
| mheidari-all | 0.255 | 0.222 | 9 | 16334 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 154 |
| geo | ClientOSError | - | 43 |
| speed | ClientOSError | - | 35 |
| 204 | TimeoutError | - | 24 |
| speed | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-12 14:29:10 |
| 运行耗时 | 884.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 100401 |
| 去重后节点 | 27831 |
| TCP 可达 | 3000 |
| 真实可用 | 485 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27831 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 46.9 |
| probe | 347.1 |
| real_test | 386.2 |
| generate | 94.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58915 |
| vmess | 16080 |
| shadowsocks | 11791 |
| trojan | 11204 |
| hysteria2 | 1469 |
| http | 651 |
| shadowsocksr | 171 |
| socks | 70 |
| anytls | 26 |
| hysteria | 17 |
| tuic | 7 |

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
| 84.79 | hysteria2 | 250.7 | 705.1 | 21.97 | 0.0 | 10.0 | 14.48 | 19.84 | Au1rxx-base64 | 129.213.91.185 |
| 82.12 | shadowsocks | 264.9 | 716.0 | 21.65 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 37.19.198.244 |
| 82.09 | shadowsocks | 266.0 | 718.4 | 21.62 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 37.19.198.236 |
| 82.04 | shadowsocks | 268.3 | 718.8 | 21.57 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 37.19.198.160 |
| 81.56 | shadowsocks | 267.3 | 673.5 | 21.59 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 140.82.63.79 |
| 81.27 | shadowsocks | 301.6 | 819.0 | 20.8 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 37.19.198.243 |
| 80.7 | hysteria2 | 304.0 | 281.4 | 20.74 | 4.45 | 9.35 | 14.48 | 19.84 | Au1rxx-base64 | 45.32.10.7 |
| 79.95 | shadowsocks | 335.4 | 828.2 | 20.01 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 66.23.205.83 |
| 79.89 | shadowsocks | 282.7 | 657.4 | 21.23 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 156.146.38.167 |
| 79.59 | shadowsocks | 286.1 | 660.5 | 21.15 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 156.146.38.170 |
| 78.69 | hysteria2 | 320.4 | 305.6 | 20.36 | 3.54 | 8.77 | 14.48 | 19.84 | Au1rxx-base64 | vp3.yysyy.online |
| 77.77 | shadowsocks | 281.5 | 645.2 | 21.26 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 156.146.38.168 |
| 76.73 | trojan | 301.9 | 799.0 | 20.79 | 0.0 | 10.0 | 14.1 | 19.84 | Au1rxx-base64 | 69.164.240.85 |
| 75.67 | hysteria2 | 466.0 | 799.1 | 16.99 | 0.0 | 10.0 | 14.48 | 19.84 | Au1rxx-base64 | 66.94.121.46 |
| 75.24 | vless | 365.7 | 999.4 | 19.31 | 0.0 | 10.0 | 6.09 | 19.84 | Au1rxx-base64 | 185.95.231.156 |
| 75.18 | shadowsocks | 327.1 | 919.6 | 20.21 | 0.0 | 10.0 | 14.63 | 19.84 | Au1rxx-base64 | 15.204.233.41 |
| 75.1 | vless | 348.9 | 796.6 | 19.7 | 0.0 | 10.0 | 6.09 | 19.84 | Au1rxx-base64 | 169.40.42.223 |
| 74.6 | vless | 338.7 | 830.4 | 19.94 | 0.0 | 10.0 | 6.09 | 19.84 | Au1rxx-base64 | 169.40.42.15 |
| 74.06 | vless | 287.1 | 631.3 | 21.13 | 0.0 | 10.0 | 6.09 | 19.84 | Au1rxx-base64 | 169.40.42.182 |
| 74.03 | hysteria2 | 463.9 | 892.1 | 17.04 | 0.0 | 10.0 | 14.48 | 19.84 | Au1rxx-base64 | 5.129.235.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | 0.91 | 355 | 1816 | prefer |
| mheidari-all | 0.847 | 0.776 | 58 | 24027 | prefer |
| DeltaKronecker-all | 0.747 | 0.675 | 40 | 5701 | prefer |
| Surfboard-tg-mixed | 0.66 | 0.582 | 110 | 7166 | observe |
| ermaozi | 0.491 | 0.463 | 54 | 675 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5028 | observe |
| Epodonios-all | 0.255 | None | 0 | 7671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9940 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5781 | observe |
| barry-far-vless | 0.255 | None | 0 | 6031 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1816 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 29 |
| cn-block | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 26 |
| geo | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 7 |
| speed | ClientOSError | - | 7 |
| geo | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

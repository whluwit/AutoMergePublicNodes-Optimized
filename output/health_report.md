# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 22:21:20 |
| 运行耗时 | 706.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97852 |
| 去重后节点 | 27615 |
| TCP 可达 | 3000 |
| 真实可用 | 435 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27615 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 47.0 |
| probe | 266.5 |
| real_test | 301.3 |
| generate | 82.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57392 |
| vmess | 15601 |
| shadowsocks | 11880 |
| trojan | 10666 |
| hysteria2 | 1499 |
| http | 505 |
| shadowsocksr | 170 |
| socks | 79 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 13 |

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
| 85.29 | hysteria2 | 239.6 | 239.4 | 22.23 | 6.02 | 9.79 | 14.21 | 19.78 | Au1rxx-base64 | 158.101.148.79 |
| 84.92 | hysteria2 | 252.6 | 618.4 | 21.93 | 0.0 | 10.0 | 14.21 | 19.78 | Au1rxx-base64 | 66.94.121.46 |
| 84.57 | vless | 180.0 | 477.1 | 23.61 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 47.251.108.158 |
| 84.56 | vless | 180.4 | 467.0 | 23.6 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 137.175.82.40 |
| 84.17 | vless | 197.2 | 499.1 | 23.21 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 144.202.126.147 |
| 84.1 | vless | 200.6 | 514.5 | 23.14 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 107.173.237.146 |
| 83.28 | vless | 235.8 | 577.0 | 22.32 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 15.204.97.216 |
| 83.2 | vless | 239.1 | 577.3 | 22.24 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 15.204.97.197 |
| 82.32 | vless | 277.3 | 737.6 | 21.36 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 23.95.222.127 |
| 81.8 | shadowsocks | 211.8 | 530.0 | 22.87 | 0.0 | 10.0 | 13.65 | 19.78 | Au1rxx-base64 | 5.78.51.123 |
| 78.75 | vless | 215.4 | 537.9 | 22.79 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 195.123.240.65 |
| 78.36 | shadowsocks | 252.5 | 611.9 | 21.93 | 0.0 | 10.0 | 13.65 | 19.78 | Au1rxx-base64 | 149.22.95.183 |
| 78.16 | vless | 256.5 | 624.0 | 21.84 | 0.0 | 10.0 | 11.18 | 19.78 | Au1rxx-base64 | 104.17.98.5 |
| 77.38 | shadowsocks | 301.3 | 670.9 | 20.8 | 0.0 | 10.0 | 13.65 | 19.78 | Au1rxx-base64 | 156.146.38.169 |
| 77.33 | shadowsocks | 291.5 | 657.8 | 21.03 | 0.0 | 10.0 | 13.65 | 19.78 | Au1rxx-base64 | 156.146.38.170 |
| 76.63 | shadowsocks | 302.3 | 678.4 | 20.78 | 0.0 | 10.0 | 13.65 | 19.78 | Au1rxx-base64 | 156.146.38.167 |
| 76.51 | shadowsocks | 224.7 | 495.7 | 22.58 | 0.0 | 10.0 | 13.65 | 19.78 | Au1rxx-base64 | 144.48.107.10 |
| 76.43 | hysteria2 | 413.9 | 937.4 | 18.2 | 0.0 | 10.0 | 14.21 | 19.78 | Au1rxx-base64 | 129.213.91.185 |
| 75.9 | shadowsocks | 289.0 | 330.2 | 21.09 | 2.62 | 9.95 | 13.65 | 19.78 | Au1rxx-base64 | 149.22.87.240 |
| 75.53 | trojan | 255.5 | 598.4 | 21.86 | 0.0 | 9.58 | 12.5 | 19.78 | Au1rxx-base64 | alert-titmouse.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | 0.909 | 353 | 1805 | prefer |
| Surfboard-tg-mixed | 0.942 | 0.889 | 27 | 7025 | prefer |
| zhangkai | 0.927 | 1.0 | 19 | 144 | prefer |
| mheidari-all | 0.844 | 0.77 | 87 | 23076 | prefer |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4984 | observe |
| Epodonios-all | 0.255 | None | 0 | 7582 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9986 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5553 | observe |
| barry-far-vless | 0.255 | None | 0 | 5812 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4346 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1805 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| geo | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| 204 | TimeoutError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

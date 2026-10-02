# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 17:28:21 |
| 运行耗时 | 539.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98378 |
| 去重后节点 | 27127 |
| TCP 可达 | 3000 |
| 真实可用 | 338 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27127 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.2 |
| tcp | 47.3 |
| probe | 215.7 |
| real_test | 168.0 |
| generate | 99.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60473 |
| vmess | 15328 |
| shadowsocks | 11486 |
| trojan | 8814 |
| hysteria2 | 1456 |
| http | 522 |
| shadowsocksr | 169 |
| socks | 66 |
| anytls | 40 |
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
| 83.16 | hysteria2 | 246.4 | 637.1 | 22.07 | 0.0 | 10.0 | 14.21 | 17.88 | Au1rxx-base64 | 192.255.128.123 |
| 81.87 | vless | 199.4 | 519.0 | 23.16 | 0.0 | 10.0 | 10.83 | 17.88 | Au1rxx-base64 | 172.235.38.85 |
| 80.78 | hysteria2 | 349.6 | 521.3 | 19.69 | 0.0 | 10.0 | 14.21 | 17.88 | Au1rxx-base64 | 66.94.121.46 |
| 79.93 | shadowsocks | 180.7 | 480.4 | 23.6 | 0.0 | 10.0 | 12.95 | 17.88 | Au1rxx-base64 | 173.234.25.90 |
| 79.69 | shadowsocks | 212.5 | 524.5 | 22.86 | 0.0 | 10.0 | 12.95 | 17.88 | Au1rxx-base64 | 173.244.56.9 |
| 78.9 | vless | 261.5 | 562.7 | 21.72 | 0.0 | 10.0 | 10.83 | 17.88 | Au1rxx-base64 | 23.95.222.127 |
| 78.64 | shadowsocks | 236.2 | 543.4 | 22.31 | 0.0 | 10.0 | 12.95 | 17.88 | Au1rxx-base64 | 108.181.118.10 |
| 78.34 | shadowsocks | 258.6 | 632.3 | 21.79 | 0.0 | 10.0 | 12.95 | 17.6 | mheidari-all | 156.146.38.168 |
| 78.24 | shadowsocks | 253.3 | 649.8 | 21.91 | 0.0 | 10.0 | 12.95 | 17.88 | Au1rxx-base64 | 108.181.0.177 |
| 77.98 | vless | 272.5 | 596.4 | 21.47 | 0.0 | 10.0 | 10.83 | 17.88 | Au1rxx-base64 | 15.204.97.216 |
| 77.15 | shadowsocks | 257.3 | 702.9 | 21.82 | 0.0 | 10.0 | 12.95 | 17.88 | Au1rxx-base64 | 74.201.177.54 |
| 76.89 | hysteria2 | 290.4 | 320.1 | 21.06 | 2.99 | 8.54 | 14.21 | 17.88 | Au1rxx-base64 | open.2ml.bid |
| 76.62 | hysteria2 | 389.8 | 903.0 | 18.75 | 0.0 | 10.0 | 14.21 | 17.88 | Au1rxx-base64 | 159.223.157.129 |
| 76.05 | shadowsocks | 262.5 | 631.9 | 21.7 | 0.0 | 10.0 | 12.95 | 15.68 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.82 | shadowsocks | 237.8 | 573.6 | 22.27 | 0.0 | 10.0 | 12.95 | 17.6 | mheidari-all | 173.244.56.6 |
| 75.74 | shadowsocks | 259.8 | 635.6 | 21.76 | 0.0 | 10.0 | 12.95 | 15.68 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.09 | vless | 336.2 | 754.5 | 20.0 | 0.0 | 10.0 | 10.83 | 17.88 | Au1rxx-base64 | 79.141.172.154 |
| 75.08 | shadowsocks | 280.1 | 284.7 | 21.29 | 4.32 | 9.91 | 12.95 | 17.88 | Au1rxx-base64 | 149.22.87.241 |
| 74.89 | vless | 285.0 | 774.5 | 21.18 | 0.0 | 10.0 | 10.83 | 17.88 | Au1rxx-base64 | 107.173.237.146 |
| 74.78 | hysteria2 | 249.4 | 289.0 | 22.0 | 4.16 | 5.45 | 14.21 | 17.88 | Au1rxx-base64 | open.w2m.ink |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.929 | 0.862 | 275 | 1750 | prefer |
| Surfboard-tg-mixed | 0.819 | 0.75 | 44 | 7244 | prefer |
| mheidari-all | 0.772 | 0.697 | 76 | 22996 | prefer |
| ermaozi | 0.506 | 0.48 | 25 | 620 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7739 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9417 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6150 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1750 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 29 |
| 204 | TimeoutError | - | 18 |
| 204 | ProxyConnectionError | - | 13 |
| speed | TimeoutError | - | 10 |
| speed | ClientOSError | - | 6 |
| 204 | ProxyError | - | 6 |
| geo | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

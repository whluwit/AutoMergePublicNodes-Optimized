# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-31 13:56:45 |
| 运行耗时 | 217.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78379 |
| 去重后节点 | 22732 |
| TCP 可达 | 3000 |
| 真实可用 | 403 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22732 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 32.8 |
| probe | 53.0 |
| real_test | 105.4 |
| generate | 19.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45405 |
| vmess | 11965 |
| shadowsocks | 10304 |
| trojan | 9840 |
| hysteria2 | 578 |
| http | 98 |
| shadowsocksr | 76 |
| socks | 57 |
| anytls | 26 |
| tuic | 16 |
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
| 79.46 | http | 430.9 | 1209.8 | 17.8 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.209 |
| 79.35 | http | 435.7 | 1227.3 | 17.69 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.204 |
| 79.33 | http | 436.9 | 1226.2 | 17.67 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.196 |
| 79.23 | http | 440.8 | 1243.2 | 17.57 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.217 |
| 79.17 | http | 443.6 | 1241.5 | 17.51 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.199 |
| 78.94 | shadowsocks | 204.4 | 517.8 | 23.05 | 0.0 | 10.0 | 12.25 | 17.64 | Au1rxx-base64 | 173.244.56.6 |
| 78.89 | http | 455.7 | 1268.7 | 17.23 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.198 |
| 78.1 | http | 489.7 | 1381.3 | 16.44 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.202 |
| 78.06 | http | 491.5 | 1391.5 | 16.4 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.205 |
| 78.01 | shadowsocks | 201.3 | 506.6 | 23.12 | 0.0 | 10.0 | 12.25 | 17.64 | Au1rxx-base64 | 173.244.56.9 |
| 77.94 | http | 496.8 | 1402.1 | 16.28 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.218 |
| 77.83 | shadowsocks | 252.2 | 603.6 | 21.94 | 0.0 | 10.0 | 12.25 | 17.64 | Au1rxx-base64 | 156.146.38.169 |
| 77.76 | shadowsocks | 255.3 | 629.3 | 21.87 | 0.0 | 10.0 | 12.25 | 17.64 | Au1rxx-base64 | 156.146.38.170 |
| 77.51 | vless | 188.1 | 462.4 | 23.42 | 0.0 | 10.0 | 8.45 | 17.64 | Au1rxx-base64 | 70.39.178.231 |
| 77.15 | shadowsocks | 259.9 | 657.5 | 21.76 | 0.0 | 10.0 | 12.25 | 17.64 | Au1rxx-base64 | 108.181.118.10 |
| 76.78 | vless | 219.9 | 461.4 | 22.69 | 0.0 | 10.0 | 8.45 | 17.64 | Au1rxx-base64 | 192.204.50.220 |
| 76.61 | http | 510.8 | 1437.6 | 15.95 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.220 |
| 75.84 | trojan | 284.0 | 637.6 | 21.2 | 0.0 | 10.0 | 12.44 | 17.64 | Au1rxx-base64 | 64.94.95.117 |
| 75.74 | shadowsocks | 319.3 | 812.9 | 20.39 | 0.0 | 10.0 | 12.25 | 17.64 | Au1rxx-base64 | 156.146.38.168 |
| 75.65 | hysteria2 | 337.4 | 746.8 | 19.97 | 0.0 | 8.71 | 13.24 | 17.64 | Au1rxx-base64 | usa1.spectrumproxy.shop |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 80 | 110 | prefer |
| Au1rxx-base64 | 0.865 | 0.809 | 272 | 1455 | prefer |
| mheidari-all | 0.658 | 0.581 | 62 | 16815 | observe |
| Surfboard-tg-mixed | 0.609 | 0.53 | 100 | 5303 | observe |
| DeltaKronecker-all | 0.573 | 0.6 | 15 | 5144 | observe |
| ninja-vless | 0.344 | 0.5 | 6 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.282 | 0.5 | 2 | 1861 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 48 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 5989 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6742 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4162 | observe |
| barry-far-vless | 0.255 | None | 0 | 4528 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5074 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 31 |
| geo | TimeoutError | - | 30 |
| 204 | ProxyError | - | 21 |
| speed | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 12 |
| geo | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

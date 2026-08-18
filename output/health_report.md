# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 12:41:29 |
| 运行耗时 | 366.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 91875 |
| 去重后节点 | 24148 |
| TCP 可达 | 3000 |
| 真实可用 | 1197 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24148 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.4 |
| tcp | 37.1 |
| probe | 70.0 |
| real_test | 201.4 |
| generate | 47.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52684 |
| trojan | 16338 |
| shadowsocks | 10476 |
| vmess | 9547 |
| hysteria2 | 2296 |
| http | 183 |
| socks | 144 |
| shadowsocksr | 132 |
| anytls | 43 |
| tuic | 19 |
| hysteria | 13 |

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
| 84.9 | http | 204.6 | 526.8 | 23.04 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 84.86 | http | 206.5 | 527.1 | 23.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 84.85 | http | 206.7 | 521.9 | 22.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 84.85 | http | 207.0 | 523.5 | 22.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 84.83 | http | 207.6 | 519.0 | 22.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 84.81 | http | 208.7 | 533.5 | 22.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 83.33 | http | 272.6 | 732.4 | 21.47 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 83.27 | http | 275.1 | 737.8 | 21.41 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 83.26 | http | 275.6 | 739.5 | 21.4 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 83.26 | http | 275.7 | 736.4 | 21.4 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 83.25 | http | 275.8 | 733.7 | 21.39 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 83.13 | http | 281.2 | 755.4 | 21.27 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 82.17 | shadowsocks | 222.7 | 513.3 | 22.62 | 0.0 | 10.0 | 13.59 | 19.96 | Surfboard-tg-mixed | 173.244.56.6 |
| 82.14 | shadowsocks | 224.1 | 514.3 | 22.59 | 0.0 | 10.0 | 13.59 | 19.96 | Surfboard-tg-mixed | 173.244.56.9 |
| 81.73 | hysteria2 | 254.6 | 618.4 | 21.88 | 0.0 | 10.0 | 13.27 | 17.58 | Au1rxx-base64 | 150.241.102.127 |
| 81.34 | shadowsocks | 237.2 | 558.3 | 22.29 | 0.0 | 10.0 | 13.59 | 19.96 | Surfboard-tg-mixed | 108.181.0.177 |
| 81.22 | http | 363.7 | 1012.6 | 19.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 81.22 | http | 363.8 | 1014.7 | 19.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 80.39 | shadowsocks | 298.0 | 753.7 | 20.88 | 0.0 | 10.0 | 13.59 | 19.96 | Surfboard-tg-mixed | 156.146.38.169 |
| 80.13 | shadowsocks | 311.1 | 797.6 | 20.58 | 0.0 | 10.0 | 13.59 | 19.96 | Surfboard-tg-mixed | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.955 | 356 | 21086 | prefer |
| zhangkai | 0.999 | 1.0 | 126 | 159 | prefer |
| Au1rxx-base64 | 0.988 | 0.918 | 662 | 1759 | prefer |
| Surfboard-tg-mixed | 0.849 | 0.773 | 154 | 6169 | prefer |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 5725 | observe |
| nscl5-all | 0.335 | 1.0 | 1 | 2992 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5068 | observe |
| Epodonios-all | 0.255 | None | 0 | 6795 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6898 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4912 | observe |
| barry-far-vless | 0.255 | None | 0 | 5206 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4045 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6329 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 23 |
| geo | TimeoutError | - | 17 |
| geo | ClientOSError | - | 11 |
| speed | TimeoutError | - | 8 |
| speed | ClientOSError | - | 7 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

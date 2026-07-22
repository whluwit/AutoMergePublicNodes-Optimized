# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-22 08:25:57 |
| 运行耗时 | 322.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 82033 |
| 去重后节点 | 22660 |
| TCP 可达 | 3000 |
| 真实可用 | 652 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22660 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 31.7 |
| probe | 68.3 |
| real_test | 174.4 |
| generate | 40.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47283 |
| trojan | 13190 |
| vmess | 10825 |
| shadowsocks | 10123 |
| hysteria2 | 416 |
| shadowsocksr | 75 |
| http | 50 |
| socks | 48 |
| hysteria | 16 |
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
| 77.5 | shadowsocks | 211.7 | 505.8 | 22.88 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 173.244.56.6 |
| 77.18 | shadowsocks | 225.4 | 508.8 | 22.56 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 173.244.56.9 |
| 77.05 | shadowsocks | 231.1 | 532.7 | 22.43 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.79 | shadowsocks | 220.5 | 541.6 | 22.67 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 108.181.118.10 |
| 76.79 | shadowsocks | 220.6 | 534.0 | 22.67 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 108.181.0.177 |
| 73.36 | shadowsocks | 273.2 | 274.9 | 21.45 | 4.69 | 9.82 | 13.62 | 15.0 | Au1rxx-base64 | 149.22.87.241 |
| 72.5 | shadowsocks | 295.2 | 665.0 | 20.94 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 156.146.38.167 |
| 72.33 | shadowsocks | 287.9 | 653.6 | 21.11 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 156.146.38.170 |
| 71.6 | vless | 181.1 | 490.4 | 23.59 | 0.0 | 10.0 | 3.15 | 14.86 | Surfboard-tg-mixed | 86.109.75.147 |
| 71.58 | shadowsocks | 333.6 | 781.0 | 20.06 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 156.146.38.169 |
| 71.55 | shadowsocks | 317.4 | 778.7 | 20.43 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 172.245.235.84 |
| 70.16 | shadowsocks | 297.4 | 344.6 | 20.89 | 2.08 | 9.82 | 13.62 | 15.0 | Au1rxx-base64 | 149.22.87.204 |
| 69.23 | hysteria2 | 272.1 | 235.7 | 21.48 | 6.16 | 9.94 | 12.0 | 8.76 | xiaoji235-airport-v2ray-all | 45.76.202.45 |
| 68.31 | shadowsocks | 363.4 | 700.6 | 19.36 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 198.98.53.130 |
| 68.22 | shadowsocks | 368.1 | 742.9 | 19.26 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 37.19.198.243 |
| 68.2 | shadowsocks | 200.7 | 544.2 | 23.13 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 216.105.168.18 |
| 68.07 | shadowsocks | 365.7 | 731.9 | 19.31 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 37.19.198.244 |
| 68.0 | shadowsocks | 292.4 | 656.0 | 21.01 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 156.146.38.168 |
| 67.95 | shadowsocks | 373.5 | 747.4 | 19.13 | 0.0 | 10.0 | 13.62 | 15.0 | Au1rxx-base64 | 37.19.198.160 |
| 67.29 | shadowsocks | 334.7 | 440.3 | 20.03 | 0.0 | 9.82 | 13.62 | 15.0 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.975 | 1.0 | 35 | 61 | prefer |
| mheidari-all | 0.869 | 0.79 | 348 | 19493 | prefer |
| Surfboard-tg-mixed | 0.668 | 0.589 | 231 | 5331 | observe |
| DeltaKronecker-all | 0.645 | 0.566 | 152 | 5212 | observe |
| Au1rxx-base64 | 0.586 | 0.569 | 202 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4246 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4613 | observe |
| Epodonios-all | 0.255 | None | 0 | 6417 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3972 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6813 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4001 | observe |
| barry-far-vless | 0.255 | None | 0 | 4606 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5204 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 108 |
| geo | TimeoutError | - | 107 |
| speed | ClientOSError | - | 43 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 13 |
| 204 | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

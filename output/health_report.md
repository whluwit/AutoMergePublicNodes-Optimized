# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-30 14:13:18 |
| 运行耗时 | 238.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 74551 |
| 去重后节点 | 23027 |
| TCP 可达 | 3000 |
| 真实可用 | 451 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23027 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 29.6 |
| probe | 55.8 |
| real_test | 113.1 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 41355 |
| trojan | 12985 |
| vmess | 10276 |
| shadowsocks | 9295 |
| hysteria2 | 269 |
| shadowsocksr | 164 |
| http | 135 |
| socks | 65 |
| hysteria | 6 |
| tuic | 1 |

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
| 76.35 | shadowsocks | 227.9 | 634.1 | 22.5 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 37.19.198.236 |
| 76.29 | shadowsocks | 230.8 | 634.0 | 22.44 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 37.19.198.243 |
| 76.27 | shadowsocks | 231.4 | 638.3 | 22.42 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 37.19.198.244 |
| 76.18 | shadowsocks | 235.5 | 653.2 | 22.33 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 37.19.198.160 |
| 74.75 | vless | 254.6 | 666.7 | 21.88 | 0.0 | 10.0 | 7.99 | 15.88 | Au1rxx-base64 | 159.89.87.21 |
| 72.55 | vless | 267.0 | 750.2 | 21.6 | 0.0 | 10.0 | 7.99 | 12.96 | mheidari-all | 47.253.226.114 |
| 72.35 | shadowsocks | 253.0 | 675.5 | 21.92 | 0.0 | 10.0 | 11.97 | 12.96 | mheidari-all | 108.181.57.93 |
| 72.16 | shadowsocks | 282.7 | 729.3 | 21.23 | 0.0 | 10.0 | 11.97 | 12.96 | mheidari-all | 198.98.53.130 |
| 71.77 | shadowsocks | 286.1 | 656.8 | 21.16 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 156.146.38.167 |
| 70.83 | shadowsocks | 286.7 | 658.8 | 21.14 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 156.146.38.168 |
| 70.76 | vmess | 400.0 | 1129.4 | 18.52 | 0.0 | 10.0 | 12.5 | 14.24 | Surfboard-tg-mixed | 67.220.85.46 |
| 70.35 | shadowsocks | 320.8 | 774.7 | 20.35 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 156.146.38.169 |
| 69.8 | hysteria2 | 359.4 | 691.2 | 19.46 | 0.0 | 10.0 | 11.25 | 15.88 | Au1rxx-base64 | 62.210.124.146 |
| 69.19 | vless | 309.9 | 714.6 | 20.6 | 0.0 | 10.0 | 7.99 | 11.7 | DeltaKronecker-all | 162.159.39.247 |
| 69.03 | shadowsocks | 339.0 | 709.7 | 19.93 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 173.244.56.6 |
| 68.59 | shadowsocks | 342.5 | 668.0 | 19.85 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 108.181.118.10 |
| 68.53 | shadowsocks | 308.4 | 577.3 | 20.64 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 173.244.56.9 |
| 68.04 | shadowsocks | 279.6 | 639.8 | 21.31 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 156.146.38.170 |
| 67.83 | vless | 310.0 | 834.8 | 20.6 | 0.0 | 10.0 | 7.99 | 14.24 | Surfboard-tg-mixed | 137.184.218.169 |
| 67.78 | shadowsocks | 343.2 | 625.6 | 19.83 | 0.0 | 10.0 | 11.97 | 15.88 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.8 | 0.809 | 47 | 102 | prefer |
| Surfboard-tg-mixed | 0.741 | 0.662 | 293 | 5386 | prefer |
| DeltaKronecker-all | 0.739 | 0.663 | 83 | 7352 | prefer |
| mheidari-all | 0.667 | 0.588 | 211 | 15693 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| xiaoji235-airport-v2ray-all | 0.303 | 1.0 | 1 | 1204 | observe |
| nscl5-all | 0.3 | 1.0 | 1 | 1136 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4139 | observe |
| Epodonios-all | 0.255 | None | 0 | 6322 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3978 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6506 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3959 | observe |
| barry-far-vless | 0.255 | None | 0 | 4531 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5353 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 114 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 16 |
| geo | TimeoutError | - | 16 |
| 204 | ClientOSError | - | 16 |
| geo | ClientOSError | - | 15 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 7 |
| cn-block | TimeoutError | - | 3 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

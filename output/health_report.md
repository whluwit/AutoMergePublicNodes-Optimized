# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-01 11:04:01 |
| 运行耗时 | 296.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 83381 |
| 去重后节点 | 24538 |
| TCP 可达 | 3000 |
| 真实可用 | 606 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24538 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 40.8 |
| probe | 84.4 |
| real_test | 129.3 |
| generate | 34.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52353 |
| vmess | 11449 |
| shadowsocks | 10172 |
| trojan | 7636 |
| hysteria2 | 1392 |
| http | 146 |
| shadowsocksr | 131 |
| socks | 81 |
| hysteria | 9 |
| tuic | 7 |
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
| 82.68 | hysteria2 | 338.2 | 871.7 | 19.95 | 0.0 | 10.0 | 13.97 | 19.76 | Au1rxx-base64 | 66.94.121.46 |
| 81.38 | vless | 261.2 | 579.7 | 21.73 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 38.180.242.205 |
| 79.52 | shadowsocks | 233.2 | 594.6 | 22.38 | 0.0 | 10.0 | 14.32 | 16.82 | Surfboard-tg-mixed | 156.146.38.167 |
| 79.36 | vless | 266.7 | 578.5 | 21.6 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 172.233.156.123 |
| 79.07 | http | 322.3 | 468.8 | 20.32 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.198 |
| 79.02 | vless | 343.2 | 834.5 | 19.83 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 15.204.97.216 |
| 79.0 | shadowsocks | 252.1 | 613.5 | 21.94 | 0.0 | 10.0 | 14.32 | 16.74 | mheidari-all | 156.146.38.170 |
| 79.0 | vless | 340.9 | 825.2 | 19.89 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 15.204.97.197 |
| 78.94 | vless | 343.6 | 830.2 | 19.82 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 15.204.97.206 |
| 78.85 | vless | 276.0 | 590.3 | 21.39 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 172.239.67.231 |
| 78.64 | vless | 272.2 | 582.7 | 21.48 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 172.233.156.118 |
| 78.49 | vless | 269.1 | 571.9 | 21.55 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 172.236.252.35 |
| 78.25 | vless | 263.9 | 563.5 | 21.67 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 172.239.67.156 |
| 78.21 | vless | 313.5 | 666.8 | 20.52 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 195.211.99.49 |
| 78.09 | vless | 283.5 | 575.5 | 21.21 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 45.33.62.166 |
| 78.04 | vless | 280.5 | 565.8 | 21.29 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 173.230.155.55 |
| 77.92 | vless | 282.2 | 560.2 | 21.25 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 192.155.87.188 |
| 77.9 | vless | 287.3 | 585.5 | 21.13 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 74.207.245.124 |
| 77.68 | vless | 266.4 | 554.6 | 21.61 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 172.235.38.85 |
| 77.62 | vless | 290.7 | 593.5 | 21.05 | 0.0 | 10.0 | 10.96 | 19.76 | Au1rxx-base64 | 45.33.107.237 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.898 | 0.834 | 319 | 1645 | prefer |
| mheidari-all | 0.884 | 0.807 | 212 | 17148 | prefer |
| zhangkai | 0.846 | 0.87 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.825 | 0.747 | 194 | 6921 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 49 | observe |
| DeltaKronecker-all | 0.255 | 0.222 | 9 | 7294 | observe |
| Epodonios-all | 0.255 | None | 0 | 7334 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7933 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5831 | observe |
| barry-far-vless | 0.255 | None | 0 | 6092 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4013 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1645 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 21 |
| geo | ClientOSError | - | 17 |
| geo | TimeoutError | - | 14 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 8 |
| 204 | ProxyConnectionError | - | 3 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

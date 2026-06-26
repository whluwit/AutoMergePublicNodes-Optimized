# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-26 02:57:56 |
| 运行耗时 | 269.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 82426 |
| 去重后节点 | 22884 |
| TCP 可达 | 3000 |
| 真实可用 | 556 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22884 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.3 |
| tcp | 30.2 |
| probe | 61.1 |
| real_test | 137.1 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45968 |
| trojan | 14605 |
| vmess | 11165 |
| shadowsocks | 10061 |
| hysteria2 | 255 |
| shadowsocksr | 161 |
| http | 129 |
| socks | 74 |
| hysteria | 6 |
| tuic | 2 |

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
| 77.54 | vless | 309.9 | 816.1 | 20.6 | 0.0 | 10.0 | 10.38 | 16.56 | Au1rxx-base64 | 15.204.97.214 |
| 77.32 | vless | 319.8 | 844.4 | 20.38 | 0.0 | 10.0 | 10.38 | 16.56 | Au1rxx-base64 | 15.204.97.219 |
| 77.28 | shadowsocks | 206.2 | 524.7 | 23.0 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 173.244.56.9 |
| 76.65 | shadowsocks | 214.5 | 531.3 | 22.81 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 108.181.0.177 |
| 76.36 | shadowsocks | 248.8 | 652.6 | 22.02 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 173.244.56.6 |
| 76.21 | vless | 226.8 | 611.0 | 22.53 | 0.0 | 10.0 | 10.38 | 13.3 | Surfboard-tg-mixed | 64.23.143.23 |
| 76.18 | shadowsocks | 256.6 | 695.7 | 21.84 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 216.105.168.18 |
| 76.11 | vless | 286.6 | 680.4 | 21.14 | 0.0 | 10.0 | 10.38 | 14.78 | mheidari-all | 34.213.172.16 |
| 75.75 | shadowsocks | 253.4 | 642.9 | 21.91 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 108.181.118.10 |
| 75.74 | shadowsocks | 241.1 | 568.3 | 22.2 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 149.22.95.183 |
| 74.59 | vless | 224.3 | 490.7 | 22.59 | 0.0 | 10.0 | 10.38 | 14.78 | mheidari-all | 173.245.59.35 |
| 72.47 | shadowsocks | 289.5 | 653.3 | 21.08 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 156.146.38.167 |
| 71.73 | trojan | 284.8 | 593.4 | 21.18 | 0.0 | 10.0 | 6.49 | 16.56 | Au1rxx-base64 | 207.126.167.162 |
| 71.29 | shadowsocks | 291.0 | 651.6 | 21.04 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 156.146.38.170 |
| 71.13 | shadowsocks | 224.9 | 627.4 | 22.57 | 0.0 | 10.0 | 11.78 | 10.88 | DeltaKronecker-all | 107.172.219.230 |
| 70.6 | trojan | 334.0 | 870.5 | 20.05 | 0.0 | 10.0 | 6.49 | 16.56 | Au1rxx-base64 | 45.61.52.243 |
| 69.96 | shadowsocks | 297.7 | 345.8 | 20.89 | 2.03 | 9.91 | 11.78 | 16.56 | Au1rxx-base64 | 149.22.87.204 |
| 69.92 | shadowsocks | 293.2 | 665.2 | 20.99 | 0.0 | 10.0 | 11.78 | 16.56 | Au1rxx-base64 | 156.146.38.169 |
| 69.52 | shadowsocks | 298.4 | 358.0 | 20.87 | 1.57 | 9.93 | 11.78 | 16.56 | Au1rxx-base64 | 149.22.87.240 |
| 69.44 | trojan | 243.1 | 623.0 | 22.15 | 0.0 | 10.0 | 6.49 | 13.3 | Surfboard-tg-mixed | 207.126.167.150 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Surfboard-tg-mixed | 0.896 | 0.819 | 281 | 5129 | prefer |
| Au1rxx-base64 | 0.758 | 0.763 | 59 | 109 | prefer |
| mheidari-all | 0.716 | 0.637 | 289 | 16097 | prefer |
| nscl5-all | 0.358 | 1.0 | 2 | 1175 | observe |
| DeltaKronecker-all | 0.34 | 0.258 | 221 | 12590 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4787 | observe |
| Epodonios-all | 0.255 | None | 0 | 7810 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3982 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7206 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3784 | observe |
| barry-far-vless | 0.255 | None | 0 | 4580 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5117 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 155 |
| geo | TimeoutError | - | 114 |
| speed | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 12 |
| geo | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| 204 | TimeoutError | - | 4 |
| geo | status | 403 | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

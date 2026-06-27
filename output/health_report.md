# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-27 13:27:28 |
| 运行耗时 | 239.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 77292 |
| 去重后节点 | 23007 |
| TCP 可达 | 3000 |
| 真实可用 | 382 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23007 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 30.2 |
| probe | 47.2 |
| real_test | 107.2 |
| generate | 48.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43364 |
| trojan | 12775 |
| vmess | 11220 |
| shadowsocks | 9380 |
| hysteria2 | 246 |
| shadowsocksr | 160 |
| http | 79 |
| socks | 59 |
| hysteria | 6 |
| tuic | 2 |
| anytls | 1 |

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
| 76.82 | trojan | 266.3 | 634.7 | 21.61 | 0.0 | 10.0 | 11.98 | 16.18 | Au1rxx-base64 | 45.61.52.243 |
| 76.2 | shadowsocks | 194.7 | 472.7 | 23.27 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 108.181.118.10 |
| 76.02 | shadowsocks | 202.7 | 492.2 | 23.09 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 108.181.0.177 |
| 75.98 | shadowsocks | 225.8 | 531.9 | 22.55 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 149.22.95.183 |
| 75.97 | trojan | 255.2 | 438.6 | 21.87 | 0.0 | 10.0 | 11.98 | 16.12 | Surfboard-tg-mixed | 94.140.0.100 |
| 75.77 | shadowsocks | 235.1 | 523.5 | 22.34 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 173.244.56.9 |
| 75.39 | vless | 309.0 | 813.5 | 20.62 | 0.0 | 10.0 | 8.59 | 16.18 | Au1rxx-base64 | 15.204.97.214 |
| 75.19 | trojan | 342.6 | 890.6 | 19.85 | 0.0 | 10.0 | 11.98 | 16.18 | Au1rxx-base64 | 207.126.167.150 |
| 75.12 | vless | 320.9 | 848.1 | 20.35 | 0.0 | 10.0 | 8.59 | 16.18 | Au1rxx-base64 | 15.204.97.219 |
| 73.49 | trojan | 386.3 | 666.4 | 18.84 | 0.0 | 10.0 | 11.98 | 16.18 | Au1rxx-base64 | 207.126.167.162 |
| 71.54 | trojan | 271.1 | 703.5 | 21.5 | 0.0 | 10.0 | 11.98 | 13.56 | DeltaKronecker-all | 45.61.58.89 |
| 71.44 | shadowsocks | 289.6 | 645.2 | 21.07 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 156.146.38.169 |
| 71.44 | trojan | 386.0 | 692.2 | 18.84 | 0.0 | 10.0 | 11.98 | 14.26 | mheidari-all | 207.126.167.241 |
| 71.29 | shadowsocks | 323.0 | 754.3 | 20.3 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 156.146.38.167 |
| 71.17 | shadowsocks | 298.6 | 672.0 | 20.87 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 156.146.38.170 |
| 71.08 | shadowsocks | 302.4 | 671.2 | 20.78 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 156.146.38.168 |
| 70.89 | trojan | 204.9 | 487.3 | 23.03 | 0.0 | 10.0 | 11.98 | 13.56 | DeltaKronecker-all | 104.17.148.22 |
| 70.05 | shadowsocks | 266.2 | 671.2 | 21.62 | 0.0 | 10.0 | 11.25 | 16.18 | Au1rxx-base64 | 173.244.56.6 |
| 69.39 | vless | 231.2 | 503.8 | 22.43 | 0.0 | 10.0 | 8.59 | 16.12 | Surfboard-tg-mixed | 141.193.154.182 |
| 69.21 | trojan | 369.8 | 362.4 | 19.22 | 1.41 | 10.0 | 11.98 | 16.12 | Surfboard-tg-mixed | 45.131.4.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.89 | 1.0 | 18 | 39 | prefer |
| Surfboard-tg-mixed | 0.835 | 0.757 | 251 | 5186 | prefer |
| mheidari-all | 0.833 | 0.758 | 91 | 16363 | prefer |
| Au1rxx-base64 | 0.788 | 0.8 | 35 | 93 | prefer |
| DeltaKronecker-all | 0.491 | 0.41 | 183 | 6822 | observe |
| nscl5-all | 0.359 | 1.0 | 2 | 1186 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4579 | observe |
| Epodonios-all | 0.255 | None | 0 | 7866 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7361 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3808 | observe |
| barry-far-vless | 0.255 | None | 0 | 4584 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5283 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 86 |
| 204 | ProxyError | - | 28 |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 12 |
| geo | TimeoutError | - | 12 |
| cn-block | ProxyError | - | 8 |
| 204 | ClientOSError | - | 8 |
| geo | ClientOSError | - | 6 |
| speed | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

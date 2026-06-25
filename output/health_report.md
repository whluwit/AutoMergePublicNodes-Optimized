# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-25 14:26:17 |
| 运行耗时 | 260.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 83048 |
| 去重后节点 | 23008 |
| TCP 可达 | 3000 |
| 真实可用 | 312 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23008 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.4 |
| tcp | 30.4 |
| probe | 56.8 |
| real_test | 134.0 |
| generate | 32.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46451 |
| trojan | 14740 |
| vmess | 11190 |
| shadowsocks | 10028 |
| hysteria2 | 270 |
| shadowsocksr | 158 |
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
| 74.99 | shadowsocks | 212.1 | 505.9 | 22.87 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 173.244.56.9 |
| 74.24 | shadowsocks | 244.5 | 586.0 | 22.12 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 149.22.95.183 |
| 74.02 | shadowsocks | 232.4 | 578.3 | 22.4 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 108.181.0.177 |
| 73.75 | shadowsocks | 243.9 | 620.6 | 22.13 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 108.181.118.10 |
| 71.8 | trojan | 354.3 | 940.4 | 19.58 | 0.0 | 10.0 | 10.86 | 13.86 | Au1rxx-base64 | 45.61.52.243 |
| 71.48 | trojan | 284.9 | 671.7 | 21.18 | 0.0 | 10.0 | 10.86 | 14.98 | Surfboard-tg-mixed | 207.126.167.150 |
| 71.47 | vless | 168.9 | 452.9 | 23.87 | 0.0 | 10.0 | 7.12 | 14.98 | Surfboard-tg-mixed | 92.223.71.246 |
| 71.46 | shadowsocks | 250.2 | 622.0 | 21.99 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 173.244.56.6 |
| 70.29 | shadowsocks | 286.9 | 634.6 | 21.14 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 156.146.38.168 |
| 69.53 | shadowsocks | 295.4 | 659.9 | 20.94 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 156.146.38.167 |
| 68.82 | trojan | 441.5 | 839.8 | 17.56 | 0.0 | 10.0 | 10.86 | 13.86 | Au1rxx-base64 | 207.126.167.162 |
| 68.45 | vless | 299.2 | 830.9 | 20.85 | 0.0 | 10.0 | 7.12 | 14.98 | Surfboard-tg-mixed | 141.193.154.182 |
| 67.72 | shadowsocks | 295.0 | 347.4 | 20.95 | 1.97 | 9.82 | 12.26 | 13.86 | Au1rxx-base64 | 149.22.87.240 |
| 67.48 | trojan | 324.8 | 852.7 | 20.26 | 0.0 | 10.0 | 10.86 | 13.86 | Au1rxx-base64 | 45.61.58.89 |
| 67.46 | trojan | 397.1 | 788.3 | 18.59 | 0.0 | 10.0 | 10.86 | 13.86 | Au1rxx-base64 | 207.126.167.241 |
| 67.4 | vmess | 204.5 | 539.8 | 23.04 | 0.0 | 10.0 | 12.5 | 6.36 | Barabama-yudou | 82.198.246.233 |
| 67.31 | shadowsocks | 299.3 | 355.1 | 20.85 | 1.68 | 9.82 | 12.26 | 13.86 | Au1rxx-base64 | 149.22.87.204 |
| 66.97 | trojan | 422.0 | 864.6 | 18.01 | 0.0 | 10.0 | 10.86 | 13.86 | Au1rxx-base64 | 198.52.244.10 |
| 66.88 | shadowsocks | 292.7 | 653.4 | 21.0 | 0.0 | 10.0 | 12.26 | 13.86 | Au1rxx-base64 | 156.146.38.170 |
| 66.3 | shadowsocks | 304.4 | 376.7 | 20.73 | 0.87 | 9.82 | 12.26 | 13.86 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Au1rxx-base64 | 0.893 | 0.912 | 34 | 101 | prefer |
| mheidari-all | 0.627 | 0.548 | 62 | 16105 | observe |
| Surfboard-tg-mixed | 0.524 | 0.444 | 322 | 5229 | observe |
| DeltaKronecker-all | 0.521 | 0.44 | 150 | 12590 | observe |
| nscl5-all | 0.3 | 1.0 | 1 | 1136 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4787 | observe |
| Epodonios-all | 0.255 | None | 0 | 7910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7492 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3885 | observe |
| barry-far-vless | 0.255 | None | 0 | 4673 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5133 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 114 |
| speed | ClientOSError | - | 72 |
| 204 | ProxyError | - | 27 |
| cn-block | ProxyError | - | 15 |
| geo | ProxyError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| geo | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| speed | ProxyError | - | 7 |
| speed | TimeoutError | - | 4 |
| geo | ClientOSError | - | 3 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

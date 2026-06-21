# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.9.1 |
| 更新时间 | 2026-06-21 14:30:30 |
| 运行耗时 | 448.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 73459 |
| 去重后节点 | 21999 |
| TCP 可达 | 842 |
| 真实可用 | 682 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21999 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.3 |
| tcp | 63.7 |
| probe | 100.8 |
| real_test | 212.3 |
| generate | 65.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42532 |
| trojan | 10211 |
| shadowsocks | 10142 |
| vmess | 9893 |
| hysteria2 | 239 |
| http | 182 |
| shadowsocksr | 160 |
| socks | 92 |
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
| 75.89 | shadowsocks | 265.3 | 727.3 | 21.64 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 37.19.198.244 |
| 75.59 | shadowsocks | 278.0 | 772.0 | 21.34 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 37.19.198.160 |
| 75.36 | vless | 272.5 | 775.1 | 21.47 | 0.0 | 10.0 | 11.19 | 16.8 | Surfboard-tg-mixed | 47.253.226.114 |
| 75.29 | shadowsocks | 291.0 | 812.2 | 21.04 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 37.19.198.236 |
| 75.09 | shadowsocks | 250.6 | 684.4 | 21.98 | 0.0 | 10.0 | 12.41 | 16.8 | Surfboard-tg-mixed | 198.98.53.130 |
| 74.38 | shadowsocks | 330.5 | 922.6 | 20.13 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 69.164.240.83 |
| 74.32 | shadowsocks | 283.8 | 758.8 | 21.21 | 0.0 | 10.0 | 12.41 | 16.8 | Surfboard-tg-mixed | 108.181.57.93 |
| 73.85 | shadowsocks | 331.8 | 925.1 | 20.1 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 69.164.240.86 |
| 73.51 | shadowsocks | 268.6 | 618.3 | 21.56 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 156.146.38.167 |
| 73.44 | shadowsocks | 285.2 | 653.0 | 21.18 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 156.146.38.168 |
| 73.21 | shadowsocks | 271.8 | 622.1 | 21.49 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 156.146.38.170 |
| 72.71 | vless | 317.3 | 760.6 | 20.43 | 0.0 | 10.0 | 11.19 | 17.94 | Au1rxx-base64 | 15.223.121.250 |
| 72.33 | shadowsocks | 419.0 | 1196.3 | 18.08 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 68.168.209.194 |
| 72.31 | shadowsocks | 313.5 | 743.7 | 20.52 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 156.146.38.169 |
| 72.25 | shadowsocks | 292.8 | 818.3 | 21.0 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 37.19.198.243 |
| 71.68 | vless | 391.2 | 994.3 | 18.72 | 0.0 | 10.0 | 11.19 | 17.16 | mheidari-all | 185.156.47.96 |
| 69.33 | shadowsocks | 308.1 | 577.4 | 20.65 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 173.244.56.9 |
| 68.98 | shadowsocks | 324.5 | 557.9 | 20.27 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 108.181.0.177 |
| 68.86 | shadowsocks | 324.1 | 591.6 | 20.28 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 149.22.95.183 |
| 68.71 | shadowsocks | 351.7 | 727.1 | 19.64 | 0.0 | 10.0 | 12.41 | 17.94 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.991 | 1.0 | 69 | 131 | prefer |
| Au1rxx-base64 | 0.898 | 0.902 | 82 | 126 | prefer |
| mheidari-all | 0.891 | 0.814 | 263 | 14966 | prefer |
| Surfboard-tg-mixed | 0.858 | 0.779 | 385 | 4933 | prefer |
| DeltaKronecker-all | 0.617 | 0.538 | 39 | 6748 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| nscl5-all | 0.303 | 1.0 | 1 | 1204 | observe |
| abc-configs-readme-latest30 | 0.256 | 1.0 | 1 | 20 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4494 | observe |
| Epodonios-all | 0.255 | None | 0 | 7303 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3978 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6910 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3718 | observe |
| barry-far-vless | 0.255 | None | 0 | 4385 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4510 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 43 |
| cn-block | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 16 |
| geo | TimeoutError | - | 13 |
| speed | TimeoutError | - | 12 |
| geo | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

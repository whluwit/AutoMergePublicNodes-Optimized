# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-24 09:03:33 |
| 运行耗时 | 223.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 77169 |
| 去重后节点 | 22356 |
| TCP 可达 | 3000 |
| 真实可用 | 394 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22356 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.6 |
| tcp | 29.4 |
| probe | 51.0 |
| real_test | 105.3 |
| generate | 32.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45547 |
| trojan | 10804 |
| vmess | 10311 |
| shadowsocks | 9872 |
| hysteria2 | 233 |
| shadowsocksr | 164 |
| http | 161 |
| socks | 69 |
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
| 75.89 | shadowsocks | 241.7 | 620.6 | 22.18 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 156.146.38.167 |
| 75.89 | shadowsocks | 241.8 | 643.2 | 22.18 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 156.146.38.170 |
| 75.79 | shadowsocks | 246.2 | 635.4 | 22.08 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 156.146.38.168 |
| 72.81 | shadowsocks | 297.9 | 690.8 | 20.88 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 37.19.198.160 |
| 72.31 | trojan | 236.8 | 572.8 | 22.3 | 0.0 | 10.0 | 13.09 | 11.92 | DeltaKronecker-all | 64.94.95.114 |
| 71.68 | trojan | 263.8 | 620.0 | 21.67 | 0.0 | 10.0 | 13.09 | 11.92 | DeltaKronecker-all | 64.94.95.117 |
| 71.65 | shadowsocks | 335.0 | 824.7 | 20.02 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 37.19.198.244 |
| 71.64 | trojan | 264.4 | 673.4 | 21.66 | 0.0 | 10.0 | 13.09 | 12.72 | mheidari-all | 64.94.95.118 |
| 71.48 | vless | 327.6 | 712.8 | 20.2 | 0.0 | 10.0 | 7.71 | 18.12 | Surfboard-tg-mixed | 137.184.218.169 |
| 71.14 | shadowsocks | 281.2 | 565.7 | 21.27 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 173.244.56.9 |
| 71.14 | shadowsocks | 327.8 | 777.8 | 20.19 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 37.19.198.243 |
| 70.96 | shadowsocks | 333.4 | 793.3 | 20.06 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 37.19.198.236 |
| 70.76 | shadowsocks | 247.2 | 638.4 | 22.05 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 156.146.38.169 |
| 69.94 | shadowsocks | 332.2 | 716.7 | 20.09 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 173.244.56.6 |
| 69.76 | vless | 417.6 | 1011.2 | 18.11 | 0.0 | 10.0 | 7.71 | 18.12 | Surfboard-tg-mixed | 15.223.121.250 |
| 69.21 | shadowsocks | 303.9 | 598.2 | 20.74 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 108.181.118.10 |
| 68.93 | shadowsocks | 295.5 | 555.9 | 20.94 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 149.22.95.183 |
| 68.59 | vless | 298.2 | 681.0 | 20.88 | 0.0 | 10.0 | 7.71 | 18.12 | Surfboard-tg-mixed | 104.16.9.20 |
| 68.33 | shadowsocks | 333.1 | 638.6 | 20.07 | 0.0 | 10.0 | 13.81 | 13.9 | Au1rxx-base64 | 108.181.0.177 |
| 68.0 | shadowsocks | 308.3 | 720.6 | 20.64 | 0.0 | 10.0 | 13.81 | 11.92 | DeltaKronecker-all | 108.181.57.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | 1.0 | 50 | 73 | prefer |
| Au1rxx-base64 | 0.942 | 0.967 | 30 | 124 | prefer |
| Surfboard-tg-mixed | 0.809 | 0.731 | 219 | 5405 | prefer |
| mheidari-all | 0.778 | 0.705 | 61 | 15611 | prefer |
| DeltaKronecker-all | 0.55 | 0.47 | 232 | 6644 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| nscl5-all | 0.301 | 1.0 | 1 | 1140 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4745 | observe |
| Epodonios-all | 0.255 | None | 0 | 8238 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3980 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7490 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4121 | observe |
| barry-far-vless | 0.255 | None | 0 | 4922 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4710 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 58 |
| geo | TimeoutError | - | 30 |
| 204 | ProxyError | - | 22 |
| geo | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 15 |
| 204 | ClientOSError | - | 11 |
| cn-block | ProxyError | - | 10 |
| geo | ProxyError | - | 7 |
| speed | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

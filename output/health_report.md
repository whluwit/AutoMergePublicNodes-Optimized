# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-26 09:02:05 |
| 运行耗时 | 260.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 82728 |
| 去重后节点 | 22675 |
| TCP 可达 | 3000 |
| 真实可用 | 402 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22675 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.3 |
| tcp | 30.4 |
| probe | 63.7 |
| real_test | 117.9 |
| generate | 41.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45863 |
| trojan | 14733 |
| vmess | 11414 |
| shadowsocks | 10094 |
| hysteria2 | 256 |
| shadowsocksr | 158 |
| http | 129 |
| socks | 73 |
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
| 77.81 | shadowsocks | 205.7 | 485.5 | 23.02 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 173.244.56.9 |
| 77.21 | shadowsocks | 210.0 | 509.3 | 22.92 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 108.181.118.10 |
| 77.06 | shadowsocks | 238.1 | 621.6 | 22.27 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 173.244.56.6 |
| 76.74 | shadowsocks | 252.0 | 617.8 | 21.95 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 156.146.38.170 |
| 76.72 | shadowsocks | 252.4 | 616.5 | 21.93 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 156.146.38.167 |
| 76.72 | trojan | 414.4 | 1064.8 | 18.18 | 0.0 | 10.0 | 13.12 | 17.92 | Surfboard-tg-mixed | 207.126.167.150 |
| 76.58 | shadowsocks | 258.7 | 640.5 | 21.79 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 156.146.38.168 |
| 75.57 | shadowsocks | 259.1 | 635.9 | 21.78 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 156.146.38.169 |
| 73.31 | shadowsocks | 264.9 | 564.7 | 21.65 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 149.22.95.183 |
| 73.13 | vless | 217.1 | 505.9 | 22.75 | 0.0 | 10.0 | 6.96 | 17.92 | Surfboard-tg-mixed | 141.193.154.182 |
| 72.87 | vless | 206.8 | 518.8 | 22.99 | 0.0 | 10.0 | 6.96 | 17.92 | Surfboard-tg-mixed | 38.244.21.213 |
| 71.31 | trojan | 361.3 | 858.0 | 19.41 | 0.0 | 10.0 | 13.12 | 14.32 | mheidari-all | 64.94.95.118 |
| 71.24 | shadowsocks | 467.9 | 1291.8 | 16.95 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 108.181.0.177 |
| 70.76 | trojan | 450.0 | 839.9 | 17.36 | 0.0 | 10.0 | 13.12 | 17.92 | Surfboard-tg-mixed | 207.126.167.241 |
| 70.66 | shadowsocks | 325.4 | 321.2 | 20.25 | 2.95 | 9.9 | 13.63 | 15.16 | Au1rxx-base64 | 149.22.87.204 |
| 70.03 | trojan | 584.6 | 1658.0 | 14.25 | 0.0 | 10.0 | 13.12 | 15.16 | Au1rxx-base64 | 45.61.52.243 |
| 69.96 | vless | 347.6 | 841.9 | 19.73 | 0.0 | 10.0 | 6.96 | 15.16 | Au1rxx-base64 | 15.204.97.214 |
| 69.42 | shadowsocks | 347.9 | 727.8 | 19.73 | 0.0 | 10.0 | 13.63 | 15.16 | Au1rxx-base64 | 37.19.198.160 |
| 69.39 | shadowsocks | 327.1 | 353.6 | 20.21 | 1.74 | 9.91 | 13.63 | 15.16 | Au1rxx-base64 | 149.22.87.241 |
| 68.87 | shadowsocks | 334.2 | 684.0 | 20.04 | 0.0 | 10.0 | 13.63 | 14.32 | mheidari-all | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Surfboard-tg-mixed | 0.797 | 0.719 | 203 | 5153 | prefer |
| mheidari-all | 0.773 | 0.695 | 203 | 16243 | prefer |
| Au1rxx-base64 | 0.754 | 0.763 | 38 | 91 | prefer |
| DeltaKronecker-all | 0.516 | 0.435 | 108 | 12590 | observe |
| nscl5-all | 0.358 | 1.0 | 2 | 1175 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4567 | observe |
| Epodonios-all | 0.255 | None | 0 | 7806 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7436 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3827 | observe |
| barry-far-vless | 0.255 | None | 0 | 4575 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5185 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 68 |
| geo | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 19 |
| 204 | ProxyError | - | 18 |
| 204 | ClientOSError | - | 16 |
| geo | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

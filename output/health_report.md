# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 06:46:16 |
| 运行耗时 | 242.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 81866 |
| 去重后节点 | 23409 |
| TCP 可达 | 3000 |
| 真实可用 | 480 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23409 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.6 |
| tcp | 34.2 |
| probe | 53.3 |
| real_test | 107.1 |
| generate | 40.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47491 |
| vmess | 12916 |
| trojan | 10272 |
| shadowsocks | 9710 |
| hysteria2 | 1277 |
| shadowsocksr | 75 |
| socks | 66 |
| http | 36 |
| hysteria | 13 |
| tuic | 9 |
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
| 84.92 | hysteria2 | 258.3 | 660.7 | 21.8 | 0.0 | 10.0 | 14.42 | 19.8 | Au1rxx-base64 | 159.223.157.129 |
| 84.01 | hysteria2 | 301.7 | 795.9 | 20.79 | 0.0 | 10.0 | 14.42 | 19.8 | Au1rxx-base64 | 138.124.68.188 |
| 81.86 | shadowsocks | 254.9 | 619.4 | 21.88 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 156.146.38.167 |
| 81.79 | shadowsocks | 257.8 | 630.2 | 21.81 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 156.146.38.169 |
| 81.78 | shadowsocks | 258.1 | 633.8 | 21.8 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 156.146.38.170 |
| 81.63 | shadowsocks | 264.7 | 681.1 | 21.65 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 37.19.198.244 |
| 81.6 | shadowsocks | 266.0 | 686.7 | 21.62 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 37.19.198.160 |
| 81.49 | shadowsocks | 270.9 | 701.8 | 21.51 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 37.19.198.243 |
| 81.3 | shadowsocks | 278.9 | 721.9 | 21.32 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 37.19.198.236 |
| 81.18 | trojan | 266.5 | 613.2 | 21.61 | 0.0 | 10.0 | 13.53 | 19.8 | Au1rxx-base64 | 64.94.95.114 |
| 80.85 | trojan | 269.0 | 621.6 | 21.55 | 0.0 | 10.0 | 13.53 | 19.8 | Au1rxx-base64 | 64.94.95.115 |
| 78.91 | hysteria2 | 296.9 | 790.1 | 20.91 | 0.0 | 4.78 | 14.42 | 19.8 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 76.75 | shadowsocks | 304.8 | 654.7 | 20.72 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 149.22.95.183 |
| 76.19 | shadowsocks | 319.7 | 706.3 | 20.38 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 108.181.57.93 |
| 76.1 | shadowsocks | 285.9 | 537.7 | 21.16 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 108.181.0.177 |
| 75.87 | shadowsocks | 294.7 | 579.7 | 20.96 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 173.244.56.9 |
| 75.73 | shadowsocks | 312.7 | 589.3 | 20.54 | 0.0 | 10.0 | 14.18 | 19.8 | Au1rxx-base64 | 173.244.56.6 |
| 75.69 | http | 310.4 | 600.8 | 20.59 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 75.15 | trojan | 324.9 | 574.4 | 20.26 | 0.0 | 10.0 | 13.53 | 19.8 | Au1rxx-base64 | 44.246.163.102 |
| 75.02 | http | 347.2 | 711.2 | 19.74 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.959 | 363 | 1368 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| DeltaKronecker-all | 0.54 | 0.459 | 98 | 5347 | observe |
| Surfboard-tg-mixed | 0.517 | 0.436 | 117 | 6313 | observe |
| mheidari-all | 0.509 | 0.424 | 33 | 17696 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 169 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5450 | observe |
| Epodonios-all | 0.255 | None | 0 | 6914 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7402 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5099 | observe |
| barry-far-vless | 0.255 | None | 0 | 5409 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5162 | observe |
| nscl5-all | 0.241 | None | 0 | 1643 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 64 |
| 204 | TimeoutError | - | 22 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 16 |
| speed | ClientOSError | - | 13 |
| speed | TimeoutError | - | 10 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

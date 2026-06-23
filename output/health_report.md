# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-23 19:59:33 |
| 运行耗时 | 250.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 77578 |
| 去重后节点 | 22291 |
| TCP 可达 | 3000 |
| 真实可用 | 351 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22291 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.4 |
| tcp | 29.4 |
| probe | 60.1 |
| real_test | 122.2 |
| generate | 31.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46338 |
| trojan | 10541 |
| vmess | 10145 |
| shadowsocks | 9906 |
| hysteria2 | 254 |
| shadowsocksr | 162 |
| http | 159 |
| socks | 64 |
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
| 77.59 | shadowsocks | 218.1 | 510.3 | 22.73 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 173.244.56.6 |
| 77.44 | shadowsocks | 224.7 | 518.0 | 22.58 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 149.22.95.183 |
| 77.21 | shadowsocks | 234.3 | 503.0 | 22.35 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 173.244.56.9 |
| 76.58 | shadowsocks | 240.2 | 615.4 | 22.22 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 108.181.0.177 |
| 76.08 | shadowsocks | 261.5 | 725.8 | 21.72 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 108.181.118.10 |
| 73.07 | vless | 303.0 | 789.0 | 20.76 | 0.0 | 10.0 | 6.27 | 16.04 | Au1rxx-base64 | 15.204.97.214 |
| 72.8 | shadowsocks | 286.6 | 641.6 | 21.14 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 156.146.38.168 |
| 72.73 | vless | 318.1 | 834.4 | 20.42 | 0.0 | 10.0 | 6.27 | 16.04 | Au1rxx-base64 | 15.204.97.219 |
| 72.2 | shadowsocks | 292.6 | 654.2 | 21.0 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 156.146.38.170 |
| 71.09 | shadowsocks | 292.8 | 661.3 | 21.0 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 156.146.38.167 |
| 70.98 | shadowsocks | 291.2 | 337.7 | 21.04 | 2.34 | 9.93 | 12.82 | 16.04 | Au1rxx-base64 | 149.22.87.240 |
| 70.44 | shadowsocks | 297.0 | 349.2 | 20.9 | 1.91 | 9.93 | 12.82 | 16.04 | Au1rxx-base64 | 149.22.87.241 |
| 70.21 | shadowsocks | 297.6 | 356.0 | 20.89 | 1.65 | 9.92 | 12.82 | 16.04 | Au1rxx-base64 | 149.22.87.204 |
| 68.25 | shadowsocks | 371.6 | 748.9 | 19.18 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 37.19.198.244 |
| 68.18 | shadowsocks | 368.3 | 741.4 | 19.25 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 37.19.198.236 |
| 68.15 | shadowsocks | 372.4 | 755.8 | 19.16 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 37.19.198.243 |
| 67.92 | shadowsocks | 377.2 | 671.9 | 19.05 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 198.98.53.130 |
| 67.71 | shadowsocks | 373.5 | 753.6 | 19.13 | 0.0 | 10.0 | 12.82 | 16.04 | Au1rxx-base64 | 37.19.198.160 |
| 65.66 | shadowsocks | 393.3 | 577.4 | 18.67 | 0.0 | 9.92 | 12.82 | 16.04 | Au1rxx-base64 | 103.106.228.175 |
| 64.3 | vless | 357.8 | 413.9 | 19.5 | 0.0 | 9.92 | 6.27 | 16.04 | Au1rxx-base64 | 13.231.185.74 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | 1.0 | 50 | 73 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.733 | 191 | 5526 | prefer |
| Au1rxx-base64 | 0.755 | 0.757 | 70 | 124 | prefer |
| mheidari-all | 0.556 | 0.475 | 162 | 15741 | observe |
| DeltaKronecker-all | 0.475 | 0.392 | 74 | 6437 | observe |
| Surfboard-tg-vless | 0.335 | 1.0 | 1 | 4176 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4576 | observe |
| Epodonios-all | 0.255 | None | 0 | 8189 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7580 | observe |
| barry-far-vless | 0.255 | None | 0 | 4987 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4664 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.237 | None | 0 | 1559 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 59 |
| geo | ClientOSError | - | 52 |
| 204 | TimeoutError | - | 23 |
| 204 | ProxyError | - | 14 |
| cn-block | TimeoutError | - | 11 |
| geo | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 6 |
| geo | ProxyError | - | 6 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

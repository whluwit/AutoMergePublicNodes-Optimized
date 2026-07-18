# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-18 02:04:51 |
| 运行耗时 | 233.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 98 |
| 原始节点 | 82903 |
| 去重后节点 | 25435 |
| TCP 可达 | 3000 |
| 真实可用 | 760 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25435 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 0.9 |
| tcp | 34.1 |
| probe | 48.3 |
| real_test | 122.3 |
| generate | 23.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47631 |
| trojan | 13817 |
| vmess | 10940 |
| shadowsocks | 9958 |
| hysteria2 | 311 |
| shadowsocksr | 125 |
| http | 54 |
| socks | 53 |
| hysteria | 9 |
| tuic | 3 |
| anytls | 2 |

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
| 77.77 | shadowsocks | 267.6 | 742.3 | 21.58 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 37.19.198.243 |
| 77.41 | shadowsocks | 283.3 | 794.5 | 21.22 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 37.19.198.160 |
| 76.66 | shadowsocks | 229.5 | 635.5 | 22.47 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 37.19.198.236 |
| 74.79 | shadowsocks | 276.2 | 631.5 | 21.38 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 156.146.38.167 |
| 74.66 | shadowsocks | 284.3 | 643.6 | 21.2 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 156.146.38.168 |
| 74.31 | shadowsocks | 286.8 | 659.7 | 21.14 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 156.146.38.169 |
| 73.7 | shadowsocks | 227.7 | 628.1 | 22.51 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 37.19.198.244 |
| 71.85 | shadowsocks | 367.6 | 907.6 | 19.27 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 184.75.221.134 |
| 71.61 | shadowsocks | 224.7 | 609.1 | 22.58 | 0.0 | 10.0 | 12.27 | 10.76 | mheidari-all | 198.98.53.130 |
| 71.59 | shadowsocks | 228.0 | 618.8 | 22.5 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 71.37 | shadowsocks | 308.5 | 573.3 | 20.64 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 173.244.56.9 |
| 71.26 | shadowsocks | 302.8 | 567.6 | 20.77 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 173.244.56.6 |
| 70.68 | shadowsocks | 326.4 | 589.2 | 20.22 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 108.181.0.177 |
| 70.3 | shadowsocks | 329.0 | 592.2 | 20.16 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 108.181.118.10 |
| 70.26 | shadowsocks | 347.8 | 652.5 | 19.73 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 149.22.95.183 |
| 69.47 | shadowsocks | 297.7 | 683.6 | 20.89 | 0.0 | 10.0 | 12.27 | 17.92 | Au1rxx-base64 | 156.146.38.170 |
| 68.06 | trojan | 379.8 | 574.9 | 18.99 | 0.0 | 10.0 | 12.34 | 15.94 | Surfboard-tg-mixed | 104.16.71.48 |
| 67.66 | shadowsocks | 346.8 | 964.7 | 19.75 | 0.0 | 10.0 | 12.27 | 10.14 | DeltaKronecker-all | 68.168.222.210 |
| 67.52 | trojan | 374.3 | 583.2 | 19.11 | 0.0 | 10.0 | 12.34 | 15.94 | Surfboard-tg-mixed | 188.114.97.6 |
| 67.17 | trojan | 473.3 | 862.0 | 16.82 | 0.0 | 10.0 | 12.34 | 15.94 | Surfboard-tg-mixed | 165.215.250.14 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.988 | 0.913 | 161 | 5576 | prefer |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.972 | 0.895 | 313 | 16586 | prefer |
| Au1rxx-base64 | 0.911 | 0.912 | 125 | 149 | prefer |
| DeltaKronecker-all | 0.688 | 0.609 | 284 | 8967 | observe |
| xiaoji235-airport-v2ray-all | 0.629 | 1.0 | 8 | 4321 | observe |
| nscl5-all | 0.39 | 1.0 | 2 | 1976 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4428 | observe |
| Epodonios-all | 0.255 | None | 0 | 6707 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6820 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4298 | observe |
| barry-far-vless | 0.255 | None | 0 | 4912 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5263 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 94 |
| geo | TimeoutError | - | 35 |
| cn-block | TimeoutError | - | 13 |
| geo | ClientOSError | - | 10 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

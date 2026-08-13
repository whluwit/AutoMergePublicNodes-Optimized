# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 07:24:17 |
| 运行耗时 | 300.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79378 |
| 去重后节点 | 22353 |
| TCP 可达 | 3000 |
| 真实可用 | 732 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22353 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 34.3 |
| probe | 64.0 |
| real_test | 157.5 |
| generate | 37.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44349 |
| vmess | 13352 |
| trojan | 10423 |
| shadowsocks | 9771 |
| hysteria2 | 1151 |
| http | 160 |
| socks | 77 |
| shadowsocksr | 76 |
| tuic | 10 |
| hysteria | 7 |
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
| 82.25 | trojan | 216.4 | 528.4 | 22.77 | 0.0 | 10.0 | 12.9 | 19.08 | Au1rxx-base64 | 35.86.90.51 |
| 81.62 | shadowsocks | 231.9 | 633.0 | 22.41 | 0.0 | 10.0 | 14.13 | 19.08 | Au1rxx-base64 | 149.22.95.183 |
| 81.19 | trojan | 262.3 | 664.2 | 21.71 | 0.0 | 10.0 | 12.9 | 19.08 | Au1rxx-base64 | 44.242.235.129 |
| 81.12 | trojan | 265.2 | 664.3 | 21.64 | 0.0 | 10.0 | 12.9 | 19.08 | Au1rxx-base64 | 44.244.3.114 |
| 80.61 | trojan | 287.3 | 736.5 | 21.13 | 0.0 | 10.0 | 12.9 | 19.08 | Au1rxx-base64 | 44.246.163.102 |
| 79.17 | shadowsocks | 256.1 | 264.9 | 21.85 | 5.07 | 10.0 | 14.13 | 19.08 | Au1rxx-base64 | 149.22.87.204 |
| 79.01 | http | 299.3 | 667.4 | 20.85 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.209 |
| 78.92 | http | 305.1 | 507.6 | 20.72 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.208 |
| 78.9 | shadowsocks | 257.8 | 272.6 | 21.81 | 4.78 | 10.0 | 14.13 | 19.08 | Au1rxx-base64 | 149.22.87.240 |
| 78.78 | http | 303.9 | 500.7 | 20.74 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.215 |
| 78.73 | http | 307.1 | 528.4 | 20.67 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.211 |
| 78.48 | http | 261.2 | 549.1 | 21.73 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.220 |
| 78.46 | http | 314.6 | 527.7 | 20.49 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.199 |
| 78.45 | http | 351.5 | 807.8 | 19.64 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.210 |
| 78.37 | http | 307.6 | 521.3 | 20.66 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.206 |
| 78.04 | http | 261.7 | 558.7 | 21.72 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.214 |
| 78.04 | http | 263.9 | 567.3 | 21.67 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.195 |
| 78.04 | hysteria2 | 380.6 | 840.9 | 18.97 | 0.0 | 10.0 | 14.32 | 19.08 | Au1rxx-base64 | 138.124.68.188 |
| 77.91 | http | 258.2 | 541.6 | 21.8 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.204 |
| 77.9 | http | 330.0 | 652.1 | 20.14 | 0.0 | 10.0 | 14.77 | 19.82 | zhangkai | 138.199.35.212 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.951 | 452 | 1509 | prefer |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Surfboard-tg-mixed | 0.777 | 0.7 | 140 | 5801 | prefer |
| mheidari-all | 0.545 | 0.464 | 125 | 16910 | observe |
| DeltaKronecker-all | 0.341 | 0.254 | 67 | 4975 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5203 | observe |
| Epodonios-all | 0.255 | None | 0 | 6457 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7624 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4621 | observe |
| barry-far-vless | 0.255 | None | 0 | 5041 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| nscl5-all | 0.241 | None | 0 | 1654 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1509 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 67 |
| speed | TimeoutError | - | 32 |
| 204 | TimeoutError | - | 23 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 13 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | status | 403 | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

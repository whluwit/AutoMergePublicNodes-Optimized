# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 01:02:37 |
| 运行耗时 | 378.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 80342 |
| 去重后节点 | 23001 |
| TCP 可达 | 3000 |
| 真实可用 | 1289 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23001 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 0.9 |
| tcp | 35.5 |
| probe | 72.6 |
| real_test | 237.5 |
| generate | 25.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45783 |
| trojan | 13495 |
| shadowsocks | 9904 |
| vmess | 8571 |
| hysteria2 | 2171 |
| http | 193 |
| socks | 122 |
| shadowsocksr | 79 |
| tuic | 15 |
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
| 85.21 | http | 191.2 | 484.5 | 23.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 85.21 | http | 191.4 | 484.6 | 23.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 85.18 | http | 192.6 | 487.4 | 23.32 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 85.15 | http | 193.9 | 485.7 | 23.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.12 | http | 195.1 | 500.5 | 23.26 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 85.09 | http | 196.6 | 506.6 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 85.07 | http | 197.1 | 510.2 | 23.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 85.07 | http | 197.3 | 507.5 | 23.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 85.06 | http | 197.6 | 510.5 | 23.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 85.06 | http | 197.8 | 504.9 | 23.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.06 | http | 198.0 | 500.3 | 23.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 85.0 | http | 200.2 | 510.1 | 23.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 84.95 | http | 202.4 | 475.6 | 23.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 84.88 | http | 205.5 | 523.0 | 23.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 84.83 | trojan | 232.6 | 536.9 | 22.39 | 0.0 | 10.0 | 14.94 | 20.0 | mheidari-all | 44.247.89.62 |
| 84.75 | trojan | 236.3 | 546.0 | 22.31 | 0.0 | 10.0 | 14.94 | 20.0 | mheidari-all | 44.251.158.80 |
| 84.63 | trojan | 241.2 | 556.7 | 22.19 | 0.0 | 10.0 | 14.94 | 20.0 | mheidari-all | 54.245.126.186 |
| 84.57 | trojan | 244.0 | 570.7 | 22.13 | 0.0 | 10.0 | 14.94 | 20.0 | mheidari-all | 35.88.210.26 |
| 84.52 | trojan | 246.0 | 577.8 | 22.08 | 0.0 | 10.0 | 14.94 | 20.0 | mheidari-all | 34.217.192.97 |
| 84.42 | trojan | 242.3 | 560.9 | 22.17 | 0.0 | 10.0 | 14.94 | 20.0 | mheidari-all | 100.22.163.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.966 | 438 | 1475 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.95 | 0.871 | 703 | 16056 | prefer |
| Surfboard-tg-mixed | 0.832 | 0.755 | 139 | 6145 | prefer |
| DeltaKronecker-all | 0.339 | 0.253 | 79 | 6368 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 179 | observe |
| Epodonios-all | 0.255 | None | 0 | 6777 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3984 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6825 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4833 | observe |
| barry-far-vless | 0.255 | None | 0 | 5165 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4027 | observe |
| nscl5-all | 0.255 | None | 0 | 2992 | observe |
| Au1rxx-clash | 0.234 | None | 0 | 1475 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 85 |
| speed | TimeoutError | - | 46 |
| geo | ClientOSError | - | 25 |
| speed | ClientOSError | - | 13 |
| cn-block | TimeoutError | - | 10 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

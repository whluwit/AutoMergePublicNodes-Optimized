# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-05 08:50:05 |
| 运行耗时 | 172.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 79583 |
| 去重后节点 | 23923 |
| TCP 可达 | 3000 |
| 真实可用 | 381 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23923 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.5 |
| tcp | 31.0 |
| probe | 44.8 |
| real_test | 72.1 |
| generate | 18.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46420 |
| trojan | 12394 |
| vmess | 10431 |
| shadowsocks | 9535 |
| hysteria2 | 456 |
| shadowsocksr | 153 |
| http | 135 |
| socks | 48 |
| hysteria | 6 |
| tuic | 5 |

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
| 78.11 | trojan | 304.6 | 745.2 | 20.73 | 0.0 | 10.0 | 13.76 | 17.12 | DeltaKronecker-all | 149.28.241.235 |
| 78.05 | trojan | 307.3 | 748.5 | 20.67 | 0.0 | 10.0 | 13.76 | 17.12 | DeltaKronecker-all | 45.32.195.168 |
| 78.02 | trojan | 306.7 | 757.6 | 20.68 | 0.0 | 10.0 | 13.76 | 17.12 | DeltaKronecker-all | 45.32.198.247 |
| 77.64 | shadowsocks | 251.4 | 627.1 | 21.96 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 156.146.38.169 |
| 77.48 | shadowsocks | 258.2 | 649.9 | 21.8 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 37.19.198.244 |
| 77.47 | shadowsocks | 258.6 | 599.3 | 21.79 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 156.146.38.168 |
| 77.45 | shadowsocks | 259.5 | 654.8 | 21.77 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 37.19.198.236 |
| 77.43 | shadowsocks | 260.4 | 641.7 | 21.75 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 156.146.38.167 |
| 77.36 | shadowsocks | 263.4 | 655.1 | 21.68 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 37.19.198.243 |
| 77.32 | shadowsocks | 265.0 | 652.4 | 21.64 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 37.19.198.160 |
| 77.16 | shadowsocks | 272.2 | 613.3 | 21.48 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 198.98.53.130 |
| 76.28 | shadowsocks | 288.3 | 690.4 | 21.1 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 108.181.57.93 |
| 76.24 | shadowsocks | 336.9 | 867.6 | 19.98 | 0.0 | 10.0 | 13.64 | 17.12 | DeltaKronecker-all | 185.196.61.82 |
| 74.92 | trojan | 292.2 | 697.7 | 21.02 | 0.0 | 10.0 | 13.76 | 17.12 | DeltaKronecker-all | 64.94.95.114 |
| 74.58 | shadowsocks | 253.8 | 630.8 | 21.9 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 156.146.38.170 |
| 74.11 | trojan | 304.7 | 583.1 | 20.73 | 0.0 | 10.0 | 13.76 | 14.2 | Surfboard-tg-mixed | 104.26.15.137 |
| 73.0 | trojan | 344.6 | 856.0 | 19.8 | 0.0 | 10.0 | 13.76 | 17.12 | DeltaKronecker-all | 64.94.95.115 |
| 72.33 | shadowsocks | 301.2 | 619.2 | 20.81 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 149.22.95.183 |
| 72.18 | shadowsocks | 296.5 | 573.5 | 20.92 | 0.0 | 10.0 | 13.64 | 16.04 | Au1rxx-base64 | 173.244.56.9 |
| 71.84 | trojan | 431.2 | 1122.4 | 17.8 | 0.0 | 10.0 | 13.76 | 17.12 | DeltaKronecker-all | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.913 | 0.841 | 82 | 16512 | prefer |
| Au1rxx-base64 | 0.911 | 0.933 | 30 | 109 | prefer |
| DeltaKronecker-all | 0.905 | 0.828 | 192 | 7739 | prefer |
| Surfboard-tg-mixed | 0.859 | 0.784 | 111 | 6080 | prefer |
| nscl5-all | 0.308 | 1.0 | 1 | 1323 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4662 | observe |
| Epodonios-all | 0.255 | None | 0 | 6920 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7236 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4554 | observe |
| barry-far-vless | 0.255 | None | 0 | 5158 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 19 |
| 204 | ProxyError | - | 13 |
| speed | ClientOSError | - | 12 |
| 204 | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 7 |
| geo | ClientOSError | - | 4 |
| cn-block | TimeoutError | - | 4 |
| speed | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

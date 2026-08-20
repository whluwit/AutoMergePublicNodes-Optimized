# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 12:42:57 |
| 运行耗时 | 337.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 94200 |
| 去重后节点 | 25172 |
| TCP 可达 | 3000 |
| 真实可用 | 1034 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25172 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 0.6 |
| tcp | 39.1 |
| probe | 66.7 |
| real_test | 190.8 |
| generate | 34.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52817 |
| trojan | 18253 |
| shadowsocks | 10723 |
| vmess | 10176 |
| hysteria2 | 1676 |
| shadowsocksr | 198 |
| http | 164 |
| socks | 134 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 12 |

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
| 84.76 | trojan | 200.6 | 514.6 | 23.13 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 14.1.28.76 |
| 84.5 | trojan | 233.7 | 542.4 | 22.37 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 35.91.138.234 |
| 84.43 | trojan | 236.8 | 547.2 | 22.3 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 35.91.251.124 |
| 84.41 | trojan | 237.3 | 543.8 | 22.28 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 100.22.163.167 |
| 84.36 | trojan | 239.5 | 551.7 | 22.23 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 84.34 | trojan | 239.4 | 558.2 | 22.24 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 35.88.120.18 |
| 84.32 | trojan | 241.5 | 565.7 | 22.19 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 34.221.30.108 |
| 84.03 | hysteria2 | 233.6 | 229.3 | 22.37 | 6.4 | 9.92 | 13.57 | 20.0 | Au1rxx-base64 | 45.32.252.144 |
| 83.98 | http | 199.2 | 508.7 | 23.17 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 83.89 | trojan | 257.1 | 605.7 | 21.83 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 54.244.169.225 |
| 83.82 | http | 205.9 | 528.1 | 23.01 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 83.8 | trojan | 261.3 | 621.3 | 21.73 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 35.90.27.143 |
| 83.69 | trojan | 268.7 | 645.8 | 21.56 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 44.243.85.47 |
| 83.61 | trojan | 272.1 | 654.5 | 21.48 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 44.251.158.80 |
| 83.3 | trojan | 285.3 | 680.6 | 21.17 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 35.160.249.189 |
| 83.25 | trojan | 287.8 | 698.4 | 21.12 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 34.220.224.252 |
| 82.91 | trojan | 289.9 | 708.4 | 21.07 | 0.0 | 10.0 | 14.63 | 20.0 | Au1rxx-base64 | 34.210.213.17 |
| 82.83 | shadowsocks | 196.0 | 473.9 | 23.24 | 0.0 | 10.0 | 14.09 | 20.0 | mheidari-all | 108.181.118.10 |
| 82.82 | trojan | 237.4 | 552.7 | 22.28 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 34.222.243.142 |
| 82.69 | trojan | 290.2 | 709.5 | 21.06 | 0.0 | 10.0 | 14.63 | 20.0 | mheidari-all | 35.88.210.26 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.979 | 565 | 1789 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| mheidari-all | 0.847 | 0.769 | 458 | 21209 | prefer |
| Surfboard-tg-mixed | 0.819 | 0.762 | 21 | 6433 | prefer |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| Epodonios-all | 0.255 | None | 0 | 7150 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3991 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7279 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5109 | observe |
| barry-far-vless | 0.255 | None | 0 | 5434 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4586 | observe |
| nscl5-all | 0.255 | None | 0 | 2418 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 48 |
| 204 | TimeoutError | - | 21 |
| geo | TimeoutError | - | 21 |
| speed | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 9 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

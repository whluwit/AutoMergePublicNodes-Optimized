# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-06 02:11:02 |
| 运行耗时 | 264.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 88519 |
| 去重后节点 | 24703 |
| TCP 可达 | 3000 |
| 真实可用 | 525 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24703 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.3 |
| tcp | 36.7 |
| probe | 52.8 |
| real_test | 130.3 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52555 |
| vmess | 13175 |
| trojan | 11033 |
| shadowsocks | 10118 |
| hysteria2 | 1388 |
| socks | 100 |
| shadowsocksr | 73 |
| http | 24 |
| hysteria | 20 |
| anytls | 19 |
| tuic | 14 |

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
| 84.32 | hysteria2 | 233.0 | 637.3 | 22.38 | 0.0 | 10.0 | 13.12 | 19.92 | Au1rxx-base64 | 159.223.157.129 |
| 84.24 | hysteria2 | 241.1 | 662.5 | 22.2 | 0.0 | 10.0 | 13.12 | 19.92 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 84.04 | hysteria2 | 249.4 | 693.8 | 22.0 | 0.0 | 10.0 | 13.12 | 19.92 | Au1rxx-base64 | 138.124.68.188 |
| 83.3 | trojan | 252.2 | 682.1 | 21.94 | 0.0 | 10.0 | 14.44 | 19.92 | Au1rxx-base64 | 153.75.250.171 |
| 80.47 | shadowsocks | 275.9 | 757.5 | 21.39 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 37.19.198.236 |
| 80.06 | shadowsocks | 293.9 | 618.5 | 20.98 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 37.19.198.244 |
| 80.03 | shadowsocks | 295.1 | 818.2 | 20.95 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 37.19.198.160 |
| 79.74 | vless | 333.7 | 905.5 | 20.05 | 0.0 | 10.0 | 9.77 | 19.92 | Au1rxx-base64 | 78.111.89.171 |
| 79.04 | shadowsocks | 294.4 | 813.6 | 20.96 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 198.98.53.130 |
| 78.62 | shadowsocks | 269.6 | 744.4 | 21.54 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 37.19.198.243 |
| 78.31 | shadowsocks | 276.5 | 638.1 | 21.38 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 156.146.38.170 |
| 77.69 | trojan | 307.5 | 663.6 | 20.66 | 0.0 | 10.0 | 14.44 | 19.92 | Au1rxx-base64 | 163.245.196.68 |
| 77.34 | shadowsocks | 292.0 | 679.8 | 21.02 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 156.146.38.167 |
| 77.32 | shadowsocks | 318.0 | 648.0 | 20.42 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 156.146.38.168 |
| 75.85 | shadowsocks | 275.2 | 634.8 | 21.41 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 156.146.38.169 |
| 75.7 | shadowsocks | 336.5 | 754.4 | 19.99 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 108.181.57.93 |
| 75.55 | shadowsocks | 467.0 | 1319.5 | 16.97 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 68.168.222.210 |
| 75.32 | shadowsocks | 364.2 | 913.8 | 19.35 | 0.0 | 10.0 | 13.16 | 19.92 | Au1rxx-base64 | 185.196.61.82 |
| 74.68 | hysteria2 | 398.7 | 795.1 | 18.55 | 0.0 | 10.0 | 13.12 | 19.92 | Au1rxx-base64 | 62.210.124.146 |
| 74.68 | hysteria2 | 420.6 | 870.0 | 18.04 | 0.0 | 10.0 | 13.12 | 19.92 | Au1rxx-base64 | 5.255.102.165 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.961 | 362 | 1423 | prefer |
| zhangkai | 0.789 | 1.0 | 15 | 25 | prefer |
| Surfboard-tg-mixed | 0.673 | 0.594 | 180 | 5917 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6515 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7468 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4798 | observe |
| barry-far-vless | 0.255 | None | 0 | 5104 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5206 | observe |
| mheidari-all | 0.254 | 0.172 | 291 | 21048 | observe |
| Au1rxx-clash | 0.232 | None | 0 | 1423 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 178 |
| speed | TimeoutError | - | 60 |
| geo | ClientOSError | - | 50 |
| speed | ClientOSError | - | 45 |
| 204 | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

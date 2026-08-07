# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 07:10:58 |
| 运行耗时 | 223.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 89355 |
| 去重后节点 | 24213 |
| TCP 可达 | 3000 |
| 真实可用 | 440 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24213 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 36.5 |
| probe | 50.0 |
| real_test | 96.1 |
| generate | 34.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52366 |
| vmess | 13507 |
| trojan | 11306 |
| shadowsocks | 10371 |
| hysteria2 | 1531 |
| socks | 106 |
| shadowsocksr | 70 |
| http | 35 |
| anytls | 30 |
| hysteria | 21 |
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
| 84.92 | hysteria2 | 237.4 | 644.4 | 22.28 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.96 | hysteria2 | 307.1 | 855.3 | 20.67 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.72 | hysteria2 | 257.7 | 703.9 | 21.81 | 0.0 | 8.62 | 14.29 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 82.53 | shadowsocks | 242.0 | 650.1 | 22.18 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 81.25 | shadowsocks | 297.0 | 817.9 | 20.9 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 79.92 | shadowsocks | 280.6 | 640.4 | 21.28 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 79.0 | trojan | 396.5 | 1099.3 | 18.6 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 78.24 | shadowsocks | 317.2 | 753.5 | 20.44 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.35 | trojan | 311.3 | 674.9 | 20.57 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 77.17 | shadowsocks | 277.7 | 640.5 | 21.35 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 77.15 | shadowsocks | 258.2 | 696.0 | 21.8 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 76.89 | shadowsocks | 463.8 | 1300.8 | 17.04 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 68.168.222.210 |
| 76.8 | trojan | 301.2 | 665.0 | 20.81 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 76.79 | shadowsocks | 309.1 | 696.9 | 20.62 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 76.63 | shadowsocks | 276.4 | 638.2 | 21.38 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 76.37 | trojan | 328.4 | 748.1 | 20.18 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 75.95 | hysteria2 | 403.3 | 647.7 | 18.44 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 75.93 | hysteria2 | 427.5 | 886.8 | 17.88 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 5.255.102.165 |
| 75.47 | trojan | 350.3 | 813.7 | 19.67 | 0.0 | 10.0 | 13.4 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 75.38 | shadowsocks | 308.0 | 602.6 | 20.65 | 0.0 | 10.0 | 14.35 | 20.0 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.954 | 368 | 1258 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| DeltaKronecker-all | 0.58 | 0.5 | 34 | 5326 | observe |
| Surfboard-tg-mixed | 0.499 | 0.417 | 84 | 6241 | observe |
| mheidari-all | 0.421 | 0.333 | 42 | 20715 | observe |
| nscl5-all | 0.278 | 0.5 | 2 | 1772 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| xiaoji235-airport-v2ray-all | 0.259 | 0.333 | 3 | 5184 | observe |
| Epodonios-all | 0.255 | None | 0 | 6539 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7511 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4967 | observe |
| barry-far-vless | 0.255 | None | 0 | 5297 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5247 | observe |
| Au1rxx-clash | 0.225 | None | 0 | 1258 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 43 |
| geo | ClientOSError | - | 24 |
| speed | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 10 |
| speed | ClientOSError | - | 9 |
| cn-block | TimeoutError | - | 9 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

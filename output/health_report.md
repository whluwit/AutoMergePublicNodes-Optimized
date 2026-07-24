# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-24 19:22:52 |
| 运行耗时 | 289.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83200 |
| 去重后节点 | 22824 |
| TCP 可达 | 3000 |
| 真实可用 | 589 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22824 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.0 |
| tcp | 32.2 |
| probe | 65.9 |
| real_test | 143.8 |
| generate | 42.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47185 |
| trojan | 15182 |
| vmess | 10266 |
| shadowsocks | 9937 |
| hysteria2 | 399 |
| socks | 79 |
| shadowsocksr | 75 |
| http | 51 |
| hysteria | 15 |
| tuic | 9 |
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
| 75.7 | vless | 230.2 | 637.7 | 22.45 | 0.0 | 10.0 | 6.89 | 16.36 | mheidari-all | 47.89.186.170 |
| 74.9 | vless | 264.5 | 650.5 | 21.65 | 0.0 | 10.0 | 6.89 | 16.36 | mheidari-all | 154.193.55.183 |
| 73.82 | trojan | 450.5 | 1279.0 | 17.35 | 0.0 | 10.0 | 13.11 | 16.36 | mheidari-all | 153.75.250.171 |
| 73.42 | vless | 292.3 | 673.1 | 21.01 | 0.0 | 10.0 | 6.89 | 16.36 | mheidari-all | 45.206.5.122 |
| 72.34 | trojan | 354.4 | 800.8 | 19.58 | 0.0 | 10.0 | 13.11 | 16.36 | mheidari-all | 163.245.196.68 |
| 71.39 | vmess | 356.1 | 1026.6 | 19.53 | 0.0 | 10.0 | 10.0 | 16.36 | mheidari-all | 67.220.95.3 |
| 69.53 | shadowsocks | 227.4 | 627.1 | 22.51 | 0.0 | 10.0 | 9.0 | 12.02 | Au1rxx-base64 | 37.19.198.243 |
| 69.5 | shadowsocks | 228.9 | 629.8 | 22.48 | 0.0 | 10.0 | 9.0 | 12.02 | Au1rxx-base64 | 37.19.198.236 |
| 69.08 | trojan | 329.8 | 746.7 | 20.14 | 0.0 | 10.0 | 13.11 | 12.02 | Au1rxx-base64 | 64.94.95.114 |
| 68.87 | trojan | 429.0 | 1095.3 | 17.85 | 0.0 | 10.0 | 13.11 | 14.22 | DeltaKronecker-all | 64.74.163.118 |
| 68.5 | vless | 288.7 | 530.5 | 21.09 | 0.0 | 10.0 | 6.89 | 16.36 | mheidari-all | 104.16.9.20 |
| 68.21 | shadowsocks | 320.8 | 863.1 | 20.35 | 0.0 | 10.0 | 9.0 | 16.36 | mheidari-all | 50.114.177.134 |
| 67.91 | trojan | 434.4 | 786.6 | 17.72 | 0.0 | 10.0 | 13.11 | 16.36 | mheidari-all | 79.133.126.237 |
| 67.73 | trojan | 436.5 | 786.4 | 17.67 | 0.0 | 10.0 | 13.11 | 16.36 | mheidari-all | 79.133.126.190 |
| 67.47 | trojan | 450.7 | 804.6 | 17.34 | 0.0 | 10.0 | 13.11 | 16.36 | mheidari-all | 89.39.70.222 |
| 67.42 | trojan | 455.0 | 823.8 | 17.25 | 0.0 | 10.0 | 13.11 | 16.36 | mheidari-all | 89.39.70.49 |
| 66.91 | vless | 332.3 | 675.5 | 20.09 | 0.0 | 10.0 | 6.89 | 16.36 | mheidari-all | 198.41.209.87 |
| 66.56 | shadowsocks | 334.5 | 842.8 | 20.04 | 0.0 | 10.0 | 9.0 | 12.02 | Au1rxx-base64 | 185.196.61.82 |
| 66.52 | trojan | 423.7 | 594.9 | 17.97 | 0.0 | 10.0 | 13.11 | 14.58 | Surfboard-tg-mixed | 151.101.1.194 |
| 66.25 | trojan | 422.9 | 997.3 | 17.99 | 0.0 | 10.0 | 13.11 | 12.02 | Au1rxx-base64 | 64.94.95.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.95 | 0.972 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.928 | 0.856 | 90 | 5475 | prefer |
| mheidari-all | 0.788 | 0.708 | 583 | 19355 | prefer |
| DeltaKronecker-all | 0.73 | 0.654 | 78 | 5559 | prefer |
| Au1rxx-base64 | 0.636 | 1.0 | 10 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 3847 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6668 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6766 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4271 | observe |
| barry-far-vless | 0.255 | None | 0 | 4905 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| nscl5-all | 0.255 | None | 0 | 3124 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 85 |
| speed | ClientOSError | - | 59 |
| cn-block | TimeoutError | - | 30 |
| 204 | TimeoutError | - | 13 |
| geo | ClientOSError | - | 10 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

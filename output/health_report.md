# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-21 02:16:08 |
| 运行耗时 | 303.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84403 |
| 去重后节点 | 24287 |
| TCP 可达 | 3000 |
| 真实可用 | 535 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24287 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.0 |
| tcp | 33.4 |
| probe | 61.9 |
| real_test | 165.0 |
| generate | 35.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50569 |
| trojan | 11918 |
| vmess | 10952 |
| shadowsocks | 10366 |
| hysteria2 | 408 |
| shadowsocksr | 71 |
| http | 53 |
| socks | 48 |
| hysteria | 10 |
| tuic | 7 |
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
| 76.67 | shadowsocks | 229.5 | 603.2 | 22.46 | 0.0 | 8.99 | 12.52 | 16.7 | Au1rxx-base64 | 198.98.53.130 |
| 76.51 | shadowsocks | 237.7 | 640.1 | 22.28 | 0.0 | 9.01 | 12.52 | 16.7 | Au1rxx-base64 | 37.19.198.243 |
| 76.5 | shadowsocks | 237.4 | 636.0 | 22.28 | 0.0 | 9.0 | 12.52 | 16.7 | Au1rxx-base64 | 37.19.198.160 |
| 76.43 | shadowsocks | 240.5 | 649.1 | 22.21 | 0.0 | 9.0 | 12.52 | 16.7 | Au1rxx-base64 | 37.19.198.236 |
| 75.76 | shadowsocks | 247.8 | 657.9 | 22.04 | 0.0 | 9.0 | 12.52 | 16.7 | Au1rxx-base64 | 68.168.222.210 |
| 75.73 | shadowsocks | 248.6 | 650.4 | 22.02 | 0.0 | 8.99 | 12.52 | 16.7 | Au1rxx-base64 | 108.181.57.93 |
| 73.47 | shadowsocks | 238.6 | 646.2 | 22.25 | 0.0 | 9.0 | 12.52 | 16.7 | Au1rxx-base64 | 37.19.198.244 |
| 73.36 | shadowsocks | 279.9 | 631.4 | 21.3 | 0.0 | 9.0 | 12.52 | 16.7 | Au1rxx-base64 | 156.146.38.170 |
| 72.74 | shadowsocks | 280.0 | 643.6 | 21.3 | 0.0 | 9.0 | 12.52 | 16.7 | Au1rxx-base64 | 156.146.38.168 |
| 71.99 | shadowsocks | 341.9 | 822.6 | 19.86 | 0.0 | 9.0 | 12.52 | 16.7 | Au1rxx-base64 | 185.196.61.82 |
| 70.33 | trojan | 290.4 | 633.0 | 21.05 | 0.0 | 9.12 | 9.5 | 16.7 | Au1rxx-base64 | 64.94.95.118 |
| 70.24 | trojan | 290.8 | 634.0 | 21.05 | 0.0 | 9.12 | 9.5 | 16.7 | Au1rxx-base64 | 64.94.95.117 |
| 70.1 | hysteria2 | 421.2 | 870.6 | 18.03 | 0.0 | 8.96 | 12.5 | 16.7 | Au1rxx-base64 | 5.255.102.165 |
| 68.59 | shadowsocks | 320.0 | 579.4 | 20.37 | 0.0 | 8.99 | 12.52 | 16.7 | Au1rxx-base64 | 173.244.56.9 |
| 68.52 | shadowsocks | 301.0 | 815.3 | 20.81 | 0.0 | 8.99 | 12.52 | 16.7 | Au1rxx-base64 | 147.90.234.133 |
| 68.51 | shadowsocks | 444.6 | 1146.9 | 17.49 | 0.0 | 8.99 | 12.52 | 16.7 | Au1rxx-base64 | 156.146.38.169 |
| 68.22 | hysteria2 | 458.5 | 760.9 | 17.16 | 0.0 | 8.96 | 12.5 | 16.7 | Au1rxx-base64 | 62.210.124.146 |
| 68.0 | shadowsocks | 327.7 | 598.7 | 20.19 | 0.0 | 8.99 | 12.52 | 16.7 | Au1rxx-base64 | 108.181.0.177 |
| 67.87 | trojan | 385.3 | 912.4 | 18.86 | 0.0 | 9.12 | 9.5 | 16.7 | Au1rxx-base64 | 64.94.95.114 |
| 67.54 | shadowsocks | 305.2 | 562.5 | 20.71 | 0.0 | 9.11 | 12.52 | 16.7 | Au1rxx-base64 | 216.105.168.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.862 | 0.843 | 249 | 528 | prefer |
| Surfboard-tg-mixed | 0.597 | 0.518 | 170 | 5484 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4304 | observe |
| mheidari-all | 0.369 | 0.289 | 620 | 19966 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4714 | observe |
| Epodonios-all | 0.255 | None | 0 | 6601 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6814 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4255 | observe |
| barry-far-vless | 0.255 | None | 0 | 4952 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5173 | observe |
| nscl5-all | 0.255 | None | 0 | 2111 | observe |
| DeltaKronecker-all | 0.254 | 0.168 | 107 | 5962 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 284 |
| geo | TimeoutError | - | 200 |
| speed | TimeoutError | - | 55 |
| geo | ClientOSError | - | 47 |
| cn-block | TimeoutError | - | 47 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

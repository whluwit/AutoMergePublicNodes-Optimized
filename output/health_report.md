# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-29 03:04:04 |
| 运行耗时 | 262.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 75922 |
| 去重后节点 | 22955 |
| TCP 可达 | 3000 |
| 真实可用 | 637 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22955 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.4 |
| tcp | 30.6 |
| probe | 55.5 |
| real_test | 140.2 |
| generate | 30.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42570 |
| trojan | 12443 |
| vmess | 10984 |
| shadowsocks | 9358 |
| hysteria2 | 222 |
| shadowsocksr | 159 |
| http | 136 |
| socks | 43 |
| hysteria | 6 |
| tuic | 1 |

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
| 79.17 | vless | 259.4 | 736.4 | 21.77 | 0.0 | 10.0 | 10.84 | 16.56 | mheidari-all | 47.253.226.114 |
| 76.02 | shadowsocks | 222.4 | 606.6 | 22.63 | 0.0 | 10.0 | 10.83 | 16.56 | mheidari-all | 198.98.53.130 |
| 75.64 | vless | 364.7 | 651.2 | 19.34 | 0.0 | 10.0 | 10.84 | 16.56 | mheidari-all | 162.159.34.128 |
| 75.43 | vless | 248.4 | 655.5 | 22.03 | 0.0 | 10.0 | 10.84 | 15.56 | Au1rxx-base64 | 159.89.87.21 |
| 74.88 | shadowsocks | 228.6 | 628.5 | 22.49 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 37.19.198.243 |
| 74.87 | shadowsocks | 250.4 | 654.9 | 21.98 | 0.0 | 10.0 | 10.83 | 16.56 | mheidari-all | 108.181.57.93 |
| 74.77 | shadowsocks | 233.3 | 651.3 | 22.38 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 37.19.198.244 |
| 74.48 | vless | 289.2 | 672.1 | 21.08 | 0.0 | 10.0 | 10.84 | 16.56 | mheidari-all | 104.19.87.194 |
| 72.8 | shadowsocks | 231.9 | 645.2 | 22.41 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 37.19.198.236 |
| 72.59 | vless | 262.9 | 653.3 | 21.69 | 0.0 | 10.0 | 10.84 | 11.06 | DeltaKronecker-all | 198.41.209.87 |
| 72.47 | vless | 267.5 | 670.8 | 21.59 | 0.0 | 10.0 | 10.84 | 11.06 | DeltaKronecker-all | 104.19.142.226 |
| 71.77 | shadowsocks | 233.2 | 649.1 | 22.38 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 37.19.198.160 |
| 71.71 | vless | 263.0 | 651.5 | 21.69 | 0.0 | 10.0 | 10.84 | 11.06 | DeltaKronecker-all | 104.25.161.29 |
| 71.62 | shadowsocks | 285.8 | 638.4 | 21.16 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 156.146.38.170 |
| 71.6 | vless | 262.5 | 646.3 | 21.7 | 0.0 | 10.0 | 10.84 | 11.06 | DeltaKronecker-all | 104.17.238.33 |
| 71.44 | shadowsocks | 278.9 | 640.2 | 21.32 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 156.146.38.168 |
| 71.31 | shadowsocks | 360.9 | 980.7 | 19.42 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 172.234.202.34 |
| 70.38 | vless | 292.8 | 804.1 | 21.0 | 0.0 | 10.0 | 10.84 | 13.42 | Surfboard-tg-mixed | 137.184.218.169 |
| 70.37 | shadowsocks | 272.4 | 622.1 | 21.47 | 0.0 | 10.0 | 10.83 | 15.56 | Au1rxx-base64 | 156.146.38.169 |
| 70.14 | vless | 274.8 | 664.4 | 21.42 | 0.0 | 10.0 | 10.84 | 11.06 | DeltaKronecker-all | 104.17.90.246 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.904 | 0.826 | 368 | 16006 | prefer |
| Surfboard-tg-mixed | 0.799 | 0.72 | 268 | 5165 | prefer |
| Au1rxx-base64 | 0.617 | 0.619 | 42 | 85 | observe |
| nscl5-all | 0.358 | 1.0 | 2 | 1166 | observe |
| DeltaKronecker-all | 0.299 | 0.218 | 349 | 6788 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7662 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6972 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3804 | observe |
| barry-far-vless | 0.255 | None | 0 | 4390 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5325 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.226 | None | 0 | 1269 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 179 |
| speed | ClientOSError | - | 130 |
| geo | ClientOSError | - | 59 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 18 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 7 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

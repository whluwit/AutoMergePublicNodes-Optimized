# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-10 19:25:15 |
| 运行耗时 | 239.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 76180 |
| 去重后节点 | 23857 |
| TCP 可达 | 3000 |
| 真实可用 | 279 |
| Verified 输出 | 279 |
| Global 输出 | 293 |
| All 输出 | 23857 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.7 |
| tcp | 32.2 |
| probe | 52.3 |
| real_test | 98.2 |
| generate | 50.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43287 |
| trojan | 12268 |
| vmess | 10648 |
| shadowsocks | 9309 |
| hysteria2 | 289 |
| shadowsocksr | 142 |
| http | 135 |
| socks | 88 |
| hysteria | 8 |
| anytls | 5 |
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
| 77.88 | shadowsocks | 250.5 | 602.9 | 21.98 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 156.146.38.167 |
| 77.82 | shadowsocks | 253.0 | 617.9 | 21.92 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 156.146.38.168 |
| 77.24 | shadowsocks | 257.8 | 622.3 | 21.81 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 156.146.38.169 |
| 77.22 | shadowsocks | 278.9 | 690.5 | 21.32 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 37.19.198.160 |
| 76.99 | shadowsocks | 287.3 | 715.5 | 21.13 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 37.19.198.243 |
| 76.23 | shadowsocks | 321.7 | 811.9 | 20.33 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 37.19.198.244 |
| 75.53 | shadowsocks | 292.6 | 736.5 | 21.0 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 156.146.38.170 |
| 74.74 | shadowsocks | 282.5 | 704.2 | 21.24 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 37.19.198.236 |
| 72.38 | shadowsocks | 295.0 | 545.0 | 20.95 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 173.244.56.9 |
| 72.36 | shadowsocks | 279.9 | 661.3 | 21.3 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 108.181.57.93 |
| 72.26 | shadowsocks | 278.6 | 548.8 | 21.33 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 108.181.0.177 |
| 72.14 | shadowsocks | 290.9 | 565.6 | 21.04 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 173.244.56.6 |
| 71.99 | shadowsocks | 311.2 | 628.1 | 20.57 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 149.22.95.183 |
| 71.84 | vmess | 391.1 | 1010.4 | 18.72 | 0.0 | 10.0 | 13.12 | 14.5 | Surfboard-tg-mixed | 67.220.95.3 |
| 71.35 | shadowsocks | 322.8 | 601.4 | 20.3 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | 108.181.118.10 |
| 70.33 | trojan | 297.6 | 730.4 | 20.89 | 0.0 | 10.0 | 6.59 | 17.54 | Au1rxx-base64 | 149.28.241.235 |
| 69.88 | hysteria2 | 394.9 | 720.4 | 18.64 | 0.0 | 9.95 | 11.25 | 17.54 | Au1rxx-base64 | 62.210.124.146 |
| 69.87 | shadowsocks | 272.7 | 655.7 | 21.46 | 0.0 | 10.0 | 12.36 | 17.54 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 69.4 | shadowsocks | 259.4 | 625.3 | 21.77 | 0.0 | 10.0 | 12.36 | 14.5 | Surfboard-tg-mixed | 198.98.53.130 |
| 69.1 | vmess | 471.6 | 1017.5 | 16.86 | 0.0 | 10.0 | 13.12 | 14.5 | Surfboard-tg-mixed | 67.220.85.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.829 | 0.833 | 72 | 120 | prefer |
| mheidari-all | 0.772 | 0.708 | 24 | 16338 | prefer |
| Surfboard-tg-mixed | 0.606 | 0.526 | 232 | 5583 | observe |
| DeltaKronecker-all | 0.503 | 0.422 | 102 | 7600 | observe |
| nscl5-all | 0.301 | 1.0 | 1 | 1148 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4165 | observe |
| Epodonios-all | 0.255 | None | 0 | 6378 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6475 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4208 | observe |
| barry-far-vless | 0.255 | None | 0 | 4674 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5415 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.228 | None | 0 | 1319 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 84 |
| geo | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 14 |
| 204 | ProxyError | - | 13 |
| cn-block | ProxyError | - | 6 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| geo | ProxyError | - | 4 |
| geo | ClientOSError | - | 4 |
| speed | ProxyError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 208 | 279 | - |
| global | False | 227 | 293 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

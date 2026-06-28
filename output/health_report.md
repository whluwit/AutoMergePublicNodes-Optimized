# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-28 13:32:32 |
| 运行耗时 | 324.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 76138 |
| 去重后节点 | 22875 |
| TCP 可达 | 3000 |
| 真实可用 | 565 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22875 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 30.8 |
| probe | 69.0 |
| real_test | 174.6 |
| generate | 41.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42998 |
| trojan | 12176 |
| vmess | 11032 |
| shadowsocks | 9364 |
| hysteria2 | 228 |
| shadowsocksr | 156 |
| http | 135 |
| socks | 41 |
| hysteria | 6 |
| tuic | 2 |

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
| 77.86 | shadowsocks | 219.2 | 524.3 | 22.7 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 173.244.56.9 |
| 77.76 | shadowsocks | 201.9 | 493.6 | 23.1 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 108.181.0.177 |
| 77.54 | vless | 206.7 | 528.6 | 22.99 | 0.0 | 10.0 | 10.05 | 16.5 | Au1rxx-base64 | 38.244.20.69 |
| 77.54 | shadowsocks | 233.1 | 554.9 | 22.38 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 149.22.95.183 |
| 77.37 | vless | 198.7 | 504.1 | 23.18 | 0.0 | 10.0 | 10.05 | 16.14 | mheidari-all | 38.244.21.164 |
| 77.01 | shadowsocks | 256.2 | 634.6 | 21.85 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 173.244.56.6 |
| 76.98 | vless | 317.5 | 838.1 | 20.43 | 0.0 | 10.0 | 10.05 | 16.5 | Au1rxx-base64 | 15.204.97.219 |
| 76.96 | vless | 318.2 | 841.1 | 20.41 | 0.0 | 10.0 | 10.05 | 16.5 | Au1rxx-base64 | 15.204.97.214 |
| 76.88 | shadowsocks | 240.0 | 616.7 | 22.22 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 108.181.118.10 |
| 76.81 | vless | 293.2 | 704.5 | 20.99 | 0.0 | 10.0 | 10.05 | 16.14 | mheidari-all | 34.213.172.16 |
| 75.31 | vless | 278.7 | 449.2 | 21.33 | 0.0 | 10.0 | 10.05 | 16.14 | mheidari-all | 104.18.42.68 |
| 73.06 | shadowsocks | 292.6 | 658.8 | 21.0 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 156.146.38.167 |
| 72.78 | shadowsocks | 297.7 | 670.9 | 20.89 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 156.146.38.170 |
| 72.46 | shadowsocks | 314.6 | 729.5 | 20.49 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 156.146.38.168 |
| 70.62 | vless | 231.7 | 496.3 | 22.41 | 0.0 | 10.0 | 10.05 | 13.56 | DeltaKronecker-all | 162.159.3.186 |
| 70.48 | shadowsocks | 297.8 | 356.6 | 20.88 | 1.63 | 9.94 | 12.66 | 16.5 | Au1rxx-base64 | 149.22.87.240 |
| 70.44 | vless | 227.4 | 487.5 | 22.51 | 0.0 | 10.0 | 10.05 | 13.56 | DeltaKronecker-all | 172.64.33.117 |
| 70.37 | trojan | 320.2 | 706.5 | 20.37 | 0.0 | 10.0 | 10.97 | 16.14 | mheidari-all | 64.94.95.118 |
| 70.31 | shadowsocks | 292.5 | 658.5 | 21.01 | 0.0 | 10.0 | 12.66 | 16.5 | Au1rxx-base64 | 156.146.38.169 |
| 68.95 | vless | 240.3 | 507.4 | 22.21 | 0.0 | 10.0 | 10.05 | 16.14 | mheidari-all | 162.159.18.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.861 | 0.783 | 341 | 16291 | prefer |
| Au1rxx-base64 | 0.859 | 0.868 | 53 | 105 | prefer |
| Surfboard-tg-mixed | 0.792 | 0.714 | 238 | 4987 | prefer |
| DeltaKronecker-all | 0.65 | 0.571 | 77 | 6788 | observe |
| xiaoji235-airport-v2ray-all | 0.305 | 1.0 | 1 | 1261 | observe |
| nscl5-all | 0.302 | 1.0 | 1 | 1174 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7519 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7282 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3691 | observe |
| barry-far-vless | 0.255 | None | 0 | 4502 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5325 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 72 |
| 204 | TimeoutError | - | 23 |
| speed | TimeoutError | - | 19 |
| geo | ClientOSError | - | 16 |
| geo | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

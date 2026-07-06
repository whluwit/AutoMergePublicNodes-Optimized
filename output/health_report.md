# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-06 02:47:23 |
| 运行耗时 | 210.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78646 |
| 去重后节点 | 23997 |
| TCP 可达 | 3000 |
| 真实可用 | 450 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23997 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 31.3 |
| probe | 46.0 |
| real_test | 87.1 |
| generate | 39.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45037 |
| trojan | 12982 |
| vmess | 10413 |
| shadowsocks | 9398 |
| hysteria2 | 472 |
| shadowsocksr | 147 |
| http | 135 |
| socks | 48 |
| tuic | 8 |
| hysteria | 6 |

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
| 76.79 | shadowsocks | 205.2 | 550.6 | 23.03 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 149.22.95.183 |
| 73.51 | shadowsocks | 227.6 | 484.6 | 22.51 | 0.0 | 10.0 | 12.2 | 14.1 | DeltaKronecker-all | 107.172.219.230 |
| 71.75 | trojan | 220.9 | 526.1 | 22.66 | 0.0 | 10.0 | 11.03 | 15.56 | Au1rxx-base64 | pro-tortoise.rooster465.autos |
| 71.57 | shadowsocks | 300.7 | 643.2 | 20.82 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 108.181.0.177 |
| 71.45 | shadowsocks | 273.7 | 546.9 | 21.44 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 173.244.56.9 |
| 70.55 | shadowsocks | 287.6 | 628.4 | 21.12 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 108.181.118.10 |
| 70.46 | shadowsocks | 280.5 | 336.1 | 21.28 | 2.4 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 149.22.87.241 |
| 70.4 | shadowsocks | 317.1 | 666.9 | 20.44 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 173.244.56.6 |
| 70.03 | shadowsocks | 284.9 | 345.6 | 21.18 | 2.04 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 149.22.87.240 |
| 69.85 | shadowsocks | 319.6 | 676.3 | 20.38 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 156.146.38.170 |
| 69.84 | shadowsocks | 279.0 | 328.0 | 21.32 | 2.7 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 149.22.87.204 |
| 69.77 | shadowsocks | 325.4 | 637.9 | 20.24 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 156.146.38.168 |
| 69.16 | trojan | 340.5 | 770.1 | 19.9 | 0.0 | 10.0 | 11.03 | 14.1 | DeltaKronecker-all | 149.28.241.235 |
| 69.12 | trojan | 339.3 | 759.5 | 19.92 | 0.0 | 10.0 | 11.03 | 14.1 | DeltaKronecker-all | 45.32.198.247 |
| 69.07 | shadowsocks | 323.6 | 676.9 | 20.29 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 156.146.38.167 |
| 68.79 | trojan | 356.8 | 780.6 | 19.52 | 0.0 | 10.0 | 11.03 | 14.1 | DeltaKronecker-all | 45.32.195.168 |
| 68.75 | shadowsocks | 360.1 | 709.8 | 19.44 | 0.0 | 10.0 | 12.2 | 16.84 | mheidari-all | 198.98.53.130 |
| 68.09 | shadowsocks | 236.4 | 534.2 | 22.31 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 216.105.168.18 |
| 68.04 | shadowsocks | 336.6 | 343.2 | 19.99 | 2.13 | 9.66 | 12.2 | 16.32 | Surfboard-tg-mixed | 61.231.25.172 |
| 67.36 | shadowsocks | 365.8 | 737.2 | 19.31 | 0.0 | 10.0 | 12.2 | 15.56 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.995 | 0.921 | 127 | 5941 | prefer |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.866 | 0.882 | 34 | 128 | prefer |
| DeltaKronecker-all | 0.814 | 0.736 | 235 | 7739 | prefer |
| mheidari-all | 0.799 | 0.722 | 126 | 16171 | prefer |
| nscl5-all | 0.321 | 1.0 | 1 | 1651 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| ermaozi | 0.256 | 1.0 | 1 | 27 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4662 | observe |
| Epodonios-all | 0.255 | None | 0 | 7009 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6691 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4343 | observe |
| barry-far-vless | 0.255 | None | 0 | 5045 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 36 |
| speed | ClientOSError | - | 32 |
| geo | ClientOSError | - | 14 |
| 204 | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 8 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 241 | 300 | - |
| global | False | 254 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-11 07:51:18 |
| 运行耗时 | 209.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 76014 |
| 去重后节点 | 23866 |
| TCP 可达 | 3000 |
| 真实可用 | 355 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23866 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.5 |
| tcp | 31.7 |
| probe | 51.9 |
| real_test | 89.8 |
| generate | 29.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43343 |
| trojan | 12014 |
| vmess | 10527 |
| shadowsocks | 9473 |
| hysteria2 | 283 |
| shadowsocksr | 145 |
| http | 135 |
| socks | 84 |
| hysteria | 8 |
| tuic | 1 |
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
| 78.38 | shadowsocks | 237.5 | 500.6 | 22.28 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 173.244.56.6 |
| 78.06 | shadowsocks | 251.4 | 484.4 | 21.96 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 173.244.56.9 |
| 76.84 | shadowsocks | 257.6 | 614.5 | 21.81 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 149.22.95.183 |
| 75.61 | trojan | 250.6 | 619.7 | 21.98 | 0.0 | 10.0 | 14.67 | 12.1 | DeltaKronecker-all | 104.16.99.215 |
| 75.61 | trojan | 256.7 | 418.3 | 21.84 | 0.0 | 10.0 | 14.67 | 12.1 | DeltaKronecker-all | 104.16.97.215 |
| 75.05 | trojan | 349.4 | 773.3 | 19.69 | 0.0 | 10.0 | 14.67 | 16.72 | Au1rxx-base64 | 149.28.241.235 |
| 74.88 | trojan | 273.0 | 451.2 | 21.46 | 0.0 | 10.0 | 14.67 | 12.1 | DeltaKronecker-all | 209.208.227.208 |
| 74.61 | shadowsocks | 277.8 | 283.2 | 21.35 | 4.38 | 9.9 | 13.38 | 16.72 | Au1rxx-base64 | 149.22.87.241 |
| 74.22 | shadowsocks | 276.8 | 291.4 | 21.37 | 4.07 | 9.9 | 13.38 | 16.72 | Au1rxx-base64 | 149.22.87.204 |
| 74.14 | shadowsocks | 296.4 | 666.1 | 20.92 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 156.146.38.168 |
| 74.01 | shadowsocks | 301.9 | 651.1 | 20.79 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 156.146.38.169 |
| 73.44 | shadowsocks | 429.3 | 1173.8 | 17.84 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 108.181.0.177 |
| 73.42 | shadowsocks | 293.4 | 662.7 | 20.99 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 156.146.38.167 |
| 72.75 | trojan | 337.8 | 343.0 | 19.96 | 2.14 | 9.33 | 14.67 | 16.72 | Au1rxx-base64 | rich-mule.rooster465.autos |
| 72.65 | shadowsocks | 336.3 | 759.9 | 19.99 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 156.146.38.170 |
| 72.54 | shadowsocks | 468.0 | 1281.1 | 16.94 | 0.0 | 10.0 | 13.38 | 16.72 | Au1rxx-base64 | 108.181.118.10 |
| 70.46 | trojan | 346.1 | 775.9 | 19.77 | 0.0 | 10.0 | 14.67 | 12.1 | DeltaKronecker-all | 45.32.198.247 |
| 70.42 | trojan | 303.8 | 650.7 | 20.74 | 0.0 | 10.0 | 14.67 | 12.1 | DeltaKronecker-all | 64.94.95.117 |
| 70.39 | trojan | 321.9 | 695.2 | 20.33 | 0.0 | 10.0 | 14.67 | 12.1 | DeltaKronecker-all | 64.94.95.115 |
| 70.37 | trojan | 297.9 | 634.5 | 20.88 | 0.0 | 10.0 | 14.67 | 11.2 | mheidari-all | 64.94.95.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.897 | 0.823 | 113 | 5476 | prefer |
| mheidari-all | 0.73 | 0.655 | 58 | 16299 | prefer |
| Au1rxx-base64 | 0.726 | 0.729 | 59 | 111 | prefer |
| DeltaKronecker-all | 0.703 | 0.624 | 229 | 7969 | prefer |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 3953 | observe |
| Epodonios-all | 0.255 | None | 0 | 6366 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6404 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4097 | observe |
| barry-far-vless | 0.255 | None | 0 | 4653 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5423 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.223 | None | 0 | 1207 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 43 |
| speed | ClientOSError | - | 23 |
| 204 | ProxyError | - | 20 |
| 204 | TimeoutError | - | 11 |
| geo | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 6 |
| cn-block | TimeoutError | - | 5 |
| geo | ProxyError | - | 5 |
| speed | ProxyError | - | 3 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

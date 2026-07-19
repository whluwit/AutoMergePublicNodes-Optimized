# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-19 02:18:29 |
| 运行耗时 | 374.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 88373 |
| 去重后节点 | 23423 |
| TCP 可达 | 3000 |
| 真实可用 | 950 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23423 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 0.8 |
| tcp | 33.7 |
| probe | 73.5 |
| real_test | 235.4 |
| generate | 27.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51335 |
| trojan | 15234 |
| vmess | 10859 |
| shadowsocks | 10386 |
| hysteria2 | 293 |
| shadowsocksr | 127 |
| socks | 62 |
| http | 56 |
| hysteria | 15 |
| tuic | 5 |
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
| 76.58 | shadowsocks | 211.2 | 494.4 | 22.89 | 0.0 | 9.95 | 11.4 | 16.34 | Au1rxx-base64 | 173.244.56.9 |
| 76.56 | shadowsocks | 211.9 | 496.0 | 22.87 | 0.0 | 9.95 | 11.4 | 16.34 | Au1rxx-base64 | 173.244.56.6 |
| 76.0 | shadowsocks | 214.8 | 532.7 | 22.81 | 0.0 | 9.95 | 11.4 | 16.34 | Au1rxx-base64 | 108.181.0.177 |
| 75.55 | shadowsocks | 255.6 | 624.2 | 21.86 | 0.0 | 9.95 | 11.4 | 16.34 | Au1rxx-base64 | 156.146.38.169 |
| 75.49 | shadowsocks | 257.8 | 621.8 | 21.81 | 0.0 | 9.94 | 11.4 | 16.34 | Au1rxx-base64 | 156.146.38.170 |
| 75.3 | shadowsocks | 266.0 | 652.4 | 21.62 | 0.0 | 9.94 | 11.4 | 16.34 | Au1rxx-base64 | 156.146.38.167 |
| 74.98 | shadowsocks | 258.9 | 650.6 | 21.79 | 0.0 | 9.95 | 11.4 | 16.34 | Au1rxx-base64 | 108.181.118.10 |
| 74.75 | shadowsocks | 290.3 | 729.9 | 21.06 | 0.0 | 9.95 | 11.4 | 16.34 | Au1rxx-base64 | 156.146.38.168 |
| 71.82 | vless | 215.0 | 514.6 | 22.8 | 0.0 | 10.0 | 3.08 | 15.94 | Surfboard-tg-mixed | 64.23.143.23 |
| 71.8 | trojan | 344.8 | 345.1 | 19.8 | 2.06 | 9.86 | 13.77 | 16.34 | Au1rxx-base64 | 54.248.166.163 |
| 71.76 | shadowsocks | 284.9 | 620.1 | 21.18 | 0.0 | 9.95 | 11.4 | 16.34 | Au1rxx-base64 | 149.22.95.183 |
| 71.04 | vless | 205.6 | 470.3 | 23.02 | 0.0 | 10.0 | 3.08 | 15.94 | Surfboard-tg-mixed | 198.41.209.87 |
| 70.37 | trojan | 346.4 | 346.9 | 19.76 | 1.99 | 8.58 | 13.77 | 16.34 | Au1rxx-base64 | alert-redfish.rooster465.autos |
| 70.28 | trojan | 349.0 | 349.2 | 19.7 | 1.91 | 8.6 | 13.77 | 16.34 | Au1rxx-base64 | caring-wallaby.rooster465.autos |
| 70.24 | trojan | 343.7 | 348.3 | 19.82 | 1.94 | 8.41 | 13.77 | 16.34 | Au1rxx-base64 | eternal-perch.rooster465.autos |
| 70.24 | trojan | 345.0 | 353.8 | 19.79 | 1.73 | 8.64 | 13.77 | 16.34 | Au1rxx-base64 | live-drake.rooster465.autos |
| 70.21 | trojan | 344.8 | 347.8 | 19.8 | 1.96 | 8.41 | 13.77 | 16.34 | Au1rxx-base64 | innocent-rattler.rooster465.autos |
| 70.2 | shadowsocks | 183.0 | 477.2 | 23.54 | 0.0 | 10.0 | 11.4 | 14.26 | mheidari-all | 216.105.168.18 |
| 70.15 | trojan | 345.0 | 346.4 | 19.79 | 2.01 | 8.28 | 13.77 | 16.34 | Au1rxx-base64 | star-cheetah.rooster465.autos |
| 70.11 | trojan | 347.4 | 337.5 | 19.74 | 2.34 | 7.96 | 13.77 | 16.34 | Au1rxx-base64 | thankful-mustang.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.888 | 0.888 | 134 | 149 | prefer |
| mheidari-all | 0.701 | 0.621 | 850 | 20024 | prefer |
| Surfboard-tg-mixed | 0.697 | 0.617 | 371 | 5481 | observe |
| xiaoji235-airport-v2ray-all | 0.373 | 0.6 | 5 | 4642 | observe |
| SoliSpirit-all | 0.335 | 1.0 | 1 | 6933 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| nscl5-all | 0.259 | 0.333 | 3 | 2755 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4371 | observe |
| Epodonios-all | 0.255 | None | 0 | 6663 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4222 | observe |
| barry-far-vless | 0.255 | None | 0 | 4859 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5340 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 351 |
| geo | TimeoutError | - | 111 |
| geo | ClientOSError | - | 104 |
| speed | TimeoutError | - | 32 |
| cn-block | TimeoutError | - | 24 |
| cn-block | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

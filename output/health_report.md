# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-07 04:09:59 |
| 运行耗时 | 796.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97169 |
| 去重后节点 | 27035 |
| TCP 可达 | 3000 |
| 真实可用 | 510 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27035 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.3 |
| tcp | 46.5 |
| probe | 279.5 |
| real_test | 391.1 |
| generate | 74.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57028 |
| vmess | 15941 |
| shadowsocks | 11589 |
| trojan | 10167 |
| hysteria2 | 1421 |
| http | 696 |
| shadowsocksr | 164 |
| socks | 105 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 11 |

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
| 84.68 | vless | 217.4 | 504.8 | 22.74 | 0.0 | 10.0 | 11.94 | 20.0 | Au1rxx-base64 | 137.175.82.40 |
| 84.64 | vless | 219.2 | 509.3 | 22.7 | 0.0 | 10.0 | 11.94 | 20.0 | Au1rxx-base64 | 47.251.108.158 |
| 83.6 | hysteria2 | 239.5 | 232.2 | 22.23 | 6.29 | 7.75 | 14.29 | 20.0 | Au1rxx-base64 | open.2ml.bid |
| 82.33 | vless | 189.7 | 490.0 | 23.39 | 0.0 | 10.0 | 11.94 | 20.0 | Au1rxx-base64 | 154.17.1.248 |
| 82.12 | shadowsocks | 229.9 | 560.5 | 22.46 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.36 | hysteria2 | 321.4 | 752.1 | 20.34 | 0.0 | 10.0 | 14.29 | 20.0 | Au1rxx-base64 | 129.213.91.185 |
| 80.9 | shadowsocks | 282.5 | 729.9 | 21.24 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 80.6 | shadowsocks | 298.5 | 588.3 | 20.87 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 80.35 | vless | 274.0 | 602.2 | 21.44 | 0.0 | 10.0 | 11.94 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 79.98 | hysteria2 | 270.0 | 361.4 | 21.53 | 1.45 | 9.57 | 14.29 | 20.0 | Au1rxx-base64 | vp3.yysyy.online |
| 79.83 | vless | 269.1 | 589.4 | 21.55 | 0.0 | 10.0 | 11.94 | 20.0 | Au1rxx-base64 | 15.204.97.197 |
| 79.42 | shadowsocks | 301.8 | 738.2 | 20.79 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 5.78.51.123 |
| 79.36 | shadowsocks | 260.5 | 632.7 | 21.75 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 78.4 | shadowsocks | 247.0 | 590.5 | 22.06 | 0.0 | 10.0 | 14.16 | 17.6 | mheidari-all | 173.244.56.9 |
| 78.14 | shadowsocks | 284.0 | 605.1 | 21.2 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 77.6 | trojan | 394.0 | 925.7 | 18.66 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 34.220.15.24 |
| 77.47 | shadowsocks | 258.1 | 633.7 | 21.8 | 0.0 | 10.0 | 14.16 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 77.46 | vless | 246.2 | 531.7 | 22.08 | 0.0 | 10.0 | 11.94 | 20.0 | Au1rxx-base64 | 23.95.222.127 |
| 76.63 | trojan | 412.2 | 907.6 | 18.24 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 44.255.123.205 |
| 76.5 | trojan | 343.7 | 762.1 | 19.82 | 0.0 | 7.95 | 14.55 | 20.0 | Au1rxx-base64 | guided-ferret.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.935 | 309 | 1832 | prefer |
| Surfboard-tg-mixed | 0.7 | 0.621 | 198 | 7006 | prefer |
| ermaozi | 0.61 | 0.585 | 41 | 726 | observe |
| mheidari-all | 0.366 | 0.284 | 250 | 22990 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7476 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9192 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5583 | observe |
| barry-far-vless | 0.255 | None | 0 | 5837 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4373 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.251 | 0.333 | 3 | 1791 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1832 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 147 |
| speed | TimeoutError | - | 41 |
| geo | ClientOSError | - | 36 |
| 204 | ProxyError | - | 27 |
| 204 | TimeoutError | - | 16 |
| speed | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

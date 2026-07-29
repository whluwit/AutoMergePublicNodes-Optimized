# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 14:03:35 |
| 运行耗时 | 268.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 78674 |
| 去重后节点 | 22641 |
| TCP 可达 | 3000 |
| 真实可用 | 494 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22641 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 32.3 |
| probe | 57.7 |
| real_test | 142.8 |
| generate | 29.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46101 |
| vmess | 10747 |
| trojan | 10608 |
| shadowsocks | 10466 |
| hysteria2 | 508 |
| shadowsocksr | 73 |
| http | 73 |
| socks | 57 |
| anytls | 26 |
| hysteria | 12 |
| tuic | 3 |

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
| 75.79 | shadowsocks | 198.2 | 501.9 | 23.19 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 173.244.56.9 |
| 75.46 | shadowsocks | 190.8 | 463.1 | 23.36 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 108.181.0.177 |
| 75.44 | shadowsocks | 213.3 | 505.8 | 22.84 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 173.244.56.6 |
| 75.23 | shadowsocks | 200.7 | 481.0 | 23.13 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 108.181.118.10 |
| 75.17 | vless | 227.8 | 506.1 | 22.51 | 0.0 | 10.0 | 6.76 | 15.9 | Au1rxx-base64 | 64.23.143.23 |
| 74.95 | hysteria2 | 331.9 | 706.4 | 20.1 | 0.0 | 10.0 | 14.0 | 15.9 | Au1rxx-base64 | 159.223.157.129 |
| 71.57 | vless | 188.9 | 491.7 | 23.41 | 0.0 | 10.0 | 6.76 | 15.9 | Au1rxx-base64 | 154.19.184.40 |
| 71.47 | trojan | 354.5 | 821.6 | 19.57 | 0.0 | 10.0 | 12.45 | 15.9 | Au1rxx-base64 | 163.245.196.68 |
| 70.31 | shadowsocks | 283.5 | 294.9 | 21.22 | 3.94 | 9.85 | 10.7 | 15.9 | Au1rxx-base64 | 149.22.87.241 |
| 68.89 | shadowsocks | 258.7 | 699.7 | 21.79 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 185.236.200.210 |
| 68.58 | vless | 265.2 | 651.7 | 21.64 | 0.0 | 10.0 | 6.76 | 14.68 | Surfboard-tg-mixed | 182.16.61.2 |
| 67.82 | hysteria2 | 505.8 | 917.6 | 16.07 | 0.0 | 9.57 | 14.0 | 15.9 | Au1rxx-base64 | 5.255.102.165 |
| 67.69 | trojan | 404.5 | 803.7 | 18.41 | 0.0 | 10.0 | 12.45 | 15.9 | Au1rxx-base64 | 153.75.250.171 |
| 67.66 | shadowsocks | 331.7 | 681.1 | 20.1 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 156.146.38.168 |
| 67.47 | shadowsocks | 329.5 | 688.2 | 20.15 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 156.146.38.170 |
| 67.24 | vless | 320.8 | 698.5 | 20.35 | 0.0 | 10.0 | 6.76 | 15.9 | Au1rxx-base64 | 52.43.158.158 |
| 67.22 | shadowsocks | 328.5 | 679.2 | 20.17 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 156.146.38.167 |
| 66.73 | shadowsocks | 359.8 | 739.1 | 19.45 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 37.19.198.244 |
| 66.69 | shadowsocks | 371.7 | 794.4 | 19.17 | 0.0 | 10.0 | 10.7 | 15.9 | Au1rxx-base64 | 37.19.198.243 |
| 65.93 | vless | 406.0 | 292.7 | 18.38 | 4.02 | 9.88 | 6.76 | 14.68 | Surfboard-tg-mixed | 43.165.186.226 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 70 | 84 | prefer |
| Au1rxx-base64 | 0.874 | 0.823 | 277 | 1337 | prefer |
| Surfboard-tg-mixed | 0.642 | 0.563 | 142 | 5713 | observe |
| DeltaKronecker-all | 0.618 | 0.539 | 193 | 5519 | observe |
| ninja-vless | 0.521 | 0.857 | 7 | 1791 | observe |
| mheidari-all | 0.372 | 0.444 | 9 | 16071 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 180 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5118 | observe |
| Epodonios-all | 0.255 | None | 0 | 6469 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6220 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4553 | observe |
| barry-far-vless | 0.255 | None | 0 | 4964 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5089 | observe |
| nscl5-all | 0.246 | None | 0 | 1774 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 73 |
| speed | TimeoutError | - | 36 |
| cn-block | TimeoutError | - | 33 |
| 204 | TimeoutError | - | 22 |
| geo | ClientOSError | - | 16 |
| 204 | ProxyError | - | 9 |
| speed | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

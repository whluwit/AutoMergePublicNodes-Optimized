# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 03:19:36 |
| 运行耗时 | 317.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 86414 |
| 去重后节点 | 21970 |
| TCP 可达 | 3000 |
| 真实可用 | 772 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21970 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.5 |
| tcp | 35.1 |
| probe | 58.0 |
| real_test | 166.8 |
| generate | 50.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52520 |
| vmess | 10878 |
| trojan | 10600 |
| shadowsocks | 10419 |
| hysteria2 | 1618 |
| http | 181 |
| shadowsocksr | 128 |
| socks | 54 |
| tuic | 8 |
| hysteria | 7 |
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
| 81.79 | shadowsocks | 237.1 | 592.6 | 22.29 | 0.0 | 10.0 | 13.84 | 19.66 | Au1rxx-base64 | 156.146.38.167 |
| 81.56 | shadowsocks | 247.2 | 597.6 | 22.06 | 0.0 | 10.0 | 13.84 | 19.66 | Au1rxx-base64 | 156.146.38.170 |
| 80.82 | shadowsocks | 235.7 | 597.2 | 22.32 | 0.0 | 10.0 | 13.84 | 19.66 | Au1rxx-base64 | 156.146.38.168 |
| 80.01 | vless | 348.4 | 839.0 | 19.71 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 15.204.97.209 |
| 79.63 | vless | 433.4 | 1145.1 | 17.74 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 38.180.242.205 |
| 79.44 | vless | 339.8 | 813.3 | 19.91 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 15.204.97.206 |
| 79.24 | vless | 276.0 | 575.1 | 21.39 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 172.233.156.42 |
| 78.81 | shadowsocks | 325.3 | 699.3 | 20.25 | 0.0 | 10.0 | 13.84 | 19.66 | Au1rxx-base64 | 84.32.131.61 |
| 78.64 | vless | 333.7 | 687.1 | 20.05 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 192.220.9.89 |
| 78.54 | vless | 266.4 | 262.1 | 21.61 | 5.17 | 9.65 | 12.23 | 16.76 | Surfboard-tg-mixed | 31.76.91.72 |
| 78.46 | shadowsocks | 359.3 | 928.4 | 19.46 | 0.0 | 10.0 | 13.84 | 19.66 | Au1rxx-base64 | 23.150.248.20 |
| 78.07 | vless | 284.4 | 608.8 | 21.19 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 70.39.196.142 |
| 77.96 | vless | 272.0 | 584.8 | 21.48 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 172.239.67.231 |
| 77.67 | vless | 275.9 | 570.6 | 21.39 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 172.236.252.35 |
| 77.43 | vless | 294.6 | 573.6 | 20.96 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 31.58.50.200 |
| 77.42 | vless | 295.8 | 582.9 | 20.93 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 45.33.62.166 |
| 77.39 | vless | 289.8 | 591.1 | 21.07 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 74.207.245.124 |
| 77.39 | vless | 396.2 | 975.4 | 18.61 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 45.138.100.226 |
| 77.38 | vless | 361.3 | 796.4 | 19.41 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 47.89.186.170 |
| 77.35 | vless | 337.8 | 734.1 | 19.96 | 0.0 | 10.0 | 12.23 | 19.66 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | 0.917 | 387 | 1860 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.832 | 0.755 | 208 | 6910 | prefer |
| DeltaKronecker-all | 0.797 | 0.722 | 97 | 4926 | prefer |
| mheidari-all | 0.65 | 0.57 | 284 | 18105 | observe |
| nscl5-all | 0.349 | 0.667 | 3 | 4310 | observe |
| tg-oneclickvpnkeys | 0.318 | 1.0 | 2 | 169 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4635 | observe |
| Epodonios-all | 0.255 | None | 0 | 7323 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7549 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5726 | observe |
| barry-far-vless | 0.255 | None | 0 | 5912 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4012 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 72 |
| geo | ClientOSError | - | 49 |
| speed | TimeoutError | - | 38 |
| cn-block | TimeoutError | - | 25 |
| speed | ClientOSError | - | 17 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

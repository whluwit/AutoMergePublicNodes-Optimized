# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-04 10:31:27 |
| 运行耗时 | 309.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83985 |
| 去重后节点 | 23373 |
| TCP 可达 | 3000 |
| 真实可用 | 615 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23373 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 37.9 |
| probe | 88.1 |
| real_test | 134.9 |
| generate | 40.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53298 |
| vmess | 11411 |
| shadowsocks | 9527 |
| trojan | 7918 |
| hysteria2 | 1452 |
| http | 142 |
| shadowsocksr | 129 |
| socks | 82 |
| tuic | 15 |
| hysteria | 10 |
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
| 82.58 | shadowsocks | 242.9 | 624.3 | 22.15 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.91 | shadowsocks | 271.9 | 708.9 | 21.48 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.96 | shadowsocks | 291.3 | 707.0 | 21.03 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 80.92 | http | 249.5 | 559.9 | 22.0 | 0.0 | 10.0 | 14.46 | 19.32 | zhangkai | 138.199.35.198 |
| 79.82 | http | 244.0 | 538.3 | 22.13 | 0.0 | 10.0 | 14.46 | 19.32 | zhangkai | 138.199.35.216 |
| 79.04 | vless | 272.9 | 551.3 | 21.46 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 172.233.156.118 |
| 78.67 | vless | 266.6 | 551.5 | 21.61 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 78.66 | vless | 266.1 | 541.2 | 21.62 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 172.239.67.231 |
| 78.33 | vless | 277.0 | 593.0 | 21.37 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 172.239.67.156 |
| 78.14 | vless | 268.3 | 569.2 | 21.57 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 172.236.252.35 |
| 78.1 | shadowsocks | 272.9 | 535.6 | 21.46 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 77.98 | shadowsocks | 308.8 | 725.6 | 20.63 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 77.94 | vless | 275.1 | 564.6 | 21.41 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 77.71 | shadowsocks | 272.2 | 521.2 | 21.48 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 77.66 | vless | 285.4 | 556.5 | 21.17 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 172.233.156.123 |
| 77.33 | shadowsocks | 242.0 | 623.6 | 22.18 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 77.17 | shadowsocks | 305.7 | 299.1 | 20.7 | 3.78 | 9.74 | 14.43 | 20.0 | Au1rxx-base64 | 149.22.87.240 |
| 77.08 | vless | 295.7 | 586.0 | 20.93 | 0.0 | 10.0 | 10.28 | 20.0 | Au1rxx-base64 | 31.58.50.200 |
| 76.95 | shadowsocks | 308.9 | 304.5 | 20.63 | 3.58 | 9.79 | 14.43 | 20.0 | Au1rxx-base64 | 149.22.87.204 |
| 76.68 | shadowsocks | 324.2 | 723.2 | 20.27 | 0.0 | 10.0 | 14.43 | 20.0 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.964 | 0.896 | 367 | 1736 | prefer |
| mheidari-all | 0.828 | 0.752 | 145 | 15923 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.743 | 167 | 7319 | prefer |
| DeltaKronecker-all | 0.747 | 0.676 | 37 | 7089 | prefer |
| tg-oneclickvpnkeys | 0.443 | 1.0 | 5 | 102 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4810 | observe |
| Epodonios-all | 0.255 | None | 0 | 7763 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7993 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6206 | observe |
| barry-far-vless | 0.255 | None | 0 | 6426 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4123 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1736 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 21 |
| geo | TimeoutError | - | 19 |
| geo | ClientOSError | - | 18 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 10 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-30 02:57:36 |
| 运行耗时 | 285.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 75440 |
| 去重后节点 | 23025 |
| TCP 可达 | 3000 |
| 真实可用 | 681 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23025 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 30.7 |
| probe | 58.6 |
| real_test | 155.5 |
| generate | 34.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42229 |
| trojan | 12861 |
| vmess | 10363 |
| shadowsocks | 9358 |
| hysteria2 | 262 |
| shadowsocksr | 157 |
| http | 135 |
| socks | 68 |
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
| 79.45 | vless | 170.3 | 468.2 | 23.83 | 0.0 | 10.0 | 10.72 | 14.9 | Surfboard-tg-mixed | 64.23.143.23 |
| 76.79 | vless | 291.7 | 685.2 | 21.03 | 0.0 | 10.0 | 10.72 | 15.96 | mheidari-all | 34.213.172.16 |
| 76.51 | vless | 304.6 | 798.1 | 20.73 | 0.0 | 10.0 | 10.72 | 15.06 | Au1rxx-base64 | 15.204.97.214 |
| 75.53 | vless | 256.0 | 681.6 | 21.85 | 0.0 | 10.0 | 10.72 | 15.96 | mheidari-all | 107.173.237.146 |
| 74.94 | shadowsocks | 221.3 | 496.5 | 22.66 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 173.244.56.9 |
| 74.91 | shadowsocks | 200.9 | 483.7 | 23.13 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 108.181.0.177 |
| 74.8 | shadowsocks | 205.4 | 499.1 | 23.02 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 108.181.118.10 |
| 74.57 | vless | 275.9 | 619.5 | 21.39 | 0.0 | 10.0 | 10.72 | 15.06 | Au1rxx-base64 | 162.159.18.241 |
| 71.99 | vless | 298.5 | 817.1 | 20.87 | 0.0 | 10.0 | 10.72 | 14.9 | Surfboard-tg-mixed | 141.193.154.182 |
| 71.98 | shadowsocks | 348.8 | 919.2 | 19.7 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 173.244.56.6 |
| 71.91 | shadowsocks | 226.9 | 513.5 | 22.52 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 149.22.95.183 |
| 70.55 | vless | 269.9 | 616.3 | 21.53 | 0.0 | 10.0 | 10.72 | 15.96 | mheidari-all | 104.19.87.194 |
| 70.49 | shadowsocks | 292.7 | 650.5 | 21.0 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 156.146.38.167 |
| 69.98 | vless | 244.3 | 481.2 | 22.12 | 0.0 | 10.0 | 10.72 | 15.96 | mheidari-all | 173.245.59.35 |
| 69.88 | shadowsocks | 290.4 | 649.0 | 21.06 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 156.146.38.169 |
| 69.74 | vless | 272.1 | 419.3 | 21.48 | 0.0 | 10.0 | 10.72 | 15.96 | mheidari-all | 162.159.43.131 |
| 69.5 | shadowsocks | 300.1 | 680.1 | 20.83 | 0.0 | 10.0 | 11.22 | 15.06 | Au1rxx-base64 | 156.146.38.168 |
| 69.31 | vless | 235.4 | 493.3 | 22.33 | 0.0 | 10.0 | 10.72 | 10.7 | DeltaKronecker-all | 104.18.36.192 |
| 69.27 | vless | 354.5 | 362.2 | 19.57 | 1.42 | 10.0 | 10.72 | 15.96 | mheidari-all | 162.159.40.181 |
| 68.86 | vless | 233.4 | 483.9 | 22.38 | 0.0 | 10.0 | 10.72 | 10.7 | DeltaKronecker-all | 104.18.37.191 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.848 | 0.77 | 352 | 5456 | prefer |
| mheidari-all | 0.824 | 0.746 | 350 | 15873 | prefer |
| Au1rxx-base64 | 0.706 | 0.709 | 55 | 101 | prefer |
| DeltaKronecker-all | 0.415 | 0.333 | 216 | 7004 | observe |
| xiaoji235-airport-v2ray-all | 0.303 | 1.0 | 1 | 1204 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6395 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3983 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6670 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4008 | observe |
| barry-far-vless | 0.255 | None | 0 | 4588 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5353 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 125 |
| geo | TimeoutError | - | 107 |
| speed | TimeoutError | - | 39 |
| geo | ClientOSError | - | 29 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

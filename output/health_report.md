# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 20:43:54 |
| 运行耗时 | 572.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 96521 |
| 去重后节点 | 26456 |
| TCP 可达 | 3000 |
| 真实可用 | 391 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26456 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 42.7 |
| probe | 277.0 |
| real_test | 169.4 |
| generate | 74.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58932 |
| vmess | 14941 |
| shadowsocks | 11305 |
| trojan | 8926 |
| hysteria2 | 1509 |
| http | 611 |
| shadowsocksr | 170 |
| socks | 77 |
| anytls | 25 |
| hysteria | 15 |
| tuic | 10 |

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
| 79.58 | shadowsocks | 245.5 | 670.0 | 22.09 | 0.0 | 9.11 | 14.28 | 18.1 | Au1rxx-base64 | 198.98.53.130 |
| 79.21 | vless | 244.2 | 694.5 | 22.13 | 0.0 | 8.8 | 10.18 | 18.1 | Au1rxx-base64 | 79.141.172.154 |
| 78.48 | vless | 274.7 | 672.5 | 21.42 | 0.0 | 8.78 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.179 |
| 78.37 | vless | 279.0 | 748.3 | 21.32 | 0.0 | 8.77 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.235 |
| 78.33 | vless | 282.0 | 756.1 | 21.25 | 0.0 | 8.8 | 10.18 | 18.1 | Au1rxx-base64 | 38.77.133.202 |
| 77.52 | vless | 305.3 | 688.7 | 20.71 | 0.0 | 8.82 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.89 |
| 77.34 | vless | 303.9 | 833.8 | 20.74 | 0.0 | 8.32 | 10.18 | 18.1 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 77.28 | vless | 248.5 | 696.3 | 22.03 | 0.0 | 8.97 | 10.18 | 18.1 | Au1rxx-base64 | 47.253.144.114 |
| 76.98 | vless | 340.1 | 918.4 | 19.9 | 0.0 | 8.8 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.16 |
| 76.71 | vless | 340.2 | 569.9 | 19.9 | 0.0 | 8.76 | 10.18 | 18.1 | Au1rxx-base64 | 195.211.98.43 |
| 76.69 | vless | 353.4 | 978.7 | 19.6 | 0.0 | 8.81 | 10.18 | 18.1 | Au1rxx-base64 | 185.95.231.156 |
| 76.63 | shadowsocks | 280.7 | 643.5 | 21.28 | 0.0 | 8.87 | 14.28 | 18.1 | Au1rxx-base64 | 156.146.38.169 |
| 76.63 | vless | 354.2 | 978.4 | 19.58 | 0.0 | 8.77 | 10.18 | 18.1 | Au1rxx-base64 | 185.95.231.233 |
| 76.44 | vless | 281.8 | 761.3 | 21.26 | 0.0 | 8.9 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.212 |
| 76.34 | vless | 368.4 | 950.6 | 19.25 | 0.0 | 8.81 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.168 |
| 76.25 | shadowsocks | 351.7 | 912.9 | 19.64 | 0.0 | 8.73 | 14.28 | 18.1 | Au1rxx-base64 | 38.180.135.156 |
| 76.17 | shadowsocks | 288.7 | 660.1 | 21.09 | 0.0 | 10.0 | 14.28 | 17.26 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.08 | vless | 394.2 | 967.0 | 18.65 | 0.0 | 9.15 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.224 |
| 76.01 | vless | 374.9 | 979.6 | 19.1 | 0.0 | 8.81 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.15 |
| 75.95 | vless | 287.8 | 646.6 | 21.11 | 0.0 | 8.85 | 10.18 | 18.1 | Au1rxx-base64 | 169.40.42.35 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.945 | 0.882 | 288 | 1654 | prefer |
| Surfboard-tg-mixed | 0.735 | 0.658 | 111 | 7263 | prefer |
| mheidari-all | 0.662 | 0.583 | 96 | 22366 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 66 | observe |
| Epodonios-all | 0.255 | None | 0 | 7740 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8923 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 6052 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1654 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 34 |
| cn-block | ClientOSError | - | 22 |
| 204 | ProxyConnectionError | - | 19 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 9 |
| speed | ClientOSError | - | 8 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| speed | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

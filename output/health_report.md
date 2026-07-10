# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-10 02:36:59 |
| 运行耗时 | 187.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 76967 |
| 去重后节点 | 23552 |
| TCP 可达 | 3000 |
| 真实可用 | 406 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23552 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.3 |
| tcp | 31.6 |
| probe | 44.7 |
| real_test | 71.5 |
| generate | 33.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43878 |
| trojan | 12471 |
| vmess | 10680 |
| shadowsocks | 9266 |
| hysteria2 | 286 |
| shadowsocksr | 147 |
| http | 135 |
| socks | 90 |
| hysteria | 8 |
| anytls | 5 |
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
| 78.99 | shadowsocks | 235.7 | 648.9 | 22.32 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 37.19.198.244 |
| 78.99 | shadowsocks | 235.7 | 651.6 | 22.32 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 37.19.198.236 |
| 78.88 | shadowsocks | 240.4 | 666.2 | 22.21 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 37.19.198.160 |
| 78.02 | shadowsocks | 277.9 | 757.7 | 21.35 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 198.98.53.130 |
| 77.98 | shadowsocks | 279.3 | 780.1 | 21.31 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 37.19.198.243 |
| 76.42 | shadowsocks | 325.1 | 879.0 | 20.25 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 108.181.57.93 |
| 75.75 | shadowsocks | 288.6 | 668.5 | 21.1 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 156.146.38.169 |
| 74.94 | shadowsocks | 284.2 | 650.1 | 21.2 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 156.146.38.168 |
| 74.88 | shadowsocks | 339.0 | 831.1 | 19.93 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 185.196.61.82 |
| 74.36 | shadowsocks | 297.8 | 653.6 | 20.88 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 156.146.38.167 |
| 71.55 | shadowsocks | 288.8 | 667.8 | 21.09 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 156.146.38.170 |
| 70.64 | shadowsocks | 337.1 | 619.2 | 19.97 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 108.181.118.10 |
| 70.44 | shadowsocks | 354.1 | 719.2 | 19.58 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 108.181.0.177 |
| 70.42 | vless | 248.4 | 654.4 | 22.03 | 0.0 | 10.0 | 5.41 | 17.98 | Au1rxx-base64 | 159.89.87.21 |
| 70.3 | shadowsocks | 362.6 | 723.5 | 19.38 | 0.0 | 10.0 | 12.69 | 17.98 | Au1rxx-base64 | 149.22.95.183 |
| 69.94 | vless | 251.6 | 684.2 | 21.95 | 0.0 | 10.0 | 5.41 | 12.58 | Surfboard-tg-mixed | 137.184.218.169 |
| 69.07 | trojan | 411.0 | 999.3 | 18.26 | 0.0 | 10.0 | 8.23 | 17.98 | Au1rxx-base64 | 149.28.241.235 |
| 67.34 | vless | 321.0 | 791.1 | 20.35 | 0.0 | 10.0 | 5.41 | 12.58 | Surfboard-tg-mixed | 104.16.75.234 |
| 67.08 | shadowsocks | 410.5 | 369.9 | 18.28 | 1.13 | 9.25 | 12.69 | 17.98 | Au1rxx-base64 | 149.22.87.241 |
| 66.34 | http | 615.7 | 935.4 | 13.53 | 0.0 | 9.82 | 14.61 | 19.52 | snakem982 | 193.176.84.37 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.764 | 0.685 | 305 | 5645 | prefer |
| Au1rxx-base64 | 0.76 | 0.771 | 35 | 79 | prefer |
| DeltaKronecker-all | 0.722 | 0.644 | 202 | 7533 | prefer |
| nscl5-all | 0.301 | 1.0 | 1 | 1148 | observe |
| barry-far-Sub1 | 0.274 | 1.0 | 1 | 485 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4306 | observe |
| Epodonios-all | 0.255 | None | 0 | 6482 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6596 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4155 | observe |
| barry-far-vless | 0.255 | None | 0 | 4678 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5403 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.227 | None | 0 | 1299 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 89 |
| geo | TimeoutError | - | 65 |
| geo | ClientOSError | - | 12 |
| speed | TimeoutError | - | 11 |
| cn-block | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 224 | 300 | - |
| global | False | 234 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

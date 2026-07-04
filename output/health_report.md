# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-04 08:34:46 |
| 运行耗时 | 232.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 78938 |
| 去重后节点 | 23506 |
| TCP 可达 | 3000 |
| 真实可用 | 310 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23506 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 30.8 |
| probe | 46.6 |
| real_test | 111.0 |
| generate | 37.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45851 |
| trojan | 12744 |
| vmess | 10496 |
| shadowsocks | 9176 |
| hysteria2 | 286 |
| shadowsocksr | 151 |
| http | 135 |
| socks | 91 |
| hysteria | 6 |
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
| 75.5 | shadowsocks | 198.1 | 488.9 | 23.19 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 108.181.0.177 |
| 74.77 | shadowsocks | 251.5 | 614.7 | 21.96 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 156.146.38.169 |
| 74.74 | shadowsocks | 230.9 | 616.8 | 22.43 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 108.181.118.10 |
| 74.64 | shadowsocks | 257.0 | 628.3 | 21.83 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 156.146.38.168 |
| 74.0 | shadowsocks | 262.3 | 642.1 | 21.71 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 156.146.38.167 |
| 73.69 | shadowsocks | 255.9 | 622.6 | 21.85 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 156.146.38.170 |
| 73.35 | vless | 208.9 | 504.5 | 22.94 | 0.0 | 10.0 | 2.99 | 19.42 | Surfboard-tg-mixed | 64.23.143.23 |
| 70.45 | trojan | 389.2 | 488.6 | 18.77 | 0.0 | 9.91 | 13.96 | 19.42 | Surfboard-tg-mixed | 103.106.228.187 |
| 70.05 | trojan | 280.6 | 627.5 | 21.28 | 0.0 | 10.0 | 13.96 | 9.82 | DeltaKronecker-all | 64.94.95.115 |
| 69.7 | shadowsocks | 267.8 | 597.6 | 21.58 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 173.244.56.9 |
| 69.5 | trojan | 289.3 | 662.2 | 21.08 | 0.0 | 10.0 | 13.96 | 9.82 | DeltaKronecker-all | 64.94.95.117 |
| 69.01 | trojan | 299.9 | 679.3 | 20.84 | 0.0 | 10.0 | 13.96 | 9.82 | DeltaKronecker-all | 64.94.95.114 |
| 68.3 | shadowsocks | 305.1 | 714.8 | 20.72 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 173.244.56.6 |
| 68.09 | shadowsocks | 278.8 | 591.0 | 21.32 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 149.22.95.183 |
| 67.75 | shadowsocks | 304.1 | 359.4 | 20.74 | 1.52 | 9.91 | 13.73 | 13.08 | Au1rxx-base64 | 149.22.87.240 |
| 67.54 | shadowsocks | 309.3 | 361.7 | 20.62 | 1.44 | 9.91 | 13.73 | 13.08 | Au1rxx-base64 | 149.22.87.204 |
| 67.16 | shadowsocks | 356.5 | 740.7 | 19.53 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 37.19.198.160 |
| 67.1 | shadowsocks | 358.8 | 739.2 | 19.47 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 37.19.198.243 |
| 66.84 | shadowsocks | 350.8 | 748.2 | 19.66 | 0.0 | 10.0 | 13.73 | 13.08 | Au1rxx-base64 | 37.19.198.236 |
| 66.82 | shadowsocks | 303.8 | 356.5 | 20.74 | 1.63 | 9.91 | 13.73 | 13.08 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.878 | 0.909 | 22 | 77 | prefer |
| Surfboard-tg-mixed | 0.707 | 0.628 | 239 | 6152 | prefer |
| DeltaKronecker-all | 0.661 | 0.582 | 170 | 7309 | observe |
| nscl5-all | 0.359 | 1.0 | 2 | 1189 | observe |
| tg-ConfigV2rayNG | 0.319 | 1.0 | 2 | 200 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4579 | observe |
| Epodonios-all | 0.255 | None | 0 | 7154 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7126 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4573 | observe |
| barry-far-vless | 0.255 | None | 0 | 5278 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5333 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| mheidari-all | 0.226 | 0.2 | 5 | 16136 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 59 |
| geo | TimeoutError | - | 29 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ProxyError | - | 8 |
| 204 | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 8 |
| speed | ProxyError | - | 6 |
| geo | ClientOSError | - | 6 |
| geo | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 02:28:03 |
| 运行耗时 | 336.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80317 |
| 去重后节点 | 22465 |
| TCP 可达 | 3000 |
| 真实可用 | 893 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22465 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 30.9 |
| probe | 64.3 |
| real_test | 206.6 |
| generate | 27.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44835 |
| trojan | 14727 |
| vmess | 10098 |
| shadowsocks | 9937 |
| hysteria2 | 465 |
| http | 81 |
| socks | 75 |
| shadowsocksr | 74 |
| hysteria | 13 |
| tuic | 11 |
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
| 77.84 | shadowsocks | 201.8 | 511.2 | 23.11 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 173.244.56.9 |
| 77.4 | shadowsocks | 220.8 | 523.0 | 22.67 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 149.22.95.183 |
| 76.48 | vless | 177.1 | 488.1 | 23.68 | 0.0 | 10.0 | 6.3 | 16.5 | Surfboard-tg-mixed | 64.23.143.23 |
| 76.17 | shadowsocks | 252.3 | 641.9 | 21.94 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 108.181.0.177 |
| 75.2 | shadowsocks | 294.1 | 777.2 | 20.97 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 108.181.118.10 |
| 74.06 | trojan | 325.6 | 329.5 | 20.24 | 2.65 | 9.94 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.82 |
| 74.03 | trojan | 324.8 | 330.9 | 20.26 | 2.59 | 9.94 | 13.24 | 17.88 | Au1rxx-base64 | 95.85.94.17 |
| 74.0 | trojan | 326.0 | 330.5 | 20.23 | 2.61 | 9.95 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.149 |
| 73.96 | trojan | 324.9 | 332.8 | 20.26 | 2.52 | 9.95 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.164 |
| 73.96 | trojan | 325.3 | 330.7 | 20.25 | 2.6 | 9.94 | 13.24 | 17.88 | Au1rxx-base64 | 95.85.94.199 |
| 73.92 | trojan | 325.4 | 331.9 | 20.24 | 2.55 | 9.95 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.238 |
| 73.92 | trojan | 326.7 | 332.5 | 20.22 | 2.53 | 9.94 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.178 |
| 73.89 | trojan | 327.4 | 332.7 | 20.2 | 2.53 | 9.95 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.58 |
| 73.85 | trojan | 326.2 | 332.3 | 20.23 | 2.54 | 9.95 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.172 |
| 73.74 | trojan | 326.8 | 336.8 | 20.21 | 2.37 | 9.94 | 13.24 | 17.88 | Au1rxx-base64 | 31.223.184.43 |
| 73.49 | shadowsocks | 272.6 | 278.4 | 21.47 | 4.56 | 9.95 | 10.85 | 17.88 | Au1rxx-base64 | 149.22.87.204 |
| 73.09 | shadowsocks | 290.4 | 652.9 | 21.06 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 156.146.38.167 |
| 73.05 | shadowsocks | 275.5 | 289.3 | 21.4 | 4.15 | 9.94 | 10.85 | 17.88 | Au1rxx-base64 | 149.22.87.240 |
| 72.88 | shadowsocks | 292.5 | 660.4 | 21.01 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 156.146.38.170 |
| 72.78 | shadowsocks | 204.3 | 520.4 | 23.05 | 0.0 | 10.0 | 10.85 | 17.88 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 76 | 119 | prefer |
| Au1rxx-base64 | 0.954 | 0.902 | 458 | 1356 | prefer |
| Surfboard-tg-mixed | 0.689 | 0.61 | 251 | 5480 | observe |
| mheidari-all | 0.604 | 0.525 | 408 | 17144 | observe |
| DeltaKronecker-all | 0.369 | 0.286 | 126 | 5838 | observe |
| tg-ConfigV2rayNG | 0.263 | 1.0 | 1 | 200 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4879 | observe |
| Epodonios-all | 0.255 | None | 0 | 6569 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6329 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4211 | observe |
| barry-far-vless | 0.255 | None | 0 | 4852 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2896 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 160 |
| geo | TimeoutError | - | 129 |
| speed | TimeoutError | - | 47 |
| cn-block | TimeoutError | - | 44 |
| geo | ClientOSError | - | 23 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 5 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

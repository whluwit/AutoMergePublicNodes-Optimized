# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-24 12:42:33 |
| 运行耗时 | 230.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 78511 |
| 去重后节点 | 21921 |
| TCP 可达 | 3000 |
| 真实可用 | 546 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21921 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.4 |
| tcp | 35.5 |
| probe | 50.8 |
| real_test | 103.6 |
| generate | 33.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49119 |
| shadowsocks | 10341 |
| vmess | 9971 |
| trojan | 7625 |
| hysteria2 | 1080 |
| http | 164 |
| shadowsocksr | 125 |
| socks | 76 |
| hysteria | 7 |
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
| 81.32 | hysteria2 | 255.4 | 685.4 | 21.87 | 0.0 | 10.0 | 13.75 | 16.8 | mheidari-all | 159.223.157.129 |
| 79.58 | shadowsocks | 228.7 | 593.9 | 22.48 | 0.0 | 10.0 | 13.74 | 17.36 | Surfboard-tg-mixed | 198.98.53.130 |
| 79.16 | shadowsocks | 246.9 | 667.9 | 22.06 | 0.0 | 10.0 | 13.74 | 17.36 | Surfboard-tg-mixed | 37.19.198.236 |
| 79.08 | shadowsocks | 250.4 | 675.2 | 21.98 | 0.0 | 10.0 | 13.74 | 17.36 | Surfboard-tg-mixed | 37.19.198.244 |
| 79.06 | shadowsocks | 251.2 | 680.7 | 21.96 | 0.0 | 10.0 | 13.74 | 17.36 | Surfboard-tg-mixed | 37.19.198.160 |
| 78.99 | shadowsocks | 254.4 | 688.4 | 21.89 | 0.0 | 10.0 | 13.74 | 17.36 | Surfboard-tg-mixed | 37.19.198.243 |
| 78.46 | vless | 262.3 | 678.8 | 21.71 | 0.0 | 10.0 | 7.43 | 19.32 | Au1rxx-base64 | 47.89.186.170 |
| 77.99 | shadowsocks | 302.1 | 791.0 | 20.78 | 0.0 | 9.15 | 13.74 | 19.32 | Au1rxx-base64 | 155.138.136.240 |
| 77.9 | shadowsocks | 328.0 | 887.7 | 20.19 | 0.0 | 9.15 | 13.74 | 19.32 | Au1rxx-base64 | 38.180.135.156 |
| 77.8 | shadowsocks | 390.4 | 992.2 | 18.74 | 0.0 | 10.0 | 13.74 | 19.32 | Au1rxx-base64 | 142.4.216.225 |
| 77.44 | shadowsocks | 384.5 | 1080.3 | 18.88 | 0.0 | 10.0 | 13.74 | 19.32 | Au1rxx-base64 | 15.204.247.175 |
| 77.41 | vless | 299.5 | 723.6 | 20.85 | 0.0 | 10.0 | 7.43 | 19.32 | Au1rxx-base64 | 66.70.179.198 |
| 77.1 | vless | 288.0 | 747.8 | 21.11 | 0.0 | 9.24 | 7.43 | 19.32 | Au1rxx-base64 | 169.40.42.35 |
| 76.87 | vless | 295.1 | 709.8 | 20.95 | 0.0 | 9.2 | 7.43 | 19.32 | Au1rxx-base64 | 169.40.42.90 |
| 76.46 | trojan | 345.0 | 848.0 | 19.79 | 0.0 | 10.0 | 12.75 | 19.32 | Au1rxx-base64 | 64.74.163.118 |
| 76.41 | vless | 317.7 | 829.6 | 20.42 | 0.0 | 9.24 | 7.43 | 19.32 | Au1rxx-base64 | 169.40.42.16 |
| 76.39 | vless | 264.4 | 672.0 | 21.66 | 0.0 | 9.21 | 7.43 | 19.32 | Au1rxx-base64 | 167.17.69.171 |
| 75.96 | vless | 336.0 | 672.2 | 20.0 | 0.0 | 9.21 | 7.43 | 19.32 | Au1rxx-base64 | 169.40.42.104 |
| 75.25 | http | 351.0 | 638.3 | 19.65 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 75.17 | http | 353.5 | 653.6 | 19.59 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | 0.918 | 330 | 1628 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| DeltaKronecker-all | 0.858 | 0.785 | 79 | 5914 | prefer |
| Surfboard-tg-mixed | 0.823 | 0.745 | 165 | 6406 | prefer |
| mheidari-all | 0.819 | 0.75 | 44 | 14541 | prefer |
| nscl5-all | 0.352 | 1.0 | 2 | 1008 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 6919 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3990 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7302 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5341 | observe |
| barry-far-vless | 0.255 | None | 0 | 5629 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4097 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| geo | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 15 |
| geo | ClientOSError | - | 11 |
| 204 | ProxyError | - | 6 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

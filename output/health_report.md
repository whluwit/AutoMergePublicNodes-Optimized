# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 20:56:40 |
| 运行耗时 | 495.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99293 |
| 去重后节点 | 27429 |
| TCP 可达 | 3000 |
| 真实可用 | 386 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27429 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.5 |
| tcp | 47.6 |
| probe | 200.4 |
| real_test | 163.5 |
| generate | 75.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59579 |
| vmess | 15697 |
| shadowsocks | 11500 |
| trojan | 10224 |
| hysteria2 | 1474 |
| http | 522 |
| shadowsocksr | 167 |
| socks | 72 |
| anytls | 27 |
| hysteria | 16 |
| tuic | 15 |

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
| 84.42 | hysteria2 | 227.5 | 574.3 | 22.51 | 0.0 | 10.0 | 13.93 | 18.98 | Au1rxx-base64 | 66.94.121.46 |
| 82.13 | vless | 230.1 | 513.4 | 22.45 | 0.0 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 137.175.82.40 |
| 80.97 | vless | 238.0 | 530.3 | 22.27 | 0.0 | 10.0 | 11.7 | 17.9 | mheidari-all | 47.251.108.158 |
| 80.45 | vless | 216.5 | 558.4 | 22.77 | 0.0 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 15.204.97.214 |
| 80.16 | shadowsocks | 213.6 | 576.2 | 22.83 | 0.0 | 10.0 | 13.35 | 18.98 | Au1rxx-base64 | 149.22.95.183 |
| 79.87 | vless | 370.8 | 1006.3 | 19.19 | 0.0 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 51.81.203.63 |
| 79.39 | vless | 209.8 | 544.9 | 22.92 | 0.0 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 15.204.97.216 |
| 78.54 | vless | 212.5 | 549.2 | 22.86 | 0.0 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 15.204.97.195 |
| 78.31 | shadowsocks | 226.3 | 569.4 | 22.54 | 0.0 | 10.0 | 13.35 | 16.92 | Surfboard-tg-mixed | 5.78.51.123 |
| 77.27 | vless | 308.0 | 316.5 | 20.65 | 3.13 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 154.31.114.248 |
| 77.25 | vless | 311.8 | 313.8 | 20.56 | 3.23 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 46.250.250.149 |
| 77.21 | hysteria2 | 338.3 | 743.2 | 19.95 | 0.0 | 10.0 | 13.93 | 17.9 | mheidari-all | 129.213.91.185 |
| 76.81 | trojan | 282.4 | 597.8 | 21.24 | 0.0 | 10.0 | 14.33 | 16.92 | Surfboard-tg-mixed | 43.173.90.202 |
| 76.66 | vless | 324.1 | 748.8 | 20.28 | 0.0 | 10.0 | 11.7 | 18.98 | Au1rxx-base64 | 23.95.222.127 |
| 76.5 | shadowsocks | 288.0 | 625.4 | 21.11 | 0.0 | 10.0 | 13.35 | 18.98 | Au1rxx-base64 | 108.181.0.177 |
| 76.46 | trojan | 313.0 | 324.2 | 20.53 | 2.84 | 9.47 | 14.33 | 18.98 | Au1rxx-base64 | jp.tronsg.com |
| 76.45 | trojan | 314.8 | 318.1 | 20.49 | 3.07 | 9.52 | 14.33 | 18.98 | Au1rxx-base64 | integral-rodent.rooster465.autos |
| 76.24 | trojan | 313.0 | 320.3 | 20.53 | 2.99 | 9.31 | 14.33 | 18.98 | Au1rxx-base64 | brief-glider.rooster465.autos |
| 76.11 | trojan | 314.5 | 329.4 | 20.5 | 2.65 | 9.53 | 14.33 | 18.98 | Au1rxx-base64 | winning-marten.rooster465.autos |
| 76.06 | trojan | 314.9 | 326.2 | 20.49 | 2.77 | 9.43 | 14.33 | 18.98 | Au1rxx-base64 | promoted-rattler.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | 0.916 | 311 | 1858 | prefer |
| mheidari-all | 0.864 | 0.791 | 86 | 23222 | prefer |
| Surfboard-tg-mixed | 0.721 | 0.649 | 37 | 7257 | prefer |
| ermaozi-get_subscribe | 0.341 | 0.75 | 4 | 518 | observe |
| ermaozi | 0.295 | 0.25 | 24 | 653 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5173 | observe |
| Epodonios-all | 0.255 | None | 0 | 7751 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9655 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5820 | observe |
| barry-far-vless | 0.255 | None | 0 | 6058 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4365 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1858 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyConnectionError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 11 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 5 |
| geo | ClientOSError | - | 4 |
| speed | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

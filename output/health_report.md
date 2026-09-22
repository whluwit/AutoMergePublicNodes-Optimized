# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 11:01:09 |
| 运行耗时 | 632.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 91067 |
| 去重后节点 | 25164 |
| TCP 可达 | 3000 |
| 真实可用 | 445 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25164 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.4 |
| tcp | 42.0 |
| probe | 280.0 |
| real_test | 214.0 |
| generate | 87.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53207 |
| vmess | 14804 |
| shadowsocks | 11268 |
| trojan | 9290 |
| hysteria2 | 1592 |
| http | 634 |
| shadowsocksr | 142 |
| socks | 84 |
| anytls | 21 |
| hysteria | 17 |
| tuic | 8 |

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
| 81.66 | hysteria2 | 300.0 | 569.7 | 20.83 | 0.0 | 9.28 | 14.29 | 18.26 | Au1rxx-base64 | 66.94.121.46 |
| 77.99 | vless | 210.1 | 546.6 | 22.91 | 0.0 | 9.23 | 7.59 | 18.26 | Au1rxx-base64 | 172.235.43.210 |
| 77.81 | vless | 219.7 | 533.3 | 22.69 | 0.0 | 9.27 | 7.59 | 18.26 | Au1rxx-base64 | 195.123.240.65 |
| 77.31 | vless | 239.7 | 592.5 | 22.23 | 0.0 | 9.23 | 7.59 | 18.26 | Au1rxx-base64 | 15.204.97.216 |
| 76.3 | hysteria2 | 358.6 | 765.9 | 19.48 | 0.0 | 9.57 | 14.29 | 18.26 | Au1rxx-base64 | 159.223.157.129 |
| 75.5 | shadowsocks | 251.5 | 609.1 | 21.96 | 0.0 | 10.0 | 14.22 | 13.32 | Surfboard-tg-mixed | 149.22.95.183 |
| 74.89 | shadowsocks | 256.3 | 653.8 | 21.85 | 0.0 | 10.0 | 14.22 | 13.32 | Surfboard-tg-mixed | 108.181.0.177 |
| 74.51 | shadowsocks | 272.3 | 705.0 | 21.47 | 0.0 | 10.0 | 14.22 | 13.32 | Surfboard-tg-mixed | 108.181.118.10 |
| 74.38 | shadowsocks | 299.8 | 709.8 | 20.84 | 0.0 | 10.0 | 14.22 | 13.32 | Surfboard-tg-mixed | 173.244.56.9 |
| 74.3 | vless | 191.7 | 482.8 | 23.34 | 0.0 | 9.36 | 7.59 | 18.26 | Au1rxx-base64 | 104.18.39.218 |
| 74.17 | vless | 195.1 | 516.0 | 23.26 | 0.0 | 10.0 | 7.59 | 13.32 | Surfboard-tg-mixed | 172.235.38.85 |
| 72.47 | vless | 233.0 | 571.2 | 22.39 | 0.0 | 9.23 | 7.59 | 18.26 | Au1rxx-base64 | 15.204.97.219 |
| 72.46 | http | 202.3 | 514.5 | 23.1 | 0.0 | 10.0 | 9.52 | 12.84 | ermaozi | 138.199.35.216 |
| 72.42 | http | 203.9 | 520.3 | 23.06 | 0.0 | 10.0 | 9.52 | 12.84 | ermaozi | 138.199.35.217 |
| 72.37 | http | 205.9 | 528.3 | 23.01 | 0.0 | 10.0 | 9.52 | 12.84 | ermaozi | 138.199.35.200 |
| 72.32 | vless | 429.3 | 1126.8 | 17.84 | 0.0 | 9.18 | 7.59 | 18.26 | Au1rxx-base64 | 51.81.203.63 |
| 72.09 | vless | 227.0 | 453.1 | 22.52 | 0.0 | 10.0 | 7.59 | 18.26 | Au1rxx-base64 | 162.159.130.234 |
| 71.91 | vless | 282.3 | 579.9 | 21.24 | 0.0 | 9.32 | 7.59 | 18.26 | Au1rxx-base64 | 188.114.97.6 |
| 71.79 | vless | 175.3 | 478.3 | 23.72 | 0.0 | 10.0 | 7.59 | 10.48 | mheidari-all | 47.251.108.158 |
| 71.46 | shadowsocks | 291.1 | 654.3 | 21.04 | 0.0 | 10.0 | 14.22 | 13.32 | Surfboard-tg-mixed | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | 0.896 | 288 | 1630 | prefer |
| ermaozi | 0.651 | 0.643 | 42 | 369 | observe |
| Surfboard-tg-mixed | 0.646 | 0.567 | 171 | 7043 | observe |
| DeltaKronecker-all | 0.402 | 0.316 | 19 | 6324 | observe |
| mheidari-all | 0.36 | 0.278 | 198 | 19835 | observe |
| ermaozi-get_subscribe | 0.256 | 0.5 | 4 | 393 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4915 | observe |
| Epodonios-all | 0.255 | None | 0 | 7495 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8686 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5601 | observe |
| barry-far-vless | 0.255 | None | 0 | 5817 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1630 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 66 |
| cn-block | ClientOSError | - | 65 |
| speed | ClientOSError | - | 33 |
| 204 | TimeoutError | - | 32 |
| geo | TimeoutError | - | 24 |
| 204 | ProxyError | - | 21 |
| cn-block | TimeoutError | - | 17 |
| speed | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

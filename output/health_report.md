# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 20:09:44 |
| 运行耗时 | 619.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 97816 |
| 去重后节点 | 27650 |
| TCP 可达 | 3000 |
| 真实可用 | 298 |
| Verified 输出 | 298 |
| Global 输出 | 300 |
| All 输出 | 27650 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 48.4 |
| probe | 279.3 |
| real_test | 198.5 |
| generate | 83.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57528 |
| vmess | 16787 |
| shadowsocks | 11730 |
| trojan | 9543 |
| hysteria2 | 1330 |
| http | 613 |
| shadowsocksr | 171 |
| socks | 68 |
| anytls | 22 |
| hysteria | 17 |
| tuic | 7 |

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
| 80.5 | vless | 265.0 | 679.7 | 21.64 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.212 |
| 80.46 | vless | 266.7 | 680.6 | 21.6 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.225 |
| 80.39 | hysteria2 | 257.6 | 670.5 | 21.81 | 0.0 | 10.0 | 12.5 | 17.58 | Au1rxx-base64 | 129.213.91.185 |
| 79.76 | vless | 297.1 | 644.6 | 20.9 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.16 |
| 78.63 | vless | 320.1 | 838.6 | 20.37 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.163 |
| 78.28 | vless | 266.2 | 673.4 | 21.62 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.35 |
| 78.18 | vless | 300.7 | 743.9 | 20.82 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 66.70.179.198 |
| 78.16 | vless | 363.7 | 845.5 | 19.36 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.229 |
| 78.11 | vless | 348.2 | 918.7 | 19.72 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.74 |
| 78.1 | vless | 369.0 | 995.3 | 19.24 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 185.95.231.156 |
| 77.93 | vless | 358.0 | 904.3 | 19.49 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.133 |
| 77.87 | vless | 378.8 | 948.4 | 19.01 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.173 |
| 77.83 | vless | 244.9 | 614.7 | 22.11 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 195.123.235.183 |
| 77.68 | vless | 280.7 | 658.4 | 21.28 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.232 |
| 77.26 | vless | 348.0 | 871.8 | 19.72 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.179 |
| 77.18 | shadowsocks | 266.9 | 718.0 | 21.6 | 0.0 | 10.0 | 12.0 | 17.58 | Au1rxx-base64 | 37.19.198.160 |
| 76.99 | vless | 274.7 | 702.8 | 21.42 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.235 |
| 76.75 | vless | 316.9 | 820.8 | 20.44 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.184 |
| 76.39 | vless | 334.1 | 888.3 | 20.04 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.89 |
| 76.1 | vless | 332.8 | 881.3 | 20.08 | 0.0 | 10.0 | 11.28 | 17.58 | Au1rxx-base64 | 169.40.42.224 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.905 | 0.838 | 265 | 1742 | prefer |
| mheidari-all | 0.756 | 0.681 | 72 | 23629 | prefer |
| Surfboard-tg-mixed | 0.663 | 0.591 | 22 | 7036 | observe |
| ermaozi | 0.662 | 0.65 | 20 | 639 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7503 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10062 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5553 | observe |
| barry-far-vless | 0.255 | None | 0 | 5767 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1742 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 8 |
| geo | ClientOSError | - | 8 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 298 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

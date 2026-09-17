# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 21:02:46 |
| 运行耗时 | 565.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84628 |
| 去重后节点 | 23061 |
| TCP 可达 | 3000 |
| 真实可用 | 447 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23061 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 37.6 |
| probe | 214.8 |
| real_test | 217.7 |
| generate | 86.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50809 |
| vmess | 13348 |
| shadowsocks | 10081 |
| trojan | 8246 |
| hysteria2 | 1351 |
| http | 595 |
| shadowsocksr | 120 |
| socks | 66 |
| hysteria | 8 |
| tuic | 2 |
| anytls | 2 |

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
| 80.57 | vless | 251.0 | 635.3 | 21.97 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 195.123.235.177 |
| 80.34 | vless | 260.9 | 659.1 | 21.74 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 79.141.172.154 |
| 80.33 | vless | 261.1 | 649.7 | 21.73 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.90 |
| 80.23 | vless | 265.8 | 674.2 | 21.63 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 167.17.69.171 |
| 79.7 | vless | 288.5 | 626.7 | 21.1 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.223 |
| 79.14 | vless | 291.1 | 688.1 | 21.04 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.89 |
| 78.99 | vless | 319.2 | 746.4 | 20.39 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.168 |
| 78.82 | vless | 322.1 | 792.6 | 20.32 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.212 |
| 78.72 | vless | 330.9 | 735.8 | 20.12 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.74 |
| 78.68 | vless | 332.7 | 819.7 | 20.08 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.15 |
| 78.29 | hysteria2 | 243.9 | 663.1 | 22.13 | 0.0 | 10.0 | 12.5 | 14.76 | mheidari-all | 159.223.157.129 |
| 78.18 | vless | 353.0 | 874.7 | 19.61 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.163 |
| 78.11 | vless | 304.2 | 674.2 | 20.74 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.235 |
| 78.11 | vless | 357.0 | 936.4 | 19.51 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.75 |
| 77.89 | vless | 366.8 | 923.1 | 19.29 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.232 |
| 77.77 | vless | 372.1 | 1022.8 | 19.17 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 185.95.231.156 |
| 77.64 | vless | 361.3 | 842.8 | 19.41 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.202 |
| 77.63 | shadowsocks | 323.4 | 882.8 | 20.29 | 0.0 | 10.0 | 13.54 | 18.3 | Au1rxx-base64 | 38.180.135.156 |
| 77.4 | vless | 269.7 | 677.1 | 21.53 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.16 |
| 77.34 | vless | 349.0 | 802.7 | 19.7 | 0.0 | 10.0 | 10.3 | 18.3 | Au1rxx-base64 | 169.40.42.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.994 | 0.939 | 33 | 16164 | prefer |
| Au1rxx-base64 | 0.93 | 0.868 | 265 | 1619 | prefer |
| DeltaKronecker-all | 0.847 | 0.771 | 118 | 5931 | prefer |
| Surfboard-tg-mixed | 0.78 | 0.703 | 118 | 7499 | prefer |
| ermaozi | 0.449 | 0.5 | 16 | 357 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4261 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7954 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8875 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5936 | observe |
| barry-far-vless | 0.255 | None | 0 | 6157 | observe |
| ermaozi-get_subscribe | 0.254 | 0.5 | 4 | 361 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyError | - | 17 |
| geo | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

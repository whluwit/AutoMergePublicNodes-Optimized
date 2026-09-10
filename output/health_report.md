# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 10:40:16 |
| 运行耗时 | 764.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91075 |
| 去重后节点 | 24106 |
| TCP 可达 | 3000 |
| 真实可用 | 467 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24106 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.4 |
| tcp | 40.5 |
| probe | 327.2 |
| real_test | 303.2 |
| generate | 84.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55365 |
| vmess | 13061 |
| shadowsocks | 10939 |
| trojan | 8856 |
| hysteria2 | 1954 |
| http | 685 |
| shadowsocksr | 124 |
| socks | 59 |
| hysteria | 15 |
| tuic | 10 |
| anytls | 7 |

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
| 81.87 | vless | 225.4 | 593.2 | 22.56 | 0.0 | 10.0 | 9.31 | 20.0 | Au1rxx-base64 | 195.123.235.177 |
| 81.4 | vless | 245.6 | 695.6 | 22.09 | 0.0 | 10.0 | 9.31 | 20.0 | Au1rxx-base64 | 47.253.226.114 |
| 81.26 | shadowsocks | 244.5 | 677.2 | 22.12 | 0.0 | 9.0 | 14.14 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 80.74 | shadowsocks | 240.2 | 670.0 | 22.22 | 0.0 | 9.38 | 14.14 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 80.24 | vless | 254.5 | 671.5 | 21.89 | 0.0 | 9.04 | 9.31 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 80.11 | vless | 262.3 | 689.1 | 21.71 | 0.0 | 9.09 | 9.31 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 79.95 | vless | 268.9 | 714.8 | 21.55 | 0.0 | 9.09 | 9.31 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 79.71 | vless | 282.2 | 719.1 | 21.24 | 0.0 | 9.16 | 9.31 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 79.57 | vless | 237.4 | 678.7 | 22.28 | 0.0 | 8.98 | 9.31 | 20.0 | Au1rxx-base64 | 79.141.172.154 |
| 79.33 | shadowsocks | 244.6 | 678.7 | 22.12 | 0.0 | 9.07 | 14.14 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 79.16 | shadowsocks | 316.5 | 837.1 | 20.45 | 0.0 | 9.07 | 14.14 | 20.0 | Au1rxx-base64 | 38.180.135.156 |
| 79.13 | vless | 287.4 | 764.2 | 21.12 | 0.0 | 9.04 | 9.31 | 20.0 | Au1rxx-base64 | 169.40.42.52 |
| 79.11 | shadowsocks | 272.4 | 769.0 | 21.47 | 0.0 | 9.0 | 14.14 | 20.0 | Au1rxx-base64 | 15.204.247.206 |
| 79.09 | vless | 303.9 | 688.0 | 20.74 | 0.0 | 9.04 | 9.31 | 20.0 | Au1rxx-base64 | 169.40.42.225 |
| 78.87 | vless | 316.2 | 788.5 | 20.46 | 0.0 | 9.1 | 9.31 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 78.72 | shadowsocks | 349.1 | 1008.4 | 19.7 | 0.0 | 9.38 | 14.14 | 20.0 | Au1rxx-base64 | 15.204.247.175 |
| 78.57 | shadowsocks | 245.9 | 683.0 | 22.09 | 0.0 | 10.0 | 14.14 | 17.34 | Surfboard-tg-mixed | 37.19.198.236 |
| 78.52 | shadowsocks | 291.4 | 665.0 | 21.03 | 0.0 | 9.31 | 14.14 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 78.48 | vless | 343.4 | 945.1 | 19.83 | 0.0 | 9.34 | 9.31 | 20.0 | Au1rxx-base64 | 185.95.231.156 |
| 78.42 | shadowsocks | 353.8 | 1009.2 | 19.59 | 0.0 | 9.19 | 14.14 | 20.0 | Au1rxx-base64 | 15.204.246.132 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.935 | 0.872 | 274 | 1628 | prefer |
| Surfboard-tg-mixed | 0.852 | 0.776 | 134 | 7346 | prefer |
| ermaozi | 0.74 | 0.731 | 52 | 449 | prefer |
| mheidari-all | 0.557 | 0.477 | 174 | 19290 | observe |
| tg-oneclickvpnkeys | 0.264 | 1.0 | 1 | 214 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7808 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8703 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5990 | observe |
| barry-far-vless | 0.255 | None | 0 | 6215 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3508 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1628 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 55 |
| cn-block | ClientOSError | - | 29 |
| 204 | ProxyError | - | 21 |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 19 |
| geo | TimeoutError | - | 13 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

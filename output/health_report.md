# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 20:48:08 |
| 运行耗时 | 668.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85321 |
| 去重后节点 | 22703 |
| TCP 可达 | 3000 |
| 真实可用 | 514 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22703 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 38.4 |
| probe | 289.7 |
| real_test | 256.2 |
| generate | 77.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52860 |
| vmess | 12052 |
| shadowsocks | 9711 |
| trojan | 8311 |
| hysteria2 | 1613 |
| http | 570 |
| shadowsocksr | 128 |
| socks | 53 |
| hysteria | 11 |
| tuic | 8 |
| anytls | 4 |

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
| 82.59 | vless | 240.6 | 607.5 | 22.21 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 195.123.235.177 |
| 81.38 | vless | 292.8 | 693.8 | 21.0 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.89 |
| 81.08 | shadowsocks | 254.7 | 677.6 | 21.88 | 0.0 | 10.0 | 13.3 | 19.9 | Au1rxx-base64 | 37.19.198.244 |
| 81.08 | vless | 282.7 | 663.2 | 21.23 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.52 |
| 80.56 | vless | 313.0 | 685.3 | 20.53 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.184 |
| 80.56 | vless | 328.4 | 865.2 | 20.18 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.74 |
| 80.53 | vless | 329.6 | 878.3 | 20.15 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 185.95.231.156 |
| 80.52 | vless | 329.9 | 853.6 | 20.14 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.163 |
| 80.47 | vless | 332.1 | 670.6 | 20.09 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.182 |
| 80.42 | vless | 334.3 | 843.9 | 20.04 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 66.70.179.198 |
| 79.93 | vless | 355.5 | 948.6 | 19.55 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.224 |
| 79.44 | hysteria2 | 245.2 | 651.0 | 22.1 | 0.0 | 10.0 | 12.86 | 15.58 | Surfboard-tg-mixed | 159.223.157.129 |
| 79.43 | vless | 355.6 | 924.4 | 19.55 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.35 |
| 79.29 | vless | 253.6 | 691.3 | 21.91 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 47.253.226.114 |
| 78.78 | vless | 369.4 | 938.6 | 19.23 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.229 |
| 78.59 | shadowsocks | 340.8 | 952.4 | 19.89 | 0.0 | 10.0 | 13.3 | 19.9 | Au1rxx-base64 | 15.204.246.189 |
| 78.53 | vless | 355.1 | 881.8 | 19.56 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.231 |
| 78.43 | vless | 381.3 | 974.5 | 18.95 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.104 |
| 78.29 | vless | 295.9 | 757.9 | 20.93 | 0.0 | 10.0 | 10.48 | 19.9 | Au1rxx-base64 | 169.40.42.179 |
| 78.11 | shadowsocks | 284.4 | 646.1 | 21.19 | 0.0 | 10.0 | 13.3 | 19.9 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 1.0 | 0.964 | 28 | 6097 | prefer |
| Au1rxx-base64 | 0.979 | 0.914 | 290 | 1700 | prefer |
| mheidari-all | 0.855 | 0.78 | 100 | 16416 | prefer |
| Surfboard-tg-mixed | 0.818 | 0.741 | 158 | 7545 | prefer |
| ermaozi | 0.719 | 0.714 | 35 | 409 | prefer |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 420 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7999 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8578 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6277 | observe |
| barry-far-vless | 0.255 | None | 0 | 6497 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1700 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 18 |
| geo | ClientOSError | - | 17 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 9 |
| speed | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

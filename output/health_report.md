# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-31 12:35:08 |
| 运行耗时 | 281.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 79305 |
| 去重后节点 | 22260 |
| TCP 可达 | 3000 |
| 真实可用 | 542 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22260 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.6 |
| tcp | 35.4 |
| probe | 85.5 |
| real_test | 116.3 |
| generate | 37.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50132 |
| vmess | 10959 |
| shadowsocks | 10137 |
| trojan | 6173 |
| hysteria2 | 1546 |
| http | 140 |
| shadowsocksr | 131 |
| socks | 76 |
| hysteria | 7 |
| tuic | 4 |

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
| 84.34 | hysteria2 | 268.3 | 660.6 | 21.57 | 0.0 | 10.0 | 14.17 | 19.7 | Au1rxx-base64 | 159.223.157.129 |
| 82.14 | shadowsocks | 237.7 | 600.0 | 22.28 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 156.146.38.168 |
| 81.04 | shadowsocks | 237.9 | 601.5 | 22.27 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 156.146.38.167 |
| 81.0 | shadowsocks | 265.2 | 703.8 | 21.64 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 84.32.131.61 |
| 80.08 | vless | 307.4 | 769.4 | 20.66 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 195.211.99.45 |
| 79.48 | vless | 333.4 | 875.1 | 20.06 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 38.180.242.205 |
| 79.14 | shadowsocks | 286.5 | 674.5 | 21.15 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 37.19.198.243 |
| 79.02 | trojan | 293.3 | 736.9 | 20.99 | 0.0 | 10.0 | 11.33 | 19.7 | Au1rxx-base64 | 64.94.95.118 |
| 78.68 | hysteria2 | 393.0 | 982.7 | 18.68 | 0.0 | 10.0 | 14.17 | 19.7 | Au1rxx-base64 | 66.94.121.46 |
| 78.53 | vless | 325.5 | 739.2 | 20.24 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 195.211.99.49 |
| 77.4 | vless | 301.6 | 683.2 | 20.8 | 0.0 | 9.06 | 9.72 | 19.7 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 77.14 | shadowsocks | 238.2 | 618.2 | 22.26 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 156.146.38.170 |
| 76.95 | shadowsocks | 284.5 | 563.7 | 21.19 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 149.22.95.183 |
| 76.93 | vless | 352.7 | 842.5 | 19.61 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 216.152.147.28 |
| 76.75 | vless | 281.4 | 576.7 | 21.26 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 64.23.229.123 |
| 76.61 | shadowsocks | 250.9 | 619.2 | 21.97 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 156.146.38.169 |
| 76.48 | vless | 297.7 | 598.1 | 20.89 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 172.239.67.231 |
| 76.4 | vless | 290.4 | 577.6 | 21.06 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 70.39.196.142 |
| 76.28 | shadowsocks | 283.9 | 680.2 | 21.21 | 0.0 | 10.0 | 14.16 | 19.7 | Au1rxx-base64 | 37.19.198.160 |
| 76.24 | vless | 349.5 | 700.3 | 19.69 | 0.0 | 10.0 | 9.72 | 19.7 | Au1rxx-base64 | 169.40.42.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | 0.928 | 304 | 1804 | prefer |
| zhangkai | 0.89 | 0.917 | 24 | 144 | prefer |
| mheidari-all | 0.872 | 0.8 | 70 | 14620 | prefer |
| DeltaKronecker-all | 0.858 | 0.787 | 61 | 5904 | prefer |
| Surfboard-tg-mixed | 0.836 | 0.759 | 174 | 6828 | prefer |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi | 0.256 | 1.0 | 1 | 22 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7174 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7956 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5768 | observe |
| barry-far-vless | 0.255 | None | 0 | 5864 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3987 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 15 |
| 204 | ProxyError | - | 14 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 6 |
| geo | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 5 |
| speed | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 2 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

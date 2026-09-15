# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 16:17:35 |
| 运行耗时 | 662.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90723 |
| 去重后节点 | 25700 |
| TCP 可达 | 3000 |
| 真实可用 | 402 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25700 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.6 |
| tcp | 43.4 |
| probe | 267.1 |
| real_test | 250.3 |
| generate | 94.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55776 |
| vmess | 13488 |
| shadowsocks | 10046 |
| trojan | 8779 |
| hysteria2 | 1797 |
| http | 624 |
| shadowsocksr | 131 |
| socks | 54 |
| hysteria | 14 |
| anytls | 8 |
| tuic | 6 |

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
| 76.89 | shadowsocks | 271.4 | 657.1 | 21.5 | 0.0 | 9.4 | 13.68 | 18.12 | Au1rxx-base64 | 156.146.38.168 |
| 76.87 | hysteria2 | 329.0 | 721.4 | 20.16 | 0.0 | 9.59 | 13.12 | 18.12 | Au1rxx-base64 | 159.223.157.129 |
| 76.07 | hysteria2 | 302.2 | 597.4 | 20.78 | 0.0 | 9.44 | 13.12 | 18.12 | Au1rxx-base64 | 66.94.121.46 |
| 75.33 | shadowsocks | 280.9 | 628.2 | 21.27 | 0.0 | 9.6 | 13.68 | 18.12 | Au1rxx-base64 | 23.150.248.20 |
| 74.02 | shadowsocks | 259.0 | 626.6 | 21.78 | 0.0 | 10.0 | 13.68 | 13.56 | Surfboard-tg-mixed | 156.146.38.167 |
| 73.95 | vless | 297.4 | 601.3 | 20.89 | 0.0 | 10.0 | 10.14 | 16.6 | mheidari-all | 216.227.161.95 |
| 73.25 | vless | 347.0 | 749.2 | 19.75 | 0.0 | 9.34 | 10.14 | 18.12 | Au1rxx-base64 | 79.141.172.154 |
| 72.88 | vless | 322.7 | 621.8 | 20.31 | 0.0 | 9.34 | 10.14 | 18.12 | Au1rxx-base64 | 192.3.247.109 |
| 72.88 | shadowsocks | 333.1 | 707.6 | 20.07 | 0.0 | 9.55 | 13.68 | 18.12 | Au1rxx-base64 | 173.244.56.9 |
| 72.75 | hysteria2 | 363.0 | 805.9 | 19.37 | 0.0 | 9.31 | 13.12 | 18.12 | Au1rxx-base64 | 107.175.219.48 |
| 72.43 | shadowsocks | 311.7 | 769.9 | 20.56 | 0.0 | 9.56 | 13.68 | 18.12 | Au1rxx-base64 | 156.146.38.170 |
| 72.14 | shadowsocks | 350.9 | 714.3 | 19.66 | 0.0 | 9.59 | 13.68 | 18.12 | Au1rxx-base64 | 37.19.198.236 |
| 71.78 | shadowsocks | 318.6 | 607.1 | 20.4 | 0.0 | 9.32 | 13.68 | 18.12 | Au1rxx-base64 | 108.181.0.177 |
| 71.41 | vless | 317.4 | 600.7 | 20.43 | 0.0 | 10.0 | 10.14 | 16.6 | mheidari-all | 47.251.108.158 |
| 71.22 | shadowsocks | 310.5 | 581.4 | 20.59 | 0.0 | 10.0 | 13.68 | 16.6 | mheidari-all | 108.181.118.10 |
| 71.11 | vless | 371.5 | 740.2 | 19.18 | 0.0 | 9.38 | 10.14 | 18.12 | Au1rxx-base64 | 2.56.124.241 |
| 71.0 | vless | 378.8 | 741.1 | 19.01 | 0.0 | 9.43 | 10.14 | 18.12 | Au1rxx-base64 | 195.123.235.177 |
| 70.79 | vless | 370.7 | 705.6 | 19.2 | 0.0 | 9.35 | 10.14 | 18.12 | Au1rxx-base64 | 198.200.42.129 |
| 70.22 | hysteria2 | 434.8 | 749.9 | 17.71 | 0.0 | 9.36 | 13.12 | 18.12 | Au1rxx-base64 | 62.210.124.146 |
| 70.06 | vless | 486.9 | 835.2 | 16.51 | 0.0 | 9.39 | 10.14 | 18.12 | Au1rxx-base64 | 38.180.242.205 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.927 | 0.868 | 280 | 1551 | prefer |
| Surfboard-tg-mixed | 0.805 | 0.731 | 67 | 7516 | prefer |
| ermaozi | 0.766 | 0.763 | 38 | 406 | prefer |
| mheidari-all | 0.521 | 0.44 | 168 | 21913 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 5932 | observe |
| ermaozi-get_subscribe | 0.328 | 1.0 | 2 | 422 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 149 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 8076 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8810 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6065 | observe |
| barry-far-vless | 0.255 | None | 0 | 6401 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 43 |
| geo | ClientOSError | - | 32 |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 14 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

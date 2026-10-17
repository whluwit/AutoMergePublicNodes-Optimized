# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 20:11:09 |
| 运行耗时 | 680.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99264 |
| 去重后节点 | 27731 |
| TCP 可达 | 3000 |
| 真实可用 | 416 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27731 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 47.8 |
| probe | 229.4 |
| real_test | 245.8 |
| generate | 150.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58455 |
| vmess | 16644 |
| shadowsocks | 11952 |
| trojan | 9990 |
| hysteria2 | 1329 |
| http | 613 |
| shadowsocksr | 175 |
| socks | 57 |
| anytls | 26 |
| hysteria | 17 |
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
| 81.07 | hysteria2 | 276.9 | 717.5 | 21.37 | 0.0 | 10.0 | 13.24 | 17.96 | Au1rxx-base64 | 129.213.91.185 |
| 80.12 | vless | 273.1 | 675.3 | 21.46 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 147.45.60.160 |
| 80.02 | shadowsocks | 235.6 | 606.2 | 22.33 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 156.146.38.169 |
| 79.99 | shadowsocks | 236.8 | 611.4 | 22.3 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 156.146.38.170 |
| 79.55 | shadowsocks | 255.6 | 624.9 | 21.86 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 156.146.38.168 |
| 78.36 | shadowsocks | 245.3 | 606.6 | 22.1 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 156.146.38.167 |
| 78.34 | vless | 259.9 | 631.6 | 21.76 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 216.227.161.95 |
| 78.04 | shadowsocks | 309.6 | 752.2 | 20.61 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 37.19.198.236 |
| 77.73 | vless | 313.7 | 750.7 | 20.52 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 47.253.226.114 |
| 77.14 | shadowsocks | 302.3 | 750.9 | 20.78 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 37.19.198.244 |
| 76.97 | shadowsocks | 326.7 | 800.8 | 20.21 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 37.19.198.160 |
| 75.73 | vless | 344.3 | 793.4 | 19.81 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 66.70.179.198 |
| 75.71 | vless | 288.9 | 651.3 | 21.09 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 195.123.235.183 |
| 75.55 | shadowsocks | 320.5 | 789.8 | 20.36 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 64.74.163.69 |
| 75.49 | vless | 296.0 | 672.0 | 20.93 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 212.104.141.233 |
| 75.44 | vless | 280.5 | 671.0 | 21.28 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 69.48.201.136 |
| 75.09 | vless | 293.8 | 591.7 | 20.98 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 144.202.126.147 |
| 74.62 | vless | 298.7 | 670.4 | 20.86 | 0.0 | 8.17 | 10.7 | 17.96 | Au1rxx-base64 | freeus.aiage.work |
| 74.55 | shadowsocks | 277.8 | 569.8 | 21.35 | 0.0 | 10.0 | 13.73 | 17.96 | Au1rxx-base64 | 173.244.56.6 |
| 74.5 | vless | 416.9 | 1038.7 | 18.13 | 0.0 | 10.0 | 10.7 | 17.96 | Au1rxx-base64 | 185.95.231.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.896 | 0.818 | 456 | 1992 | prefer |
| ermaozi | 0.873 | 0.871 | 31 | 623 | prefer |
| mheidari-all | 0.58 | 0.5 | 24 | 23876 | observe |
| Surfboard-tg-mixed | 0.438 | 1.0 | 3 | 7087 | observe |
| ermaozi-get_subscribe | 0.275 | 1.0 | 1 | 510 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1992 | observe |
| Epodonios-all | 0.255 | None | 0 | 7590 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10108 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5622 | observe |
| barry-far-vless | 0.255 | None | 0 | 5860 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| speed | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 15 |
| 204 | ProxyError | - | 8 |
| geo | ClientOSError | - | 8 |
| geo | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

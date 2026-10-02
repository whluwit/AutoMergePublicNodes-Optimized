# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 11:56:18 |
| 运行耗时 | 582.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97759 |
| 去重后节点 | 26962 |
| TCP 可达 | 3000 |
| 真实可用 | 335 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26962 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.0 |
| tcp | 46.2 |
| probe | 285.2 |
| real_test | 160.1 |
| generate | 81.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59655 |
| vmess | 15409 |
| shadowsocks | 11466 |
| trojan | 8917 |
| hysteria2 | 1500 |
| http | 521 |
| shadowsocksr | 169 |
| socks | 60 |
| anytls | 35 |
| hysteria | 17 |
| tuic | 10 |

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
| 85.37 | hysteria2 | 225.1 | 527.1 | 22.57 | 0.0 | 10.0 | 14.12 | 19.68 | Au1rxx-base64 | 192.255.128.123 |
| 83.84 | hysteria2 | 291.1 | 763.1 | 21.04 | 0.0 | 10.0 | 14.12 | 19.68 | Au1rxx-base64 | 66.94.121.46 |
| 82.69 | shadowsocks | 205.7 | 554.3 | 23.02 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 173.234.25.90 |
| 81.27 | shadowsocks | 267.0 | 693.5 | 21.6 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 108.181.0.177 |
| 81.01 | shadowsocks | 278.2 | 726.2 | 21.34 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 108.181.118.10 |
| 80.97 | shadowsocks | 246.9 | 548.6 | 22.06 | 0.0 | 10.0 | 14.49 | 18.42 | Surfboard-tg-mixed | 173.244.56.9 |
| 80.86 | shadowsocks | 198.3 | 529.7 | 23.19 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 74.201.177.54 |
| 79.02 | hysteria2 | 268.7 | 342.0 | 21.56 | 2.18 | 9.39 | 14.12 | 19.68 | Au1rxx-base64 | open.2ml.bid |
| 78.87 | vless | 197.9 | 516.4 | 23.2 | 0.0 | 10.0 | 5.99 | 19.68 | Au1rxx-base64 | 172.235.38.85 |
| 78.83 | vless | 199.4 | 524.7 | 23.16 | 0.0 | 10.0 | 5.99 | 19.68 | Au1rxx-base64 | 172.233.139.46 |
| 78.78 | vless | 201.4 | 533.8 | 23.11 | 0.0 | 10.0 | 5.99 | 19.68 | Au1rxx-base64 | 172.235.43.210 |
| 78.72 | hysteria2 | 352.4 | 760.8 | 19.62 | 0.0 | 10.0 | 14.12 | 19.68 | Au1rxx-base64 | 159.223.157.129 |
| 78.18 | shadowsocks | 346.1 | 943.2 | 19.77 | 0.0 | 10.0 | 14.49 | 18.42 | Surfboard-tg-mixed | 5.78.51.123 |
| 78.14 | shadowsocks | 297.3 | 669.3 | 20.9 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 156.146.38.167 |
| 77.95 | vless | 237.5 | 639.6 | 22.28 | 0.0 | 10.0 | 5.99 | 19.68 | Au1rxx-base64 | 23.95.222.127 |
| 77.76 | shadowsocks | 202.3 | 543.1 | 23.09 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 216.105.168.157 |
| 77.71 | shadowsocks | 204.6 | 551.7 | 23.04 | 0.0 | 10.0 | 14.49 | 19.68 | Au1rxx-base64 | 103.214.109.197 |
| 76.92 | shadowsocks | 289.4 | 652.5 | 21.08 | 0.0 | 10.0 | 14.49 | 18.42 | Surfboard-tg-mixed | 156.146.38.168 |
| 76.63 | vless | 176.0 | 483.5 | 23.7 | 0.0 | 10.0 | 5.99 | 19.68 | Au1rxx-base64 | 137.175.82.40 |
| 76.26 | shadowsocks | 293.2 | 337.2 | 20.99 | 2.36 | 9.94 | 14.49 | 19.68 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.894 | 0.829 | 258 | 1676 | prefer |
| mheidari-all | 0.88 | 0.811 | 53 | 23059 | prefer |
| Surfboard-tg-mixed | 0.784 | 0.708 | 96 | 7176 | prefer |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 4981 | observe |
| ermaozi | 0.294 | 0.25 | 24 | 618 | observe |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 475 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7676 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9233 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5828 | observe |
| barry-far-vless | 0.255 | None | 0 | 6070 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 19 |
| 204 | ProxyConnectionError | - | 18 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 9 |
| geo | TimeoutError | - | 8 |
| geo | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| speed | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

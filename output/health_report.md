# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 11:10:12 |
| 运行耗时 | 621.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96962 |
| 去重后节点 | 26300 |
| TCP 可达 | 3000 |
| 真实可用 | 365 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26300 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.3 |
| tcp | 43.0 |
| probe | 266.8 |
| real_test | 158.9 |
| generate | 146.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58837 |
| vmess | 15126 |
| shadowsocks | 11411 |
| trojan | 9018 |
| hysteria2 | 1644 |
| http | 635 |
| shadowsocksr | 172 |
| socks | 73 |
| anytls | 24 |
| hysteria | 15 |
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
| 82.48 | hysteria2 | 314.9 | 883.8 | 20.49 | 0.0 | 10.0 | 13.57 | 19.42 | Au1rxx-base64 | 66.94.121.46 |
| 78.13 | vless | 261.1 | 665.5 | 21.73 | 0.0 | 10.0 | 6.98 | 19.42 | Au1rxx-base64 | 136.117.218.86 |
| 77.14 | vless | 279.9 | 767.5 | 21.3 | 0.0 | 9.44 | 6.98 | 19.42 | Au1rxx-base64 | 5.78.159.214 |
| 77.12 | shadowsocks | 263.4 | 725.5 | 21.68 | 0.0 | 10.0 | 14.3 | 15.64 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.5 | hysteria2 | 260.9 | 369.4 | 21.74 | 1.15 | 8.28 | 13.57 | 19.42 | Au1rxx-base64 | open.w2m.ink |
| 75.26 | hysteria2 | 372.3 | 778.8 | 19.16 | 0.0 | 9.38 | 13.57 | 19.42 | Au1rxx-base64 | 159.223.157.129 |
| 74.97 | vless | 255.8 | 570.0 | 21.86 | 0.0 | 9.42 | 6.98 | 19.42 | Au1rxx-base64 | 192.3.247.109 |
| 72.94 | vless | 247.7 | 457.0 | 22.04 | 0.0 | 10.0 | 6.98 | 19.42 | Au1rxx-base64 | 162.159.48.32 |
| 72.78 | vless | 234.0 | 523.8 | 22.36 | 0.0 | 9.39 | 6.98 | 19.42 | Au1rxx-base64 | 137.175.82.40 |
| 72.4 | vless | 508.8 | 1417.9 | 16.0 | 0.0 | 10.0 | 6.98 | 19.42 | Au1rxx-base64 | 51.81.203.63 |
| 72.19 | vless | 252.8 | 447.2 | 21.92 | 0.0 | 10.0 | 6.98 | 19.42 | Au1rxx-base64 | 172.64.32.103 |
| 71.81 | shadowsocks | 350.0 | 546.1 | 19.68 | 0.0 | 9.34 | 14.3 | 19.42 | Au1rxx-base64 | 149.22.87.204 |
| 71.45 | shadowsocks | 427.3 | 985.7 | 17.89 | 0.0 | 9.36 | 14.3 | 19.42 | Au1rxx-base64 | 185.156.47.97 |
| 71.39 | vless | 357.9 | 769.5 | 19.49 | 0.0 | 9.39 | 6.98 | 19.42 | Au1rxx-base64 | 79.141.172.154 |
| 71.38 | shadowsocks | 425.3 | 880.9 | 17.93 | 0.0 | 9.34 | 14.3 | 19.42 | Au1rxx-base64 | 198.98.53.130 |
| 70.92 | vless | 331.3 | 798.5 | 20.11 | 0.0 | 10.0 | 6.98 | 15.64 | Surfboard-tg-mixed | 172.235.38.85 |
| 70.86 | shadowsocks | 313.9 | 671.9 | 20.51 | 0.0 | 9.35 | 14.3 | 19.42 | Au1rxx-base64 | 156.146.38.170 |
| 70.67 | vless | 343.5 | 698.0 | 19.83 | 0.0 | 9.42 | 6.98 | 19.42 | Au1rxx-base64 | 195.211.98.43 |
| 70.61 | shadowsocks | 401.8 | 944.1 | 18.48 | 0.0 | 10.0 | 14.3 | 15.64 | Surfboard-tg-mixed | 173.244.56.6 |
| 70.49 | shadowsocks | 325.1 | 688.9 | 20.25 | 0.0 | 9.36 | 14.3 | 19.42 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | 0.871 | 232 | 1624 | prefer |
| mheidari-all | 0.82 | 0.747 | 75 | 22444 | prefer |
| ermaozi | 0.701 | 0.696 | 46 | 338 | prefer |
| Surfboard-tg-mixed | 0.7 | 0.623 | 106 | 7280 | prefer |
| DeltaKronecker-all | 0.407 | 0.455 | 11 | 5452 | observe |
| ninja-vless | 0.312 | 0.5 | 4 | 1791 | observe |
| ermaozi-get_subscribe | 0.269 | 1.0 | 1 | 359 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7869 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9065 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5801 | observe |
| barry-far-vless | 0.255 | None | 0 | 6140 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4324 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 25 |
| 204 | ProxyError | - | 23 |
| geo | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| geo | ProxyError | - | 2 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

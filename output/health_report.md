# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-28 03:02:39 |
| 运行耗时 | 235.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 76048 |
| 去重后节点 | 23107 |
| TCP 可达 | 3000 |
| 真实可用 | 555 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23107 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 31.0 |
| probe | 52.0 |
| real_test | 112.6 |
| generate | 34.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42236 |
| trojan | 12740 |
| vmess | 11174 |
| shadowsocks | 9335 |
| hysteria2 | 228 |
| shadowsocksr | 150 |
| http | 135 |
| socks | 42 |
| hysteria | 6 |
| tuic | 2 |

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
| 76.21 | vless | 239.8 | 644.4 | 22.23 | 0.0 | 10.0 | 8.98 | 16.0 | Surfboard-tg-mixed | 137.184.218.169 |
| 74.97 | shadowsocks | 228.1 | 630.1 | 22.5 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 37.19.198.160 |
| 74.91 | shadowsocks | 230.4 | 628.8 | 22.44 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 37.19.198.244 |
| 74.85 | shadowsocks | 233.3 | 645.2 | 22.38 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 37.19.198.243 |
| 74.8 | vless | 258.3 | 723.7 | 21.8 | 0.0 | 10.0 | 8.98 | 14.02 | mheidari-all | 47.253.226.114 |
| 73.48 | shadowsocks | 243.0 | 650.3 | 22.15 | 0.0 | 10.0 | 11.81 | 14.02 | mheidari-all | 108.181.57.93 |
| 73.3 | vmess | 239.9 | 650.0 | 22.22 | 0.0 | 10.0 | 13.12 | 12.46 | DeltaKronecker-all | 67.220.85.46 |
| 73.01 | vless | 291.5 | 710.1 | 21.03 | 0.0 | 10.0 | 8.98 | 16.0 | Surfboard-tg-mixed | 162.159.18.241 |
| 71.7 | shadowsocks | 347.5 | 938.6 | 19.73 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 172.234.202.34 |
| 71.37 | shadowsocks | 284.8 | 655.4 | 21.19 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 156.146.38.167 |
| 71.31 | shadowsocks | 291.5 | 679.5 | 21.03 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 156.146.38.168 |
| 71.22 | vless | 286.2 | 696.0 | 21.15 | 0.0 | 10.0 | 8.98 | 16.0 | Surfboard-tg-mixed | 104.18.42.68 |
| 70.84 | vless | 240.9 | 636.5 | 22.2 | 0.0 | 10.0 | 8.98 | 14.66 | Au1rxx-base64 | 159.89.87.21 |
| 70.67 | vmess | 353.7 | 989.8 | 19.59 | 0.0 | 10.0 | 13.12 | 12.46 | DeltaKronecker-all | 67.220.95.3 |
| 70.4 | shadowsocks | 278.9 | 645.7 | 21.32 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 156.146.38.170 |
| 67.92 | vless | 421.6 | 792.0 | 18.02 | 0.0 | 10.0 | 8.98 | 14.02 | mheidari-all | 104.18.29.234 |
| 67.67 | shadowsocks | 312.3 | 567.4 | 20.55 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 173.244.56.9 |
| 66.88 | shadowsocks | 241.8 | 652.3 | 22.18 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 66.75 | shadowsocks | 359.3 | 680.4 | 19.46 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 108.181.0.177 |
| 66.32 | shadowsocks | 277.5 | 638.3 | 21.35 | 0.0 | 10.0 | 11.81 | 14.66 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.882 | 0.804 | 291 | 5007 | prefer |
| mheidari-all | 0.734 | 0.655 | 235 | 16017 | prefer |
| Au1rxx-base64 | 0.711 | 0.712 | 66 | 122 | prefer |
| DeltaKronecker-all | 0.612 | 0.532 | 154 | 6822 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4579 | observe |
| Epodonios-all | 0.255 | None | 0 | 7553 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3982 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7010 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3707 | observe |
| barry-far-vless | 0.255 | None | 0 | 4479 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5287 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.225 | None | 0 | 1261 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 95 |
| geo | TimeoutError | - | 67 |
| geo | ClientOSError | - | 18 |
| cn-block | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 11 |
| speed | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 6 |
| 204 | ProxyError | - | 5 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

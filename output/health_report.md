# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 19:55:30 |
| 运行耗时 | 308.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96449 |
| 去重后节点 | 25551 |
| TCP 可达 | 3000 |
| 真实可用 | 503 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25551 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 41.8 |
| probe | 93.0 |
| real_test | 123.6 |
| generate | 41.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61416 |
| vmess | 12547 |
| shadowsocks | 11043 |
| trojan | 9161 |
| hysteria2 | 1883 |
| http | 144 |
| shadowsocksr | 121 |
| socks | 62 |
| anytls | 38 |
| hysteria | 20 |
| tuic | 14 |

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
| 84.27 | vless | 234.5 | 631.9 | 22.35 | 0.0 | 9.26 | 12.8 | 19.86 | Au1rxx-base64 | 204.48.20.223 |
| 83.59 | vless | 264.4 | 649.1 | 21.66 | 0.0 | 9.27 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.212 |
| 83.46 | vless | 301.3 | 756.6 | 20.8 | 0.0 | 10.0 | 12.8 | 19.86 | Au1rxx-base64 | 66.70.179.198 |
| 83.13 | vless | 315.6 | 785.7 | 20.47 | 0.0 | 10.0 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.235 |
| 81.99 | vless | 333.2 | 835.9 | 20.06 | 0.0 | 9.27 | 12.8 | 19.86 | Au1rxx-base64 | 158.69.112.254 |
| 81.91 | vless | 263.7 | 695.5 | 21.67 | 0.0 | 9.26 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.225 |
| 81.83 | vless | 249.9 | 650.2 | 21.99 | 0.0 | 8.99 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.173 |
| 81.67 | vless | 338.8 | 865.0 | 19.94 | 0.0 | 9.07 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.182 |
| 81.66 | vless | 335.4 | 897.4 | 20.01 | 0.0 | 8.99 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.184 |
| 81.56 | vless | 340.0 | 912.6 | 19.91 | 0.0 | 8.99 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.52 |
| 81.54 | vless | 276.7 | 769.6 | 21.37 | 0.0 | 8.61 | 12.8 | 19.86 | Au1rxx-base64 | using.neobo-tooth.ru |
| 81.54 | vless | 340.6 | 940.6 | 19.89 | 0.0 | 8.99 | 12.8 | 19.86 | Au1rxx-base64 | 185.95.231.156 |
| 81.53 | vless | 339.2 | 856.1 | 19.93 | 0.0 | 8.94 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.95 |
| 81.41 | vless | 346.7 | 934.3 | 19.75 | 0.0 | 9.0 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.202 |
| 81.37 | vless | 267.2 | 637.4 | 21.59 | 0.0 | 9.26 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.104 |
| 81.27 | vless | 364.7 | 868.8 | 19.34 | 0.0 | 9.27 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.35 |
| 81.11 | vless | 362.7 | 926.8 | 19.38 | 0.0 | 9.07 | 12.8 | 19.86 | Au1rxx-base64 | 216.152.147.28 |
| 81.06 | vless | 365.4 | 921.2 | 19.32 | 0.0 | 9.08 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.163 |
| 81.04 | vless | 366.1 | 921.7 | 19.3 | 0.0 | 9.08 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.15 |
| 79.6 | vless | 350.0 | 820.5 | 19.68 | 0.0 | 9.26 | 12.8 | 19.86 | Au1rxx-base64 | 169.40.42.231 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.926 | 0.957 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.888 | 0.819 | 354 | 1764 | prefer |
| Surfboard-tg-mixed | 0.83 | 0.753 | 146 | 7188 | prefer |
| mheidari-all | 0.521 | 0.44 | 168 | 22630 | observe |
| tg-oneclickvpnkeys | 0.39 | 0.714 | 7 | 132 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 6212 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6965 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4887 | observe |
| Epodonios-all | 0.255 | None | 0 | 7653 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8188 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6027 | observe |
| barry-far-vless | 0.255 | None | 0 | 6249 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4087 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 57 |
| 204 | TimeoutError | - | 51 |
| geo | ClientOSError | - | 32 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 7 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| geo | TimeoutError | - | 4 |
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

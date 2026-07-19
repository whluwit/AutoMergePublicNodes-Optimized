# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-19 19:03:55 |
| 运行耗时 | 263.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 86063 |
| 去重后节点 | 23799 |
| TCP 可达 | 3000 |
| 真实可用 | 398 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23799 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 34.6 |
| probe | 64.7 |
| real_test | 130.6 |
| generate | 27.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50022 |
| trojan | 14309 |
| vmess | 10867 |
| shadowsocks | 10229 |
| hysteria2 | 431 |
| shadowsocksr | 75 |
| http | 57 |
| socks | 44 |
| hysteria | 15 |
| tuic | 13 |
| anytls | 1 |

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
| 78.88 | shadowsocks | 241.4 | 605.9 | 22.19 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 156.146.38.168 |
| 78.85 | shadowsocks | 242.9 | 624.9 | 22.16 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 156.146.38.169 |
| 78.8 | shadowsocks | 244.9 | 628.3 | 22.11 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 156.146.38.170 |
| 77.95 | shadowsocks | 281.4 | 735.4 | 21.26 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 156.146.38.167 |
| 76.65 | trojan | 340.6 | 856.5 | 19.89 | 0.0 | 10.0 | 12.02 | 17.74 | Au1rxx-base64 | 64.94.95.118 |
| 74.84 | shadowsocks | 268.3 | 537.1 | 21.57 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 173.244.56.9 |
| 74.26 | shadowsocks | 265.6 | 521.4 | 21.63 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 108.181.0.177 |
| 73.61 | trojan | 342.7 | 853.2 | 19.85 | 0.0 | 10.0 | 12.02 | 17.74 | Au1rxx-base64 | 64.94.95.117 |
| 73.54 | shadowsocks | 324.4 | 721.9 | 20.27 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 37.19.198.244 |
| 73.4 | shadowsocks | 323.9 | 710.1 | 20.28 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 147.90.234.133 |
| 73.22 | trojan | 272.8 | 644.8 | 21.46 | 0.0 | 10.0 | 12.02 | 17.74 | Au1rxx-base64 | 64.94.95.115 |
| 72.98 | shadowsocks | 292.4 | 574.6 | 21.01 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 149.22.95.183 |
| 72.97 | shadowsocks | 317.1 | 709.7 | 20.44 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 37.19.198.243 |
| 72.84 | shadowsocks | 328.9 | 722.6 | 20.16 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 37.19.198.236 |
| 72.71 | shadowsocks | 321.4 | 706.5 | 20.34 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 37.19.198.160 |
| 71.8 | shadowsocks | 347.5 | 768.0 | 19.73 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 108.181.118.10 |
| 71.77 | shadowsocks | 357.9 | 722.6 | 19.49 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 68.168.222.210 |
| 71.65 | shadowsocks | 400.3 | 904.6 | 18.51 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 172.245.235.84 |
| 70.93 | shadowsocks | 307.6 | 313.1 | 20.66 | 3.26 | 9.78 | 12.95 | 17.74 | Au1rxx-base64 | 149.22.87.204 |
| 70.72 | shadowsocks | 378.3 | 891.5 | 19.02 | 0.0 | 10.0 | 12.95 | 17.74 | Au1rxx-base64 | 50.114.177.235 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.86 | 0.82 | 233 | 1082 | prefer |
| Surfboard-tg-mixed | 0.445 | 0.364 | 176 | 5352 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4642 | observe |
| mheidari-all | 0.418 | 0.335 | 155 | 19340 | observe |
| nscl5-all | 0.391 | 1.0 | 2 | 2755 | observe |
| DeltaKronecker-all | 0.339 | 0.257 | 183 | 6235 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4478 | observe |
| Epodonios-all | 0.255 | None | 0 | 6712 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7035 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4199 | observe |
| barry-far-vless | 0.255 | None | 0 | 4995 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 200 |
| geo | TimeoutError | - | 75 |
| 204 | TimeoutError | - | 37 |
| cn-block | TimeoutError | - | 33 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 13 |
| 204 | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

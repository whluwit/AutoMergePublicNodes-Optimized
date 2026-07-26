# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 19:08:37 |
| 运行耗时 | 313.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84027 |
| 去重后节点 | 22059 |
| TCP 可达 | 3000 |
| 真实可用 | 688 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22059 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.3 |
| tcp | 31.8 |
| probe | 64.6 |
| real_test | 166.9 |
| generate | 43.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46668 |
| trojan | 16155 |
| shadowsocks | 10242 |
| vmess | 10093 |
| hysteria2 | 567 |
| shadowsocksr | 102 |
| http | 84 |
| socks | 70 |
| anytls | 21 |
| hysteria | 15 |
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
| 80.3 | shadowsocks | 195.6 | 522.3 | 23.25 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 173.244.56.9 |
| 79.69 | shadowsocks | 200.5 | 482.5 | 23.14 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 108.181.0.177 |
| 79.67 | shadowsocks | 201.3 | 488.0 | 23.12 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 108.181.118.10 |
| 76.12 | trojan | 303.5 | 656.7 | 20.75 | 0.0 | 10.0 | 12.57 | 19.38 | Au1rxx-base64 | 163.245.196.68 |
| 75.74 | shadowsocks | 274.9 | 623.9 | 21.41 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 156.146.38.167 |
| 75.4 | shadowsocks | 285.2 | 652.9 | 21.18 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 156.146.38.170 |
| 75.37 | shadowsocks | 192.6 | 516.9 | 23.32 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 173.244.56.6 |
| 75.34 | shadowsocks | 288.0 | 667.4 | 21.11 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 156.146.38.169 |
| 75.28 | shadowsocks | 267.1 | 562.9 | 21.59 | 0.0 | 10.0 | 11.67 | 19.38 | Au1rxx-base64 | 149.22.95.183 |
| 74.44 | trojan | 352.0 | 320.0 | 19.63 | 3.0 | 9.91 | 12.57 | 19.38 | Au1rxx-base64 | 31.223.184.109 |
| 73.88 | trojan | 348.6 | 338.1 | 19.71 | 2.32 | 9.91 | 12.57 | 19.38 | Au1rxx-base64 | 31.223.184.238 |
| 73.82 | trojan | 336.3 | 345.9 | 19.99 | 2.03 | 9.89 | 12.57 | 19.38 | Au1rxx-base64 | 31.223.184.218 |
| 73.65 | vless | 186.7 | 490.8 | 23.46 | 0.0 | 10.0 | 5.81 | 19.38 | Au1rxx-base64 | 154.26.183.5 |
| 73.63 | trojan | 341.1 | 349.8 | 19.88 | 1.88 | 9.88 | 12.57 | 19.38 | Au1rxx-base64 | 31.223.184.164 |
| 73.61 | trojan | 337.8 | 342.7 | 19.96 | 2.15 | 9.56 | 12.57 | 19.38 | Au1rxx-base64 | inspired-hound.rooster465.autos |
| 73.6 | vless | 188.7 | 491.8 | 23.41 | 0.0 | 10.0 | 5.81 | 19.38 | Au1rxx-base64 | 154.21.83.77 |
| 73.03 | vless | 213.4 | 491.7 | 22.84 | 0.0 | 10.0 | 5.81 | 19.38 | Au1rxx-base64 | 173.249.200.68 |
| 72.57 | vless | 233.3 | 435.9 | 22.38 | 0.0 | 10.0 | 5.81 | 19.38 | Au1rxx-base64 | 154.17.238.183 |
| 71.81 | vless | 194.5 | 476.3 | 23.28 | 0.0 | 10.0 | 5.81 | 13.72 | mheidari-all | 198.41.209.87 |
| 71.74 | trojan | 354.5 | 392.1 | 19.57 | 0.3 | 9.9 | 12.57 | 19.38 | Au1rxx-base64 | 31.223.184.125 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 1.0 | 76 | 86 | prefer |
| Au1rxx-base64 | 0.964 | 0.906 | 446 | 1507 | prefer |
| mheidari-all | 0.519 | 0.439 | 278 | 19379 | observe |
| Surfboard-tg-mixed | 0.496 | 0.415 | 164 | 5487 | observe |
| tg-oneclickvpnkeys | 0.483 | 1.0 | 6 | 164 | observe |
| DeltaKronecker-all | 0.404 | 0.314 | 35 | 4320 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3959 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6631 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3967 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6559 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4235 | observe |
| barry-far-vless | 0.255 | None | 0 | 4894 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5003 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 114 |
| speed | ClientOSError | - | 81 |
| cn-block | TimeoutError | - | 36 |
| 204 | TimeoutError | - | 24 |
| geo | ClientOSError | - | 21 |
| speed | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 10 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

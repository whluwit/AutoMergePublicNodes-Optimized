# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 08:37:45 |
| 运行耗时 | 350.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 78927 |
| 去重后节点 | 22698 |
| TCP 可达 | 3000 |
| 真实可用 | 682 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22698 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 32.2 |
| probe | 70.6 |
| real_test | 209.8 |
| generate | 30.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46094 |
| trojan | 11167 |
| shadowsocks | 10717 |
| vmess | 10174 |
| hysteria2 | 501 |
| http | 98 |
| shadowsocksr | 75 |
| socks | 60 |
| anytls | 26 |
| hysteria | 12 |
| tuic | 3 |

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
| 84.24 | hysteria2 | 259.2 | 663.5 | 21.78 | 0.0 | 10.0 | 14.12 | 19.44 | Au1rxx-base64 | 159.223.157.129 |
| 80.76 | shadowsocks | 258.5 | 632.8 | 21.79 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 156.146.38.168 |
| 80.68 | shadowsocks | 251.6 | 612.3 | 21.95 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 156.146.38.170 |
| 80.49 | shadowsocks | 270.2 | 678.3 | 21.52 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 37.19.198.243 |
| 80.42 | shadowsocks | 273.2 | 693.7 | 21.45 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 37.19.198.244 |
| 80.05 | shadowsocks | 289.5 | 738.2 | 21.08 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 37.19.198.160 |
| 79.02 | shadowsocks | 334.0 | 864.5 | 20.05 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 156.146.38.167 |
| 78.97 | trojan | 296.2 | 725.8 | 20.92 | 0.0 | 10.0 | 12.57 | 19.44 | Au1rxx-base64 | 153.75.250.171 |
| 77.66 | trojan | 394.5 | 1095.6 | 18.65 | 0.0 | 10.0 | 12.57 | 19.44 | Au1rxx-base64 | 148.72.168.35 |
| 77.19 | trojan | 284.3 | 637.2 | 21.2 | 0.0 | 10.0 | 12.57 | 19.44 | Au1rxx-base64 | 163.245.196.68 |
| 76.94 | shadowsocks | 276.9 | 700.6 | 21.37 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 37.19.198.236 |
| 75.89 | shadowsocks | 274.5 | 555.9 | 21.42 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 173.244.56.9 |
| 75.64 | shadowsocks | 281.9 | 573.0 | 21.25 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 173.244.56.6 |
| 75.63 | shadowsocks | 458.9 | 1072.6 | 17.16 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 68.168.222.210 |
| 75.6 | shadowsocks | 356.4 | 899.8 | 19.53 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 146.70.34.226 |
| 75.3 | shadowsocks | 364.6 | 917.2 | 19.34 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 185.247.68.94 |
| 74.77 | shadowsocks | 332.9 | 705.6 | 20.07 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 149.22.95.183 |
| 74.7 | shadowsocks | 395.5 | 951.4 | 18.62 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 185.232.22.18 |
| 74.53 | vless | 297.4 | 680.0 | 20.89 | 0.0 | 10.0 | 9.58 | 16.06 | DeltaKronecker-all | 78.153.155.112 |
| 74.46 | shadowsocks | 324.4 | 653.2 | 20.27 | 0.0 | 10.0 | 13.53 | 19.44 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 96 | 167 | prefer |
| Au1rxx-base64 | 0.795 | 0.747 | 269 | 1232 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.667 | 24 | 5709 | prefer |
| DeltaKronecker-all | 0.526 | 0.446 | 810 | 5519 | observe |
| mheidari-all | 0.402 | 0.316 | 19 | 16908 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5118 | observe |
| Epodonios-all | 0.255 | None | 0 | 6451 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6039 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4501 | observe |
| barry-far-vless | 0.255 | None | 0 | 4902 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5089 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 201 |
| cn-block | TimeoutError | - | 77 |
| speed | ClientOSError | - | 65 |
| speed | TimeoutError | - | 57 |
| 204 | ProxyError | - | 46 |
| geo | ClientOSError | - | 41 |
| 204 | TimeoutError | - | 32 |
| cn-block | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 6 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

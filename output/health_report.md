# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 02:29:49 |
| 运行耗时 | 253.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 89263 |
| 去重后节点 | 24750 |
| TCP 可达 | 3000 |
| 真实可用 | 443 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24750 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.3 |
| tcp | 36.9 |
| probe | 53.1 |
| real_test | 117.0 |
| generate | 38.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52078 |
| vmess | 13373 |
| trojan | 11706 |
| shadowsocks | 10326 |
| hysteria2 | 1512 |
| socks | 96 |
| shadowsocksr | 72 |
| http | 35 |
| anytls | 30 |
| hysteria | 21 |
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
| 84.79 | trojan | 218.1 | 534.5 | 22.73 | 0.0 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 44.244.3.114 |
| 84.6 | trojan | 199.8 | 471.8 | 23.15 | 0.0 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 35.86.90.51 |
| 84.57 | trojan | 231.6 | 571.4 | 22.42 | 0.0 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 44.246.163.102 |
| 84.11 | trojan | 251.4 | 634.1 | 21.96 | 0.0 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 35.91.251.124 |
| 82.11 | trojan | 198.1 | 476.6 | 23.19 | 0.0 | 6.77 | 14.71 | 19.94 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 82.05 | trojan | 199.5 | 479.6 | 23.16 | 0.0 | 6.74 | 14.71 | 19.94 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 81.94 | trojan | 199.7 | 472.3 | 23.15 | 0.0 | 6.64 | 14.71 | 19.94 | Au1rxx-base64 | sincere-gelding.rooster465.autos |
| 81.57 | trojan | 213.4 | 519.9 | 22.84 | 0.0 | 6.58 | 14.71 | 19.94 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 81.42 | trojan | 312.3 | 815.3 | 20.55 | 0.0 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 44.242.235.129 |
| 80.38 | trojan | 268.1 | 681.3 | 21.57 | 0.0 | 6.66 | 14.71 | 19.94 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 79.8 | shadowsocks | 256.4 | 266.1 | 21.84 | 5.02 | 10.0 | 13.9 | 19.94 | Au1rxx-base64 | 149.22.87.240 |
| 79.27 | hysteria2 | 265.4 | 688.1 | 21.63 | 0.0 | 10.0 | 13.7 | 19.94 | Au1rxx-base64 | lll.lucklyee.xyz |
| 78.42 | trojan | 311.9 | 317.2 | 20.56 | 3.11 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 3.112.223.141 |
| 78.36 | trojan | 310.5 | 319.4 | 20.59 | 3.02 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 57.180.13.78 |
| 78.36 | trojan | 315.4 | 312.7 | 20.48 | 3.27 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 43.207.89.29 |
| 78.23 | trojan | 314.2 | 320.5 | 20.5 | 2.98 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 18.181.175.120 |
| 78.23 | trojan | 321.6 | 315.2 | 20.33 | 3.18 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 54.249.34.120 |
| 78.17 | trojan | 311.1 | 318.9 | 20.58 | 3.04 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 13.230.118.96 |
| 78.17 | trojan | 312.2 | 323.4 | 20.55 | 2.87 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 43.207.140.98 |
| 78.15 | trojan | 311.5 | 324.5 | 20.57 | 2.83 | 10.0 | 14.71 | 19.94 | Au1rxx-base64 | 13.231.232.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.977 | 345 | 1260 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.486 | 0.4 | 30 | 5948 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 5184 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5219 | observe |
| nscl5-all | 0.326 | 1.0 | 1 | 1772 | observe |
| DeltaKronecker-all | 0.294 | 0.2 | 40 | 5897 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6478 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7798 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4749 | observe |
| barry-far-vless | 0.255 | None | 0 | 5038 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5225 | observe |
| mheidari-all | 0.243 | 0.161 | 378 | 20680 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 202 |
| geo | ClientOSError | - | 63 |
| speed | TimeoutError | - | 56 |
| speed | ClientOSError | - | 40 |
| 204 | ClientOSError | - | 4 |
| 204 | TimeoutError | - | 4 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

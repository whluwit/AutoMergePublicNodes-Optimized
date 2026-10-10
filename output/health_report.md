# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 04:17:54 |
| 运行耗时 | 1053.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98044 |
| 去重后节点 | 27733 |
| TCP 可达 | 3000 |
| 真实可用 | 553 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27733 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 47.7 |
| probe | 344.2 |
| real_test | 563.6 |
| generate | 88.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57282 |
| vmess | 15696 |
| shadowsocks | 11876 |
| trojan | 10782 |
| hysteria2 | 1553 |
| http | 555 |
| shadowsocksr | 173 |
| socks | 70 |
| anytls | 28 |
| hysteria | 17 |
| tuic | 12 |

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
| 82.41 | vless | 297.9 | 681.9 | 20.88 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.225 |
| 82.4 | vless | 299.0 | 729.9 | 20.86 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.133 |
| 82.35 | hysteria2 | 265.1 | 706.9 | 21.64 | 0.0 | 10.0 | 12.63 | 19.58 | Au1rxx-base64 | 129.213.91.185 |
| 81.69 | vless | 336.7 | 731.2 | 19.98 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.182 |
| 81.39 | shadowsocks | 253.7 | 620.3 | 21.91 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 156.146.38.170 |
| 81.37 | shadowsocks | 254.2 | 619.2 | 21.89 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 156.146.38.169 |
| 81.37 | shadowsocks | 254.2 | 621.5 | 21.89 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 156.146.38.167 |
| 81.17 | vless | 304.6 | 719.8 | 20.73 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 66.70.179.198 |
| 81.1 | vless | 362.4 | 911.4 | 19.39 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 137.184.218.169 |
| 81.04 | shadowsocks | 246.9 | 713.1 | 22.06 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 66.23.204.214 |
| 80.69 | shadowsocks | 283.9 | 727.1 | 21.21 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 37.19.198.243 |
| 80.61 | shadowsocks | 287.3 | 742.6 | 21.13 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 37.19.198.244 |
| 80.55 | vless | 386.3 | 1003.5 | 18.84 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 185.95.231.156 |
| 80.52 | shadowsocks | 291.3 | 745.3 | 21.04 | 0.0 | 10.0 | 13.9 | 19.58 | Au1rxx-base64 | 37.19.198.160 |
| 80.45 | vless | 390.4 | 818.5 | 18.74 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.15 |
| 80.38 | vless | 333.1 | 719.0 | 20.07 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.75 |
| 80.27 | vless | 268.7 | 678.2 | 21.56 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 198.251.78.29 |
| 80.26 | vless | 287.9 | 703.0 | 21.11 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.16 |
| 79.82 | vless | 395.5 | 944.5 | 18.62 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.52 |
| 79.58 | vless | 428.0 | 1002.8 | 17.87 | 0.0 | 10.0 | 12.13 | 19.58 | Au1rxx-base64 | 169.40.42.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | 0.928 | 359 | 1803 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Surfboard-tg-mixed | 0.695 | 0.617 | 193 | 7155 | observe |
| ermaozi-get_subscribe | 0.656 | 0.64 | 25 | 653 | observe |
| mheidari-all | 0.34 | 0.258 | 240 | 23395 | observe |
| 10ium-ScrapeCategorize-Vless | 0.287 | 0.5 | 2 | 4984 | observe |
| Epodonios-all | 0.255 | None | 0 | 7634 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9711 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5643 | observe |
| barry-far-vless | 0.255 | None | 0 | 5793 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4346 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1803 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 131 |
| speed | TimeoutError | - | 67 |
| geo | ClientOSError | - | 35 |
| speed | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

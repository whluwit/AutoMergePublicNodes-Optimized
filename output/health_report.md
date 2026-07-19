# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-19 13:11:56 |
| 运行耗时 | 322.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 86855 |
| 去重后节点 | 23672 |
| TCP 可达 | 3000 |
| 真实可用 | 443 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23672 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.0 |
| tcp | 34.1 |
| probe | 61.4 |
| real_test | 178.4 |
| generate | 42.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49475 |
| trojan | 15571 |
| vmess | 10849 |
| shadowsocks | 10315 |
| hysteria2 | 393 |
| shadowsocksr | 124 |
| http | 55 |
| socks | 50 |
| hysteria | 15 |
| tuic | 7 |
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
| 77.52 | shadowsocks | 206.4 | 554.2 | 23.0 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 149.22.95.183 |
| 73.3 | shadowsocks | 244.6 | 497.4 | 22.12 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 108.181.118.10 |
| 73.24 | shadowsocks | 253.8 | 523.9 | 21.9 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 108.181.0.177 |
| 72.56 | vless | 229.8 | 515.9 | 22.46 | 0.0 | 10.0 | 2.75 | 18.04 | Surfboard-tg-mixed | 64.23.143.23 |
| 72.47 | shadowsocks | 281.3 | 547.7 | 21.27 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 173.244.56.9 |
| 72.08 | trojan | 331.2 | 676.1 | 20.11 | 0.0 | 10.0 | 13.95 | 15.54 | Au1rxx-base64 | 64.94.95.118 |
| 71.42 | shadowsocks | 279.1 | 332.4 | 21.32 | 2.54 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 149.22.87.241 |
| 71.27 | shadowsocks | 256.5 | 268.0 | 21.84 | 4.95 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 149.22.87.204 |
| 71.26 | vless | 272.4 | 654.2 | 21.47 | 0.0 | 10.0 | 2.75 | 18.04 | Surfboard-tg-mixed | 198.41.209.87 |
| 70.53 | shadowsocks | 329.7 | 704.0 | 20.15 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 156.146.38.169 |
| 70.47 | shadowsocks | 323.4 | 699.0 | 20.29 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 156.146.38.168 |
| 70.27 | shadowsocks | 316.1 | 686.0 | 20.46 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 156.146.38.167 |
| 69.67 | shadowsocks | 323.4 | 677.3 | 20.29 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 156.146.38.170 |
| 69.51 | shadowsocks | 378.0 | 758.8 | 19.03 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 172.245.235.84 |
| 69.36 | trojan | 335.2 | 365.1 | 20.02 | 1.31 | 10.0 | 13.95 | 18.04 | Surfboard-tg-mixed | 198.177.57.9 |
| 69.34 | shadowsocks | 260.3 | 266.6 | 21.75 | 5.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 149.22.87.240 |
| 69.03 | trojan | 287.6 | 725.6 | 21.12 | 0.0 | 10.0 | 13.95 | 11.46 | mheidari-all | 44.243.31.46 |
| 68.52 | shadowsocks | 358.0 | 724.7 | 19.49 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 37.19.198.244 |
| 68.44 | shadowsocks | 362.0 | 743.7 | 19.4 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 37.19.198.160 |
| 68.43 | shadowsocks | 358.4 | 738.3 | 19.48 | 0.0 | 10.0 | 12.98 | 15.54 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.887 | 0.845 | 213 | 1125 | prefer |
| Surfboard-tg-mixed | 0.463 | 0.382 | 204 | 5424 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4642 | observe |
| mheidari-all | 0.348 | 0.268 | 512 | 20221 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6635 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4191 | observe |
| barry-far-vless | 0.255 | None | 0 | 4858 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5355 | observe |
| nscl5-all | 0.255 | None | 0 | 2755 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| Au1rxx-clash | 0.22 | None | 0 | 1125 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 346 |
| speed | ClientOSError | - | 96 |
| geo | ClientOSError | - | 70 |
| cn-block | TimeoutError | - | 49 |
| 204 | TimeoutError | - | 20 |
| speed | TimeoutError | - | 14 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37748: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

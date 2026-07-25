# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 13:19:58 |
| 运行耗时 | 329.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78949 |
| 去重后节点 | 22521 |
| TCP 可达 | 3000 |
| 真实可用 | 739 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22521 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.3 |
| tcp | 31.4 |
| probe | 66.1 |
| real_test | 177.8 |
| generate | 47.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44218 |
| trojan | 14034 |
| vmess | 10110 |
| shadowsocks | 9906 |
| hysteria2 | 432 |
| http | 81 |
| shadowsocksr | 74 |
| socks | 67 |
| hysteria | 15 |
| tuic | 11 |
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
| 76.77 | vless | 283.9 | 709.1 | 21.21 | 0.0 | 10.0 | 5.98 | 19.58 | mheidari-all | 47.89.186.170 |
| 76.28 | shadowsocks | 257.1 | 633.8 | 21.83 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 156.146.38.170 |
| 76.14 | shadowsocks | 263.0 | 656.1 | 21.69 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 37.19.198.244 |
| 75.95 | shadowsocks | 268.6 | 670.4 | 21.56 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 156.146.38.169 |
| 75.9 | trojan | 371.0 | 935.0 | 19.19 | 0.0 | 10.0 | 13.78 | 16.6 | Au1rxx-base64 | 64.94.95.117 |
| 75.88 | shadowsocks | 274.1 | 617.5 | 21.43 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 156.146.38.167 |
| 75.84 | shadowsocks | 275.8 | 694.2 | 21.39 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 37.19.198.160 |
| 75.53 | shadowsocks | 289.3 | 727.2 | 21.08 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 37.19.198.243 |
| 74.08 | shadowsocks | 330.6 | 869.9 | 20.13 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 185.196.61.82 |
| 72.91 | trojan | 408.6 | 1031.0 | 18.32 | 0.0 | 10.0 | 13.78 | 16.6 | Au1rxx-base64 | 163.245.196.68 |
| 72.87 | trojan | 299.0 | 721.0 | 20.86 | 0.0 | 10.0 | 13.78 | 16.6 | Au1rxx-base64 | 64.94.95.115 |
| 72.38 | trojan | 362.6 | 904.5 | 19.38 | 0.0 | 10.0 | 13.78 | 13.06 | DeltaKronecker-all | 64.74.163.118 |
| 71.99 | vless | 313.2 | 711.5 | 20.53 | 0.0 | 10.0 | 5.98 | 19.58 | mheidari-all | 104.16.9.20 |
| 71.5 | trojan | 486.7 | 805.8 | 16.51 | 0.0 | 10.0 | 13.78 | 19.58 | mheidari-all | 104.16.174.121 |
| 71.25 | trojan | 494.9 | 859.1 | 16.32 | 0.0 | 10.0 | 13.78 | 19.58 | mheidari-all | 104.18.152.219 |
| 71.22 | trojan | 480.6 | 800.6 | 16.65 | 0.0 | 10.0 | 13.78 | 19.58 | mheidari-all | 104.16.174.37 |
| 71.02 | trojan | 506.7 | 828.4 | 16.05 | 0.0 | 10.0 | 13.78 | 19.58 | mheidari-all | 104.16.174.71 |
| 70.76 | trojan | 494.7 | 805.4 | 16.33 | 0.0 | 10.0 | 13.78 | 19.58 | mheidari-all | 8.6.112.6 |
| 70.58 | shadowsocks | 287.1 | 664.5 | 21.13 | 0.0 | 10.0 | 11.85 | 16.6 | Au1rxx-base64 | 156.146.38.168 |
| 70.32 | shadowsocks | 282.7 | 577.9 | 21.23 | 0.0 | 9.24 | 11.85 | 16.6 | Au1rxx-base64 | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.979 | 0.987 | 76 | 119 | prefer |
| Au1rxx-base64 | 0.914 | 0.885 | 295 | 803 | prefer |
| mheidari-all | 0.81 | 0.731 | 391 | 17158 | prefer |
| Surfboard-tg-mixed | 0.663 | 0.586 | 58 | 5379 | observe |
| DeltaKronecker-all | 0.521 | 0.44 | 184 | 5838 | observe |
| Epodonios-all | 0.335 | 1.0 | 1 | 6540 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 180 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6338 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4058 | observe |
| barry-far-vless | 0.255 | None | 0 | 4746 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5009 | observe |
| nscl5-all | 0.255 | None | 0 | 2974 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 52 |
| geo | TimeoutError | - | 51 |
| 204 | ProxyError | - | 41 |
| speed | ClientOSError | - | 41 |
| 204 | TimeoutError | - | 34 |
| cn-block | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 9 |
| geo | ProxyError | - | 8 |
| geo | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| speed | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:31485: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 06:42:07 |
| 运行耗时 | 268.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78216 |
| 去重后节点 | 22272 |
| TCP 可达 | 3000 |
| 真实可用 | 635 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22272 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 35.3 |
| probe | 56.3 |
| real_test | 123.1 |
| generate | 46.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49037 |
| shadowsocks | 10812 |
| vmess | 10367 |
| trojan | 6642 |
| hysteria2 | 992 |
| http | 164 |
| shadowsocksr | 123 |
| socks | 69 |
| hysteria | 7 |
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
| 81.54 | shadowsocks | 239.6 | 667.0 | 22.23 | 0.0 | 10.0 | 13.99 | 19.32 | Au1rxx-base64 | 37.19.198.243 |
| 80.73 | shadowsocks | 242.7 | 676.6 | 22.16 | 0.0 | 9.26 | 13.99 | 19.32 | Au1rxx-base64 | 37.19.198.160 |
| 80.67 | shadowsocks | 245.5 | 643.8 | 22.09 | 0.0 | 9.27 | 13.99 | 19.32 | Au1rxx-base64 | 155.138.136.240 |
| 79.65 | shadowsocks | 299.9 | 850.1 | 20.84 | 0.0 | 10.0 | 13.99 | 19.32 | Au1rxx-base64 | 15.204.246.132 |
| 79.64 | shadowsocks | 288.1 | 812.3 | 21.11 | 0.0 | 9.22 | 13.99 | 19.32 | Au1rxx-base64 | 37.19.198.244 |
| 79.63 | shadowsocks | 234.2 | 647.3 | 22.36 | 0.0 | 10.0 | 13.99 | 17.28 | Surfboard-tg-mixed | 37.19.198.236 |
| 78.3 | vless | 252.0 | 699.7 | 21.94 | 0.0 | 10.0 | 7.04 | 19.32 | Au1rxx-base64 | 47.89.186.170 |
| 78.3 | shadowsocks | 358.0 | 1034.3 | 19.49 | 0.0 | 10.0 | 13.99 | 19.32 | Au1rxx-base64 | 15.204.247.175 |
| 78.05 | vless | 263.0 | 631.5 | 21.69 | 0.0 | 10.0 | 7.04 | 19.32 | Au1rxx-base64 | 195.211.99.49 |
| 77.97 | vless | 266.4 | 706.5 | 21.61 | 0.0 | 10.0 | 7.04 | 19.32 | Au1rxx-base64 | 169.40.42.231 |
| 77.62 | vless | 281.6 | 759.3 | 21.26 | 0.0 | 10.0 | 7.04 | 19.32 | Au1rxx-base64 | 169.40.42.184 |
| 77.54 | shadowsocks | 278.4 | 635.0 | 21.33 | 0.0 | 9.22 | 13.99 | 19.32 | Au1rxx-base64 | 156.146.38.170 |
| 77.22 | vless | 298.7 | 736.1 | 20.86 | 0.0 | 10.0 | 7.04 | 19.32 | Au1rxx-base64 | 158.69.112.254 |
| 76.59 | vless | 295.6 | 745.0 | 20.94 | 0.0 | 9.29 | 7.04 | 19.32 | Au1rxx-base64 | 169.40.42.133 |
| 76.5 | vless | 297.4 | 735.2 | 20.89 | 0.0 | 9.25 | 7.04 | 19.32 | Au1rxx-base64 | 66.70.179.198 |
| 76.45 | vless | 332.1 | 826.6 | 20.09 | 0.0 | 10.0 | 7.04 | 19.32 | Au1rxx-base64 | 169.40.42.173 |
| 76.32 | vless | 307.2 | 702.1 | 20.67 | 0.0 | 9.29 | 7.04 | 19.32 | Au1rxx-base64 | 169.40.42.89 |
| 76.24 | shadowsocks | 360.7 | 975.6 | 19.43 | 0.0 | 10.0 | 13.99 | 19.32 | Au1rxx-base64 | 140.238.153.81 |
| 76.23 | shadowsocks | 278.2 | 633.7 | 21.34 | 0.0 | 10.0 | 13.99 | 17.28 | Surfboard-tg-mixed | 156.146.38.168 |
| 76.07 | vless | 316.2 | 881.4 | 20.46 | 0.0 | 9.25 | 7.04 | 19.32 | Au1rxx-base64 | 137.184.218.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Au1rxx-base64 | 0.929 | 0.862 | 501 | 1700 | prefer |
| Surfboard-tg-mixed | 0.805 | 0.728 | 136 | 6406 | prefer |
| DeltaKronecker-all | 0.604 | 0.524 | 82 | 6340 | observe |
| mheidari-all | 0.602 | 0.523 | 65 | 14480 | observe |
| roosterkid-openproxylist-v2ray | 0.406 | 1.0 | 4 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6925 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6957 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5245 | observe |
| barry-far-vless | 0.255 | None | 0 | 5525 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1705 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 63 |
| 204 | TimeoutError | - | 31 |
| speed | TimeoutError | - | 24 |
| speed | ClientOSError | - | 18 |
| geo | ClientOSError | - | 15 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33531: bind: address already in use | - | 1 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

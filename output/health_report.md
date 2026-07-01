# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-01 03:02:15 |
| 运行耗时 | 228.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 75310 |
| 去重后节点 | 23048 |
| TCP 可达 | 3000 |
| 真实可用 | 544 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23048 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.4 |
| tcp | 30.7 |
| probe | 54.2 |
| real_test | 106.7 |
| generate | 31.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42266 |
| trojan | 12936 |
| vmess | 10187 |
| shadowsocks | 9316 |
| hysteria2 | 258 |
| shadowsocksr | 147 |
| http | 135 |
| socks | 58 |
| hysteria | 6 |
| tuic | 1 |

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
| 77.18 | shadowsocks | 241.4 | 648.4 | 22.19 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 37.19.198.236 |
| 77.14 | shadowsocks | 243.2 | 654.0 | 22.15 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 37.19.198.160 |
| 77.14 | shadowsocks | 243.2 | 655.0 | 22.15 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 37.19.198.244 |
| 77.13 | shadowsocks | 243.8 | 656.8 | 22.14 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 37.19.198.243 |
| 76.06 | shadowsocks | 268.3 | 710.5 | 21.57 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 108.181.57.93 |
| 74.23 | shadowsocks | 284.1 | 651.2 | 21.2 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 156.146.38.167 |
| 73.44 | shadowsocks | 272.0 | 622.6 | 21.48 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 156.146.38.168 |
| 73.35 | vless | 266.4 | 731.3 | 21.61 | 0.0 | 10.0 | 5.6 | 16.14 | mheidari-all | 47.253.226.114 |
| 72.87 | shadowsocks | 272.6 | 630.6 | 21.47 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 156.146.38.170 |
| 72.81 | shadowsocks | 321.7 | 767.2 | 20.33 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 156.146.38.169 |
| 72.51 | shadowsocks | 227.9 | 600.0 | 22.5 | 0.0 | 10.0 | 11.91 | 16.14 | mheidari-all | 198.98.53.130 |
| 71.37 | hysteria2 | 351.4 | 687.9 | 19.64 | 0.0 | 10.0 | 11.25 | 17.08 | Au1rxx-base64 | 62.210.124.146 |
| 70.72 | shadowsocks | 367.0 | 973.5 | 19.28 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 172.234.202.34 |
| 70.17 | shadowsocks | 310.1 | 572.4 | 20.6 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 173.244.56.9 |
| 69.49 | shadowsocks | 309.0 | 538.0 | 20.62 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 108.181.118.10 |
| 69.33 | shadowsocks | 341.7 | 709.3 | 19.87 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 173.244.56.6 |
| 68.64 | shadowsocks | 359.9 | 648.0 | 19.45 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 149.22.95.183 |
| 68.6 | vless | 289.7 | 740.4 | 21.07 | 0.0 | 10.0 | 5.6 | 16.14 | mheidari-all | 104.19.87.194 |
| 68.32 | shadowsocks | 242.9 | 640.3 | 22.15 | 0.0 | 10.0 | 11.91 | 17.08 | Au1rxx-base64 | 147.90.234.133 |
| 68.03 | shadowsocks | 254.4 | 662.6 | 21.89 | 0.0 | 9.93 | 11.91 | 17.08 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.827 | 0.749 | 350 | 5600 | prefer |
| Au1rxx-base64 | 0.808 | 0.816 | 49 | 93 | prefer |
| mheidari-all | 0.693 | 0.614 | 259 | 15713 | observe |
| DeltaKronecker-all | 0.49 | 0.408 | 98 | 7352 | observe |
| nscl5-all | 0.356 | 1.0 | 2 | 1113 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| ermaozi | 0.256 | 1.0 | 1 | 28 | observe |
| Epodonios-all | 0.255 | None | 0 | 6537 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6510 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4134 | observe |
| barry-far-vless | 0.255 | None | 0 | 4706 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 146 |
| geo | TimeoutError | - | 63 |
| speed | TimeoutError | - | 30 |
| geo | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 8 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| 204 | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 174 | 300 | - |
| global | False | 184 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

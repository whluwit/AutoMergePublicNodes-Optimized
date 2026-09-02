# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-02 02:37:45 |
| 运行耗时 | 322.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82084 |
| 去重后节点 | 23584 |
| TCP 可达 | 3000 |
| 真实可用 | 617 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23584 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 38.8 |
| probe | 81.6 |
| real_test | 167.8 |
| generate | 28.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51229 |
| vmess | 11361 |
| shadowsocks | 9900 |
| trojan | 7685 |
| hysteria2 | 1543 |
| http | 142 |
| shadowsocksr | 125 |
| socks | 81 |
| tuic | 11 |
| hysteria | 7 |

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
| 85.19 | vless | 206.8 | 505.8 | 22.99 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 172.233.139.46 |
| 85.16 | vless | 208.0 | 509.2 | 22.96 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 172.239.67.231 |
| 85.15 | vless | 208.8 | 545.4 | 22.95 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 172.239.67.156 |
| 84.97 | vless | 216.4 | 507.1 | 22.77 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 192.155.87.188 |
| 84.86 | vless | 221.1 | 521.9 | 22.66 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 74.207.245.124 |
| 84.81 | vless | 223.3 | 514.3 | 22.61 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 45.79.103.108 |
| 84.7 | vless | 228.0 | 538.2 | 22.5 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 45.33.62.166 |
| 84.7 | vless | 228.2 | 502.9 | 22.5 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 172.236.252.35 |
| 84.61 | vless | 231.8 | 542.5 | 22.41 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 45.33.107.60 |
| 84.61 | vless | 232.0 | 543.9 | 22.41 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 50.116.9.184 |
| 84.49 | vless | 237.2 | 624.4 | 22.29 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 108.186.202.51 |
| 84.13 | hysteria2 | 235.2 | 547.2 | 22.33 | 0.0 | 10.0 | 13.24 | 19.56 | Au1rxx-base64 | 66.94.121.46 |
| 83.06 | vless | 204.0 | 506.8 | 23.05 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 172.233.156.118 |
| 82.98 | vless | 230.6 | 555.7 | 22.44 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 45.33.107.237 |
| 82.81 | vless | 236.0 | 536.0 | 22.31 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 31.58.50.200 |
| 82.57 | http | 198.1 | 511.2 | 23.19 | 0.0 | 10.0 | 13.8 | 18.58 | zhangkai | 138.199.35.198 |
| 82.42 | http | 204.7 | 504.2 | 23.04 | 0.0 | 10.0 | 13.8 | 18.58 | zhangkai | 138.199.35.216 |
| 81.46 | shadowsocks | 230.2 | 540.2 | 22.45 | 0.0 | 10.0 | 13.45 | 19.56 | Au1rxx-base64 | 173.244.56.9 |
| 81.36 | shadowsocks | 234.3 | 553.0 | 22.35 | 0.0 | 10.0 | 13.45 | 19.56 | Au1rxx-base64 | 173.244.56.6 |
| 81.19 | vless | 236.0 | 553.1 | 22.31 | 0.0 | 10.0 | 12.64 | 19.56 | Au1rxx-base64 | 173.255.242.56 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | 0.916 | 415 | 1750 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| mheidari-all | 0.616 | 0.537 | 136 | 15712 | observe |
| Surfboard-tg-mixed | 0.556 | 0.667 | 12 | 6990 | observe |
| DeltaKronecker-all | 0.348 | 0.267 | 495 | 7294 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4708 | observe |
| Epodonios-all | 0.255 | None | 0 | 7407 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7632 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5850 | observe |
| barry-far-vless | 0.255 | None | 0 | 6027 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4159 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1750 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 218 |
| geo | ClientOSError | - | 76 |
| speed | ClientOSError | - | 63 |
| speed | TimeoutError | - | 55 |
| cn-block | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42554: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

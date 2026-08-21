# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 18:35:39 |
| 运行耗时 | 388.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 93267 |
| 去重后节点 | 23290 |
| TCP 可达 | 3000 |
| 真实可用 | 1127 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23290 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 19.1 |
| geo | 1.2 |
| tcp | 38.3 |
| probe | 67.2 |
| real_test | 225.3 |
| generate | 37.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51501 |
| trojan | 18654 |
| shadowsocks | 10623 |
| vmess | 10324 |
| hysteria2 | 1606 |
| shadowsocksr | 204 |
| http | 167 |
| socks | 128 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 84.93 | trojan | 191.3 | 500.4 | 23.35 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 128.14.181.220 |
| 84.89 | http | 202.9 | 503.6 | 23.08 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 84.65 | http | 213.5 | 540.7 | 22.84 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 84.55 | trojan | 226.8 | 513.8 | 22.53 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 44.247.89.62 |
| 84.53 | trojan | 230.4 | 527.2 | 22.45 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 34.222.243.142 |
| 84.46 | trojan | 233.2 | 535.8 | 22.38 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 44.255.190.116 |
| 84.29 | trojan | 240.6 | 538.5 | 22.21 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 35.91.98.35 |
| 84.28 | trojan | 241.1 | 552.8 | 22.2 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 54.245.126.186 |
| 84.24 | trojan | 242.8 | 564.5 | 22.16 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 34.223.2.163 |
| 84.13 | trojan | 230.7 | 522.6 | 22.44 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 35.91.138.234 |
| 84.06 | trojan | 233.4 | 533.0 | 22.37 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 44.243.85.47 |
| 83.54 | trojan | 273.0 | 646.8 | 21.46 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 54.244.169.225 |
| 83.5 | trojan | 274.6 | 649.2 | 21.42 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 44.251.158.80 |
| 83.5 | trojan | 274.8 | 655.0 | 21.42 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 35.88.210.26 |
| 83.42 | trojan | 277.9 | 666.8 | 21.34 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 34.220.224.252 |
| 83.41 | trojan | 278.6 | 667.6 | 21.33 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 34.210.213.17 |
| 83.19 | trojan | 283.7 | 688.4 | 21.21 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 100.22.163.167 |
| 82.98 | trojan | 216.7 | 482.6 | 22.76 | 0.0 | 10.0 | 14.58 | 18.3 | Surfboard-tg-mixed | 35.88.120.18 |
| 82.93 | trojan | 299.4 | 731.8 | 20.85 | 0.0 | 10.0 | 14.58 | 20.0 | Au1rxx-base64 | 35.90.27.143 |
| 82.83 | trojan | 226.2 | 511.4 | 22.54 | 0.0 | 10.0 | 14.58 | 18.3 | Surfboard-tg-mixed | 35.92.245.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.967 | 673 | 1933 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| mheidari-all | 0.98 | 0.904 | 219 | 21956 | prefer |
| Surfboard-tg-mixed | 0.862 | 0.784 | 204 | 6453 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 177 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5148 | observe |
| Epodonios-all | 0.255 | None | 0 | 7154 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7163 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5214 | observe |
| barry-far-vless | 0.255 | None | 0 | 5535 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4091 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| geo | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 16 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyError | - | 9 |
| geo | ClientOSError | - | 7 |
| speed | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32671: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 03:02:55 |
| 运行耗时 | 757.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82231 |
| 去重后节点 | 23232 |
| TCP 可达 | 3000 |
| 真实可用 | 611 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23232 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 39.4 |
| probe | 273.2 |
| real_test | 362.4 |
| generate | 73.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50142 |
| vmess | 11861 |
| shadowsocks | 9906 |
| trojan | 8248 |
| hysteria2 | 1225 |
| http | 649 |
| shadowsocksr | 123 |
| socks | 64 |
| hysteria | 8 |
| anytls | 3 |
| tuic | 2 |

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
| 82.86 | hysteria2 | 228.2 | 569.7 | 22.5 | 0.0 | 10.0 | 12.86 | 18.5 | Au1rxx-base64 | 66.94.121.46 |
| 80.43 | shadowsocks | 244.0 | 583.9 | 22.13 | 0.0 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 149.22.95.183 |
| 80.24 | vless | 245.7 | 643.2 | 22.09 | 0.0 | 10.0 | 9.65 | 18.5 | Au1rxx-base64 | 172.235.43.210 |
| 79.82 | trojan | 180.8 | 473.3 | 23.59 | 0.0 | 10.0 | 10.23 | 18.5 | Au1rxx-base64 | 100.42.228.109 |
| 78.61 | vless | 316.0 | 815.9 | 20.46 | 0.0 | 10.0 | 9.65 | 18.5 | Au1rxx-base64 | 15.204.97.216 |
| 76.86 | http | 200.0 | 492.9 | 23.15 | 0.0 | 10.0 | 10.15 | 16.56 | ermaozi | 138.199.35.217 |
| 76.77 | vless | 179.7 | 479.0 | 23.62 | 0.0 | 10.0 | 9.65 | 18.5 | Au1rxx-base64 | 31.58.50.200 |
| 76.75 | http | 204.8 | 515.4 | 23.04 | 0.0 | 10.0 | 10.15 | 16.56 | ermaozi | 138.199.35.219 |
| 76.74 | http | 205.3 | 504.0 | 23.03 | 0.0 | 10.0 | 10.15 | 16.56 | ermaozi | 138.199.35.206 |
| 76.7 | vless | 182.6 | 464.7 | 23.55 | 0.0 | 10.0 | 9.65 | 18.5 | Au1rxx-base64 | 154.21.89.50 |
| 76.7 | http | 206.8 | 496.5 | 22.99 | 0.0 | 10.0 | 10.15 | 16.56 | ermaozi | 138.199.35.198 |
| 76.66 | http | 208.4 | 515.1 | 22.95 | 0.0 | 10.0 | 10.15 | 16.56 | ermaozi | 138.199.35.212 |
| 76.65 | vless | 217.1 | 487.6 | 22.75 | 0.0 | 10.0 | 9.65 | 18.5 | Au1rxx-base64 | 108.162.198.178 |
| 76.62 | http | 210.1 | 520.1 | 22.91 | 0.0 | 10.0 | 10.15 | 16.56 | ermaozi | 138.199.35.200 |
| 76.51 | vless | 223.2 | 518.5 | 22.61 | 0.0 | 10.0 | 9.65 | 18.5 | Au1rxx-base64 | 172.64.32.103 |
| 75.78 | shadowsocks | 293.0 | 640.6 | 21.0 | 0.0 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 156.146.38.169 |
| 75.68 | hysteria2 | 358.5 | 735.8 | 19.48 | 0.0 | 10.0 | 12.86 | 18.5 | Au1rxx-base64 | 159.223.157.129 |
| 75.66 | shadowsocks | 300.0 | 668.8 | 20.83 | 0.0 | 10.0 | 13.8 | 18.5 | Au1rxx-base64 | 156.146.38.170 |
| 75.65 | vless | 201.1 | 498.9 | 23.12 | 0.0 | 10.0 | 9.65 | 18.5 | Au1rxx-base64 | 162.159.48.32 |
| 75.41 | shadowsocks | 184.5 | 486.4 | 23.51 | 0.0 | 10.0 | 13.8 | 15.1 | Surfboard-tg-mixed | 216.105.168.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | 0.874 | 326 | 1774 | prefer |
| Surfboard-tg-mixed | 0.769 | 0.691 | 262 | 7266 | prefer |
| ermaozi | 0.764 | 0.76 | 50 | 358 | prefer |
| mheidari-all | 0.514 | 0.432 | 111 | 13937 | observe |
| roosterkid-openproxylist-v2ray | 0.512 | 0.8 | 10 | 150 | observe |
| DeltaKronecker-all | 0.475 | 0.393 | 112 | 6040 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| ermaozi-get_subscribe | 0.333 | 0.417 | 12 | 387 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5822 | observe |
| barry-far-vless | 0.255 | None | 0 | 6112 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1775 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-ScrapeCategorize-Vless | 0.216 | 0.167 | 6 | 5076 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 99 |
| speed | TimeoutError | - | 54 |
| geo | ClientOSError | - | 34 |
| 204 | ProxyError | - | 24 |
| speed | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

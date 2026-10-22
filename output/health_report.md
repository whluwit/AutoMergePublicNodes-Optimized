# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 16:39:55 |
| 运行耗时 | 581.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96308 |
| 去重后节点 | 26641 |
| TCP 可达 | 3000 |
| 真实可用 | 314 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26641 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.6 |
| tcp | 45.3 |
| probe | 244.8 |
| real_test | 199.7 |
| generate | 82.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56956 |
| vmess | 17183 |
| shadowsocks | 12424 |
| trojan | 7900 |
| hysteria2 | 1340 |
| http | 239 |
| shadowsocksr | 166 |
| socks | 55 |
| anytls | 22 |
| hysteria | 17 |
| tuic | 6 |

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
| 78.87 | vless | 190.9 | 484.4 | 23.36 | 0.0 | 9.01 | 10.32 | 16.18 | Au1rxx-base64 | 45.63.53.81 |
| 78.68 | vless | 241.7 | 618.1 | 22.18 | 0.0 | 10.0 | 10.32 | 16.18 | Au1rxx-base64 | 144.202.126.147 |
| 78.65 | vless | 200.3 | 503.3 | 23.14 | 0.0 | 9.01 | 10.32 | 16.18 | Au1rxx-base64 | 45.32.69.110 |
| 77.72 | vless | 200.1 | 492.8 | 23.15 | 0.0 | 9.07 | 10.32 | 16.18 | Au1rxx-base64 | 45.76.172.197 |
| 76.74 | vless | 196.2 | 490.8 | 23.24 | 0.0 | 9.0 | 10.32 | 16.18 | Au1rxx-base64 | 104.36.69.180 |
| 76.64 | vless | 203.6 | 523.0 | 23.06 | 0.0 | 9.08 | 10.32 | 16.18 | Au1rxx-base64 | 172.236.227.60 |
| 74.62 | shadowsocks | 259.9 | 622.6 | 21.76 | 0.0 | 10.0 | 11.97 | 15.54 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.5 | hysteria2 | 330.4 | 670.1 | 20.13 | 0.0 | 9.01 | 13.33 | 16.18 | Au1rxx-base64 | 129.213.91.185 |
| 74.41 | shadowsocks | 256.0 | 689.2 | 21.85 | 0.0 | 8.91 | 11.97 | 16.18 | Au1rxx-base64 | 95.215.201.18 |
| 74.3 | shadowsocks | 262.1 | 630.9 | 21.71 | 0.0 | 8.94 | 11.97 | 16.18 | Au1rxx-base64 | 156.146.38.170 |
| 73.82 | shadowsocks | 270.0 | 653.3 | 21.53 | 0.0 | 8.98 | 11.97 | 16.18 | Au1rxx-base64 | 156.146.38.167 |
| 72.44 | vless | 325.9 | 698.1 | 20.23 | 0.0 | 8.97 | 10.32 | 16.18 | Au1rxx-base64 | 44.248.233.99 |
| 72.38 | vless | 427.4 | 583.6 | 17.89 | 0.0 | 9.08 | 10.32 | 16.18 | Au1rxx-base64 | 154.12.38.159 |
| 72.36 | shadowsocks | 364.0 | 580.8 | 19.35 | 0.0 | 10.0 | 11.97 | 15.54 | Surfboard-tg-mixed | 103.11.76.248 |
| 72.01 | vless | 325.5 | 704.7 | 20.24 | 0.0 | 8.59 | 10.32 | 16.18 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 71.91 | vless | 274.9 | 455.0 | 21.41 | 0.0 | 9.0 | 10.32 | 16.18 | Au1rxx-base64 | 176.122.189.94 |
| 71.58 | shadowsocks | 279.6 | 282.0 | 21.31 | 4.43 | 8.9 | 11.97 | 16.18 | Au1rxx-base64 | 149.22.87.240 |
| 71.29 | vless | 286.2 | 738.0 | 21.15 | 0.0 | 10.0 | 10.32 | 16.18 | Au1rxx-base64 | 216.167.126.97 |
| 70.89 | hysteria2 | 433.0 | 511.2 | 17.75 | 0.0 | 8.95 | 13.33 | 16.18 | Au1rxx-base64 | 66.94.121.46 |
| 69.3 | shadowsocks | 380.6 | 933.6 | 18.97 | 0.0 | 8.95 | 11.97 | 16.18 | Au1rxx-base64 | 185.215.132.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | 0.875 | 40 | 24062 | prefer |
| Au1rxx-base64 | 0.842 | 0.783 | 249 | 1529 | prefer |
| Surfboard-tg-mixed | 0.743 | 0.667 | 102 | 7043 | prefer |
| ermaozi | 0.321 | 0.289 | 45 | 573 | observe |
| DeltaKronecker-all | 0.3 | 0.4 | 5 | 3641 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7538 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10202 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5382 | observe |
| barry-far-vless | 0.255 | None | 0 | 5601 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 26 |
| 204 | ProxyError | - | 25 |
| cn-block | TimeoutError | - | 18 |
| speed | TimeoutError | - | 16 |
| speed | ClientOSError | - | 15 |
| 204 | ProxyConnectionError | - | 12 |
| geo | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 254 | 300 | - |
| global | False | 270 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

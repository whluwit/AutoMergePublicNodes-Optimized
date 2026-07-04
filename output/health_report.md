# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-04 02:33:33 |
| 运行耗时 | 240.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 78122 |
| 去重后节点 | 23056 |
| TCP 可达 | 3000 |
| 真实可用 | 424 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23056 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 30.6 |
| probe | 54.5 |
| real_test | 127.8 |
| generate | 21.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45342 |
| trojan | 12495 |
| vmess | 10493 |
| shadowsocks | 9139 |
| hysteria2 | 282 |
| shadowsocksr | 151 |
| http | 135 |
| socks | 77 |
| hysteria | 6 |
| tuic | 1 |
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
| 77.05 | shadowsocks | 215.5 | 510.0 | 22.79 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 173.244.56.9 |
| 76.09 | shadowsocks | 256.8 | 654.7 | 21.83 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 173.244.56.6 |
| 76.01 | shadowsocks | 238.8 | 607.6 | 22.25 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 108.181.118.10 |
| 75.97 | shadowsocks | 240.4 | 603.0 | 22.21 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 108.181.0.177 |
| 73.45 | shadowsocks | 241.6 | 580.2 | 22.19 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 149.22.95.183 |
| 73.25 | shadowsocks | 274.4 | 271.3 | 21.43 | 4.83 | 9.9 | 11.52 | 16.74 | Au1rxx-base64 | 149.22.87.204 |
| 72.64 | vless | 323.9 | 847.4 | 20.28 | 0.0 | 10.0 | 5.62 | 16.74 | Au1rxx-base64 | 15.204.97.214 |
| 72.31 | shadowsocks | 291.1 | 653.4 | 21.04 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 156.146.38.168 |
| 72.28 | shadowsocks | 228.1 | 649.2 | 22.5 | 0.0 | 10.0 | 11.52 | 12.36 | DeltaKronecker-all | 107.172.219.230 |
| 72.28 | shadowsocks | 287.5 | 637.8 | 21.12 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 156.146.38.170 |
| 72.18 | shadowsocks | 301.8 | 633.7 | 20.79 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 156.146.38.167 |
| 71.48 | vless | 184.8 | 484.9 | 23.5 | 0.0 | 10.0 | 5.62 | 12.36 | DeltaKronecker-all | 112.121.184.10 |
| 71.41 | shadowsocks | 290.2 | 644.6 | 21.06 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 156.146.38.169 |
| 70.66 | shadowsocks | 275.5 | 759.1 | 21.4 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 216.105.168.18 |
| 69.86 | shadowsocks | 298.9 | 346.1 | 20.86 | 2.02 | 9.9 | 11.52 | 16.74 | Au1rxx-base64 | 149.22.87.240 |
| 69.38 | shadowsocks | 308.9 | 704.9 | 20.63 | 0.0 | 10.0 | 11.52 | 12.36 | DeltaKronecker-all | 172.245.235.84 |
| 68.23 | shadowsocks | 357.6 | 718.0 | 19.5 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 37.19.198.236 |
| 68.07 | shadowsocks | 365.8 | 736.2 | 19.31 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 37.19.198.243 |
| 67.55 | shadowsocks | 300.0 | 354.9 | 20.83 | 1.69 | 9.9 | 11.52 | 16.74 | Au1rxx-base64 | 149.22.87.241 |
| 66.92 | shadowsocks | 405.8 | 860.0 | 18.38 | 0.0 | 10.0 | 11.52 | 16.74 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.971 | 0.897 | 126 | 6191 | prefer |
| Au1rxx-base64 | 0.654 | 0.658 | 38 | 103 | observe |
| DeltaKronecker-all | 0.491 | 0.411 | 587 | 6997 | observe |
| nscl5-all | 0.359 | 1.0 | 2 | 1189 | observe |
| tg-ConfigV2rayNG | 0.319 | 1.0 | 2 | 200 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4368 | observe |
| Epodonios-all | 0.255 | None | 0 | 7108 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6864 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4665 | observe |
| barry-far-vless | 0.255 | None | 0 | 5289 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5333 | observe |
| mheidari-all | 0.247 | 0.143 | 28 | 16050 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 210 |
| speed | ClientOSError | - | 110 |
| geo | ClientOSError | - | 38 |
| speed | TimeoutError | - | 25 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 209 | 300 | - |
| global | False | 217 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

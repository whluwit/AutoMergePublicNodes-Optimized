# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-02 19:22:03 |
| 运行耗时 | 240.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 77440 |
| 去重后节点 | 23177 |
| TCP 可达 | 3000 |
| 真实可用 | 352 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23177 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 30.0 |
| probe | 58.9 |
| real_test | 105.9 |
| generate | 39.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44653 |
| trojan | 12735 |
| vmess | 10348 |
| shadowsocks | 9014 |
| hysteria2 | 245 |
| socks | 154 |
| shadowsocksr | 149 |
| http | 135 |
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
| 76.95 | shadowsocks | 213.9 | 507.3 | 22.83 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 173.244.56.6 |
| 76.82 | vless | 304.9 | 794.6 | 20.72 | 0.0 | 10.0 | 9.84 | 16.26 | Au1rxx-base64 | 15.204.97.214 |
| 76.45 | shadowsocks | 235.4 | 525.2 | 22.33 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 173.244.56.9 |
| 76.39 | shadowsocks | 216.2 | 542.5 | 22.77 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 108.181.118.10 |
| 76.21 | shadowsocks | 245.7 | 585.3 | 22.09 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 149.22.95.183 |
| 76.2 | shadowsocks | 224.7 | 554.5 | 22.58 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 108.181.0.177 |
| 75.03 | vless | 185.4 | 482.9 | 23.49 | 0.0 | 10.0 | 9.84 | 13.7 | mheidari-all | 112.121.184.10 |
| 74.52 | vless | 171.9 | 477.4 | 23.8 | 0.0 | 10.0 | 9.84 | 15.88 | Surfboard-tg-mixed | 64.23.143.23 |
| 74.23 | shadowsocks | 169.5 | 465.4 | 23.85 | 0.0 | 10.0 | 11.86 | 12.62 | DeltaKronecker-all | 107.172.219.230 |
| 72.31 | shadowsocks | 287.0 | 647.7 | 21.13 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 156.146.38.167 |
| 71.23 | shadowsocks | 324.0 | 750.0 | 20.28 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 156.146.38.168 |
| 71.19 | socks | 340.4 | 858.6 | 19.9 | 0.0 | 10.0 | 11.91 | 15.88 | Surfboard-tg-mixed | 104.152.50.252 |
| 70.55 | shadowsocks | 331.7 | 777.2 | 20.1 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 156.146.38.169 |
| 70.03 | shadowsocks | 275.1 | 286.2 | 21.41 | 4.27 | 9.93 | 11.86 | 13.7 | mheidari-all | 149.22.87.240 |
| 69.81 | shadowsocks | 276.6 | 291.2 | 21.38 | 4.08 | 9.95 | 11.86 | 13.7 | mheidari-all | 149.22.87.241 |
| 69.7 | shadowsocks | 293.8 | 665.6 | 20.98 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 156.146.38.170 |
| 68.45 | vless | 237.3 | 625.0 | 22.29 | 0.0 | 10.0 | 9.84 | 13.7 | mheidari-all | 107.173.237.146 |
| 68.41 | vless | 373.9 | 727.0 | 19.12 | 0.0 | 10.0 | 9.84 | 15.88 | Surfboard-tg-mixed | 104.25.161.29 |
| 67.98 | shadowsocks | 416.1 | 989.1 | 18.15 | 0.0 | 10.0 | 11.86 | 16.26 | Au1rxx-base64 | 172.234.202.34 |
| 67.55 | shadowsocks | 374.2 | 756.2 | 19.12 | 0.0 | 9.97 | 11.86 | 16.26 | Au1rxx-base64 | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.836 | 0.857 | 28 | 58 | prefer |
| Surfboard-tg-mixed | 0.668 | 0.588 | 294 | 6022 | observe |
| DeltaKronecker-all | 0.594 | 0.514 | 70 | 7467 | observe |
| mheidari-all | 0.565 | 0.485 | 165 | 16059 | observe |
| nscl5-all | 0.358 | 1.0 | 2 | 1162 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4254 | observe |
| Epodonios-all | 0.255 | None | 0 | 6895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6658 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4492 | observe |
| barry-far-vless | 0.255 | None | 0 | 5048 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5372 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 145 |
| 204 | TimeoutError | - | 31 |
| geo | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 6 |
| speed | TimeoutError | - | 5 |
| 204 | ProxyError | - | 4 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

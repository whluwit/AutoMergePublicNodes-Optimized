# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 12:42:09 |
| 运行耗时 | 261.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78304 |
| 去重后节点 | 22373 |
| TCP 可达 | 3000 |
| 真实可用 | 568 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22373 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 36.1 |
| probe | 56.3 |
| real_test | 118.6 |
| generate | 42.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48486 |
| shadowsocks | 10798 |
| vmess | 10449 |
| trojan | 6704 |
| hysteria2 | 1500 |
| http | 164 |
| shadowsocksr | 125 |
| socks | 68 |
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
| 80.06 | vless | 285.9 | 789.4 | 21.16 | 0.0 | 10.0 | 10.32 | 18.58 | Au1rxx-base64 | 15.204.97.209 |
| 79.94 | trojan | 272.4 | 685.7 | 21.47 | 0.0 | 10.0 | 12.39 | 18.58 | Au1rxx-base64 | 35.91.251.124 |
| 79.76 | vless | 299.0 | 824.2 | 20.86 | 0.0 | 10.0 | 10.32 | 18.58 | Au1rxx-base64 | 15.204.97.197 |
| 79.25 | shadowsocks | 199.0 | 542.2 | 23.17 | 0.0 | 10.0 | 13.98 | 16.1 | Surfboard-tg-mixed | 94.72.127.55 |
| 78.82 | shadowsocks | 217.6 | 556.1 | 22.74 | 0.0 | 10.0 | 13.98 | 16.1 | Surfboard-tg-mixed | 149.22.95.183 |
| 78.65 | shadowsocks | 254.4 | 261.7 | 21.89 | 5.19 | 10.0 | 13.98 | 18.58 | Au1rxx-base64 | 149.22.87.240 |
| 78.1 | vless | 222.4 | 231.1 | 22.63 | 6.34 | 10.0 | 10.32 | 16.1 | Surfboard-tg-mixed | 31.76.91.72 |
| 78.03 | vless | 257.5 | 550.8 | 21.82 | 0.0 | 10.0 | 10.32 | 18.58 | Au1rxx-base64 | 23.172.40.60 |
| 77.31 | shadowsocks | 260.1 | 510.0 | 21.76 | 0.0 | 10.0 | 13.98 | 18.58 | Au1rxx-base64 | 108.181.118.10 |
| 76.7 | vless | 255.4 | 570.9 | 21.87 | 0.0 | 10.0 | 10.32 | 18.58 | Au1rxx-base64 | 23.94.239.108 |
| 76.18 | trojan | 300.2 | 702.3 | 20.83 | 0.0 | 10.0 | 12.39 | 18.58 | Au1rxx-base64 | 14.1.28.76 |
| 75.66 | shadowsocks | 261.7 | 274.6 | 21.72 | 4.7 | 9.95 | 13.98 | 18.58 | Au1rxx-base64 | 149.22.87.241 |
| 75.58 | trojan | 289.6 | 639.2 | 21.07 | 0.0 | 10.0 | 12.39 | 18.58 | Au1rxx-base64 | 107.150.105.84 |
| 75.24 | shadowsocks | 279.0 | 338.7 | 21.32 | 2.3 | 10.0 | 13.98 | 18.58 | Au1rxx-base64 | 149.22.87.204 |
| 75.18 | shadowsocks | 190.2 | 504.2 | 23.37 | 0.0 | 10.0 | 13.98 | 12.08 | DeltaKronecker-all | 94.72.127.58 |
| 74.47 | shadowsocks | 317.3 | 674.5 | 20.43 | 0.0 | 10.0 | 13.98 | 18.58 | Au1rxx-base64 | 156.146.38.169 |
| 74.09 | vless | 317.3 | 456.8 | 20.43 | 0.0 | 10.0 | 10.32 | 18.58 | Au1rxx-base64 | 69.63.193.78 |
| 74.06 | shadowsocks | 316.7 | 672.5 | 20.45 | 0.0 | 10.0 | 13.98 | 16.1 | Surfboard-tg-mixed | 108.181.0.177 |
| 74.05 | shadowsocks | 328.3 | 699.5 | 20.18 | 0.0 | 10.0 | 13.98 | 18.58 | Au1rxx-base64 | 156.146.38.168 |
| 73.49 | trojan | 270.2 | 574.6 | 21.52 | 0.0 | 10.0 | 12.39 | 18.58 | Au1rxx-base64 | us01.duotg.top |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.96 | 25 | 14402 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.905 | 0.844 | 397 | 1581 | prefer |
| Surfboard-tg-mixed | 0.894 | 0.818 | 159 | 6506 | prefer |
| DeltaKronecker-all | 0.804 | 0.73 | 74 | 6340 | prefer |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 167 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 7010 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7084 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5298 | observe |
| barry-far-vless | 0.255 | None | 0 | 5577 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 36 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 14 |
| speed | TimeoutError | - | 13 |
| speed | ClientOSError | - | 10 |
| geo | ClientOSError | - | 9 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

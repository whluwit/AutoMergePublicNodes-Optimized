# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 22:54:53 |
| 运行耗时 | 504.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98637 |
| 去重后节点 | 27606 |
| TCP 可达 | 3000 |
| 真实可用 | 388 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27606 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.3 |
| tcp | 46.7 |
| probe | 200.7 |
| real_test | 181.8 |
| generate | 69.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58723 |
| vmess | 15765 |
| shadowsocks | 11976 |
| trojan | 10039 |
| hysteria2 | 1414 |
| http | 410 |
| shadowsocksr | 162 |
| socks | 88 |
| anytls | 34 |
| hysteria | 16 |
| tuic | 10 |

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
| 82.27 | hysteria2 | 273.6 | 713.2 | 21.44 | 0.0 | 10.0 | 13.75 | 18.58 | Au1rxx-base64 | 129.213.91.185 |
| 79.69 | shadowsocks | 248.5 | 620.0 | 22.03 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 156.146.38.168 |
| 79.68 | shadowsocks | 248.9 | 639.6 | 22.02 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 156.146.38.167 |
| 79.6 | shadowsocks | 252.0 | 630.2 | 21.94 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 156.146.38.170 |
| 79.43 | hysteria2 | 299.7 | 286.7 | 20.84 | 4.25 | 9.63 | 13.75 | 18.58 | Au1rxx-base64 | 158.101.148.79 |
| 79.12 | shadowsocks | 272.9 | 693.5 | 21.46 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 156.146.38.169 |
| 78.26 | hysteria2 | 291.0 | 295.8 | 21.04 | 3.91 | 8.99 | 13.75 | 18.58 | Au1rxx-base64 | open.2ml.bid |
| 77.63 | shadowsocks | 318.6 | 784.5 | 20.4 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 37.19.198.243 |
| 77.36 | shadowsocks | 298.4 | 745.0 | 20.87 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 37.19.198.244 |
| 77.36 | shadowsocks | 303.2 | 753.2 | 20.76 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 37.19.198.160 |
| 77.22 | shadowsocks | 354.8 | 885.9 | 19.56 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 37.19.198.236 |
| 76.75 | vless | 275.1 | 562.7 | 21.41 | 0.0 | 10.0 | 10.96 | 18.58 | Au1rxx-base64 | 47.251.108.158 |
| 76.47 | vless | 352.3 | 771.8 | 19.62 | 0.0 | 10.0 | 10.96 | 18.58 | Au1rxx-base64 | 169.40.42.212 |
| 76.4 | vless | 277.2 | 654.7 | 21.36 | 0.0 | 10.0 | 10.96 | 18.58 | Au1rxx-base64 | uspanel.unixzone.us |
| 75.18 | shadowsocks | 275.2 | 583.6 | 21.41 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 5.78.51.123 |
| 75.08 | shadowsocks | 319.3 | 731.7 | 20.39 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 140.82.63.79 |
| 75.06 | shadowsocks | 210.8 | 564.7 | 22.9 | 0.0 | 10.0 | 13.08 | 18.58 | Au1rxx-base64 | 103.214.111.125 |
| 74.88 | vless | 416.8 | 917.2 | 18.13 | 0.0 | 10.0 | 10.96 | 18.58 | Au1rxx-base64 | 169.40.42.52 |
| 74.64 | vless | 344.4 | 757.2 | 19.81 | 0.0 | 10.0 | 10.96 | 18.58 | Au1rxx-base64 | 66.70.179.198 |
| 74.61 | vless | 415.6 | 1036.3 | 18.16 | 0.0 | 10.0 | 10.96 | 18.58 | Au1rxx-base64 | 185.95.231.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | 0.9 | 311 | 1827 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| mheidari-all | 0.838 | 0.763 | 97 | 23588 | prefer |
| Surfboard-tg-mixed | 0.507 | 0.75 | 8 | 7187 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 175 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7650 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9660 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5683 | observe |
| barry-far-vless | 0.255 | None | 0 | 5923 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 12 |
| geo | ClientOSError | - | 9 |
| speed | ClientOSError | - | 8 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyError | - | 4 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

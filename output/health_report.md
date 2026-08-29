# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-29 20:23:30 |
| 运行耗时 | 260.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 79278 |
| 去重后节点 | 21317 |
| TCP 可达 | 3000 |
| 真实可用 | 568 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21317 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.4 |
| tcp | 35.2 |
| probe | 57.2 |
| real_test | 120.9 |
| generate | 39.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49815 |
| vmess | 10918 |
| shadowsocks | 10559 |
| trojan | 6062 |
| hysteria2 | 1545 |
| http | 173 |
| shadowsocksr | 132 |
| socks | 57 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 2 |

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
| 81.85 | shadowsocks | 233.6 | 558.4 | 22.37 | 0.0 | 10.0 | 13.48 | 20.0 | mheidari-all | 156.146.38.169 |
| 81.44 | vless | 276.4 | 656.7 | 21.38 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 64.23.229.123 |
| 80.92 | shadowsocks | 231.6 | 591.1 | 22.42 | 0.0 | 10.0 | 13.48 | 19.02 | Au1rxx-base64 | 156.146.38.170 |
| 79.72 | shadowsocks | 239.9 | 590.2 | 22.22 | 0.0 | 10.0 | 13.48 | 19.02 | Au1rxx-base64 | 23.150.248.20 |
| 78.93 | vless | 350.2 | 852.1 | 19.67 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 15.204.97.209 |
| 78.88 | shadowsocks | 275.6 | 723.5 | 21.4 | 0.0 | 10.0 | 13.48 | 20.0 | mheidari-all | 156.146.38.168 |
| 78.8 | vless | 334.6 | 797.8 | 20.03 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 15.204.97.216 |
| 78.78 | vless | 343.8 | 831.2 | 19.82 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 15.204.97.197 |
| 78.59 | vless | 346.2 | 836.9 | 19.76 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 15.204.97.195 |
| 78.04 | shadowsocks | 255.7 | 595.0 | 21.86 | 0.0 | 10.0 | 13.48 | 19.02 | Au1rxx-base64 | 84.32.131.61 |
| 77.97 | vless | 302.8 | 664.8 | 20.77 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 195.211.99.49 |
| 77.89 | vless | 277.2 | 554.5 | 21.36 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 192.220.9.89 |
| 77.88 | shadowsocks | 228.0 | 579.3 | 22.5 | 0.0 | 10.0 | 13.48 | 15.9 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.69 | vless | 317.6 | 666.8 | 20.43 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 198.251.78.29 |
| 77.61 | vless | 304.7 | 669.7 | 20.73 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 195.211.99.45 |
| 77.49 | vless | 344.3 | 829.8 | 19.81 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 15.204.97.206 |
| 77.1 | vless | 281.2 | 603.6 | 21.27 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 172.233.156.42 |
| 76.88 | trojan | 252.5 | 530.0 | 21.93 | 0.0 | 10.0 | 12.0 | 19.02 | Au1rxx-base64 | 14.1.28.76 |
| 76.65 | vless | 272.2 | 561.2 | 21.48 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 172.235.38.85 |
| 76.63 | vless | 388.4 | 958.2 | 18.79 | 0.0 | 10.0 | 11.68 | 19.02 | Au1rxx-base64 | 45.138.100.226 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | 0.915 | 353 | 1756 | prefer |
| DeltaKronecker-all | 0.937 | 0.885 | 26 | 4926 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.838 | 0.761 | 159 | 6924 | prefer |
| mheidari-all | 0.825 | 0.75 | 100 | 14908 | prefer |
| tg-oneclickvpnkeys | 0.364 | 1.0 | 3 | 155 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4635 | observe |
| Epodonios-all | 0.255 | None | 0 | 7291 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7802 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5706 | observe |
| barry-far-vless | 0.255 | None | 0 | 5901 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4012 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1756 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 21 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 9 |
| geo | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

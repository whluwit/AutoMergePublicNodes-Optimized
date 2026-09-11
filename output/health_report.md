# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 02:56:02 |
| 运行耗时 | 955.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 86971 |
| 去重后节点 | 24411 |
| TCP 可达 | 3000 |
| 真实可用 | 619 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24411 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 42.5 |
| probe | 312.3 |
| real_test | 516.4 |
| generate | 77.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52341 |
| vmess | 12928 |
| shadowsocks | 10522 |
| trojan | 8504 |
| hysteria2 | 1839 |
| http | 622 |
| shadowsocksr | 129 |
| socks | 57 |
| tuic | 13 |
| hysteria | 12 |
| anytls | 4 |

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
| 82.49 | vless | 205.8 | 521.2 | 23.01 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 172.233.139.46 |
| 82.48 | vless | 206.5 | 521.8 | 23.0 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 172.235.38.85 |
| 82.41 | vless | 209.3 | 528.7 | 22.93 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 107.173.237.146 |
| 80.97 | vless | 236.3 | 543.0 | 22.31 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 31.58.50.200 |
| 80.58 | hysteria2 | 257.0 | 566.8 | 21.83 | 0.0 | 10.0 | 13.5 | 18.68 | Au1rxx-base64 | 66.94.121.46 |
| 79.57 | shadowsocks | 268.5 | 666.0 | 21.56 | 0.0 | 10.0 | 13.33 | 18.68 | Au1rxx-base64 | 173.244.56.9 |
| 78.84 | http | 252.0 | 669.1 | 21.94 | 0.0 | 10.0 | 12.78 | 17.12 | ermaozi | 138.199.35.200 |
| 78.02 | trojan | 214.2 | 536.9 | 22.82 | 0.0 | 9.16 | 11.25 | 18.68 | Au1rxx-base64 | us01.duotg.top |
| 77.79 | http | 197.0 | 499.9 | 23.22 | 0.0 | 10.0 | 12.78 | 17.12 | ermaozi | 138.199.35.216 |
| 77.63 | vless | 213.8 | 528.0 | 22.83 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 172.236.233.59 |
| 77.45 | vless | 342.1 | 823.4 | 19.86 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 15.204.97.216 |
| 77.28 | http | 200.8 | 513.1 | 23.13 | 0.0 | 10.0 | 12.78 | 17.12 | ermaozi | 138.199.35.219 |
| 77.28 | vless | 326.7 | 738.7 | 20.22 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 79.141.172.154 |
| 76.97 | hysteria2 | 339.6 | 753.9 | 19.92 | 0.0 | 10.0 | 13.5 | 18.68 | Au1rxx-base64 | 159.223.157.129 |
| 76.88 | vless | 354.3 | 841.3 | 19.58 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 51.81.203.63 |
| 76.83 | shadowsocks | 285.8 | 641.4 | 21.16 | 0.0 | 10.0 | 13.33 | 18.68 | Au1rxx-base64 | 23.150.248.20 |
| 76.81 | shadowsocks | 192.5 | 498.3 | 23.32 | 0.0 | 10.0 | 13.33 | 15.16 | Surfboard-tg-mixed | 216.105.168.18 |
| 76.61 | trojan | 306.8 | 756.2 | 20.68 | 0.0 | 10.0 | 11.25 | 18.68 | Au1rxx-base64 | 107.150.105.84 |
| 76.12 | vless | 244.0 | 285.9 | 22.13 | 4.28 | 9.89 | 10.8 | 15.16 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.12 | vless | 315.8 | 697.2 | 20.47 | 0.0 | 10.0 | 10.8 | 18.68 | Au1rxx-base64 | 38.180.242.205 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.899 | 0.839 | 330 | 1551 | prefer |
| mheidari-all | 0.875 | 0.81 | 42 | 15718 | prefer |
| Surfboard-tg-mixed | 0.826 | 0.749 | 171 | 7329 | prefer |
| ermaozi | 0.71 | 0.7 | 50 | 431 | prefer |
| xiaoji235-airport-v2ray-all | 0.519 | 1.0 | 5 | 3508 | observe |
| DeltaKronecker-all | 0.375 | 0.295 | 455 | 5853 | observe |
| ermaozi-get_subscribe | 0.363 | 0.4 | 15 | 461 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8685 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5926 | observe |
| barry-far-vless | 0.255 | None | 0 | 6145 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1551 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 179 |
| speed | ClientOSError | - | 91 |
| geo | ClientOSError | - | 79 |
| speed | TimeoutError | - | 42 |
| 204 | ProxyError | - | 19 |
| cn-block | TimeoutError | - | 15 |
| 204 | ProxyConnectionError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

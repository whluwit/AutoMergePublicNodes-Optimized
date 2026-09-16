# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 03:19:57 |
| 运行耗时 | 1135.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85245 |
| 去重后节点 | 23243 |
| TCP 可达 | 3000 |
| 真实可用 | 651 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23243 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.5 |
| tcp | 38.6 |
| probe | 365.1 |
| real_test | 588.5 |
| generate | 135.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51965 |
| vmess | 12887 |
| shadowsocks | 9591 |
| trojan | 8316 |
| hysteria2 | 1600 |
| http | 679 |
| shadowsocksr | 123 |
| socks | 68 |
| hysteria | 9 |
| tuic | 5 |
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
| 83.0 | vless | 229.4 | 596.2 | 22.47 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 195.123.235.177 |
| 82.71 | vless | 241.8 | 683.7 | 22.18 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 47.253.226.114 |
| 82.56 | vless | 248.4 | 646.6 | 22.03 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.16 |
| 82.33 | vless | 258.2 | 639.1 | 21.8 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.104 |
| 81.69 | vless | 286.0 | 703.2 | 21.16 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.212 |
| 81.68 | vless | 286.5 | 633.9 | 21.15 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.15 |
| 81.67 | vless | 286.6 | 711.6 | 21.14 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.232 |
| 81.58 | vless | 290.8 | 656.9 | 21.05 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.74 |
| 81.08 | vless | 312.3 | 841.5 | 20.55 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.182 |
| 81.0 | vless | 282.1 | 689.5 | 21.25 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 216.152.147.28 |
| 80.99 | vless | 243.4 | 642.1 | 22.14 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.225 |
| 80.62 | vless | 332.3 | 840.2 | 20.09 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.224 |
| 80.58 | vless | 261.0 | 631.3 | 21.74 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.235 |
| 80.52 | vless | 262.2 | 625.1 | 21.71 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.229 |
| 80.51 | vless | 258.0 | 675.3 | 21.81 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.173 |
| 80.32 | vless | 286.6 | 720.2 | 21.14 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.179 |
| 80.32 | vless | 345.3 | 814.7 | 19.79 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.223 |
| 80.23 | vless | 349.1 | 971.6 | 19.7 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 185.95.231.156 |
| 80.17 | vless | 290.0 | 783.9 | 21.06 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.184 |
| 79.93 | vless | 361.8 | 862.3 | 19.4 | 0.0 | 10.0 | 11.65 | 18.88 | Au1rxx-base64 | 169.40.42.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | 0.881 | 278 | 1640 | prefer |
| ermaozi | 0.757 | 0.75 | 52 | 407 | prefer |
| Surfboard-tg-mixed | 0.685 | 0.606 | 193 | 7549 | observe |
| mheidari-all | 0.682 | 0.604 | 106 | 16114 | observe |
| ermaozi-get_subscribe | 0.467 | 0.857 | 7 | 438 | observe |
| DeltaKronecker-all | 0.447 | 0.367 | 480 | 5932 | observe |
| roosterkid-openproxylist-v2ray | 0.317 | 1.0 | 2 | 150 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 148 | observe |
| Epodonios-all | 0.255 | None | 0 | 8042 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8952 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6134 | observe |
| barry-far-vless | 0.255 | None | 0 | 6344 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 201 |
| geo | ClientOSError | - | 82 |
| speed | TimeoutError | - | 59 |
| speed | ClientOSError | - | 48 |
| cn-block | TimeoutError | - | 27 |
| 204 | ProxyError | - | 19 |
| 204 | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyConnectionError | - | 6 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 21:54:05 |
| 运行耗时 | 580.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98966 |
| 去重后节点 | 27189 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27189 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 0.9 |
| tcp | 47.1 |
| probe | 249.9 |
| real_test | 172.8 |
| generate | 103.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60742 |
| vmess | 15453 |
| shadowsocks | 11464 |
| trojan | 8911 |
| hysteria2 | 1566 |
| http | 523 |
| shadowsocksr | 174 |
| socks | 68 |
| anytls | 40 |
| hysteria | 17 |
| tuic | 8 |

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
| 84.21 | hysteria2 | 193.6 | 513.8 | 23.3 | 0.0 | 10.0 | 13.33 | 18.58 | Au1rxx-base64 | 192.255.128.123 |
| 83.26 | vless | 197.6 | 514.8 | 23.2 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 172.235.38.85 |
| 83.2 | vless | 200.3 | 527.6 | 23.14 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 172.235.43.210 |
| 83.07 | vless | 206.0 | 518.6 | 23.01 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 195.123.240.65 |
| 82.76 | vless | 219.3 | 571.7 | 22.7 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 172.233.139.46 |
| 80.82 | shadowsocks | 183.9 | 495.3 | 23.52 | 0.0 | 10.0 | 13.22 | 18.58 | Au1rxx-base64 | 74.201.177.54 |
| 79.79 | vless | 211.9 | 498.0 | 22.87 | 0.0 | 10.0 | 11.48 | 15.44 | mheidari-all | 47.251.108.158 |
| 79.63 | shadowsocks | 257.0 | 629.7 | 21.83 | 0.0 | 10.0 | 13.22 | 18.58 | Au1rxx-base64 | 156.146.38.167 |
| 79.6 | shadowsocks | 256.4 | 629.3 | 21.84 | 0.0 | 10.0 | 13.22 | 18.58 | Au1rxx-base64 | 156.146.38.169 |
| 79.53 | shadowsocks | 261.4 | 632.7 | 21.73 | 0.0 | 10.0 | 13.22 | 18.58 | Au1rxx-base64 | 156.146.38.168 |
| 79.4 | vless | 271.8 | 603.8 | 21.49 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 15.204.97.216 |
| 79.39 | shadowsocks | 245.8 | 628.5 | 22.09 | 0.0 | 10.0 | 13.22 | 18.58 | Au1rxx-base64 | 108.181.118.10 |
| 78.16 | vless | 223.9 | 521.8 | 22.6 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 172.64.32.103 |
| 77.81 | hysteria2 | 283.4 | 311.9 | 21.22 | 3.3 | 8.89 | 13.33 | 18.58 | Au1rxx-base64 | open.2ml.bid |
| 77.6 | vless | 324.7 | 738.3 | 20.26 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 79.141.172.154 |
| 77.54 | vless | 219.3 | 509.1 | 22.7 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 172.64.32.108 |
| 77.39 | vless | 256.8 | 455.3 | 21.83 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 162.159.24.131 |
| 77.37 | shadowsocks | 218.9 | 541.9 | 22.71 | 0.0 | 10.0 | 13.22 | 15.44 | mheidari-all | 173.244.56.9 |
| 76.91 | shadowsocks | 217.2 | 541.2 | 22.75 | 0.0 | 10.0 | 13.22 | 15.44 | mheidari-all | 108.181.0.177 |
| 76.87 | vless | 309.2 | 756.8 | 20.62 | 0.0 | 10.0 | 11.48 | 18.58 | Au1rxx-base64 | 23.95.222.127 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.967 | 0.899 | 69 | 23213 | prefer |
| Au1rxx-base64 | 0.961 | 0.893 | 298 | 1771 | prefer |
| ermaozi | 0.914 | 0.92 | 25 | 620 | prefer |
| Surfboard-tg-mixed | 0.793 | 0.717 | 127 | 7321 | prefer |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 4981 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7814 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9326 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5999 | observe |
| barry-far-vless | 0.255 | None | 0 | 6241 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4357 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1771 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 15 |
| speed | TimeoutError | - | 12 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。

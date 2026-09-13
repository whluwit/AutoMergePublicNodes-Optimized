# AutoNodes 每日报告

生成时间：2026-09-13 20:22:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 90439 |
| 去重后节点数 | 25490 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25490 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 78.3 |
| geo | 1.4 |
| probe | 255.6 |
| real_test | 228.6 |
| tcp | 43.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 38 | 20 | 18 | 52.6% |
| hysteria2 | 24 | 23 | 1 | 95.8% |
| shadowsocks | 162 | 148 | 14 | 91.4% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 17 | 15 | 2 | 88.2% |
| vless | 301 | 233 | 68 | 77.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 28 |
| 204:ProxyError | 20 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 12 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ProxyConnectionError | 5 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:exit-country | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6119 |
| ConnectionRefusedError | 982 |
| gaierror | 419 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | prefer | 307 | 0.912 | 1781 |
| mheidari-all | 0.868 | prefer | 50 | 0.8 | 16210 |
| Surfboard-tg-mixed | 0.758 | prefer | 116 | 0.681 | 7573 |
| DeltaKronecker-all | 0.757 | prefer | 29 | 0.69 | 5892 |
| ermaozi | 0.583 | observe | 35 | 0.571 | 382 |
| xiaoji235-airport-v2ray-all | 0.421 | observe | 6 | 0.667 | 5301 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| Epodonios-all | 0.255 | observe | 0 | None | 8029 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| ermaozi | 0.571 | 20 | 15 | 35 |
| xiaoji235-airport-v2ray-all | 0.667 | 4 | 2 | 6 |
| Surfboard-tg-mixed | 0.681 | 79 | 37 | 116 |
| DeltaKronecker-all | 0.69 | 20 | 9 | 29 |
| mheidari-all | 0.8 | 40 | 10 | 50 |
| Au1rxx-base64 | 0.912 | 280 | 27 | 307 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16210 | yes | 6.15 | 0 |
| SoliSpirit-all | 8804 | yes | 1.65 | 0 |
| Epodonios-all | 8029 | yes | 3.18 | 0 |
| Surfboard-tg-mixed | 7573 | yes | 5.24 | 0 |
| barry-far-vless | 6390 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 6175 | yes | 3.85 | 0 |
| DeltaKronecker-all | 5892 | yes | 5.19 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 2.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.04 | 0 |
| mahdibland-V2RayAggregator | 4222 | yes | 2.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| geo | 32 |
| cn-block | 21 |
| speed | 17 |

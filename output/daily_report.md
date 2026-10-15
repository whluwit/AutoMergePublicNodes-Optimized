# AutoNodes 每日报告

生成时间：2026-10-15 03:05:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 98773 |
| 去重后节点数 | 27498 |
| TCP 可达数 | 3000 |
| 真测通过数 | 377 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27498 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 75.4 |
| geo | 1.5 |
| probe | 240.5 |
| real_test | 298.8 |
| tcp | 46.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 57 | 22 | 35 | 38.6% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 158 | 150 | 8 | 94.9% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 47 | 43 | 4 | 91.5% |
| vless | 320 | 144 | 176 | 45.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 101 |
| speed:ClientOSError | 29 |
| 204:ProxyError | 27 |
| geo:ClientOSError | 25 |
| 204:ProxyConnectionError | 11 |
| speed:TimeoutError | 10 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| cn-block:TimeoutError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6463 |
| ConnectionRefusedError | 1069 |
| gaierror | 442 |
| OSError | 240 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | prefer | 344 | 0.884 | 1564 |
| DeltaKronecker-all | 0.446 | observe | 8 | 0.625 | 4803 |
| ermaozi | 0.438 | observe | 59 | 0.407 | 703 |
| mheidari-all | 0.316 | observe | 180 | 0.233 | 23886 |
| Surfboard-tg-mixed | 0.255 | observe | 9 | 0.222 | 7169 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5125 |
| Epodonios-all | 0.255 | observe | 0 | None | 7681 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9909 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5728 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.222 | 2 | 7 | 9 |
| mheidari-all | 0.233 | 42 | 138 | 180 |
| ermaozi | 0.407 | 24 | 35 | 59 |
| DeltaKronecker-all | 0.625 | 5 | 3 | 8 |
| Au1rxx-base64 | 0.884 | 304 | 40 | 344 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23886 | yes | 6.13 | 0 |
| SoliSpirit-all | 9909 | yes | 2.88 | 0 |
| Epodonios-all | 7681 | yes | 7.19 | 0 |
| Surfboard-tg-mixed | 7169 | yes | 4.34 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.44 | 0 |
| barry-far-vless | 5978 | yes | 3.8 | 0 |
| Surfboard-tg-vless | 5728 | yes | 6.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 5125 | yes | 1.39 | 0 |
| DeltaKronecker-all | 4803 | yes | 6.63 | 0 |
| mahdibland-V2RayAggregator | 4271 | yes | 0.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 127 |
| 204 | 50 |
| speed | 41 |
| cn-block | 8 |

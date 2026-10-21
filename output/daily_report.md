# AutoNodes 每日报告

生成时间：2026-10-21 03:11:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 95345 |
| 去重后节点数 | 26608 |
| TCP 可达数 | 3000 |
| 真测通过数 | 396 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26608 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 80.0 |
| geo | 1.5 |
| probe | 205.9 |
| real_test | 231.9 |
| tcp | 45.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 57 | 27 | 30 | 47.4% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 170 | 153 | 17 | 90.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 69 | 64 | 5 | 92.8% |
| vless | 265 | 139 | 126 | 52.5% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 54 |
| 204:ProxyError | 28 |
| geo:ClientOSError | 27 |
| speed:ClientOSError | 24 |
| speed:TimeoutError | 14 |
| 204:TimeoutError | 10 |
| 204:ProxyConnectionError | 9 |
| cn-block:TimeoutError | 9 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6665 |
| ConnectionRefusedError | 1030 |
| OSError | 233 |
| gaierror | 206 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.955 | prefer | 213 | 0.901 | 1439 |
| Surfboard-tg-mixed | 0.931 | prefer | 85 | 0.859 | 7115 |
| mheidari-all | 0.559 | observe | 211 | 0.479 | 23653 |
| zhangkai | 0.501 | observe | 20 | 0.5 | 31 |
| ermaozi-get_subscribe | 0.496 | observe | 38 | 0.474 | 516 |
| DeltaKronecker-all | 0.255 | observe | 9 | 0.222 | 3519 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7598 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10013 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.222 | 2 | 7 | 9 |
| ermaozi-get_subscribe | 0.474 | 18 | 20 | 38 |
| mheidari-all | 0.479 | 101 | 110 | 211 |
| zhangkai | 0.5 | 10 | 10 | 20 |
| Surfboard-tg-mixed | 0.859 | 73 | 12 | 85 |
| Au1rxx-base64 | 0.901 | 192 | 21 | 213 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23653 | yes | 5.25 | 0 |
| SoliSpirit-all | 10013 | yes | 2.44 | 0 |
| Epodonios-all | 7598 | yes | 5.45 | 0 |
| Surfboard-tg-mixed | 7115 | yes | 0.73 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.33 | 0 |
| barry-far-vless | 5764 | yes | 0.78 | 0 |
| Surfboard-tg-vless | 5552 | yes | 4.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 0.45 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 3.57 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 81 |
| 204 | 50 |
| speed | 38 |
| cn-block | 12 |

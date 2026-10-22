# AutoNodes 每日报告

生成时间：2026-10-22 21:17:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96202 |
| 去重后节点数 | 26677 |
| TCP 可达数 | 3000 |
| 真测通过数 | 331 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26677 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 78.6 |
| geo | 1.5 |
| probe | 250.0 |
| real_test | 203.5 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 33 | 15 | 18 | 45.5% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 157 | 141 | 16 | 89.8% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 39 | 35 | 4 | 89.7% |
| vless | 190 | 124 | 66 | 65.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 17 |
| speed:ClientOSError | 16 |
| speed:TimeoutError | 12 |
| 204:TimeoutError | 12 |
| geo:ClientOSError | 8 |
| 204:ProxyConnectionError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6426 |
| ConnectionRefusedError | 1059 |
| gaierror | 299 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.887 | prefer | 81 | 0.815 | 23896 |
| Au1rxx-base64 | 0.856 | prefer | 264 | 0.795 | 1575 |
| Surfboard-tg-mixed | 0.82 | prefer | 48 | 0.75 | 7066 |
| ermaozi | 0.48 | observe | 33 | 0.455 | 573 |
| DeltaKronecker-all | 0.314 | observe | 9 | 0.333 | 3641 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7550 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10034 |

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
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 3 | 6 | 9 |
| ermaozi | 0.455 | 15 | 18 | 33 |
| Surfboard-tg-mixed | 0.75 | 36 | 12 | 48 |
| Au1rxx-base64 | 0.795 | 210 | 54 | 264 |
| mheidari-all | 0.815 | 66 | 15 | 81 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23896 | yes | 4.27 | 0 |
| SoliSpirit-all | 10034 | yes | 4.55 | 0 |
| Epodonios-all | 7550 | yes | 3.75 | 0 |
| Surfboard-tg-mixed | 7066 | yes | 5.52 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.31 | 0 |
| barry-far-vless | 5640 | yes | 0.75 | 0 |
| Surfboard-tg-vless | 5426 | yes | 2.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 2.33 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 39 |
| cn-block | 28 |
| speed | 28 |
| geo | 12 |

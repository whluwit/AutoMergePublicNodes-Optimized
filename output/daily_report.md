# AutoNodes 每日报告

生成时间：2026-10-15 16:25:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 100067 |
| 去重后节点数 | 27874 |
| TCP 可达数 | 3000 |
| 真测通过数 | 374 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27874 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 90.2 |
| geo | 1.4 |
| probe | 350.8 |
| real_test | 326.8 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 10 | 27 | 27.0% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 136 | 121 | 15 | 89.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 64 | 36 | 28 | 56.2% |
| vless | 325 | 191 | 134 | 58.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 52 |
| 204:ProxyError | 39 |
| geo:ClientOSError | 21 |
| speed:ClientOSError | 21 |
| speed:TimeoutError | 18 |
| cn-block:TimeoutError | 18 |
| cn-block:ClientOSError | 15 |
| geo:TimeoutError | 10 |
| 204:ClientOSError | 8 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6536 |
| ConnectionRefusedError | 1049 |
| gaierror | 332 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.829 | prefer | 433 | 0.76 | 1767 |
| mheidari-all | 0.421 | observe | 6 | 0.667 | 24080 |
| DeltaKronecker-all | 0.4 | observe | 73 | 0.315 | 5147 |
| Surfboard-tg-mixed | 0.338 | observe | 29 | 0.241 | 7281 |
| ermaozi | 0.308 | observe | 37 | 0.27 | 659 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7794 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10074 |

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
| Surfboard-tg-mixed | 0.241 | 7 | 22 | 29 |
| ermaozi | 0.27 | 10 | 27 | 37 |
| DeltaKronecker-all | 0.315 | 23 | 50 | 73 |
| mheidari-all | 0.667 | 4 | 2 | 6 |
| Au1rxx-base64 | 0.76 | 329 | 104 | 433 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24080 | yes | 5.28 | 0 |
| SoliSpirit-all | 10074 | yes | 3.74 | 0 |
| Epodonios-all | 7794 | yes | 4.09 | 0 |
| Surfboard-tg-mixed | 7281 | yes | 3.26 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.07 | 0 |
| barry-far-vless | 5961 | yes | 2.36 | 0 |
| Surfboard-tg-vless | 5707 | yes | 3.45 | 0 |
| DeltaKronecker-all | 5147 | yes | 4.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 0.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 99 |
| speed | 40 |
| cn-block | 35 |
| geo | 32 |

# AutoNodes 每日报告

生成时间：2026-10-15 21:04:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99871 |
| 去重后节点数 | 27648 |
| TCP 可达数 | 3000 |
| 真测通过数 | 372 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27648 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 72.0 |
| geo | 1.5 |
| probe | 330.0 |
| real_test | 288.5 |
| tcp | 49.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 66 | 24 | 42 | 36.4% |
| hysteria2 | 11 | 9 | 2 | 81.8% |
| shadowsocks | 132 | 123 | 9 | 93.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 38 | 33 | 5 | 86.8% |
| vless | 261 | 180 | 81 | 69.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 45 |
| 204:TimeoutError | 29 |
| speed:TimeoutError | 14 |
| geo:ClientOSError | 11 |
| speed:ClientOSError | 10 |
| geo:TimeoutError | 10 |
| cn-block:TimeoutError | 9 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7460 |
| ConnectionRefusedError | 1018 |
| OSError | 234 |
| gaierror | 106 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.9 | prefer | 391 | 0.829 | 1827 |
| mheidari-all | 0.745 | prefer | 17 | 0.765 | 24072 |
| Surfboard-tg-mixed | 0.507 | observe | 8 | 0.75 | 7281 |
| ermaozi | 0.385 | observe | 65 | 0.354 | 659 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 89 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9885 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.148 | 4 | 23 | 27 |
| ermaozi | 0.354 | 23 | 42 | 65 |
| Surfboard-tg-mixed | 0.75 | 6 | 2 | 8 |
| mheidari-all | 0.765 | 13 | 4 | 17 |
| Au1rxx-base64 | 0.829 | 324 | 67 | 391 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24072 | yes | 3.16 | 0 |
| SoliSpirit-all | 9885 | yes | 2.4 | 0 |
| Epodonios-all | 7793 | yes | 2.77 | 0 |
| Surfboard-tg-mixed | 7281 | yes | 2.29 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.8 | 0 |
| barry-far-vless | 5957 | yes | 1.93 | 0 |
| Surfboard-tg-vless | 5707 | yes | 2.39 | 0 |
| DeltaKronecker-all | 5147 | yes | 3.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 3.03 | 0 |
| mahdibland-V2RayAggregator | 4235 | yes | 0.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 75 |
| speed | 25 |
| geo | 22 |
| cn-block | 18 |

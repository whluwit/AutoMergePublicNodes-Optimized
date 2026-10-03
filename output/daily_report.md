# AutoNodes 每日报告

生成时间：2026-10-03 03:46:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99149 |
| 去重后节点数 | 27181 |
| TCP 可达数 | 3000 |
| 真测通过数 | 507 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27181 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 89.6 |
| geo | 1.3 |
| probe | 323.1 |
| real_test | 522.5 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 4 | 1 | 80.0% |
| http | 24 | 9 | 15 | 37.5% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 168 | 157 | 11 | 93.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 47 | 32 | 15 | 68.1% |
| vless | 639 | 284 | 355 | 44.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 186 |
| speed:TimeoutError | 87 |
| geo:ClientOSError | 38 |
| cn-block:TimeoutError | 22 |
| speed:ClientOSError | 19 |
| 204:ProxyConnectionError | 15 |
| 204:TimeoutError | 15 |
| cn-block:ClientOSError | 8 |
| 204:ProxyError | 6 |
| speed:ClientPayloadError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6518 |
| ConnectionRefusedError | 1171 |
| gaierror | 438 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | prefer | 308 | 0.89 | 1762 |
| Surfboard-tg-mixed | 0.928 | prefer | 64 | 0.859 | 7256 |
| mheidari-all | 0.405 | observe | 487 | 0.324 | 23323 |
| DeltaKronecker-all | 0.397 | observe | 12 | 0.417 | 4981 |
| ermaozi | 0.396 | observe | 25 | 0.36 | 645 |
| ermaozi-get_subscribe | 0.387 | observe | 5 | 0.8 | 516 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7743 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.324 | 158 | 329 | 487 |
| ninja-vless | 0.333 | 1 | 2 | 3 |
| ermaozi | 0.36 | 9 | 16 | 25 |
| DeltaKronecker-all | 0.417 | 5 | 7 | 12 |
| ermaozi-get_subscribe | 0.8 | 4 | 1 | 5 |
| Surfboard-tg-mixed | 0.859 | 55 | 9 | 64 |
| Au1rxx-base64 | 0.89 | 274 | 34 | 308 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23323 | yes | 6.58 | 0 |
| SoliSpirit-all | 9542 | yes | 2.55 | 0 |
| Epodonios-all | 7743 | yes | 3.57 | 0 |
| Surfboard-tg-mixed | 7256 | yes | 4.59 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.14 | 0 |
| barry-far-vless | 6214 | yes | 1.5 | 0 |
| Surfboard-tg-vless | 5980 | yes | 4.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 0.97 | 0 |
| DeltaKronecker-all | 4981 | yes | 6.56 | 0 |
| mahdibland-V2RayAggregator | 4357 | yes | 0.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 224 |
| speed | 108 |
| 204 | 37 |
| cn-block | 31 |

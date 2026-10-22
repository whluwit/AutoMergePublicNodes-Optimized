# AutoNodes 每日报告

生成时间：2026-10-22 11:10:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 95606 |
| 去重后节点数 | 26580 |
| TCP 可达数 | 3000 |
| 真测通过数 | 254 |
| verified 输出数 | 254 |
| global 输出数 | 270 |
| all 输出数 | 26580 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 81.3 |
| geo | 1.5 |
| probe | 176.9 |
| real_test | 190.8 |
| tcp | 44.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 40 | 19 | 21 | 47.5% |
| hysteria2 | 7 | 7 | 0 | 100.0% |
| shadowsocks | 87 | 70 | 17 | 80.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 39 | 28 | 11 | 71.8% |
| vless | 184 | 127 | 57 | 69.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 23 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 17 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| geo:ClientOSError | 8 |
| geo:TimeoutError | 5 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6472 |
| ConnectionRefusedError | 1024 |
| gaierror | 277 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.828 | prefer | 21 | 0.857 | 45 |
| Au1rxx-base64 | 0.809 | prefer | 216 | 0.75 | 1526 |
| Surfboard-tg-mixed | 0.777 | prefer | 87 | 0.701 | 6970 |
| mheidari-all | 0.547 | observe | 9 | 0.778 | 23951 |
| DeltaKronecker-all | 0.446 | observe | 8 | 0.625 | 3641 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 7460 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10066 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5452 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.113 | 19 | 0.053 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.053 | 1 | 18 | 19 |
| DeltaKronecker-all | 0.625 | 5 | 3 | 8 |
| Surfboard-tg-mixed | 0.701 | 61 | 26 | 87 |
| Au1rxx-base64 | 0.75 | 162 | 54 | 216 |
| mheidari-all | 0.778 | 7 | 2 | 9 |
| zhangkai | 0.857 | 18 | 3 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23951 | yes | 6.5 | 0 |
| SoliSpirit-all | 10066 | yes | 3.55 | 0 |
| Epodonios-all | 7460 | yes | 4.35 | 0 |
| Surfboard-tg-mixed | 6970 | yes | 3.55 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.29 | 0 |
| barry-far-vless | 5666 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5452 | yes | 4.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 0.63 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 3.63 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.84 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 51 |
| speed | 24 |
| cn-block | 19 |
| geo | 13 |

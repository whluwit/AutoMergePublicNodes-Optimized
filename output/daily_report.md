# AutoNodes 每日报告

生成时间：2026-10-18 20:10:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 97816 |
| 去重后节点数 | 27650 |
| TCP 可达数 | 3000 |
| 真测通过数 | 298 |
| verified 输出数 | 298 |
| global 输出数 | 300 |
| all 输出数 | 27650 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 83.7 |
| geo | 1.5 |
| probe | 279.3 |
| real_test | 198.5 |
| tcp | 48.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 19 | 12 | 7 | 63.2% |
| hysteria2 | 6 | 5 | 1 | 83.3% |
| shadowsocks | 122 | 102 | 20 | 83.6% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 6 | 5 | 1 | 83.3% |
| vless | 228 | 169 | 59 | 74.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 14 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 11 |
| 204:ProxyConnectionError | 8 |
| geo:ClientOSError | 8 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6943 |
| ConnectionRefusedError | 1033 |
| gaierror | 386 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.905 | prefer | 265 | 0.838 | 1742 |
| mheidari-all | 0.756 | prefer | 72 | 0.681 | 23629 |
| Surfboard-tg-mixed | 0.663 | observe | 22 | 0.591 | 7036 |
| ermaozi | 0.662 | observe | 20 | 0.65 | 639 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7503 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10062 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5553 |
| barry-far-vless | 0.255 | observe | 0 | None | 5767 |

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
| downweight | DeltaKronecker-all | 0.202 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.125 | 1 | 7 | 8 |
| Surfboard-tg-mixed | 0.591 | 13 | 9 | 22 |
| ermaozi | 0.65 | 13 | 7 | 20 |
| mheidari-all | 0.681 | 49 | 23 | 72 |
| Au1rxx-base64 | 0.838 | 222 | 43 | 265 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23629 | yes | 6.25 | 0 |
| SoliSpirit-all | 10062 | yes | 4.3 | 0 |
| Epodonios-all | 7503 | yes | 6.45 | 0 |
| Surfboard-tg-mixed | 7036 | yes | 4.88 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.05 | 0 |
| barry-far-vless | 5767 | yes | 0.84 | 0 |
| Surfboard-tg-vless | 5553 | yes | 4.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 0.62 | 0 |
| DeltaKronecker-all | 4750 | yes | 6.59 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 3.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 38 |
| cn-block | 24 |
| speed | 15 |
| geo | 12 |

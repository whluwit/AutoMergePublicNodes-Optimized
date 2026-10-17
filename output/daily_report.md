# AutoNodes 每日报告

生成时间：2026-10-17 10:16:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99237 |
| 去重后节点数 | 27753 |
| TCP 可达数 | 3000 |
| 真测通过数 | 440 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27753 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| generate | 100.1 |
| geo | 1.5 |
| probe | 318.1 |
| real_test | 340.6 |
| tcp | 48.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 99 | 44 | 55 | 44.4% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 151 | 133 | 18 | 88.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 34 | 24 | 10 | 70.6% |
| vless | 307 | 226 | 81 | 73.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 44 |
| 204:TimeoutError | 38 |
| speed:TimeoutError | 17 |
| speed:ClientOSError | 17 |
| 204:ProxyConnectionError | 13 |
| geo:ClientOSError | 13 |
| cn-block:TimeoutError | 10 |
| cn-block:ClientOSError | 7 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7029 |
| ConnectionRefusedError | 1035 |
| OSError | 236 |
| gaierror | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.91 | prefer | 440 | 0.832 | 1993 |
| mheidari-all | 0.595 | observe | 13 | 0.692 | 23828 |
| Surfboard-tg-mixed | 0.512 | observe | 35 | 0.429 | 7109 |
| ermaozi | 0.479 | observe | 100 | 0.45 | 702 |
| DeltaKronecker-all | 0.361 | observe | 18 | 0.278 | 4999 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |
| Epodonios-all | 0.255 | observe | 0 | None | 7611 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9902 |

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
| Pawdroid | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.278 | 5 | 13 | 18 |
| Surfboard-tg-mixed | 0.429 | 15 | 20 | 35 |
| ermaozi | 0.45 | 45 | 55 | 100 |
| mheidari-all | 0.692 | 9 | 4 | 13 |
| Au1rxx-base64 | 0.832 | 366 | 74 | 440 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23828 | yes | 6.72 | 0 |
| SoliSpirit-all | 9902 | yes | 6.38 | 0 |
| Epodonios-all | 7611 | yes | 6.03 | 0 |
| Surfboard-tg-mixed | 7109 | yes | 5.59 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.18 | 0 |
| barry-far-vless | 5842 | yes | 2.47 | 0 |
| Surfboard-tg-vless | 5597 | yes | 5.79 | 0 |
| DeltaKronecker-all | 4999 | yes | 6.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 3.58 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 3.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 98 |
| speed | 34 |
| cn-block | 20 |
| geo | 17 |

# AutoNodes 每日报告

生成时间：2026-10-14 03:30:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98610 |
| 去重后节点数 | 27423 |
| TCP 可达数 | 3000 |
| 真测通过数 | 514 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27423 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 72.4 |
| geo | 1.4 |
| probe | 333.1 |
| real_test | 428.0 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 58 | 41 | 17 | 70.7% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 122 | 120 | 2 | 98.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 114 | 108 | 6 | 94.7% |
| vless | 441 | 225 | 216 | 51.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 113 |
| geo:ClientOSError | 31 |
| speed:ClientOSError | 31 |
| 204:ProxyError | 24 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 13 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6659 |
| ConnectionRefusedError | 1053 |
| gaierror | 345 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | prefer | 42 | 0.952 | 7113 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.963 | prefer | 340 | 0.894 | 1781 |
| ermaozi-get_subscribe | 0.574 | observe | 38 | 0.553 | 598 |
| mheidari-all | 0.489 | observe | 301 | 0.409 | 24076 |
| DeltaKronecker-all | 0.291 | observe | 12 | 0.25 | 5076 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7613 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9824 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.25 | 3 | 9 | 12 |
| mheidari-all | 0.409 | 123 | 178 | 301 |
| ermaozi-get_subscribe | 0.553 | 21 | 17 | 38 |
| Au1rxx-base64 | 0.894 | 304 | 36 | 340 |
| Surfboard-tg-mixed | 0.952 | 40 | 2 | 42 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24076 | yes | 4.73 | 0 |
| SoliSpirit-all | 9824 | yes | 2.89 | 0 |
| Epodonios-all | 7613 | yes | 5.11 | 0 |
| Surfboard-tg-mixed | 7113 | yes | 2.98 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.11 | 0 |
| barry-far-vless | 5866 | yes | 2.5 | 0 |
| Surfboard-tg-vless | 5621 | yes | 3.98 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 2.26 | 0 |
| DeltaKronecker-all | 5076 | yes | 5.07 | 0 |
| mahdibland-V2RayAggregator | 4216 | yes | 1.38 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 146 |
| speed | 40 |
| 204 | 38 |
| cn-block | 20 |

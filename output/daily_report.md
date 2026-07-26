# AutoNodes 每日报告

生成时间：2026-07-26 08:25:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 81009 |
| 去重后节点数 | 22426 |
| TCP 可达数 | 3000 |
| 真测通过数 | 929 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22426 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 41.1 |
| geo | 1.3 |
| probe | 63.2 |
| real_test | 194.0 |
| tcp | 30.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 138 | 117 | 21 | 84.8% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 634 | 587 | 47 | 92.6% |
| vless | 284 | 139 | 145 | 48.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 58 |
| cn-block:TimeoutError | 29 |
| speed:ClientOSError | 26 |
| 204:ProxyError | 24 |
| speed:TimeoutError | 21 |
| 204:TimeoutError | 19 |
| geo:ClientOSError | 15 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 6 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 3 |
| speed:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 3938 |
| ConnectionRefusedError | 696 |
| gaierror | 340 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 76 | 1.0 | 86 |
| Au1rxx-base64 | 0.952 | prefer | 454 | 0.896 | 1442 |
| mheidari-all | 0.9 | prefer | 231 | 0.823 | 17285 |
| DeltaKronecker-all | 0.826 | prefer | 203 | 0.749 | 5950 |
| Surfboard-tg-mixed | 0.664 | observe | 176 | 0.585 | 5447 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6589 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6596 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.585 | 103 | 73 | 176 |
| DeltaKronecker-all | 0.749 | 152 | 51 | 203 |
| mheidari-all | 0.823 | 190 | 41 | 231 |
| Au1rxx-base64 | 0.896 | 407 | 47 | 454 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 76 | 0 | 76 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17285 | yes | 4.44 | 0 |
| SoliSpirit-all | 6596 | yes | 3.25 | 0 |
| Epodonios-all | 6589 | yes | 2.38 | 0 |
| DeltaKronecker-all | 5950 | yes | 4.61 | 0 |
| Surfboard-tg-mixed | 5447 | yes | 3.09 | 0 |
| mahdibland-V2RayAggregator | 4980 | yes | 2.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.6 | 0 |
| barry-far-vless | 4874 | yes | 2.02 | 0 |
| Surfboard-tg-vless | 4215 | yes | 2.78 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.38 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 76 |
| speed | 50 |
| 204 | 47 |
| cn-block | 43 |

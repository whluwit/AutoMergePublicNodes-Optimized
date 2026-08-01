# AutoNodes 每日报告

生成时间：2026-08-01 19:06:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78657 |
| 去重后节点数 | 23488 |
| TCP 可达数 | 3000 |
| 真测通过数 | 592 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23488 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 41.9 |
| geo | 1.4 |
| probe | 59.0 |
| real_test | 146.1 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 146 | 146 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 129 | 107 | 22 | 82.9% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 32 | 27 | 5 | 84.4% |
| vless | 484 | 288 | 196 | 59.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 95 |
| speed:TimeoutError | 26 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 23 |
| geo:ClientOSError | 19 |
| speed:ClientOSError | 12 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 9 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4794 |
| ConnectionRefusedError | 787 |
| gaierror | 295 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.994 | prefer | 148 | 0.993 | 194 |
| Au1rxx-base64 | 0.786 | prefer | 463 | 0.719 | 1692 |
| DeltaKronecker-all | 0.62 | observe | 124 | 0.54 | 5502 |
| Surfboard-tg-mixed | 0.617 | observe | 78 | 0.538 | 5294 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5391 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 16619 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 55 |
| Epodonios-all | 0.255 | observe | 0 | None | 5908 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6646 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.538 | 42 | 36 | 78 |
| DeltaKronecker-all | 0.54 | 67 | 57 | 124 |
| Au1rxx-base64 | 0.719 | 333 | 130 | 463 |
| zhangkai | 0.993 | 147 | 1 | 148 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16619 | yes | 4.43 | 0 |
| SoliSpirit-all | 6646 | yes | 2.35 | 0 |
| Epodonios-all | 5908 | yes | 4.67 | 0 |
| DeltaKronecker-all | 5502 | yes | 4.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 1.12 | 0 |
| Surfboard-tg-mixed | 5294 | yes | 3.38 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 2.66 | 0 |
| barry-far-vless | 4547 | yes | 0.41 | 0 |
| Surfboard-tg-vless | 4168 | yes | 3.2 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 0.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 114 |
| 204 | 45 |
| speed | 38 |
| cn-block | 30 |

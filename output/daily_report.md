# AutoNodes 每日报告

生成时间：2026-08-01 13:13:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79417 |
| 去重后节点数 | 23458 |
| TCP 可达数 | 3000 |
| 真测通过数 | 614 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23458 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 36.0 |
| geo | 1.4 |
| probe | 62.7 |
| real_test | 154.7 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 157 | 157 | 0 | 100.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 149 | 134 | 15 | 89.9% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 30 | 22 | 8 | 73.3% |
| vless | 455 | 285 | 170 | 62.6% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 71 |
| speed:TimeoutError | 36 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 14 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4640 |
| ConnectionRefusedError | 773 |
| gaierror | 307 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 158 | 1.0 | 228 |
| Au1rxx-base64 | 0.833 | prefer | 483 | 0.766 | 1689 |
| Surfboard-tg-mixed | 0.638 | observe | 84 | 0.56 | 5348 |
| DeltaKronecker-all | 0.52 | observe | 82 | 0.439 | 5502 |
| mheidari-all | 0.391 | observe | 2 | 1.0 | 16803 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5391 |
| Epodonios-all | 0.255 | observe | 0 | None | 5964 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7133 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.439 | 36 | 46 | 82 |
| Surfboard-tg-mixed | 0.56 | 47 | 37 | 84 |
| Au1rxx-base64 | 0.766 | 370 | 113 | 483 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 158 | 0 | 158 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16803 | yes | 5.23 | 0 |
| SoliSpirit-all | 6948 | yes | 4.47 | 0 |
| Epodonios-all | 5964 | yes | 4.74 | 0 |
| DeltaKronecker-all | 5502 | yes | 5.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 5391 | yes | 2.78 | 0 |
| Surfboard-tg-mixed | 5348 | yes | 3.56 | 0 |
| mahdibland-V2RayAggregator | 5039 | yes | 3.1 | 0 |
| barry-far-vless | 4602 | yes | 2.94 | 0 |
| Surfboard-tg-vless | 4142 | yes | 3.28 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 94 |
| speed | 50 |
| 204 | 33 |
| cn-block | 22 |

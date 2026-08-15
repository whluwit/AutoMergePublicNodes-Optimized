# AutoNodes 每日报告

生成时间：2026-08-15 18:26:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78589 |
| 去重后节点数 | 22397 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1021 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22397 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.4 |
| generate | 29.8 |
| geo | 0.7 |
| probe | 68.3 |
| real_test | 193.5 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 127 | 1 | 99.2% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 116 | 108 | 8 | 93.1% |
| socks | 13 | 10 | 3 | 76.9% |
| trojan | 576 | 575 | 1 | 99.8% |
| vless | 224 | 182 | 42 | 81.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 13 |
| geo:TimeoutError | 9 |
| speed:TimeoutError | 8 |
| cn-block:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| geo:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4509 |
| ConnectionRefusedError | 790 |
| gaierror | 341 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 691 | 0.971 | 1997 |
| zhangkai | 0.991 | prefer | 127 | 0.992 | 159 |
| mheidari-all | 0.967 | prefer | 184 | 0.891 | 16339 |
| Surfboard-tg-mixed | 0.898 | prefer | 42 | 0.833 | 5620 |
| DeltaKronecker-all | 0.79 | prefer | 29 | 0.724 | 5773 |
| nscl5-all | 0.349 | observe | 3 | 0.667 | 2081 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5113 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.667 | 2 | 1 | 3 |
| DeltaKronecker-all | 0.724 | 21 | 8 | 29 |
| Surfboard-tg-mixed | 0.833 | 35 | 7 | 42 |
| mheidari-all | 0.891 | 164 | 20 | 184 |
| Au1rxx-base64 | 0.971 | 671 | 20 | 691 |
| zhangkai | 0.992 | 126 | 1 | 127 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16339 | yes | 4.42 | 0 |
| SoliSpirit-all | 7464 | yes | 3.25 | 0 |
| Epodonios-all | 6266 | yes | 4.62 | 0 |
| DeltaKronecker-all | 5773 | yes | 4.8 | 0 |
| Surfboard-tg-mixed | 5620 | yes | 4.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 1.24 | 0 |
| barry-far-vless | 4694 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 4366 | yes | 3.45 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.52 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 2.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 18 |
| geo | 14 |
| cn-block | 13 |
| speed | 12 |

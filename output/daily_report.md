# AutoNodes 每日报告

生成时间：2026-08-16 06:38:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 78622 |
| 去重后节点数 | 21798 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1160 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21798 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 36.6 |
| geo | 1.4 |
| probe | 65.6 |
| real_test | 220.4 |
| tcp | 32.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 152 | 144 | 8 | 94.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 635 | 626 | 9 | 98.6% |
| vless | 385 | 238 | 147 | 61.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 54 |
| speed:TimeoutError | 39 |
| geo:ClientOSError | 20 |
| speed:ClientOSError | 12 |
| 204:TimeoutError | 11 |
| cn-block:TimeoutError | 11 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4105 |
| ConnectionRefusedError | 799 |
| gaierror | 332 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 795 | 0.975 | 1997 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.787 | prefer | 145 | 0.71 | 16464 |
| Surfboard-tg-mixed | 0.751 | prefer | 211 | 0.673 | 5651 |
| nscl5-all | 0.349 | observe | 3 | 0.667 | 2601 |
| DeltaKronecker-all | 0.347 | observe | 43 | 0.256 | 5092 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1997 |
| Epodonios-all | 0.255 | observe | 0 | None | 6328 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3984 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.256 | 11 | 32 | 43 |
| nscl5-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.673 | 142 | 69 | 211 |
| mheidari-all | 0.71 | 103 | 42 | 145 |
| Au1rxx-base64 | 0.975 | 775 | 20 | 795 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16464 | yes | 4.56 | 0 |
| SoliSpirit-all | 7355 | yes | 4.79 | 0 |
| Epodonios-all | 6328 | yes | 4.74 | 0 |
| Surfboard-tg-mixed | 5651 | yes | 3.6 | 0 |
| DeltaKronecker-all | 5092 | yes | 5.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.34 | 0 |
| barry-far-vless | 4736 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 4394 | yes | 3.38 | 0 |
| MatinGhanbari-all-sub | 3984 | yes | 0.87 | 0 |
| mahdibland-V2RayAggregator | 3950 | yes | 2.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 74 |
| speed | 53 |
| cn-block | 21 |
| 204 | 18 |

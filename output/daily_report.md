# AutoNodes 每日报告

生成时间：2026-08-22 12:34:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 92264 |
| 去重后节点数 | 23731 |
| TCP 可达数 | 3000 |
| 真测通过数 | 804 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23731 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 38.3 |
| geo | 1.3 |
| probe | 59.9 |
| real_test | 156.3 |
| tcp | 40.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 114 | 114 | 0 | 100.0% |
| hysteria2 | 28 | 27 | 1 | 96.4% |
| shadowsocks | 186 | 173 | 13 | 93.0% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 168 | 163 | 5 | 97.0% |
| vless | 430 | 324 | 106 | 75.3% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 30 |
| geo:TimeoutError | 22 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 16 |
| speed:TimeoutError | 16 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| 204:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5361 |
| ConnectionRefusedError | 950 |
| gaierror | 588 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 507 | 0.941 | 1674 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.886 | prefer | 178 | 0.809 | 6287 |
| mheidari-all | 0.608 | observe | 125 | 0.528 | 21719 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3321 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 146 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5096 |
| Epodonios-all | 0.255 | observe | 0 | None | 6868 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3989 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.528 | 66 | 59 | 125 |
| Surfboard-tg-mixed | 0.809 | 144 | 34 | 178 |
| Au1rxx-base64 | 0.941 | 477 | 30 | 507 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21719 | yes | 5.26 | 0 |
| SoliSpirit-all | 6876 | yes | 3.61 | 0 |
| Epodonios-all | 6868 | yes | 4.64 | 0 |
| Surfboard-tg-mixed | 6287 | yes | 3.48 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 2.17 | 0 |
| barry-far-vless | 5403 | yes | 1.78 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 2.46 | 0 |
| Surfboard-tg-vless | 5093 | yes | 3.0 | 0 |
| DeltaKronecker-all | 5015 | yes | 4.38 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 1.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 53 |
| cn-block | 25 |
| speed | 25 |
| 204 | 23 |

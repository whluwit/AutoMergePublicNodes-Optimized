# AutoNodes 每日报告

生成时间：2026-08-09 01:22:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83131 |
| 去重后节点数 | 23580 |
| TCP 可达数 | 3000 |
| 真测通过数 | 494 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23580 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 31.0 |
| geo | 1.4 |
| probe | 53.1 |
| real_test | 107.8 |
| tcp | 34.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 27 | 26 | 1 | 96.3% |
| shadowsocks | 159 | 148 | 11 | 93.1% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 174 | 153 | 21 | 87.9% |
| vless | 297 | 142 | 155 | 47.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 80 |
| speed:TimeoutError | 33 |
| geo:ClientOSError | 21 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 16 |
| 204:ProxyError | 8 |
| 204:TimeoutError | 5 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4805 |
| ConnectionRefusedError | 833 |
| gaierror | 339 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 347 | 0.945 | 1540 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.726 | prefer | 142 | 0.648 | 6513 |
| DeltaKronecker-all | 0.438 | observe | 107 | 0.355 | 5347 |
| mheidari-all | 0.322 | observe | 60 | 0.233 | 17775 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 123 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5450 |
| Epodonios-all | 0.255 | observe | 0 | None | 7127 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7538 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.128 | observe | 1 | 0.0 | 0 | 12 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.233 | 14 | 46 | 60 |
| DeltaKronecker-all | 0.355 | 38 | 69 | 107 |
| Surfboard-tg-mixed | 0.648 | 92 | 50 | 142 |
| Au1rxx-base64 | 0.945 | 328 | 19 | 347 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17775 | yes | 3.64 | 0 |
| SoliSpirit-all | 7538 | yes | 2.98 | 0 |
| Epodonios-all | 7127 | yes | 2.59 | 0 |
| Surfboard-tg-mixed | 6513 | yes | 3.85 | 0 |
| barry-far-vless | 5644 | yes | 2.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 1.47 | 0 |
| DeltaKronecker-all | 5347 | yes | 5.01 | 0 |
| Surfboard-tg-vless | 5322 | yes | 4.09 | 0 |
| mahdibland-V2RayAggregator | 5127 | yes | 2.87 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 102 |
| speed | 49 |
| cn-block | 22 |
| 204 | 15 |

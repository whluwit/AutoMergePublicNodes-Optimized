# AutoNodes 每日报告

生成时间：2026-07-03 09:00:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77372 |
| 去重后节点数 | 22723 |
| TCP 可达数 | 3000 |
| 真测通过数 | 465 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22723 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 35.4 |
| geo | 1.4 |
| probe | 57.4 |
| real_test | 139.6 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 97 | 85 | 12 | 87.6% |
| socks | 26 | 21 | 5 | 80.8% |
| trojan | 158 | 124 | 34 | 78.5% |
| vless | 403 | 192 | 211 | 47.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 123 |
| geo:TimeoutError | 65 |
| 204:TimeoutError | 16 |
| 204:ProxyError | 13 |
| cn-block:TimeoutError | 13 |
| 204:ClientOSError | 9 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| geo:ClientOSError | 4 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4430 |
| ConnectionRefusedError | 687 |
| OSError | 152 |
| gaierror | 70 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.825 | prefer | 26 | 0.846 | 84 |
| DeltaKronecker-all | 0.767 | prefer | 94 | 0.691 | 6997 |
| Surfboard-tg-mixed | 0.751 | prefer | 317 | 0.672 | 6013 |
| mheidari-all | 0.586 | observe | 251 | 0.506 | 16051 |
| nscl5-all | 0.356 | observe | 2 | 1.0 | 1114 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4368 |
| Epodonios-all | 0.255 | observe | 0 | None | 6902 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6955 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.506 | 127 | 124 | 251 |
| Surfboard-tg-mixed | 0.672 | 213 | 104 | 317 |
| DeltaKronecker-all | 0.691 | 65 | 29 | 94 |
| Au1rxx-base64 | 0.846 | 22 | 4 | 26 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16051 | yes | 3.2 | 0 |
| DeltaKronecker-all | 6997 | yes | 3.25 | 0 |
| SoliSpirit-all | 6955 | yes | 1.84 | 0 |
| Epodonios-all | 6902 | yes | 1.59 | 0 |
| Surfboard-tg-mixed | 6013 | yes | 2.53 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 1.02 | 0 |
| barry-far-vless | 5055 | yes | 1.22 | 0 |
| Surfboard-tg-vless | 4518 | yes | 2.29 | 0 |
| 10ium-ScrapeCategorize-Vless | 4368 | yes | 1.03 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 1.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 133 |
| geo | 71 |
| 204 | 38 |
| cn-block | 20 |

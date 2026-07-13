# AutoNodes 每日报告

生成时间：2026-07-13 09:20:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76605 |
| 去重后节点数 | 23706 |
| TCP 可达数 | 3000 |
| 真测通过数 | 291 |
| verified 输出数 | 291 |
| global 输出数 | 300 |
| all 输出数 | 23706 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 24.2 |
| geo | 1.4 |
| probe | 46.2 |
| real_test | 77.1 |
| tcp | 31.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| shadowsocks | 95 | 82 | 13 | 86.3% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 192 | 146 | 46 | 76.0% |
| vless | 85 | 21 | 64 | 24.7% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 40 |
| speed:ClientOSError | 23 |
| cn-block:ClientOSError | 11 |
| 204:ProxyError | 10 |
| 204:TimeoutError | 9 |
| geo:ClientOSError | 7 |
| cn-block:ProxyError | 7 |
| speed:TimeoutError | 5 |
| speed:ProxyError | 5 |
| cn-block:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4294 |
| ConnectionRefusedError | 660 |
| gaierror | 312 |
| OSError | 192 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.772 | prefer | 115 | 0.696 | 5436 |
| mheidari-all | 0.751 | prefer | 68 | 0.676 | 16299 |
| DeltaKronecker-all | 0.736 | prefer | 193 | 0.658 | 7926 |
| nscl5-all | 0.316 | observe | 1 | 1.0 | 1526 |
| xiaoji235-airport-v2ray-all | 0.273 | observe | 2 | 0.5 | 1647 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3897 |
| Epodonios-all | 0.255 | observe | 0 | None | 6476 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3979 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6409 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.658 | 127 | 66 | 193 |
| mheidari-all | 0.676 | 46 | 22 | 68 |
| Surfboard-tg-mixed | 0.696 | 80 | 35 | 115 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16299 | yes | 3.49 | 0 |
| DeltaKronecker-all | 7926 | yes | 3.78 | 0 |
| Epodonios-all | 6476 | yes | 1.87 | 0 |
| SoliSpirit-all | 6409 | yes | 1.83 | 0 |
| Surfboard-tg-mixed | 5436 | yes | 2.31 | 0 |
| mahdibland-V2RayAggregator | 5412 | yes | 1.62 | 0 |
| barry-far-vless | 4724 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 4097 | yes | 2.12 | 0 |
| MatinGhanbari-all-sub | 3979 | yes | 1.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 3897 | yes | 1.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 49 |
| speed | 33 |
| 204 | 22 |
| cn-block | 22 |

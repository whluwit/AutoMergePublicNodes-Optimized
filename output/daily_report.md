# AutoNodes 每日报告

生成时间：2026-07-25 02:16:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 80522 |
| 去重后节点数 | 22888 |
| TCP 可达数 | 3000 |
| 真测通过数 | 771 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22888 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.1 |
| generate | 24.2 |
| geo | 1.3 |
| probe | 60.1 |
| real_test | 180.6 |
| tcp | 32.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 20 | 17 | 3 | 85.0% |
| socks | 15 | 12 | 3 | 80.0% |
| trojan | 540 | 514 | 26 | 95.2% |
| vless | 592 | 188 | 404 | 31.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 155 |
| speed:ClientOSError | 123 |
| geo:ClientOSError | 55 |
| speed:TimeoutError | 49 |
| cn-block:TimeoutError | 40 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 2 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4514 |
| ConnectionRefusedError | 695 |
| gaierror | 291 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.76 | prefer | 320 | 0.681 | 5472 |
| DeltaKronecker-all | 0.725 | prefer | 229 | 0.646 | 5559 |
| mheidari-all | 0.673 | observe | 602 | 0.593 | 19388 |
| Au1rxx-base64 | 0.58 | observe | 10 | 0.9 | 432 |
| tg-ConfigV2rayNG | 0.263 | observe | 1 | 1.0 | 200 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4588 |
| Epodonios-all | 0.255 | observe | 0 | None | 6656 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3967 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.218 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.593 | 357 | 245 | 602 |
| DeltaKronecker-all | 0.646 | 148 | 81 | 229 |
| Surfboard-tg-mixed | 0.681 | 218 | 102 | 320 |
| Au1rxx-base64 | 0.9 | 9 | 1 | 10 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-ConfigV2rayNG | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19388 | yes | 2.94 | 0 |
| Epodonios-all | 6656 | yes | 2.35 | 0 |
| SoliSpirit-all | 6637 | yes | 1.57 | 0 |
| DeltaKronecker-all | 5559 | yes | 2.3 | 0 |
| Surfboard-tg-mixed | 5472 | yes | 1.99 | 0 |
| mahdibland-V2RayAggregator | 5027 | yes | 1.6 | 0 |
| barry-far-vless | 4847 | yes | 0.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 4588 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 4180 | yes | 1.43 | 0 |
| MatinGhanbari-all-sub | 3967 | yes | 1.21 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 210 |
| speed | 172 |
| cn-block | 43 |
| 204 | 11 |

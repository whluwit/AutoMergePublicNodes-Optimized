# AutoNodes 每日报告

生成时间：2026-06-26 14:17:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76309 |
| 去重后节点数 | 22702 |
| TCP 可达数 | 3000 |
| 真测通过数 | 401 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22702 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 31.1 |
| geo | 1.4 |
| probe | 58.2 |
| real_test | 91.1 |
| tcp | 30.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 2 | 1 | 66.7% |
| shadowsocks | 116 | 95 | 21 | 81.9% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 108 | 57 | 51 | 52.8% |
| vless | 325 | 206 | 119 | 63.4% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 85 |
| 204:ProxyError | 23 |
| 204:TimeoutError | 22 |
| 204:ClientOSError | 16 |
| cn-block:TimeoutError | 13 |
| geo:TimeoutError | 12 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| geo:ProxyError | 3 |
| speed:ProxyError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4321 |
| ConnectionRefusedError | 623 |
| gaierror | 150 |
| OSError | 118 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Au1rxx-base64 | 0.83 | prefer | 44 | 0.841 | 95 |
| mheidari-all | 0.799 | prefer | 201 | 0.721 | 16250 |
| Surfboard-tg-mixed | 0.78 | prefer | 211 | 0.701 | 5176 |
| DeltaKronecker-all | 0.42 | observe | 98 | 0.337 | 6283 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4567 |
| Epodonios-all | 0.255 | observe | 0 | None | 7885 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3983 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7254 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.174 | observe | 1 | 0.0 | 0 | 1175 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.337 | 33 | 65 | 98 |
| Surfboard-tg-mixed | 0.701 | 148 | 63 | 211 |
| mheidari-all | 0.721 | 145 | 56 | 201 |
| Au1rxx-base64 | 0.841 | 37 | 7 | 44 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16250 | yes | 3.27 | 0 |
| Epodonios-all | 7885 | yes | 1.71 | 0 |
| SoliSpirit-all | 7254 | yes | 2.2 | 0 |
| DeltaKronecker-all | 6283 | yes | 4.02 | 0 |
| mahdibland-V2RayAggregator | 5185 | yes | 2.32 | 0 |
| Surfboard-tg-mixed | 5176 | yes | 2.83 | 0 |
| barry-far-vless | 4612 | yes | 1.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4567 | yes | 1.6 | 0 |
| MatinGhanbari-all-sub | 3983 | yes | 1.76 | 0 |
| Surfboard-tg-vless | 3834 | yes | 2.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 89 |
| 204 | 61 |
| geo | 21 |
| cn-block | 21 |

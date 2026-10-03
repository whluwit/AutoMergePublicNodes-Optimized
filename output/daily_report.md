# AutoNodes 每日报告

生成时间：2026-10-03 20:40:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99459 |
| 去重后节点数 | 27313 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27313 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 88.4 |
| geo | 1.0 |
| probe | 226.9 |
| real_test | 173.5 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 24 | 20 | 4 | 83.3% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 125 | 111 | 14 | 88.8% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 45 | 41 | 4 | 91.1% |
| vless | 264 | 219 | 45 | 83.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 6 |
| 204:ProxyConnectionError | 5 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:TimeoutError | 3 |
| speed:TimeoutError | 3 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6702 |
| ConnectionRefusedError | 1138 |
| gaierror | 374 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 334 | 0.895 | 1802 |
| mheidari-all | 0.901 | prefer | 37 | 0.838 | 23599 |
| Surfboard-tg-mixed | 0.808 | prefer | 79 | 0.734 | 7340 |
| ermaozi | 0.804 | prefer | 25 | 0.8 | 656 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5192 |
| Epodonios-all | 0.255 | observe | 0 | None | 7819 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9376 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5938 |
| barry-far-vless | 0.255 | observe | 0 | None | 6176 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.734 | 58 | 21 | 79 |
| ermaozi | 0.8 | 20 | 5 | 25 |
| mheidari-all | 0.838 | 31 | 6 | 37 |
| Au1rxx-base64 | 0.895 | 299 | 35 | 334 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23599 | yes | 6.11 | 0 |
| SoliSpirit-all | 9376 | yes | 2.25 | 0 |
| Epodonios-all | 7819 | yes | 3.35 | 0 |
| Surfboard-tg-mixed | 7340 | yes | 3.82 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.98 | 0 |
| barry-far-vless | 6176 | yes | 0.92 | 0 |
| Surfboard-tg-vless | 5938 | yes | 4.47 | 0 |
| DeltaKronecker-all | 5207 | yes | 3.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 4285 | yes | 3.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 34 |
| cn-block | 27 |
| speed | 8 |
| geo | 3 |

# AutoNodes 每日报告

生成时间：2026-09-29 18:09:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96917 |
| 去重后节点数 | 27000 |
| TCP 可达数 | 3000 |
| 真测通过数 | 328 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27000 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 90.0 |
| geo | 1.5 |
| probe | 202.0 |
| real_test | 143.4 |
| tcp | 45.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 23 | 13 | 10 | 56.5% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 127 | 110 | 17 | 86.6% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 8 | 4 | 4 | 50.0% |
| vless | 230 | 174 | 56 | 75.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 23 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 14 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 8 |
| 204:ProxyConnectionError | 5 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6699 |
| ConnectionRefusedError | 1001 |
| gaierror | 253 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.875 | prefer | 18 | 0.889 | 7053 |
| Au1rxx-base64 | 0.864 | prefer | 288 | 0.799 | 1683 |
| mheidari-all | 0.856 | prefer | 83 | 0.783 | 22753 |
| ermaozi | 0.553 | observe | 22 | 0.545 | 291 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 5528 |
| ermaozi-get_subscribe | 0.323 | observe | 2 | 1.0 | 293 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| Epodonios-all | 0.255 | observe | 0 | None | 7546 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.545 | 12 | 10 | 22 |
| mheidari-all | 0.783 | 65 | 18 | 83 |
| Au1rxx-base64 | 0.799 | 230 | 58 | 288 |
| Surfboard-tg-mixed | 0.889 | 16 | 2 | 18 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22753 | yes | 5.38 | 0 |
| SoliSpirit-all | 9402 | yes | 3.79 | 0 |
| Epodonios-all | 7546 | yes | 4.5 | 0 |
| Surfboard-tg-mixed | 7053 | yes | 3.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.7 | 0 |
| barry-far-vless | 5930 | yes | 0.95 | 0 |
| Surfboard-tg-vless | 5690 | yes | 2.95 | 0 |
| DeltaKronecker-all | 5528 | yes | 4.17 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 0.49 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 36 |
| speed | 31 |
| cn-block | 18 |
| geo | 5 |

# AutoNodes 每日报告

生成时间：2026-09-29 04:09:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96586 |
| 去重后节点数 | 26963 |
| TCP 可达数 | 3000 |
| 真测通过数 | 519 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26963 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 75.5 |
| geo | 1.4 |
| probe | 342.9 |
| real_test | 496.8 |
| tcp | 45.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 38 | 29 | 9 | 76.3% |
| hysteria2 | 31 | 30 | 1 | 96.8% |
| shadowsocks | 142 | 129 | 13 | 90.8% |
| socks | 3 | 3 | 0 | 100.0% |
| trojan | 11 | 5 | 6 | 45.5% |
| vless | 750 | 322 | 428 | 42.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 170 |
| speed:TimeoutError | 85 |
| speed:ClientOSError | 84 |
| cn-block:TimeoutError | 39 |
| geo:ClientOSError | 38 |
| 204:ProxyError | 13 |
| 204:TimeoutError | 13 |
| 204:ProxyConnectionError | 5 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6455 |
| ConnectionRefusedError | 981 |
| gaierror | 304 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.869 | prefer | 358 | 0.81 | 1519 |
| ermaozi | 0.779 | prefer | 32 | 0.781 | 354 |
| Surfboard-tg-mixed | 0.633 | observe | 19 | 0.579 | 7142 |
| mheidari-all | 0.416 | observe | 543 | 0.335 | 22589 |
| DeltaKronecker-all | 0.389 | observe | 13 | 0.385 | 5428 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 121 |
| ermaozi-get_subscribe | 0.287 | observe | 6 | 0.5 | 367 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5326 |
| Epodonios-all | 0.255 | observe | 0 | None | 7625 |

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
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.335 | 182 | 361 | 543 |
| DeltaKronecker-all | 0.385 | 5 | 8 | 13 |
| ermaozi-get_subscribe | 0.5 | 3 | 3 | 6 |
| Surfboard-tg-mixed | 0.579 | 11 | 8 | 19 |
| ermaozi | 0.781 | 25 | 7 | 32 |
| Au1rxx-base64 | 0.81 | 290 | 68 | 358 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22589 | yes | 6.07 | 0 |
| SoliSpirit-all | 9229 | yes | 2.57 | 0 |
| Epodonios-all | 7625 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 7142 | yes | 3.58 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.11 | 0 |
| barry-far-vless | 6028 | yes | 1.48 | 0 |
| Surfboard-tg-vless | 5799 | yes | 3.83 | 0 |
| DeltaKronecker-all | 5428 | yes | 5.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5326 | yes | 1.26 | 0 |
| mahdibland-V2RayAggregator | 4237 | yes | 2.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 209 |
| speed | 169 |
| cn-block | 44 |
| 204 | 36 |

# AutoNodes 每日报告

生成时间：2026-09-12 20:13:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83807 |
| 去重后节点数 | 23040 |
| TCP 可达数 | 3000 |
| 真测通过数 | 398 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23040 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 86.5 |
| geo | 1.4 |
| probe | 195.1 |
| real_test | 177.8 |
| tcp | 39.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 22 | 8 | 14 | 36.4% |
| hysteria2 | 26 | 24 | 2 | 92.3% |
| shadowsocks | 150 | 139 | 11 | 92.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 13 | 9 | 4 | 69.2% |
| vless | 282 | 216 | 66 | 76.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 19 |
| geo:ClientOSError | 19 |
| speed:ClientOSError | 15 |
| cn-block:TimeoutError | 12 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 6 |
| speed:TimeoutError | 5 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 2 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5579 |
| ConnectionRefusedError | 897 |
| gaierror | 386 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.919 | prefer | 54 | 0.852 | 15722 |
| Au1rxx-base64 | 0.909 | prefer | 317 | 0.845 | 1650 |
| DeltaKronecker-all | 0.822 | prefer | 29 | 0.759 | 5970 |
| Surfboard-tg-mixed | 0.82 | prefer | 71 | 0.746 | 7382 |
| ermaozi | 0.436 | observe | 18 | 0.444 | 393 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 161 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7802 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8913 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 4 | 4 |
| ermaozi | 0.444 | 8 | 10 | 18 |
| Surfboard-tg-mixed | 0.746 | 53 | 18 | 71 |
| DeltaKronecker-all | 0.759 | 22 | 7 | 29 |
| Au1rxx-base64 | 0.845 | 268 | 49 | 317 |
| mheidari-all | 0.852 | 46 | 8 | 54 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15722 | yes | 5.47 | 0 |
| SoliSpirit-all | 8913 | yes | 3.92 | 0 |
| Epodonios-all | 7802 | yes | 3.64 | 0 |
| Surfboard-tg-mixed | 7382 | yes | 3.99 | 0 |
| barry-far-vless | 6127 | yes | 2.41 | 0 |
| Surfboard-tg-vless | 5991 | yes | 5.1 | 0 |
| DeltaKronecker-all | 5970 | yes | 5.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 2.62 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 1.88 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| cn-block | 22 |
| geo | 21 |
| speed | 20 |

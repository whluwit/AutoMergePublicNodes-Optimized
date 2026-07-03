# AutoNodes 每日报告

生成时间：2026-07-03 13:56:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77176 |
| 去重后节点数 | 22933 |
| TCP 可达数 | 3000 |
| 真测通过数 | 263 |
| verified 输出数 | 263 |
| global 输出数 | 269 |
| all 输出数 | 22933 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 32.1 |
| geo | 1.5 |
| probe | 46.2 |
| real_test | 85.0 |
| tcp | 31.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 91 | 73 | 18 | 80.2% |
| socks | 3 | 3 | 0 | 100.0% |
| trojan | 133 | 113 | 20 | 85.0% |
| vless | 184 | 31 | 153 | 16.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 95 |
| geo:TimeoutError | 48 |
| 204:ClientOSError | 11 |
| 204:TimeoutError | 10 |
| geo:ClientOSError | 10 |
| cn-block:TimeoutError | 6 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 2 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4429 |
| ConnectionRefusedError | 664 |
| OSError | 152 |
| gaierror | 137 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.804 | prefer | 96 | 0.729 | 5871 |
| Au1rxx-base64 | 0.67 | observe | 37 | 0.676 | 79 |
| DeltaKronecker-all | 0.542 | observe | 277 | 0.462 | 6997 |
| nscl5-all | 0.356 | observe | 2 | 1.0 | 1114 |
| tg-ConfigV2rayNG | 0.263 | observe | 1 | 1.0 | 200 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4368 |
| Epodonios-all | 0.255 | observe | 0 | None | 6926 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| mheidari-all | 0.16 | observe | 4 | 0.0 | 0 | 15866 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 12 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 4 | 4 |
| DeltaKronecker-all | 0.462 | 128 | 149 | 277 |
| Au1rxx-base64 | 0.676 | 25 | 12 | 37 |
| Surfboard-tg-mixed | 0.729 | 70 | 26 | 96 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| tg-ConfigV2rayNG | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15866 | yes | 2.99 | 0 |
| SoliSpirit-all | 7163 | yes | 2.17 | 0 |
| DeltaKronecker-all | 6997 | yes | 3.32 | 0 |
| Epodonios-all | 6926 | yes | 1.3 | 0 |
| Surfboard-tg-mixed | 5871 | yes | 2.3 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 1.65 | 0 |
| barry-far-vless | 5041 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 4477 | yes | 1.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 4368 | yes | 1.42 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 97 |
| geo | 59 |
| 204 | 25 |
| cn-block | 10 |

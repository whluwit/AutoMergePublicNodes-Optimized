# AutoNodes 每日报告

生成时间：2026-09-14 11:45:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84316 |
| 去重后节点数 | 22916 |
| TCP 可达数 | 3000 |
| 真测通过数 | 468 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22916 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 135.7 |
| geo | 1.5 |
| probe | 221.9 |
| real_test | 230.2 |
| tcp | 37.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 69 | 47 | 22 | 68.1% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 164 | 157 | 7 | 95.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 18 | 14 | 4 | 77.8% |
| vless | 330 | 228 | 102 | 69.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 31 |
| 204:ProxyError | 26 |
| speed:ClientOSError | 20 |
| geo:TimeoutError | 17 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 14 |
| speed:TimeoutError | 6 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4899 |
| ConnectionRefusedError | 880 |
| gaierror | 501 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | prefer | 284 | 0.87 | 1623 |
| Surfboard-tg-mixed | 0.832 | prefer | 135 | 0.756 | 7444 |
| mheidari-all | 0.821 | prefer | 56 | 0.75 | 15903 |
| ermaozi | 0.715 | prefer | 51 | 0.706 | 417 |
| ermaozi-get_subscribe | 0.617 | observe | 19 | 0.632 | 444 |
| DeltaKronecker-all | 0.563 | observe | 58 | 0.483 | 5972 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 131 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 7910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| DeltaKronecker-all | 0.483 | 28 | 30 | 58 |
| ermaozi-get_subscribe | 0.632 | 12 | 7 | 19 |
| ermaozi | 0.706 | 36 | 15 | 51 |
| mheidari-all | 0.75 | 42 | 14 | 56 |
| Surfboard-tg-mixed | 0.756 | 102 | 33 | 135 |
| Au1rxx-base64 | 0.87 | 247 | 37 | 284 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15903 | yes | 4.97 | 0 |
| SoliSpirit-all | 8753 | yes | 1.55 | 0 |
| Epodonios-all | 7910 | yes | 5.4 | 0 |
| Surfboard-tg-mixed | 7444 | yes | 4.03 | 0 |
| barry-far-vless | 6310 | yes | 0.49 | 0 |
| Surfboard-tg-vless | 6094 | yes | 3.63 | 0 |
| DeltaKronecker-all | 5972 | yes | 4.18 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 2.97 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.57 | 0 |

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
| geo | 48 |
| 204 | 41 |
| speed | 26 |
| cn-block | 22 |

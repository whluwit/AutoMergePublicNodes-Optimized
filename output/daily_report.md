# AutoNodes 每日报告

生成时间：2026-10-02 21:54:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98966 |
| 去重后节点数 | 27189 |
| TCP 可达数 | 3000 |
| 真测通过数 | 444 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27189 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 103.5 |
| geo | 0.9 |
| probe | 249.9 |
| real_test | 172.8 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 3 | 2 | 60.0% |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 158 | 145 | 13 | 91.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 11 | 11 | 0 | 100.0% |
| vless | 310 | 249 | 61 | 80.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 15 |
| speed:TimeoutError | 12 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6533 |
| ConnectionRefusedError | 1147 |
| gaierror | 442 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.967 | prefer | 69 | 0.899 | 23213 |
| Au1rxx-base64 | 0.961 | prefer | 298 | 0.893 | 1771 |
| ermaozi | 0.914 | prefer | 25 | 0.92 | 620 |
| Surfboard-tg-mixed | 0.793 | prefer | 127 | 0.717 | 7321 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 4981 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7814 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9326 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5999 |

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
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.717 | 91 | 36 | 127 |
| Au1rxx-base64 | 0.893 | 266 | 32 | 298 |
| mheidari-all | 0.899 | 62 | 7 | 69 |
| ermaozi | 0.92 | 23 | 2 | 25 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23213 | yes | 3.67 | 0 |
| SoliSpirit-all | 9326 | yes | 2.43 | 0 |
| Epodonios-all | 7814 | yes | 0.25 | 0 |
| Surfboard-tg-mixed | 7321 | yes | 3.01 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 6241 | yes | 0.37 | 0 |
| Surfboard-tg-vless | 5999 | yes | 3.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 1.43 | 0 |
| DeltaKronecker-all | 4981 | yes | 4.52 | 0 |
| mahdibland-V2RayAggregator | 4357 | yes | 2.53 | 0 |

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
| cn-block | 29 |
| 204 | 28 |
| speed | 17 |
| geo | 7 |

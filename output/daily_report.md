# AutoNodes 每日报告

生成时间：2026-10-10 17:03:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97961 |
| 去重后节点数 | 27259 |
| TCP 可达数 | 3000 |
| 真测通过数 | 407 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27259 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 86.6 |
| geo | 1.4 |
| probe | 278.4 |
| real_test | 326.0 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 1 | 5 | 16.7% |
| http | 36 | 22 | 14 | 61.1% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 103 | 94 | 9 | 91.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 107 | 99 | 8 | 92.5% |
| vless | 243 | 175 | 68 | 72.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| 204:TimeoutError | 21 |
| speed:ClientOSError | 16 |
| 204:ProxyConnectionError | 14 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 9 |
| 204:ClientOSError | 5 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| geo:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6332 |
| ConnectionRefusedError | 1017 |
| gaierror | 396 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | prefer | 365 | 0.86 | 1857 |
| zhangkai | 0.886 | prefer | 23 | 0.913 | 144 |
| mheidari-all | 0.743 | prefer | 96 | 0.667 | 23714 |
| Surfboard-tg-mixed | 0.446 | observe | 5 | 0.8 | 7171 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7647 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9352 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5676 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.161 | 19 | 0.105 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.105 | 2 | 17 | 19 |
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.667 | 64 | 32 | 96 |
| Surfboard-tg-mixed | 0.8 | 4 | 1 | 5 |
| Au1rxx-base64 | 0.86 | 314 | 51 | 365 |
| zhangkai | 0.913 | 21 | 2 | 23 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23714 | yes | 4.83 | 0 |
| SoliSpirit-all | 9352 | yes | 5.5 | 0 |
| Epodonios-all | 7647 | yes | 4.06 | 0 |
| Surfboard-tg-mixed | 7171 | yes | 5.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.68 | 0 |
| barry-far-vless | 5861 | yes | 3.36 | 0 |
| Surfboard-tg-vless | 5676 | yes | 5.34 | 0 |
| DeltaKronecker-all | 5009 | yes | 7.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 2.81 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 3.83 | 0 |

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
| 204 | 49 |
| cn-block | 27 |
| speed | 25 |
| geo | 6 |

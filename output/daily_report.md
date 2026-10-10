# AutoNodes 每日报告

生成时间：2026-10-10 12:00:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 97839 |
| 去重后节点数 | 27241 |
| TCP 可达数 | 3000 |
| 真测通过数 | 433 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27241 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 93.1 |
| geo | 1.2 |
| probe | 272.8 |
| real_test | 309.5 |
| tcp | 46.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 24 | 21 | 3 | 87.5% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 137 | 126 | 11 | 92.0% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 103 | 93 | 10 | 90.3% |
| vless | 243 | 174 | 69 | 71.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 26 |
| geo:ClientOSError | 17 |
| 204:ProxyError | 11 |
| 204:TimeoutError | 11 |
| 204:ProxyConnectionError | 8 |
| speed:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6427 |
| ConnectionRefusedError | 1024 |
| gaierror | 394 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.94 | prefer | 323 | 0.87 | 1820 |
| mheidari-all | 0.926 | prefer | 24 | 0.875 | 23754 |
| zhangkai | 0.886 | prefer | 23 | 0.913 | 144 |
| DeltaKronecker-all | 0.781 | prefer | 18 | 0.778 | 5009 |
| Surfboard-tg-mixed | 0.756 | prefer | 134 | 0.679 | 7103 |
| ermaozi-get_subscribe | 0.426 | observe | 4 | 1.0 | 653 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7579 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.679 | 91 | 43 | 134 |
| DeltaKronecker-all | 0.778 | 14 | 4 | 18 |
| Au1rxx-base64 | 0.87 | 281 | 42 | 323 |
| mheidari-all | 0.875 | 21 | 3 | 24 |
| zhangkai | 0.913 | 21 | 2 | 23 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23754 | yes | 7.88 | 0 |
| SoliSpirit-all | 9335 | yes | 1.37 | 0 |
| Epodonios-all | 7579 | yes | 6.22 | 0 |
| Surfboard-tg-mixed | 7103 | yes | 4.2 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.33 | 0 |
| barry-far-vless | 5884 | yes | 0.79 | 0 |
| Surfboard-tg-vless | 5620 | yes | 4.63 | 0 |
| DeltaKronecker-all | 5009 | yes | 6.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4999 | yes | 1.62 | 0 |
| mahdibland-V2RayAggregator | 4347 | yes | 3.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 32 |
| 204 | 31 |
| geo | 17 |
| speed | 15 |

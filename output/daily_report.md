# AutoNodes 每日报告

生成时间：2026-10-08 22:55:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98637 |
| 去重后节点数 | 27606 |
| TCP 可达数 | 3000 |
| 真测通过数 | 388 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27606 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 69.3 |
| geo | 1.3 |
| probe | 200.7 |
| real_test | 181.8 |
| tcp | 46.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 2 | 4 | 33.3% |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 116 | 111 | 5 | 95.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 73 | 70 | 3 | 95.9% |
| vless | 208 | 158 | 50 | 76.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 12 |
| geo:ClientOSError | 9 |
| speed:ClientOSError | 8 |
| speed:TimeoutError | 4 |
| 204:ProxyError | 4 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6564 |
| ConnectionRefusedError | 1014 |
| gaierror | 384 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | prefer | 311 | 0.9 | 1827 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| mheidari-all | 0.838 | prefer | 97 | 0.763 | 23588 |
| Surfboard-tg-mixed | 0.507 | observe | 8 | 0.75 | 7187 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 175 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7650 |

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
| downweight | ermaozi-get_subscribe | 0.226 | 6 | 0.333 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| ermaozi-get_subscribe | 0.333 | 2 | 4 | 6 |
| Surfboard-tg-mixed | 0.75 | 6 | 2 | 8 |
| mheidari-all | 0.763 | 74 | 23 | 97 |
| Au1rxx-base64 | 0.9 | 280 | 31 | 311 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23588 | yes | 3.98 | 0 |
| SoliSpirit-all | 9660 | yes | 1.61 | 0 |
| Epodonios-all | 7650 | yes | 2.19 | 0 |
| Surfboard-tg-mixed | 7187 | yes | 2.39 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.03 | 0 |
| barry-far-vless | 5923 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 5683 | yes | 3.18 | 0 |
| DeltaKronecker-all | 5197 | yes | 3.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 0.57 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 2.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 20 |
| 204 | 18 |
| geo | 14 |
| speed | 13 |

# AutoNodes 每日报告

生成时间：2026-07-02 13:53:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 77153 |
| 去重后节点数 | 23310 |
| TCP 可达数 | 3000 |
| 真测通过数 | 387 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23310 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 29.3 |
| geo | 1.4 |
| probe | 54.7 |
| real_test | 104.6 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 9 | 3 | 6 | 33.3% |
| shadowsocks | 127 | 101 | 26 | 79.5% |
| socks | 32 | 26 | 6 | 81.2% |
| trojan | 178 | 96 | 82 | 53.9% |
| vless | 184 | 121 | 63 | 65.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 64 |
| 204:ProxyError | 33 |
| 204:ClientOSError | 14 |
| 204:TimeoutError | 10 |
| geo:TimeoutError | 10 |
| cn-block:TimeoutError | 10 |
| geo:ClientOSError | 9 |
| cn-block:ClientOSError | 9 |
| speed:ProxyError | 8 |
| geo:ProxyError | 7 |
| cn-block:ProxyError | 6 |
| speed:TimeoutError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4353 |
| ConnectionRefusedError | 693 |
| gaierror | 171 |
| OSError | 151 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.813 | prefer | 40 | 0.825 | 78 |
| Surfboard-tg-mixed | 0.794 | prefer | 264 | 0.716 | 5750 |
| mheidari-all | 0.685 | observe | 84 | 0.607 | 16231 |
| DeltaKronecker-all | 0.631 | observe | 136 | 0.551 | 7467 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1162 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4254 |
| Epodonios-all | 0.255 | observe | 0 | None | 6611 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.12 | downweight | 6 | 0.0 | 0 | 1293 |
| ermaozi | 0.128 | observe | 1 | 0.0 | 0 | 6 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.12 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.551 | 75 | 61 | 136 |
| mheidari-all | 0.607 | 51 | 33 | 84 |
| Surfboard-tg-mixed | 0.716 | 189 | 75 | 264 |
| Au1rxx-base64 | 0.825 | 33 | 7 | 40 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16231 | yes | 3.49 | 0 |
| DeltaKronecker-all | 7467 | yes | 3.07 | 0 |
| SoliSpirit-all | 7019 | yes | 2.29 | 0 |
| Epodonios-all | 6611 | yes | 4.07 | 0 |
| Surfboard-tg-mixed | 5750 | yes | 2.41 | 0 |
| mahdibland-V2RayAggregator | 5365 | yes | 1.53 | 0 |
| barry-far-vless | 4895 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 4338 | yes | 2.22 | 0 |
| 10ium-ScrapeCategorize-Vless | 4254 | yes | 1.24 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 75 |
| 204 | 57 |
| geo | 26 |
| cn-block | 25 |

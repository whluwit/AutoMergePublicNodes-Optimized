# AutoNodes 每日报告

生成时间：2026-08-10 18:54:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84978 |
| 去重后节点数 | 24647 |
| TCP 可达数 | 3000 |
| 真测通过数 | 452 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24647 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 35.9 |
| geo | 1.3 |
| probe | 52.6 |
| real_test | 115.8 |
| tcp | 36.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 49 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 144 | 121 | 23 | 84.0% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 134 | 129 | 5 | 96.3% |
| vless | 221 | 132 | 89 | 59.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 26 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 18 |
| geo:ClientOSError | 12 |
| geo:TimeoutError | 5 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4559 |
| ConnectionRefusedError | 837 |
| gaierror | 291 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.983 | prefer | 49 | 1.0 | 67 |
| Au1rxx-base64 | 0.939 | prefer | 396 | 0.876 | 1614 |
| DeltaKronecker-all | 0.515 | observe | 106 | 0.434 | 5881 |
| Surfboard-tg-mixed | 0.461 | observe | 11 | 0.545 | 6152 |
| mheidari-all | 0.324 | observe | 8 | 0.375 | 20189 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 6803 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7537 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.375 | 3 | 5 | 8 |
| DeltaKronecker-all | 0.434 | 46 | 60 | 106 |
| Surfboard-tg-mixed | 0.545 | 6 | 5 | 11 |
| Au1rxx-base64 | 0.876 | 347 | 49 | 396 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 49 | 0 | 49 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20189 | yes | 3.02 | 0 |
| SoliSpirit-all | 7537 | yes | 3.03 | 0 |
| Epodonios-all | 6803 | yes | 1.2 | 0 |
| Surfboard-tg-mixed | 6152 | yes | 2.54 | 0 |
| DeltaKronecker-all | 5881 | yes | 3.78 | 0 |
| barry-far-vless | 5417 | yes | 1.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.75 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 1.06 | 0 |
| Surfboard-tg-vless | 5085 | yes | 3.16 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.07 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 52 |
| cn-block | 25 |
| speed | 23 |
| geo | 19 |

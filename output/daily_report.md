# AutoNodes 每日报告

生成时间：2026-08-10 01:24:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 86098 |
| 去重后节点数 | 23943 |
| TCP 可达数 | 3000 |
| 真测通过数 | 543 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23943 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 43.5 |
| geo | 1.4 |
| probe | 52.7 |
| real_test | 126.9 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 155 | 150 | 5 | 96.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 140 | 128 | 12 | 91.4% |
| vless | 501 | 224 | 277 | 44.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 122 |
| speed:TimeoutError | 58 |
| geo:ClientOSError | 48 |
| cn-block:TimeoutError | 30 |
| speed:ClientOSError | 22 |
| 204:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4407 |
| ConnectionRefusedError | 845 |
| gaierror | 389 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Au1rxx-base64 | 0.953 | prefer | 443 | 0.887 | 1698 |
| Surfboard-tg-mixed | 0.711 | prefer | 139 | 0.633 | 6612 |
| mheidari-all | 0.27 | observe | 177 | 0.186 | 20202 |
| nscl5-all | 0.265 | observe | 2 | 0.5 | 1442 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5505 |
| Epodonios-all | 0.255 | observe | 0 | None | 7220 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7572 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5465 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.228 | 59 | 0.136 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.136 | 8 | 51 | 59 |
| mheidari-all | 0.186 | 33 | 144 | 177 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.633 | 88 | 51 | 139 |
| Au1rxx-base64 | 0.887 | 393 | 50 | 443 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20202 | yes | 3.47 | 0 |
| SoliSpirit-all | 7572 | yes | 1.29 | 0 |
| Epodonios-all | 7220 | yes | 1.89 | 0 |
| Surfboard-tg-mixed | 6612 | yes | 2.45 | 0 |
| barry-far-vless | 5808 | yes | 0.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 5505 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 5465 | yes | 2.28 | 0 |
| mahdibland-V2RayAggregator | 5189 | yes | 2.02 | 0 |
| DeltaKronecker-all | 4998 | yes | 3.4 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.1 | 0 |

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
| geo | 171 |
| speed | 80 |
| cn-block | 33 |
| 204 | 14 |

# AutoNodes 每日报告

生成时间：2026-09-14 17:40:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 84471 |
| 去重后节点数 | 22923 |
| TCP 可达数 | 3000 |
| 真测通过数 | 404 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22923 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 77.3 |
| geo | 1.5 |
| probe | 239.6 |
| real_test | 196.8 |
| tcp | 37.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 52 | 30 | 22 | 57.7% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 142 | 132 | 10 | 93.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 11 | 8 | 3 | 72.7% |
| vless | 264 | 216 | 48 | 81.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 21 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 13 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 4 |
| geo:TimeoutError | 3 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4376 |
| ConnectionRefusedError | 860 |
| gaierror | 468 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | prefer | 282 | 0.911 | 1619 |
| DeltaKronecker-all | 0.913 | prefer | 22 | 0.864 | 5972 |
| Surfboard-tg-mixed | 0.811 | prefer | 91 | 0.736 | 7478 |
| mheidari-all | 0.807 | prefer | 42 | 0.738 | 15899 |
| ermaozi | 0.69 | observe | 41 | 0.683 | 393 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 145 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 7933 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8881 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.13 | 10 | 0.1 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.1 | 1 | 9 | 10 |
| ermaozi | 0.683 | 28 | 13 | 41 |
| Surfboard-tg-mixed | 0.736 | 67 | 24 | 91 |
| mheidari-all | 0.738 | 31 | 11 | 42 |
| DeltaKronecker-all | 0.864 | 19 | 3 | 22 |
| Au1rxx-base64 | 0.911 | 257 | 25 | 282 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15899 | yes | 5.57 | 0 |
| SoliSpirit-all | 8881 | yes | 2.82 | 0 |
| Epodonios-all | 7933 | yes | 3.75 | 0 |
| Surfboard-tg-mixed | 7478 | yes | 4.82 | 0 |
| barry-far-vless | 6293 | yes | 2.08 | 0 |
| Surfboard-tg-vless | 6074 | yes | 3.98 | 0 |
| DeltaKronecker-all | 5972 | yes | 5.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 1.86 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 2.45 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.18 | 0 |

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
| 204 | 39 |
| cn-block | 19 |
| geo | 15 |
| speed | 13 |

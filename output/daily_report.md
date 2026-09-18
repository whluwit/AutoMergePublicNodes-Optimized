# AutoNodes 每日报告

生成时间：2026-09-18 15:51:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83888 |
| 去重后节点数 | 23080 |
| TCP 可达数 | 3000 |
| 真测通过数 | 400 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23080 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 80.1 |
| geo | 1.4 |
| probe | 213.3 |
| real_test | 223.4 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 33 | 21 | 12 | 63.6% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 180 | 152 | 28 | 84.4% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 3 | 3 | 0 | 100.0% |
| vless | 308 | 210 | 98 | 68.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 25 |
| geo:ClientOSError | 21 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 16 |
| geo:TimeoutError | 16 |
| speed:ClientOSError | 13 |
| cn-block:ClientOSError | 9 |
| speed:TimeoutError | 8 |
| cn-block:ProxyError | 4 |
| 204:ProxyConnectionError | 3 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38166: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5282 |
| ConnectionRefusedError | 810 |
| gaierror | 430 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.926 | prefer | 260 | 0.865 | 1596 |
| ermaozi | 0.791 | prefer | 25 | 0.8 | 325 |
| Surfboard-tg-mixed | 0.733 | prefer | 148 | 0.655 | 7397 |
| mheidari-all | 0.726 | prefer | 63 | 0.651 | 15758 |
| DeltaKronecker-all | 0.551 | observe | 32 | 0.469 | 6040 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5076 |
| Epodonios-all | 0.255 | observe | 0 | None | 7860 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8961 |

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
| downweight | ermaozi-get_subscribe | 0.136 | 8 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.125 | 1 | 7 | 8 |
| DeltaKronecker-all | 0.469 | 15 | 17 | 32 |
| mheidari-all | 0.651 | 41 | 22 | 63 |
| Surfboard-tg-mixed | 0.655 | 97 | 51 | 148 |
| ermaozi | 0.8 | 20 | 5 | 25 |
| Au1rxx-base64 | 0.865 | 225 | 35 | 260 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15758 | yes | 5.38 | 0 |
| SoliSpirit-all | 8961 | yes | 3.15 | 0 |
| Epodonios-all | 7860 | yes | 4.81 | 0 |
| Surfboard-tg-mixed | 7397 | yes | 4.01 | 0 |
| barry-far-vless | 6127 | yes | 1.58 | 0 |
| DeltaKronecker-all | 6040 | yes | 4.04 | 0 |
| Surfboard-tg-vless | 5909 | yes | 3.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 0.75 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 2.27 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.05 | 0 |

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
| geo | 37 |
| cn-block | 29 |
| speed | 23 |
| sing-box exited 1 | 1 |

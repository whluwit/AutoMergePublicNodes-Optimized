# AutoNodes 每日报告

生成时间：2026-09-18 20:29:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 87606 |
| 去重后节点数 | 25089 |
| TCP 可达数 | 3000 |
| 真测通过数 | 425 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25089 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 92.7 |
| geo | 1.4 |
| probe | 250.8 |
| real_test | 227.5 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 32 | 22 | 10 | 68.8% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 161 | 149 | 12 | 92.5% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 20 | 14 | 6 | 70.0% |
| vless | 340 | 219 | 121 | 64.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 39 |
| cn-block:ClientOSError | 26 |
| cn-block:TimeoutError | 18 |
| 204:TimeoutError | 16 |
| 204:ProxyError | 15 |
| geo:TimeoutError | 14 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6136 |
| ConnectionRefusedError | 899 |
| gaierror | 327 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.925 | prefer | 277 | 0.863 | 1615 |
| ermaozi | 0.828 | prefer | 25 | 0.84 | 325 |
| Surfboard-tg-mixed | 0.755 | prefer | 158 | 0.677 | 7333 |
| mheidari-all | 0.613 | observe | 103 | 0.534 | 19747 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4241 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5076 |
| Epodonios-all | 0.255 | observe | 0 | None | 7771 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8922 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5838 |

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
| downweight | ermaozi-get_subscribe | 0.142 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.534 | 55 | 48 | 103 |
| Surfboard-tg-mixed | 0.677 | 107 | 51 | 158 |
| ermaozi | 0.84 | 21 | 4 | 25 |
| Au1rxx-base64 | 0.863 | 239 | 38 | 277 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19747 | yes | 3.16 | 0 |
| SoliSpirit-all | 8922 | yes | 2.03 | 0 |
| Epodonios-all | 7771 | yes | 2.17 | 0 |
| Surfboard-tg-mixed | 7333 | yes | 2.4 | 0 |
| barry-far-vless | 6051 | yes | 3.3 | 0 |
| DeltaKronecker-all | 6040 | yes | 3.38 | 0 |
| Surfboard-tg-vless | 5838 | yes | 2.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 5076 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 1.97 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.83 | 0 |

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
| geo | 54 |
| cn-block | 46 |
| 204 | 34 |
| speed | 18 |

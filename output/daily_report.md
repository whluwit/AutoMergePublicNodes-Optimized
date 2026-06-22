# AutoNodes 每日报告

生成时间：2026-06-22 05:07:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 74096 |
| 去重后节点数 | 22723 |
| TCP 可达数 | 3000 |
| 真测通过数 | 633 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22723 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 27.5 |
| geo | 1.3 |
| probe | 52.6 |
| real_test | 132.3 |
| tcp | 30.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 98 | 94 | 4 | 95.9% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 221 | 178 | 43 | 80.5% |
| vless | 439 | 286 | 153 | 65.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 78 |
| geo:TimeoutError | 69 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 8 |
| cn-block:TimeoutError | 8 |
| 204:TimeoutError | 8 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4410 |
| ConnectionRefusedError | 571 |
| gaierror | 115 |
| OSError | 107 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.991 | prefer | 69 | 1.0 | 131 |
| mheidari-all | 0.865 | prefer | 380 | 0.787 | 14957 |
| Au1rxx-base64 | 0.797 | prefer | 108 | 0.796 | 149 |
| DeltaKronecker-all | 0.726 | prefer | 269 | 0.647 | 7452 |
| Surfboard-tg-mixed | 0.373 | observe | 5 | 0.6 | 4738 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4494 |
| Epodonios-all | 0.255 | observe | 0 | None | 7244 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3980 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 5 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.6 | 3 | 2 | 5 |
| DeltaKronecker-all | 0.647 | 174 | 95 | 269 |
| mheidari-all | 0.787 | 299 | 81 | 380 |
| Au1rxx-base64 | 0.796 | 86 | 22 | 108 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 69 | 0 | 69 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14957 | yes | 3.61 | 0 |
| DeltaKronecker-all | 7452 | yes | 3.37 | 0 |
| Epodonios-all | 7244 | yes | 2.61 | 0 |
| SoliSpirit-all | 6973 | yes | 2.15 | 0 |
| Surfboard-tg-mixed | 4738 | yes | 2.34 | 0 |
| mahdibland-V2RayAggregator | 4505 | yes | 1.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 4494 | yes | 1.85 | 0 |
| barry-far-vless | 4479 | yes | 1.06 | 0 |
| MatinGhanbari-all-sub | 3980 | yes | 1.65 | 0 |
| Surfboard-tg-vless | 3632 | yes | 1.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 85 |
| geo | 84 |
| 204 | 21 |
| cn-block | 10 |

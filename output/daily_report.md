# AutoNodes 每日报告

生成时间：2026-06-25 02:53:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 75407 |
| 去重后节点数 | 22420 |
| TCP 可达数 | 3000 |
| 真测通过数 | 539 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22420 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 29.9 |
| geo | 1.4 |
| probe | 55.6 |
| real_test | 136.2 |
| tcp | 29.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 105 | 92 | 13 | 87.6% |
| trojan | 144 | 119 | 25 | 82.6% |
| vless | 634 | 285 | 349 | 45.0% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 151 |
| geo:TimeoutError | 141 |
| geo:ClientOSError | 35 |
| speed:TimeoutError | 28 |
| cn-block:TimeoutError | 9 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4155 |
| ConnectionRefusedError | 624 |
| gaierror | 193 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Surfboard-tg-mixed | 0.852 | prefer | 292 | 0.774 | 5184 |
| mheidari-all | 0.706 | prefer | 271 | 0.627 | 15461 |
| Au1rxx-base64 | 0.697 | observe | 76 | 0.697 | 119 |
| nscl5-all | 0.357 | observe | 2 | 1.0 | 1136 |
| DeltaKronecker-all | 0.288 | observe | 248 | 0.206 | 6644 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4745 |
| Epodonios-all | 0.255 | observe | 0 | None | 7785 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ISVvpn | 0.175 | observe | 0 | None | 0 | 10 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.206 | 51 | 197 | 248 |
| mheidari-all | 0.627 | 170 | 101 | 271 |
| Au1rxx-base64 | 0.697 | 53 | 23 | 76 |
| Surfboard-tg-mixed | 0.774 | 226 | 66 | 292 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15461 | yes | 3.43 | 0 |
| Epodonios-all | 7785 | yes | 2.49 | 0 |
| SoliSpirit-all | 7180 | yes | 2.28 | 0 |
| DeltaKronecker-all | 6644 | yes | 3.96 | 0 |
| Surfboard-tg-mixed | 5184 | yes | 2.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4745 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4710 | yes | 0.64 | 0 |
| barry-far-vless | 4704 | yes | 1.46 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.55 | 0 |
| Surfboard-tg-vless | 3909 | yes | 1.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 180 |
| geo | 177 |
| 204 | 15 |
| cn-block | 15 |

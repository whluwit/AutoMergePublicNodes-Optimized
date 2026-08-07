# AutoNodes 每日报告

生成时间：2026-08-07 02:30:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 89263 |
| 去重后节点数 | 24750 |
| TCP 可达数 | 3000 |
| 真测通过数 | 443 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24750 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 38.6 |
| geo | 1.3 |
| probe | 53.1 |
| real_test | 117.0 |
| tcp | 36.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 159 | 153 | 6 | 96.2% |
| socks | 16 | 13 | 3 | 81.2% |
| trojan | 176 | 158 | 18 | 89.8% |
| vless | 428 | 77 | 351 | 18.0% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 202 |
| geo:ClientOSError | 63 |
| speed:TimeoutError | 56 |
| speed:ClientOSError | 40 |
| 204:ClientOSError | 4 |
| 204:TimeoutError | 4 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| cn-block:TimeoutError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4749 |
| ConnectionRefusedError | 845 |
| gaierror | 326 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 345 | 0.977 | 1260 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.486 | observe | 30 | 0.4 | 5948 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 5184 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5219 |
| nscl5-all | 0.326 | observe | 1 | 1.0 | 1772 |
| DeltaKronecker-all | 0.294 | observe | 40 | 0.2 | 5897 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6478 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.243 | 378 | 0.161 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.161 | 61 | 317 | 378 |
| DeltaKronecker-all | 0.2 | 8 | 32 | 40 |
| Surfboard-tg-mixed | 0.4 | 12 | 18 | 30 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.977 | 337 | 8 | 345 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20680 | yes | 5.36 | 0 |
| SoliSpirit-all | 7798 | yes | 2.27 | 0 |
| Epodonios-all | 6478 | yes | 5.81 | 0 |
| Surfboard-tg-mixed | 5948 | yes | 3.16 | 0 |
| DeltaKronecker-all | 5897 | yes | 3.55 | 0 |
| mahdibland-V2RayAggregator | 5225 | yes | 3.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 5219 | yes | 0.94 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 1.78 | 0 |
| barry-far-vless | 5038 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 4749 | yes | 2.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 265 |
| speed | 97 |
| 204 | 11 |
| cn-block | 6 |

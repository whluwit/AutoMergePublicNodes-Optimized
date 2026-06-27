# AutoNodes 每日报告

生成时间：2026-06-27 02:47:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76051 |
| 去重后节点数 | 22904 |
| TCP 可达数 | 3000 |
| 真测通过数 | 506 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22904 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 41.1 |
| geo | 1.4 |
| probe | 51.9 |
| real_test | 98.5 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 18 | 18 | 0 | 100.0% |
| hysteria2 | 6 | 4 | 2 | 66.7% |
| shadowsocks | 126 | 114 | 12 | 90.5% |
| socks | 25 | 23 | 2 | 92.0% |
| trojan | 142 | 127 | 15 | 89.4% |
| vless | 479 | 217 | 262 | 45.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 133 |
| geo:TimeoutError | 78 |
| geo:ClientOSError | 35 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 8 |
| speed:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 1 |
| geo:status | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4363 |
| ConnectionRefusedError | 641 |
| gaierror | 162 |
| OSError | 139 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.909 | prefer | 325 | 0.831 | 5149 |
| snakem982 | 0.89 | prefer | 18 | 1.0 | 39 |
| mheidari-all | 0.739 | prefer | 206 | 0.66 | 16221 |
| Au1rxx-base64 | 0.64 | observe | 42 | 0.643 | 100 |
| nscl5-all | 0.359 | observe | 2 | 1.0 | 1186 |
| DeltaKronecker-all | 0.342 | observe | 200 | 0.26 | 6283 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7720 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7255 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.147 | observe | 2 | 0.0 | 0 | 1084 |
| 10ium-ScrapeCategorize-Vless | 0.17 | observe | 3 | 0.0 | 0 | 4567 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.26 | 52 | 148 | 200 |
| Au1rxx-base64 | 0.643 | 27 | 15 | 42 |
| mheidari-all | 0.66 | 136 | 70 | 206 |
| Surfboard-tg-mixed | 0.831 | 270 | 55 | 325 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16221 | yes | 3.63 | 0 |
| Epodonios-all | 7720 | yes | 1.85 | 0 |
| SoliSpirit-all | 7255 | yes | 2.47 | 0 |
| DeltaKronecker-all | 6283 | yes | 3.4 | 0 |
| mahdibland-V2RayAggregator | 5248 | yes | 2.16 | 0 |
| Surfboard-tg-mixed | 5149 | yes | 3.17 | 0 |
| 10ium-ScrapeCategorize-Vless | 4567 | yes | 1.49 | 0 |
| barry-far-vless | 4565 | yes | 1.69 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 1.86 | 0 |
| Surfboard-tg-vless | 3785 | yes | 2.07 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 140 |
| geo | 114 |
| 204 | 20 |
| cn-block | 19 |

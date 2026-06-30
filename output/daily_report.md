# AutoNodes 每日报告

生成时间：2026-06-30 09:30:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 75285 |
| 去重后节点数 | 23005 |
| TCP 可达数 | 3000 |
| 真测通过数 | 454 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23005 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 37.8 |
| geo | 1.4 |
| probe | 55.3 |
| real_test | 108.4 |
| tcp | 29.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 117 | 94 | 23 | 80.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 174 | 108 | 66 | 62.1% |
| vless | 392 | 209 | 183 | 53.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 139 |
| geo:TimeoutError | 32 |
| 204:TimeoutError | 23 |
| 204:ClientOSError | 19 |
| geo:ClientOSError | 17 |
| cn-block:TimeoutError | 11 |
| 204:ProxyError | 10 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| speed:ProxyError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4216 |
| ConnectionRefusedError | 611 |
| gaierror | 199 |
| OSError | 132 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.794 | prefer | 41 | 0.805 | 95 |
| Surfboard-tg-mixed | 0.712 | prefer | 321 | 0.632 | 5386 |
| mheidari-all | 0.648 | observe | 227 | 0.568 | 15701 |
| DeltaKronecker-all | 0.585 | observe | 97 | 0.505 | 7352 |
| xiaoji235-airport-v2ray-all | 0.303 | observe | 1 | 1.0 | 1204 |
| nscl5-all | 0.3 | observe | 1 | 1.0 | 1136 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4139 |
| Epodonios-all | 0.255 | observe | 0 | None | 6386 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.505 | 49 | 48 | 97 |
| mheidari-all | 0.568 | 129 | 98 | 227 |
| Surfboard-tg-mixed | 0.632 | 203 | 118 | 321 |
| Au1rxx-base64 | 0.805 | 33 | 8 | 41 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15701 | yes | 3.27 | 0 |
| DeltaKronecker-all | 7352 | yes | 3.45 | 0 |
| SoliSpirit-all | 6946 | yes | 2.0 | 0 |
| Epodonios-all | 6386 | yes | 3.48 | 0 |
| Surfboard-tg-mixed | 5386 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 5353 | yes | 1.86 | 0 |
| barry-far-vless | 4573 | yes | 0.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 4139 | yes | 1.34 | 0 |
| MatinGhanbari-all-sub | 3981 | yes | 1.61 | 0 |
| Surfboard-tg-vless | 3959 | yes | 2.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 151 |
| 204 | 52 |
| geo | 50 |
| cn-block | 21 |

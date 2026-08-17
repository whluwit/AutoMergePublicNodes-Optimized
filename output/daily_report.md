# AutoNodes 每日报告

生成时间：2026-08-17 12:41:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83031 |
| 去重后节点数 | 23188 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1295 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23188 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 39.3 |
| geo | 0.9 |
| probe | 83.9 |
| real_test | 267.7 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 24 | 21 | 3 | 87.5% |
| shadowsocks | 138 | 129 | 9 | 93.5% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 782 | 781 | 1 | 99.9% |
| vless | 325 | 231 | 94 | 71.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 23 |
| speed:TimeoutError | 23 |
| geo:TimeoutError | 14 |
| cn-block:TimeoutError | 14 |
| 204:ProxyError | 10 |
| speed:ClientOSError | 8 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 5 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4632 |
| ConnectionRefusedError | 815 |
| gaierror | 321 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 879 | 0.945 | 1983 |
| mheidari-all | 1.0 | prefer | 225 | 0.991 | 17057 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.757 | prefer | 162 | 0.679 | 6086 |
| DeltaKronecker-all | 0.314 | observe | 9 | 0.333 | 6368 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 194 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5085 |
| Epodonios-all | 0.255 | observe | 0 | None | 6645 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7827 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.333 | 3 | 6 | 9 |
| Surfboard-tg-mixed | 0.679 | 110 | 52 | 162 |
| Au1rxx-base64 | 0.945 | 831 | 48 | 879 |
| mheidari-all | 0.991 | 223 | 2 | 225 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17057 | yes | 4.47 | 0 |
| SoliSpirit-all | 7827 | yes | 4.56 | 0 |
| Epodonios-all | 6645 | yes | 5.11 | 0 |
| DeltaKronecker-all | 6368 | yes | 4.25 | 0 |
| Surfboard-tg-mixed | 6086 | yes | 3.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 5085 | yes | 2.99 | 0 |
| barry-far-vless | 4992 | yes | 3.88 | 0 |
| Surfboard-tg-vless | 4669 | yes | 3.46 | 0 |
| mahdibland-V2RayAggregator | 4046 | yes | 3.3 | 0 |
| MatinGhanbari-all-sub | 3987 | yes | 2.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 35 |
| speed | 31 |
| cn-block | 23 |
| geo | 19 |

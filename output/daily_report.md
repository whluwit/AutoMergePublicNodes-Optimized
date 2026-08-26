# AutoNodes 每日报告

生成时间：2026-08-26 06:44:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77676 |
| 去重后节点数 | 22059 |
| TCP 可达数 | 3000 |
| 真测通过数 | 600 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22059 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 39.4 |
| geo | 1.4 |
| probe | 58.2 |
| real_test | 136.2 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 25 | 24 | 1 | 96.0% |
| shadowsocks | 183 | 166 | 17 | 90.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 49 | 39 | 10 | 79.6% |
| vless | 515 | 345 | 170 | 67.0% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 54 |
| speed:TimeoutError | 53 |
| cn-block:TimeoutError | 24 |
| geo:ClientOSError | 20 |
| speed:ClientOSError | 19 |
| 204:TimeoutError | 15 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4912 |
| ConnectionRefusedError | 837 |
| gaierror | 306 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.926 | prefer | 23 | 0.957 | 144 |
| Au1rxx-base64 | 0.925 | prefer | 393 | 0.847 | 1986 |
| Surfboard-tg-mixed | 0.829 | prefer | 185 | 0.751 | 6366 |
| DeltaKronecker-all | 0.626 | observe | 106 | 0.547 | 6107 |
| mheidari-all | 0.538 | observe | 81 | 0.457 | 14091 |
| nscl5-all | 0.475 | observe | 5 | 1.0 | 887 |
| 10ium-ScrapeCategorize-Vless | 0.391 | observe | 2 | 1.0 | 4825 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 191 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.457 | 37 | 44 | 81 |
| DeltaKronecker-all | 0.547 | 58 | 48 | 106 |
| Surfboard-tg-mixed | 0.751 | 139 | 46 | 185 |
| Au1rxx-base64 | 0.847 | 333 | 60 | 393 |
| zhangkai | 0.957 | 22 | 1 | 23 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14091 | yes | 4.13 | 0 |
| SoliSpirit-all | 6976 | yes | 4.51 | 0 |
| Epodonios-all | 6845 | yes | 4.42 | 0 |
| Surfboard-tg-mixed | 6366 | yes | 3.35 | 0 |
| DeltaKronecker-all | 6107 | yes | 4.64 | 0 |
| barry-far-vless | 5459 | yes | 2.28 | 0 |
| Surfboard-tg-vless | 5211 | yes | 5.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 2.5 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.57 | 0 |
| mahdibland-V2RayAggregator | 3981 | yes | 1.4 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 75 |
| speed | 72 |
| cn-block | 29 |
| 204 | 25 |

# AutoNodes 每日报告

生成时间：2026-08-21 12:42:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 95291 |
| 去重后节点数 | 24832 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1152 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24832 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 26.3 |
| geo | 0.8 |
| probe | 68.2 |
| real_test | 221.7 |
| tcp | 39.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 183 | 165 | 18 | 90.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 641 | 624 | 17 | 97.3% |
| vless | 328 | 226 | 102 | 68.9% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 42 |
| geo:TimeoutError | 19 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 16 |
| speed:TimeoutError | 15 |
| 204:ClientOSError | 12 |
| cn-block:ClientOSError | 7 |
| speed:ClientOSError | 6 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5438 |
| ConnectionRefusedError | 936 |
| gaierror | 350 |
| OSError | 225 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 715 | 0.955 | 1897 |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.915 | prefer | 113 | 0.841 | 6408 |
| mheidari-all | 0.831 | prefer | 336 | 0.753 | 22031 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| DeltaKronecker-all | 0.372 | observe | 9 | 0.444 | 6250 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 192 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5148 |
| Epodonios-all | 0.255 | observe | 0 | None | 7104 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.444 | 4 | 5 | 9 |
| mheidari-all | 0.753 | 253 | 83 | 336 |
| Surfboard-tg-mixed | 0.841 | 95 | 18 | 113 |
| Au1rxx-base64 | 0.955 | 683 | 32 | 715 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22031 | yes | 4.42 | 0 |
| SoliSpirit-all | 7205 | yes | 3.48 | 0 |
| Epodonios-all | 7104 | yes | 5.19 | 0 |
| Surfboard-tg-mixed | 6408 | yes | 5.64 | 0 |
| DeltaKronecker-all | 6250 | yes | 6.67 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 2.1 | 0 |
| barry-far-vless | 5469 | yes | 1.07 | 0 |
| Surfboard-tg-vless | 5150 | yes | 5.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 0.72 | 0 |
| mahdibland-V2RayAggregator | 4647 | yes | 2.81 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 61 |
| 204 | 33 |
| cn-block | 24 |
| speed | 21 |

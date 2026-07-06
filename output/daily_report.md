# AutoNodes 每日报告

生成时间：2026-07-06 02:47:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78646 |
| 去重后节点数 | 23997 |
| TCP 可达数 | 3000 |
| 真测通过数 | 450 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23997 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 39.9 |
| geo | 1.3 |
| probe | 46.0 |
| real_test | 87.1 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 146 | 133 | 13 | 91.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 258 | 240 | 18 | 93.0% |
| vless | 112 | 32 | 80 | 28.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 36 |
| speed:ClientOSError | 32 |
| geo:ClientOSError | 14 |
| 204:ClientOSError | 10 |
| cn-block:TimeoutError | 8 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 3 |
| 204:TimeoutError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4510 |
| ConnectionRefusedError | 766 |
| OSError | 158 |
| gaierror | 102 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.995 | prefer | 127 | 0.921 | 5941 |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.866 | prefer | 34 | 0.882 | 128 |
| DeltaKronecker-all | 0.814 | prefer | 235 | 0.736 | 7739 |
| mheidari-all | 0.799 | prefer | 126 | 0.722 | 16171 |
| nscl5-all | 0.321 | observe | 1 | 1.0 | 1651 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| ermaozi | 0.256 | observe | 1 | 1.0 | 27 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4662 |
| Epodonios-all | 0.255 | observe | 0 | None | 7009 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.722 | 91 | 35 | 126 |
| DeltaKronecker-all | 0.736 | 173 | 62 | 235 |
| Au1rxx-base64 | 0.882 | 30 | 4 | 34 |
| Surfboard-tg-mixed | 0.921 | 117 | 10 | 127 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16171 | yes | 3.79 | 0 |
| DeltaKronecker-all | 7739 | yes | 3.46 | 0 |
| Epodonios-all | 7009 | yes | 1.74 | 0 |
| SoliSpirit-all | 6691 | yes | 2.5 | 0 |
| Surfboard-tg-mixed | 5941 | yes | 2.78 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 2.07 | 0 |
| barry-far-vless | 5045 | yes | 1.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4662 | yes | 1.22 | 0 |
| Surfboard-tg-vless | 4343 | yes | 3.35 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.72 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 50 |
| speed | 37 |
| 204 | 13 |
| cn-block | 12 |

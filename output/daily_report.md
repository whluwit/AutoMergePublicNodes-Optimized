# AutoNodes Daily Report

Generated at: 2026-06-21 14:30:48

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 104/107 |
| Cleanup disable/downweight | 0/0 |
| Cleanup prefer/observe | 4/103 |
| Raw nodes | 73459 |
| Dedup nodes | 21999 |
| TCP ok | 842 |
| Real ok | 682 |
| Verified output | 300 |
| Global output | 300 |
| All output | 21999 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 4.5 |
| generate | 65.4 |
| geo | 1.3 |
| probe | 100.8 |
| real_test | 212.3 |
| tcp | 63.7 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 113 | 99 | 14 | 87.6% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 64 | 44 | 20 | 68.8% |
| vless | 588 | 462 | 126 | 78.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| speed:ClientOSError | 43 |
| cn-block:TimeoutError | 28 |
| 204:TimeoutError | 24 |
| 204:ProxyError | 16 |
| geo:TimeoutError | 13 |
| speed:TimeoutError | 12 |
| geo:ClientOSError | 8 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 3253 |
| ConnectionRefusedError | 647 |
| gaierror | 391 |
| OSError | 109 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.991 | prefer | 69 | 1.0 | 131 |
| Au1rxx-base64 | 0.898 | prefer | 82 | 0.902 | 126 |
| mheidari-all | 0.891 | prefer | 263 | 0.814 | 14966 |
| Surfboard-tg-mixed | 0.858 | prefer | 385 | 0.779 | 4933 |
| DeltaKronecker-all | 0.617 | observe | 39 | 0.538 | 6748 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.303 | observe | 1 | 1.0 | 1204 |
| abc-configs-readme-latest30 | 0.256 | observe | 1 | 1.0 | 20 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4494 |
| Epodonios-all | 0.255 | observe | 0 | None | 7303 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 5 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.538 | 21 | 18 | 39 |
| Surfboard-tg-mixed | 0.779 | 300 | 85 | 385 |
| mheidari-all | 0.814 | 214 | 49 | 263 |
| Au1rxx-base64 | 0.902 | 74 | 8 | 82 |
| abc-configs-readme-latest30 | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 69 | 0 | 69 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 14966 | yes | 3.0 | 0 |
| Epodonios-all | 7303 | yes | 1.9 | 0 |
| SoliSpirit-all | 6910 | yes | 2.45 | 0 |
| DeltaKronecker-all | 6748 | yes | 2.99 | 0 |
| Surfboard-tg-mixed | 4933 | yes | 2.03 | 0 |
| mahdibland-V2RayAggregator | 4510 | yes | 1.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4494 | yes | 1.44 | 0 |
| barry-far-vless | 4385 | yes | 1.09 | 0 |
| MatinGhanbari-all-sub | 3978 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 3718 | yes | 2.6 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Real-test error alerts
| Error | Count |
| --- | --- |
| speed | 58 |
| 204 | 44 |
| cn-block | 35 |
| geo | 23 |

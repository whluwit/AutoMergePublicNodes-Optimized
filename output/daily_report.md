# AutoNodes Daily Report

Generated at: 2026-06-20 01:58:55

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 105/107 |
| Cleanup disable/downweight | 0/1 |
| Cleanup prefer/observe | 3/103 |
| Raw nodes | 73168 |
| Dedup nodes | 22175 |
| TCP ok | 975 |
| Real ok | 703 |
| Verified output | 300 |
| Global output | 300 |
| All output | 22175 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 4.5 |
| generate | 34.5 |
| geo | 1.3 |
| probe | 104.1 |
| real_test | 212.6 |
| tcp | 62.7 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 116 | 106 | 10 | 91.4% |
| socks | 2 | 2 | 0 | 100.0% |
| trojan | 114 | 90 | 24 | 78.9% |
| vless | 713 | 475 | 238 | 66.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| geo:TimeoutError | 94 |
| speed:ClientOSError | 82 |
| cn-block:TimeoutError | 32 |
| speed:TimeoutError | 24 |
| geo:ClientOSError | 16 |
| 204:TimeoutError | 7 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 1 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 3092 |
| ConnectionRefusedError | 679 |
| gaierror | 448 |
| OSError | 84 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | prefer | 25 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.924 | prefer | 441 | 0.846 | 5022 |
| mheidari-all | 0.824 | prefer | 330 | 0.745 | 14629 |
| Au1rxx-base64 | 0.671 | observe | 40 | 0.675 | 100 |
| DeltaKronecker-all | 0.317 | observe | 129 | 0.233 | 6989 |
| nscl5-all | 0.309 | observe | 1 | 1.0 | 1360 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7454 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3982 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6670 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-configfa | 0.133 | observe | 1 | 0.0 | 0 | 129 |
| ninja-vless | 0.14 | downweight | 6 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 7 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## Source Cleanup Suggestions

| Bucket | Source | Score | Tested | Pass Rate | Dead | Reason |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.14 | 6 | 0.0 | 0 | low score with tested >= 5 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| tg-configfa | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.233 | 30 | 99 | 129 |
| Au1rxx-base64 | 0.675 | 27 | 13 | 40 |
| mheidari-all | 0.745 | 246 | 84 | 330 |
| Surfboard-tg-mixed | 0.846 | 373 | 68 | 441 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 25 | 0 | 25 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 14629 | yes | 3.53 | 0 |
| Epodonios-all | 7454 | yes | 2.85 | 0 |
| DeltaKronecker-all | 6989 | yes | 4.47 | 0 |
| SoliSpirit-all | 6670 | yes | 2.39 | 0 |
| Surfboard-tg-mixed | 5022 | yes | 1.97 | 0 |
| mahdibland-V2RayAggregator | 4527 | yes | 1.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 4458 | yes | 1.64 | 0 |
| barry-far-vless | 4406 | yes | 1.4 | 0 |
| MatinGhanbari-all-sub | 3982 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 3739 | yes | 1.81 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Real-test error alerts
| Error | Count |
| --- | --- |
| geo | 111 |
| speed | 106 |
| cn-block | 37 |
| 204 | 18 |

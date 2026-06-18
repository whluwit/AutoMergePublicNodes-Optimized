# AutoNodes Daily Report

Generated at: 2026-06-18 04:44:10

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 44/44 |
| Cleanup disable/downweight | 0/1 |
| Cleanup prefer/observe | 4/39 |
| Raw nodes | 67675 |
| Dedup nodes | 22191 |
| TCP ok | 807 |
| Real ok | 614 |
| Verified output | 300 |
| Global output | 300 |
| All output | 22191 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 2.0 |
| generate | 16.7 |
| geo | 1.2 |
| probe | 103.2 |
| real_test | 35.9 |
| tcp | 57.1 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 110 | 103 | 7 | 93.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 139 | 119 | 20 | 85.6% |
| vless | 524 | 359 | 165 | 68.5% |
| vmess | 5 | 5 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| general:unknown | 179 |
| speed:ClientOSError | 3 |
| 204:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 2 |
| speed:TimeoutError | 2 |
| 204:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 2958 |
| ConnectionRefusedError | 622 |
| gaierror | 375 |
| OSError | 60 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | prefer | 25 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.926 | prefer | 356 | 0.848 | 4586 |
| Au1rxx-base64 | 0.868 | prefer | 78 | 0.872 | 126 |
| mheidari-all | 0.845 | prefer | 215 | 0.767 | 13927 |
| DeltaKronecker-all | 0.493 | observe | 124 | 0.411 | 7763 |
| Epodonios-all | 0.335 | observe | 1 | 1.0 | 6401 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4274 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 5959 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| ninja-vless | 0.14 | downweight | 6 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tonykong-base64 | 0.175 | observe | 0 | None | 0 | 5 |
| tonykong-clash | 0.175 | observe | 0 | None | 0 | 5 |
| Barabama-we | 0.176 | observe | 0 | None | 0 | 23 |
| Mr8AHAL | 0.176 | observe | 0 | None | 0 | 26 |
| Pawdroid | 0.176 | observe | 0 | None | 0 | 20 |
| abc-configs-readme-latest30 | 0.176 | observe | 0 | None | 0 | 22 |
| barabama-nodefree | 0.176 | observe | 0 | None | 0 | 23 |

## Source Cleanup Suggestions

| Bucket | Source | Score | Tested | Pass Rate | Dead | Reason |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.14 | 6 | 0.0 | 0 | low score with tested >= 5 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.411 | 51 | 73 | 124 |
| mheidari-all | 0.767 | 165 | 50 | 215 |
| Surfboard-tg-mixed | 0.848 | 302 | 54 | 356 |
| Au1rxx-base64 | 0.872 | 68 | 10 | 78 |
| Epodonios-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 25 | 0 | 25 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 13927 | yes | 23.7 | 0 |
| DeltaKronecker-all | 7763 | yes | 3.14 | 0 |
| Epodonios-all | 6401 | yes | 1.18 | 0 |
| SoliSpirit-all | 5959 | yes | 1.19 | 0 |
| Surfboard-tg-mixed | 4586 | yes | 1.3 | 0 |
| mahdibland-V2RayAggregator | 4541 | yes | 0.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 4274 | yes | 0.71 | 0 |
| barry-far-vless | 4240 | yes | 0.75 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 1.17 | 0 |
| Surfboard-tg-vless | 3590 | yes | 1.08 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Real-test error alerts
| Error | Count |
| --- | --- |
| general | 179 |
| 204 | 5 |
| speed | 5 |
| cn-block | 2 |
| geo | 2 |

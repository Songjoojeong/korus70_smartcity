# 데이터 안내 (Data Directory)

이 폴더에는 분석에 사용한 **원자료(raw data)가 포함되어 있지 않습니다.**
원본 데이터는 용량과 각 기관의 재배포 약관 문제로 저장소에 올리지 않으며,
아래 출처에서 직접 내려받아 이 `data/` 경로에 배치하면 노트북을 재현할 수 있습니다.

---

## 1. 데이터 출처 및 다운로드

| 데이터 | 기관 | 기간 | 다운로드 |
|--------|------|------|----------|
| PM2.5 · NO2 일별 농도 | US EPA — Air Quality System (AQS) | 2023–2026 | https://www.epa.gov/aqs |
| 교통량 (일평균·피크·트럭) | Florida DOT — Traffic Monitoring (TMSCOUNT) | 2025–2026 | https://www.fdot.gov/statistics/trafficdata/ |
| 기상 (기온·강수·풍속) | NOAA — Climate Data Online (GHCN-Daily) | 2023–2026 | https://www.ncei.noaa.gov/cdo-web/ |
| 대중교통 (버스정류장) | LYNX (Central Florida RTA) — GTFS / Bus Stops | 2026 | https://www.golynx.com/ |
| 사회경제 지표 | US Census Bureau — ACS 5-Year Estimates | 5년 추정 | https://data.census.gov/ |

> 대상 지역: 미국 플로리다주 올랜도 도시권 (Orange · Seminole · Osceola 카운티)

---

## 2. 권장 배치 경로

내려받은 파일을 아래 구조로 두면 노트북이 그대로 읽습니다.
(정확한 파일명·경로는 노트북 데이터 로드 셀 `[3]`~`[5]`를 참고하세요.)

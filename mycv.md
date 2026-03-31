# Future CV : Yoonkyong Lee (가상 이력서: 이윤경)
> 
> *Space Data Systems Engineer · Mission Data Engineer*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)

-----

## Contact
| Type | Detail | Link |
| :--- | :--- | :--- |
| **Email** | `ynkynglee@gmail.com` | [Send Email](mailto:ynkynglee@gmail.com) |
| **LinkedIn** | `/in/yoonkyong-lee` | [Visit Profile](https://www.linkedin.com/in/yoonkyong-lee) |
| **GitHub** | `@febyoon03` | [Visit GitHub](https://github.com/febyoon03) |
| **Location**| Seoul, KR  (Open to US Relocation) |



-----

## About Me

항공우주 도메인 지식과 대용량 데이터 엔지니어링을 결합한 우주 데이터 과학자입니다.
위성 원격측정 실시간 스트리밍부터 SAR/광학 융합 분석, ML 기반 객체 탐지까지 **end-to-end 파이프라인**을 설계합니다.

- **희망직무** — Mission Data Engineer · Geospatial AI Researcher · Space Data Scientist

-----

## Education

### Kwangwoon University — Seoul, South Korea

> Dept. of Information Convergence · B.S. | Mar 2024 – Feb 2028 | GPA 4.0 / 4.5

### UC San Diego(UCSD) — La Jolla, CA 

> Exchange Student · Jacobs School of Engineering | Sep 2026 – Jun 2027
> 
> [Calit2 / Engineers for Exploration Lab](https://e4e.ucsd.edu) — Research Assistant

-----

## Work Experience

### Mission Data Engineering Intern

**[Planet Labs PBC](https://www.planet.com)** · San Francisco, CA *(Remote)* · `Jun – Aug 2027`

- PlanetScope 텔레메트리 파이프라인 재설계
- Kafka + Apache Flink 기반 실시간 이상 탐지 모듈 처리
- 영상 품질 QA 자동화 파이프라인 구축

### Research Assistant — Space Data Systems

**[UCSD Calit2 / Engineers for Exploration Lab](https://e4e.ucsd.edu)** · La Jolla, CA · `Sep 2026 – Jun 2027`

- 드론 다분광 센서 데이터 실시간 지리참조(Georeferencing) 파이프라인 연구
- **IEEE IGARSS 2027** 제1저자 논문 투고 *(Under Review)*
- NASA JPL Open Source Day 참여 · STK 연동 시뮬레이션 코드 기여

### Geospatial AI & Data Intern

**[SIA (SI Analytics)](https://www.si-analytics.ai)** · Seoul · `Jun – Aug 2028`

- KOMPSAT-5 SAR 선박 탐지 모델 정확도 개선
- GDAL/Rasterio 좌표계 자동 정합 모듈 개발
- 변화 탐지 대시보드 PoC 구현 (Streamlit + PostgreSQL + PostGIS)

### Remote Data Engineering Intern

**[SkyTruth](https://skytruth.org)** · Global NGO *(Remote)* · `Jan – Apr 2028`

- AIS + SAR 크로스매칭으로 불법 조업 의심 선박 식별 (남중국해)
- Google Earth Engine + BigQuery 분석 워크플로우 이용하여 처리 시간 감소

-----

## Projects

### [실시간 우주 잔해물 충돌 경보 시스템 (CADS)](https://github.com/febyoon03)

> NASA Space Apps 2026 **Global Nominee** 

[Space-Track.org](https://www.space-track.org) TLE 데이터를 5분 주기 수집 → Kafka 스트림 주입 → SGP4로 LEO 위성 1,200기 실시간 궤도 예측.
충돌 확률 임계값 초과 시 자동 경보 + Streamlit 3D 궤도 시각화.

- **Tech Stack:** `Python` `Kafka` `SGP4` `Streamlit` `AWS Lambda` `Three.js`

-----

### [SAR/광학 융합 선박 탐지 파이프라인](https://github.com/febyoon03) 

> SIA 인턴십 확장 · Kaggle **Silver Medal** · arXiv 사전 공개

KOMPSAT-5 SAR + PlanetScope 광학 영상 Co-registration → FPN+ResNet50 객체 탐지.
Docker 패키징 + Kubernetes 배포.

- **Tech Stack:** `PyTorch` `GDAL` `QGIS` `Docker` `Kubernetes` `GEE`

-----

### NASA Kepler 실시간 스트리밍 파이프라인

> 개인 프로젝트 · AWS 클라우드 데이터 레이크

Kafka로 시계열 측광 데이터 수신 → Astropy Transit 이상 탐지 → S3 자동 적재.
행성 후보 탐지 False Positive율 감소.

- **Tech Stack:** `Python` `Kafka` `Astropy` `AWS S3` `SQL`

-----

### LEO 군집위성 네트워크 안정성 시뮬레이션

> 학부 연구 · 광운대 기초로봇수학 강의

확률미분방정식(SDE)으로 다중 위성 통신 지연·위치 오차 모델링.
몬테카를로 **10만 회** 시나리오 검증.

- **Tech Stack:** `Python`, `SDE`, `Monte Carlo`, `Matplotlib`

-----

### NASA Citizen Science: Planet Hunters TESS & Active Fire Mapping

> 자발적 시민 과학자 · 오픈소스 툴킷 배포

NASA TESS 위성의 광도 곡선(Light curve) 및 Earthdata를 분석하여 외계 행성 후보군 식별과 산불 데이터 레이블링에 기여.
누락된 메타데이터와 노이즈가 심한 날것(Raw)의 시계열 데이터를 Python 기반으로 정제하고 시각화하는 자체 자동화 스크립트를 개발하여 글로벌 커뮤니티에 오픈소스로 배포.
- **Tech Stack:** `Python`, `Lightkurve`, `Pandas`, `Earthdata`
  
## Publications

|제목                                                                                       |학회 / 저널                              |역할  |
|:----------------------------------------------------------------------------------------|:------------------------------------|:--:|
|Automated Data Processing Pipeline for UAV-based Multispectral Imagery (드론 다분광 영상을 위한 자동화 데이터 처리 파이프라인)|**IEEE IGARSS 2027** *(Under Review)*|제1저자|
|Performance Optimization of Object Detection Models for Maritime Vessels using SAR Imagery (SAR 영상을 활용한 해상 선박 객체 탐지 모델 성능 최적화)|**arXiv:2027** *(Preprint)*    |공동저자|

-----

## Awards

|연도  |대회                                                             |결과                                         |
|:--:|:--------------------------------------------------------------|:------------------------------------------|
|2026| **Yonsei ASTI Space & Aerospace Technology Competition**<br>(연세대학교 우주항공 기술 및 정책·전략 공모전) | **은상 (Sliver Prize)** — 제1분야 (기술 트랙) |
|2026|[NASA Space Apps Challenge](https://www.spaceappschallenge.org)|**Global Nominee**|
|2026|[ESA Φ-lab Open Challenge](https://philab.esa.int)             |**2nd Place** — Earth Observation AI Track |


-----

## Certifications

**Cloud & Data**

- **AWS Certified Data Engineer – Associate** · *Amazon Web Services*
- **Google Professional Data Engineer** · *Google Cloud*
- **Databricks Certified Data Engineer Associate** · *Databricks*

**Space & Earth Observation**

- **NASA Fundamentals of Remote Sensing** · *NASA ARSET*
- **NASA Open Science 101 (TOPS)** · *NASA*
- **GIS, Mapping, and Spatial Analysis** · *UoT Coursera*

**Korean National**

- **빅데이터 분석기사** · 과학기술정보통신부
- **정보처리기사** · 과학기술정보통신부
- **SQLD · ADsP** · 한국데이터산업진흥원

-----

## Skills

|분야                 |기술                                                                |
|:------------------|:-----------------------------------------------------------------|
|**Languages**      |`Python` `SQL` `C/C++` `Bash`                                     |
|**Space & Geo**    |`Astropy` `GDAL` `QGIS` `SGP4` `Rasterio` `GEE` `Satpy` `Skyfield` |
|**Data & ML**      |`Kafka` `Flink` `Spark` `PyTorch` `Pandas` `dbt`                  |
|**Infra**          |`AWS` `GCP` `Docker` `Kubernetes` `Linux` `Airflow`               |
|**Database**       |`PostgreSQL` `PostGIS` `BigQuery`                                  |
|**Human Languages**|Korean (Native) · English (Fluent) · Japanese (Intermediate)                                 |

-----

## Community

- **AIAA Student Member** — [aiaa.org](https://www.aiaa.org)
- **Open Source Contributor** — [Satpy](https://github.com/pytroll/satpy) · [Pyresample](https://github.com/pytroll/pyresample)
- **NASA Earthdata Community Contributor** — [earthdata.nasa.gov](https://earthdata.nasa.gov)
- **SpaceML / Frontier Development Lab Mentee** — [frontierdevelopmentlab.org](https://frontierdevelopmentlab.org)

-----

<sub>Last updated: 2026 · Built with GitHub Pages</sub>

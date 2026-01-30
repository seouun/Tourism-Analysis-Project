# Tourism Analysis Project  
국민여행조사 기반 관광 데이터 분석  
(제3회 BDA 채용 공모전 제출작)

## 1. Background
관광 정책 및 지역경제 활성화를 위해서는 단순 방문객 수가 아닌  
**여행 패턴과 지출 구조를 고려한 숙박 인프라 입지 분석**이 필요하다.  
본 프로젝트는 국민여행조사 데이터를 활용하여 **고지출·숙박형 관광 지역**을 도출하고,  
실제 관광지 및 지역 여건을 결합한 데이터 기반 정책 제안을 목표로 한다.

## 2. Data
- Source: 국민여행조사
- Unit of Analysis: 지역 단위 관광 패턴
- Key Variables:
  - 여행 유형 (숙박/당일)
  - 관광 지출
  - 방문 지역
  - 관광지 분포

## 3. Methodology
1. 관광 데이터 EDA를 통한 지역별 여행·지출 패턴 분석  
2. 고지출 숙박형 관광 지역 후보군 도출  
3. 관광지 분포 및 빈집 지역 데이터 결합  
4. 최종 숙박 인프라 입지 후보 지역 선정  
5. 숙박시설 유치 시 기대효과 분석

## 4. Key Results
- 고지출 숙박형 관광 지역으로 **여수** 최종 선정
- 여수 내 주요 관광지와 빈집 지역을 결합한 입지 분석 수행
- 숙박시설 유치 시 지역경제 활성화 효과 도출

## 5. Tech Stack
- Python: pandas, numpy, scikit-learn, matplotlib, seaborn
- Jupyter Notebook

## 6. Files
- `notebooks/main_analysis.ipynb`  
  : 전체 분석 파이프라인 (EDA → 분석 → 결과)
- `docs/report_round1.pdf`  
  : 공모전 1차 제출 보고서
- `docs/final_presentation.pdf`  
  : 공모전 2차 본선 발표 자료

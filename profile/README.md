# LLM 기반 공공데이터 품질 관리 및 분석 자동화 시스템

<img width="150" height="50" alt="Image" src="https://github.com/user-attachments/assets/b0bb2947-f574-48f3-9f3e-ac0e09168c5e" />
<br>
행정안전부 데이터정보화담당관이 보유한 본 저작물은 “공공누리” 제4유형: 출처표시 + 상업적 이용금지 + 변경금지 조건에 따라 이용할 수 있습니다.

## 파이프라인
<img width="849" height="362" alt="Image" src="https://github.com/user-attachments/assets/3812c26a-97f4-468f-8aa4-c3b9d3e328c1" />

---

## 주요 기능

### 초기 화면

<img width="855" height="422" alt="Image" src="https://github.com/user-attachments/assets/0307268e-816f-4ed6-ac67-8ec9a79ce72a" />

- GPT-4o-mini LLM 모델 사용

### 검증 결과

<img width="860" height="413" alt="Image" src="https://github.com/user-attachments/assets/325afdd0-edd2-4a70-a58b-e8815c5bef22" />

- LLM 기반 규칙 결정 후 형식 검증, 통계적 검증, LLM 기반 의미적 검증 수행

### 데이터 미리보기

<img width="863" height="423" alt="Image" src="https://github.com/user-attachments/assets/2f8d6212-38ef-4a38-b7b2-20b19e732624" />

- 표준 용어 매핑의 경우 공공데이터 공통 표준 용어 데이터 사용

### 추천 데이터 분석

<img width="856" height="419" alt="Image" src="https://github.com/user-attachments/assets/91b7dfcb-9d84-437c-bb00-311f3871c054" />

- 컬럼 명 및 샘플 데이터를 LLM이 보고 분석 항목 도출 및 분석 코드 작성
- 실행 버튼 클릭을 통해 작성된 분석 코드 실행 가능
- 출력된 분석 결과의 경우 시설 종류 별 CCTV 설치 비율으로 초등학교 근처에 CCTV가 가장 많이 설치되어 있다는 사실 확인 가능

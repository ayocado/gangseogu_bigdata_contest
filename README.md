# 🚔 강서 방위대 : 강서구 주차장 부지선정
- [2023 강서구 빅데이터 활용 공모전](https://allforyoung.com/posts/26465)
- 프로젝트 기간 : 2023.02.20 ~ 2023.03.24

## 💡 선정 배경 및 필요성
- 2022년 강서구 민원 통계를 보았을 때, 교통-불법주정차 비율이 약 88%로 높을 비율을 차지하고 있음
- 또한 불법주정차 민원건수가 해마다 증가하는 것으로 보아 불편이 해소되지 않음을 알 수 있음
- 2022 사회안전지수 발표에 의하면 강서구의 주거 환경 순위는 93위로 매우 낮음

<br>

## 📑 프로젝트 flow
#### CRISP-DM 기반 프로젝트 수행
#### 1. Business Understanding
- 각종 미디어를 통한 강서구의 문제점 파악

#### 2. Data Understanding
- 공공데이터 수집
- 데이터 전처리 및 가설 수립

#### 3. Data Preparation
- 단변량 분석을 통한 이상치 및 결측치 처리
- 이변량 분석을 통한 상관관계 파악 및 주요 변수 추출
#### 4. Modeling
- 차원축소(t-SNE)로 특징 추출, 클러스터링(K-means)를 이용한 군집화
- Elbow method를 적용하여 최적 군집 수 결정
#### 5. Evaluation
- 군집 별 특징 파악
- 강서구 최적 주차장 부지 선정

<br>


## ✨ 활용방안 및 기대효과
- 교통 혼잡 완화
  - 주차장 부족으로 인한 불법 주정차 방지를 통한 도로 통행 속도 개선
  - 소방차, 구급차의 긴급 이동 원활
- 환경 개선
  - 교통 체증으로 생기는 대기 오염 심화 방지
  - 사회안전지수 개선
- 만족도 향상
  - 주차 공간 부족을 해결하여 주민 불편 해소
  - 지역 경제 발전 및 교통 체증 개선으로 삶의 질 향상 기대

<br>

## 🧑‍🤝‍🧑 팀원 및 역할
<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/jian1114">
          <img src="https://avatars.githubusercontent.com/u/77630266?v=4" width="100px;">  <br>
          <sub><b>이지안</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/brojoon1">
          <img src="https://avatars.githubusercontent.com/u/81418195?v=4" width="100px;">  <br>
          <sub><b>김형준</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/ayocado">
          <img src="https://avatars.githubusercontent.com/u/89889583?v=4" width="100px;">  <br>
          <sub><b>윤용완</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/JunePark-00">
          <img src="https://avatars.githubusercontent.com/u/81201633?v=4" width="100px;">  <br>
          <sub><b>박주은</b></sub>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">팀장, 데이터분석, 모델링</td>
      <td align="center">데이터분석, 모델링</td>
      <td align="center">데이터분석, 모델링</td>
      <td align="center">데이터분석, 모델링</td>
    </tr>
  </tbody>
</table>

<br>

## 💻 기술 스택
##### 언어
<span><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"></span>
##### 라이브러리
<span><img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/scipy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/folium-77B829?style=for-the-badge&logo=folium&logoColor=white"></span>
##### 프로그래밍 인터페이스
<span><img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"></span>
##### 협업툴
<span><img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"></span>
<span><img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"></span>

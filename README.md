# 로봇공학 산업의 취업시장 동향 및 핵심기업 분석

<div align="center">
    <img src="https://github.com/AUTO-KKYU/test/assets/118419026/d74713fd-3663-47f1-987c-e1df1d9fba07">
</div>

<div align="center">
  
### Robot. EDA, ***"로봇을 알다"***

<div align="left">

## 1. 🤖 프로젝트 소개
- 로봇, 자율주행, AI 기업이 요구하는 핵심 능력 및 기술 스택 파악
- 로봇, 자율주행, AI 관련 시장 분석 및 기업 분위기 및 가치 파악
- 기업별 복지, 급여 수준 파악

## 2. 👨‍👦‍👦 팀원 소개
|구분|이름|업무|
|:---:|:---:|:---|
|팀장|유윤하|- 채용사이트 사람인, 점핏 크롤링 <br> - DB분석 및 시각화 타겟 선정 <br> - 과제 관리, 발표자료 작성 및 발표|
|팀원|김동규|- 채용사이트 워크넷 크롤링 <br> - 필요역량 분석을 위한 파이썬 시각화 <br> - Folium 지도 시각화를 통한 위치 시각화 <br> - Github 관리
|팀원|송용탁|- 채용사이트 인크루트, 잡플래닛 클롤링 <br> - 기업 재무재표 분석 및 발표 자료 수집 <br> - 직무 별 연봉, 평점 분석 시각화|
|팀원|양혜경|- 채용사이트 원티드 크롤링 <br> - 구축된 DB 관리 <br> - MySQL Query 작성 <br> - 불용어 처리 및 워드 클라우드|

## 3. 🔍 활용 기술
|구분|상세|
|:---:|:---|
|개발환경|<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" /> <img src="https://img.shields.io/badge/VSC-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />   |
|EDA 시각화|<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white" /> <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" /> <img src="https://github.com/AUTO-KKYU/test/assets/118419026/84383d37-3bf5-4e4b-807f-da746c547577" width="130" height="40"/>|
|웹 크롤링| <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white" /> <img src="https://github.com/AUTO-KKYU/test/assets/118419026/449dc150-2eb0-48d7-9187-e4443d92006c" width="130" height="30"/>| 
|데이터베이스|<img src="https://img.shields.io/badge/Amazon_RDS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" />|
|형상관리 및 협업|<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" /> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" /> |

## 4. 📜 채용사이트 EDA 과정
![스크린샷 2024-04-15 220340](https://github.com/AUTO-KKYU/test/assets/118419026/b947e93e-28f8-4e63-9809-1a854083ed1a)

### 4.1 채용사이트 선정
- 네이버 조회 수 기준 채용사이트 Top10 선정 후, 6개의 사이트로 결정
- 선정된 사이트 (사람인, 워크넷, 잡코리아, 잡플래닛, 인크루트, 원티드, 점핏)

### 4.2 크롤링 데이터 수집 
- 채용사이트 크롤링 데이터 : **기업이름, 기업주소, 연봉, 키워드, 담당업무, 필요역량**
- 사람인 크롤링 데이터 : **기업이름, 고용형태, 연봉, 기업주소, 키워드, 기업형태, 사원수, 매출액**
- 잡플래닛 크롤링 데이터 : **기업이름, 분야, 평점, 연봉, 2차산업군**

### 4.3 수집 데이터 전처리
- **불용어 처리**
    - 필요없는 단어 리스트를 생성 후 불용어 처리를 통해 1차 필터링
    - 이후 핵심 키워드 2차 필터링을 통해 해당 단어의 빈출 정도를 파악
    - 빈출도가 높은 순으로 글씨가 크게 나옴

### 4.4 직무별 핵심 요구 기술 파악
<div align="left">
    
- **Word Clound 기반 직무별 필요역량 파악**
<img src="https://github.com/AUTO-KKYU/test/assets/118419026/84f6870c-059d-45d9-9bf8-7112e7928ed0" width="800" height="300"/>

- **Word Cloud 기반 빈출 단어**
<img src="https://github.com/AUTO-KKYU/test/assets/118419026/60e6aeb8-f7f1-458d-b029-180a3d69abf2" width="500" height="300"/>

- **직무 별 핵심 키워드**
<img src="https://github.com/AUTO-KKYU/test/assets/118419026/d7da46d6-f5fa-42e3-811b-c8a6811d7d81" width="700" height="500"/>

### 4.5 Folium을 활용한 지역별 직무 분포 시각화
<img src="https://github.com/AUTO-KKYU/test/assets/118419026/098ffbb2-ead2-46d3-b911-36799ed0cef3" width="800" height="300"/>

<figure class="half">
  <a href="link"><img src="https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/6991e47e-5ee7-4d36-ade3-576eb313e484"  width="400" height="200"/ ></a>
  <a href="link"><img src="https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/06d4e91a-7c3d-4ebb-a4be-f54f78f6de3d"  width="400" height="200"/ ></a>
</figure>

## 5. 🗂️ DB 구축
- 채용사이트 DB
    - 기업이름, 고용형태, 연봉, 기업주소, 키워드, 담당업무, 필요역량, 인덱스
- Folium DB
    - 기업이름, 고용형태, 연봉, 기업주소, 키워드, 기업형태, 사원수, 매출액, 인덱스
- 잡플래닛 전체 직무 DB
    - 기업이름, 분야, 평점, 연봉, 2차산업군
- 기업 성장 지표 DB
    - 기업이름, 기업규모, 매출액(21/22/23/ALL), 평균연봉, 자본총계(21/22/23), 순이익(21/22/23), 기준년도, 키워드, 인덱스
<div align="left">

![스크린샷 2024-04-16 005126](https://github.com/AUTO-KKYU/test/assets/118419026/377b30a5-d4f8-42f9-a53e-9ea1649c14ef)

---
## 6. ✅ 취업시장 동향 및 기업 분석

### 6.1 로봇 취업 시장 동향
- **고용 형태 비중**
<div align="left">

![스크린샷 2024-04-16 002117](https://github.com/AUTO-KKYU/test/assets/118419026/1b665299-b6a2-4d3c-bbb4-3ce32904751f)

- **로봇 기술의 가치**
    - 로봇 기술 시장에서의 가치
        - 로봇기술 사용 유무에 따른 기업 평점 비교 시, 기술 사용 기업이 평점이 높음
    - 로봇 산업군의 연봉
        - 건설업을 제외한 나머지 분야에서 로봇 기술의 가치가 높음
<div align="left">

![스크린샷 2024-04-16 002344](https://github.com/AUTO-KKYU/test/assets/118419026/e42f3bd8-0af2-4c00-ab74-af7be8e676bc)

- **각 분야 별 매출액 및 평균연봉 비교**
    - HW와 SW 모두 사용하는 분야이므로, 상대적으로 매출액 범위와 연봉이 높다
<div align="left">

![Screenshot from 2024-04-16 16-53-09](https://github.com/AUTO-KKYU/test/assets/118419026/6e1c226e-a0ac-44d3-8ead-f954a1d444d4)

## 7. 🏁 기업 분석 및 추천

**1. 매출액, 순이익, 자본총계, 성장률, 연봉, 평점 순으로 각 1차 기업 추천리스트 Top10을 선정함**

**2. 뉴스기사 및 기업사이트 등 종합적으로 분석하여 각 키워드별로 기업 추천**
- 자율주행 42dot
- 딥러닝 크래프톤
- 로봇제어 유진로봇
<div align="left">

![Screenshot from 2024-04-16 17-05-03](https://github.com/AUTO-KKYU/test/assets/118419026/0d0b6a96-be2b-4ea8-86be-5bbcc2f88e1e)




## 수집된 데이터 및 기타 자료
[Google Drive Link](https://drive.google.com/file/d/1fB4zlZonkEtg19NGn8OFWV3gBHmEoXFH/view?usp=sharing)

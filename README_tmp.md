# merge_project
---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="Introduction">Introduction</a>
      <ul>
        <li><a href="프로젝트 소개">프로젝트 소개</a></li>
        <li><a href="프로젝트 기술">프로젝트 기술</a></li>       
        <li><a href="프로젝트 멤버">프로젝트 멤버</a></li>       
      </ul>
    </li>
    <li>
      <a href="#Body">Body</a>
      <ul>
        <li><a href="#가설 설정">가설 설정</a></li>
        <li><a href="#데이터 수집">데이터 수집</a></li>
        <li><a href="#데이터 시각화">데이터 시각화</a></li>
        <li><a href="#DB 구축 및 전망 분석">DB 구축 및 전망 분석</a></li>
      </ul>
    </li>
    <li>
      <a href="#Conclusion">Conclusion</a>
      <ul>
        <li><a href="#가설 검증">가설 검증</a></li>
        <li><a href="#실전 문제 해결 사례">실전 문제 해결 사례</a></li>
        <ul>
    </li>
    </ol>
</details>

## Introduction

### 01. 🏁 프로젝트 소개
- 산업 동향 이해: 로봇공학 산업의 최신 취업 시장 동향을 파악하여, 이 분야에서 어떤 기술이 중요한지 파악
- 핵심 기업 분석: 주요 로봇공학 기업들의 사업 영역, 재무 상태, 채용 동향 등을 분석하여 취업준비생들 궁금해 하는 로봇 분야의 시장경쟁력, 연봉 등을 분석
- 데이터 구축을 통한 CS지식 함양: 크롤링과 DB구을 통해 수집된 데이터와 EDA를 통한 분석을 통해, Code 작성과 데이터 시각화의 insight함양


#### 수행 계획 및 예상 결과물
* 1월 17일 - 주제 선정 및 1차 데이터 크롤링 : 기업이름, url
* 1월 18일 - url기반 2차  크롤링 
* 1월 19일 - url 기반 2~3차 크롤링 
* 1월 20일 - Pandas를 활용한 데이터 전처리 및 MySQL 기반 DB 구축 
* 1월 21일 - 웹크롤링 DB 보완 및 시각화 시작
* 1월 22일 - Folium과 seaborn을 통한 데이터 시각화 및 발표 내용 논의
* 1월 23일 - 코드 및 데이터 총 정리, 발표자료 수정 및 시각화 보완
* 1월 24일 - 최종 발표준비

#### 프로젝트 목적
- AI를 응용하려는/하고있는 채용 시장 파악
- 각 직무별 요구하는 핵심 능력 파악
- 기업 분위기 및 기업 가치
- 기업별 요구 기술 스택

### 02. 📝 프로젝트 기술
-	MySQL 기반 DB 구축 및 AWS 연동을 통한 관리
-	selenium과 beautifulsoup를 활용한 웹크롤링
-	pandas 모듈을 통한 데이터 전처리
-	matplotlib, seaborn, plotly,folium등을 활용한 데이터 시각

## 03. 🫂 프로젝트 멤버
- 팀명: R.DA(알다)
- 팀장: 유윤하
    - 담당 : 채용 사이트[사람인, 점핏], 크롤링, 과제 관리, 발표자료 작성 및 발표, DB 분석 및 시각화 타겟 선정
- 팀원: 김동규 송용탁 양혜경
    - 김동규 : 워크넷 크롤링, 필요 역량 분석을 위한 Python 시각화, Folium 지도 시각화를 통한 위치 시각화
    - 송용탁 : 인크루트, 잡플래닛 크롤링, 기업 재무재표 분석 및 발표 자료 수집,직무 별 연봉, 평점 분석 시각화
    - 양혜경 : 원티드 크롤링, 구축된 DB 관리, Query 작성, 불용어 처리 및 Word Cloud






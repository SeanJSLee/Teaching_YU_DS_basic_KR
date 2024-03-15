# 경제금융 데이터 분석 소프트웨어 사용법 특강

<p style="text-align: center;">Slow Track class 2024.3.11-15, 상경관 306호<br>이재석, University of Missouri, Columbia</p>

**_경제학적 접근법의 실제적 문제해결_**  

- 현실적인 경제학적 문제해결방법을 연습
- 최근 잡마켓에서 주목받는 파이썬의 사용방법을 연습
- 이론적 배경과 계량경제학적 방법론에 대한 이해를 바탕으로, OLS 회귀분석을 사용

## 소개

- University of Missouri, Columbia. 경제학 박사과정 ([LinkedIn](nkedin.com/in/seanjaeseoklee/))
  - 연구주제: 기후경제와 교육경제의 주제들에 관하여 **_불평등 문제_**
  - ["Academic mobility in U.S. public schools: Evidence from nearly 3 million students"](https://doi.org/10.1016/j.jpubeco.2023.105016)
- 경제금융학부 2015 졸업
- [취미](https://photos.app.goo.gl/Q8MYyrtTXNLsTiTt8): 낚시, 등산, 산책
- TMIs: INTJ

## 참고자료
- Mostly Harmless Econometrics ([link](https://www.mostlyharmlesseconometrics.com/)) - 챕터 3까지의 내용에 집중
  - [Joshua Angrist](https://www.nobelprize.org/prizes/economic-sciences/2021/angrist/facts/) **_2021 노벨경제학상 수상_**  
  - [Jörn-Steffen Pischke](https://personal.lse.ac.uk/pischke/)  
    <img src="doc\img\MHE_cover.jpg" width="300" height="400" border="5"/>
 <!-- * The Credibility Revolution in Empirical Economics: How Better Research Design Is Taking the Con out of Econometrics ([link](https://www.aeaweb.org/articles?id=10.1257/jep.24.2.3)) **_인과관계 추정의 방법론_** -->

## Motivation

- 한정된 자원, 어떻게 더 효율적으로 사용할 것인가?
  - 투입한 자원보다 얻는 이득이 평균적으로 더 크다면, 효율적인 사용이라고 약속함.
- 계량경제학 모형(model)은 위 질문에 대답하기 위함.
  - 자원의 유형이나 질문에 따라, 적합한 모형을 사용.
  - ["All models are wrong, but some are useful." - George Box (1976)](https://en.wikipedia.org/wiki/All_models_are_wrong)
- 일정 조건을 만족하는 모형과 데이터(full rank, and linear)는 OLS로 편리하게 추정이 가능함. 
  - OLS (Ordinary Least Squares; 단순회귀분석)은 가장 이해하기 쉬운 분석방법이며, 현재도 범용적으로 사용함.
  - OLS는 조건부평균과 같다고 말 수 있음. 평균과 평균의 통계적 검정방법을 이해하는 것이 중요함.
  - 다른 분석방법들은 특정 상황에서 발생하는 OLS의 단점들을 개선하거나 발전 시킨 것.

## 강의구성

 <!-- 1. [강의소개](https://colab.research.google.com/github/SeanJSLee/Teaching_YU_DS_basic_KR/blob/main/Lecture_Intro.ipynb) -->

 1. [소프트웨이 소개](https://colab.research.google.com/github/SeanJSLee/Teaching_YU_DS_basic_KR/blob/main/Lecture_tools.ipynb)
    - [Google Colab](https://colab.research.google.com/) - 
            [Jupyter 노트북 파이썬 개발환경](https://jupyter.org/)
            <!-- Colab -->
            [![colab](https://i.ytimg.com/an_webp/inN8seMm7UI/mqdefault_6s.webp?du=3000&sqp=CID_ua8G&rs=AOn4CLCWeXC7JkOqIDUFy4lHACarGQUGcQ)](https://www.youtube.com/watch?v=inN8seMm7UI)

    - [numpy](https://numpy.org/doc/stable/reference/index.html#reference) - 
               기본 함수
    - [pandas](https://pandas.pydata.org/docs/reference/index.html#api) - 
               엑셀 워크시트
    - [matplotlib](https://matplotlib.org/stable/gallery/index.html) - 
               그래프 라이브러리
    - [statsmodels](https://www.statsmodels.org/stable/api.html) - 
               회귀분석 라이브러리
 1. [기본통계](https://colab.research.google.com/github/SeanJSLee/Teaching_YU_DS_basic_KR/blob/main/Lecture_basic_stat.ipynb)
 1. [데이터 불러오기](https://colab.research.google.com/github/SeanJSLee/Teaching_YU_DS_basic_KR/blob/main/Lecture_data_import.ipynb)
 1. [OLS 회귀분석](https://colab.research.google.com/github/SeanJSLee/Teaching_YU_DS_basic_KR/blob/main/Lecture_ols.ipynb)
 1. [OLS 회귀분석 heterogeneity](https://colab.research.google.com/github/SeanJSLee/Teaching_YU_DS_basic_KR/blob/main/Lecture_ols_heterogeneity.ipynb)
 1. [OLS 회귀분석 alternative specification](https://colab.research.google.com/github/SeanJSLee/Teaching_YU_DS_basic_KR/blob/main/Lecture_ols_alt_spec.ipynb)
 <!-- 1. OLS 회귀분석 연습 -->
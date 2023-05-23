# 대선주에 올라타려는 초보 개미들에게

> 데잇걸즈 5기 2조 더 리치 뽀모도로사의 정치대선주 분석 프로젝트입니다. 대한민국의 17대~19대 대통령 선거에서 각 당선자와 2위 후보자를 중심으로 분석했습니다

## 디렉토리 구성
```
  ├── data
  │   ├── code : 데이터셋을 만드는 코드
  │   └── dataset : 데이터셋
  └── analysis
      ├── hypo1 : 가설1 분석 결과
      ├── hypo2 : 가설2 분석 결과
      └── hypo3 : 가설3 분석 결과
```


## 파일 명명방식
17대 이명박 후보 -> 17_lee
<br>
17대 정동영 후보 -> 17_jeong
<br>
18대 박근혜 후보 -> 18_park
<br>
18대 문재인 후보 -> 18_moon
<br>
19대 문재인 후보 -> 19_moon
<br>
19대 홍준표 후보 -> 19_hong
<br>
모든 후보가 포함된 파일 -> all
<br>

- analysis/hypo1
1. 10years_대선회차_후보의성씨.ipynb -> 10년 초장기 종가 추이
2. Bollinger_대선회차_후보의성씨.ipynb파일 -> 1년간 코스피지수 볼린저밴드와 주가 추이

- analysis/hypo2
1. Corr_대선회차_후보의성씨.ipynb -> 후보의 대선주 종목별 피어슨 상관관계 히트맵
2. Similar_visualize_대선회차_후보의성씨.ipynb -> 후보의 대선주 종목별 피어슨 유사도

- analysis/hypo3
1. boxplot_대선회차_후보의성씨.ipynb -> 후보의 대선주 상자수염그림
2. Event_대선회차_후보의성씨.ipynb -> 후보의 대선주 종가와 후보의 이벤트
3. cumrefum_대선회차_후보의성씨.ipynb -> 후보의 대선주의 1년간 수익률 추이와 삼성전자와의 수익률 비교
4. funcion_investment_대선회차_후보의성씨.ipynb -> 투자 시나리오

<br>

## 사용법(아나콘다 환경)
```
git clone https://github.com/ppomodor/phase3.git
cd phase3
conda install --file requirements.txt
```
이후에 analysis의 hypo1 or hypo2 or hypo3폴더에 들어가 ipynb파일들을 실행해주세요


## 환경
- python 3.8.8
- conda 4.10.3
- Jupyter or Colab

## 사용 패키지
- FinanceDataReader 0.9.31
- Numpy 1.20.1
- Pandas 1.2.4
- Plotly 5.3.1
- Seaborn 0.11.2
- matplotlib 3.3.4

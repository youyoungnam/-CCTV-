# Pandas와 matplotlib 라이브러리 문법 기초연습 프로젝트입니다. 

## 프로젝트 개요
Pandas의 기초 문법과 matplotlib의 시각화 기초를 활용하여 서울시 cctv를 분석하는 연습프로젝트입니다. 

## 프로젝트 본문

### Pandas 문법
- csv file 읽기 pd.read_csv()
- excel file 읽기 pd.read_excel()
- 상위 데이터 5개 읽기pd.head()
- 하위 데이터 5개 읽기 pd.tail()
- 데이터 컬러명 변경하기  데이터프레임.rename()함수
- 특정 컬럼기준 데이터 정렬하기 sort_values(by ='특정컬럼')
- 특정 데이터 제거하기 del 방식과 drop방식
- 데이터 상관관계보기 corr() 
- pandas plot함수로 시각화하기 
- 데이터프레임 간단 요약확인 함수 dataframe.info()
- 데이터프레임 기술통계 정보확인 dataframe.describe()
- 데이터프레임 합치기 merge() 함수 
   - on option:  두 데이터프레임의 겹치는 key값
   - how option: 데이터프레임 어디쪽으로 합치는 옵션
        - inner: 교집합
        - outer: 합집합
        - left: 왼쪽 데이터프레임 key값으로 병합 
        - right: 오른쪽 데이터프레임 key값으로 병합
- 데이터프레임 만들기 두가지 방법
   - 딕셔너리안에 리스트 방식
   - 리스트안에 딕셔너리 방식

### matplotlib 문법
- jupyter notebook에서 한글깨짐 해결하기 
- 도화지 그리기 plt.figure(figsize=(a, b))
- plot() 선 그래프 그리기
  - plot(x, y,  color, linestyle, marker, markerfacecolor, markersize, label = '선 이름')
     - color: 선 색상을 설정할 수 있습니다. 
     - linestyle: 선 모양 선택 dashed 점선 형태
     - marker: 마커모양을  'o' 동그라미모양으로 
     - markerfacecolor: 마커 색상 설정
     - markersize: 마커 사이즈 설정 
- plt.grid(True) 도화지 격자무늬 추가하기
- plt.lenged() 그래프 선 이름 위치 설정
- plt.title() 전체 그래프 이름 설정
- plt.xlabel() x축 이름 설정
- plt.ylabel() y축 이름 설정
- plt.scatter() 두 데이터 산점도 그래프 그리기
    - plt.scatter(x, y, s,  c, marker)
        - s: 마커 크기 설정
        - c: 마커 색상 설정
        - marker: 마커 모양설정
 

# bigdata
big data code
한국외대 빅데이터 월456 수업 발표자료를 위한 github 주소입니다.

## 프로젝트 개요
사피어-워프의 가설에 의하면 인간은 언어에 의해 사고가 지배당한다.
유명한 예로 이누이트어의 눈(snow)에 관한 것이 있다.
이누이트어에서는 눈(snow)을 표현하는 다양한 단어가 있다.
- 내리는 눈(falling snow)
- 바람에 휩쓸려온 눈(wind-driven snow)
- 녹기 시작한 눈(slushy snow)
- 땅 위에 있는 눈(snow on the ground)

색깔도 마찬가지이다. 같은 색을 보더라도 구분하는 단어의 존재가 모두 다르기 때문에 다르게 구분한다.
그리스와 러시아에서는 ‘파란색’을 칭하는 단어는 없지만, '밝은 파란색'과 '짙은 파란색'을 칭하는 단어는 있다.
선행 연구에 의하면 색깔을 지칭하는 단어의 차이는 색을 구별하는 능력에도 영향을 미친다. 가령 밝은 파란색과 짙은 파란색을 의미하는 단어를 가진 러시아인은 이런 단어가 없는 미국인보다 두 색을 식별해내는 속도가 빠르다.
만약 파란색을 초록색과 구별하지 않는 나라에서는 둘의 차이를 모를 것이다.

이러한 인식의 차이를 구별하고, 시각화하기 위해 프로젝트를 시작하게 되었다.

## 프로젝트 목표
- 여러 나라의 화자들이 색을 보고 구별한 데이터 셋을 통해 각국의 색깔의 바운더리를 선으로 나타낸다.
- 같은 색이라고 판단한 색의 chip들을 같은 직선 내에 넣는다.

## 프로젝트 결과 미리보기
<img width="674" alt="image" src="https://github.com/user-attachments/assets/e5e640ad-8ca2-4d82-918e-886cc802b157" />
<img width="681" alt="image" src="https://github.com/user-attachments/assets/dfd97a37-e918-4a2b-b3dc-ce72ca556143" />



## data set
raw_data 출처 : https://linguistics.berkeley.edu/wcs/data.html#wmt 
raw_data = WCS의 data, 총 8개 파일 
merged_data => raw_data 병합 후 data set
cleaned_data => 전처리 완료 후 data set (총85만개 data)
빅데이터.ipynb => 전체 코드 
visualization => 시각화 결과 (110개 언어에 대한 인식 분석)

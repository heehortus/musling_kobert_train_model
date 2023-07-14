# musling_kobert_train_model
일기 감정 분석 애플리케이션 &lt;뮤즐링>의 kobert 학습 모델입니다.
<br/>
<br/>

## 모델 선정 및 설명 
* 한국어 500만 개의 문장, 5400만 개의 단어 pretrain된 모델
* **다중 감정 분류 가능**
* **사용자의 목적에 따라 파인튜닝 가능**


## 학습 데이터셋  
  1. AI hub 감성 대화 말뭉치
  2. AI hub 주제별 텍스트 일상 대화 데이터
  3. 국립국어원 비출판물 말뭉치
     


## 데이터 전처리
  * 약 6만 개의 데이터를 총 5가지의 감정으로 분류
    - 사랑/기쁨
    - 이별/슬픔
    - 멘붕/불안
    - 우울
    - 짜증/스트레스

      
## 다중 문장 처리
  * 여러 개의 문장으로 이루어진 일기의 특성 상 다중 문장을 처리해야 함. <br/>
      <img src="https://user-images.githubusercontent.com/108612816/253501199-f939cbf9-199d-482a-934d-421867515a3b.png" width="700px">


## Flask 구동 결과
  <img src="https://user-images.githubusercontent.com/108612816/253498368-fbd66374-9052-4c86-a1da-937132d15a13.png" width="700px">

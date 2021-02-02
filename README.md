# dacon_cup

1. **기간 : 2021.01.01~2021.01.21**

2. **기술스택 : python, keras, tensorflow, sklearn, lstm**

3. **내용 : lstm을 이용하여 향후 1개월간의 사용자,세션,신규방문자,페이지뷰 데이터 예측**
    1. 데이터 전처리 : 시간(H)단위 데이터를 일단위(Day) 데이터로 합치기
    2. lstm모델 구축
    3. 1스텝 교차검사(one-step ahead cross-validation을 통한 순차적 예측
      
        <img width="444" alt="1스텝교차검사" src="https://user-images.githubusercontent.com/50386280/106535264-34e69500-6539-11eb-97d0-befc49bef049.png">

4. **파일설명**
    1. train_csv 
        - 1차 트레이닝 data
    2. 2차_train_csv  
        - 2차 트레이닝 data
    3. train.ipynb  
        **[ input file : train_csv, 2차_train_csv, output finle : my_sub.csv ]**
        - lstm 모델링 및 코드
    4. my_sub.csv
        - 결과파일(제출파일)


5. **결과**
    <img width="967" alt="스크린샷 2021-02-02 오전 9 36 17" src="https://user-images.githubusercontent.com/50386280/106535830-6f046680-653a-11eb-8c54-326feb1cf2b6.png">

# TIL

## 순방향 신경망의 구조

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b3b20b63-c6df-4f6e-8ced-38587402047b/Untitled.png)

- 순방향 신경망은 위와 같이 뉴런들이 모여 Layer들을 이루고 계층이 쌓여
    
    전체 신경망을 이루는 구조 
    
- 순방향 신경망 모델은 데이터가 한 방향으로 전달되어 순방향 연결만 갖는 구조
- +
    
    순방향 신경망(fnn)과 달리 합성곱 신경망(cnn)은 공간 데이터를 가정하며 순환 신경망(rnn)은 순차 데이터를 가정함.
    

### 순방향 신경망의 계층 구조

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a367a43e-1698-427f-8ac5-8b28ca8f0c31/Untitled.png)

순방향 신경망은 입력계층, 은닉계층, 출력계층으로 나뉜다.

입력 계층 : 데이터를 전달 받는다.

은닉 계층 : 데이터의 특징 추출 

출력 계층 : 특징을 바탕으로 추론한 결과를 출력

# CC2021-1
## IRIS Msazure result

> 1. 데이터 업로드

![image](https://user-images.githubusercontent.com/74414773/115009498-4d830c00-9ee7-11eb-80ec-20146586f2d2.png)



> 2. 모델 생성 및 실행

![image](https://user-images.githubusercontent.com/74414773/115009336-29272f80-9ee7-11eb-9dca-79141da39568.png)

데이터 8:2로 분리

Multiclass Neural Network 모델 사용

학습시킬 칼럼 : sepal_length, sepal_width, petal_length, petal_width

분류할 칼럼 : species



> 3. 결과

![image](https://user-images.githubusercontent.com/74414773/115009193-fd0bae80-9ee6-11eb-84c0-b425cc29bf63.png)

예측 결과 Metrics를 보면 Overall accuracy(전체 정확도)는 0.966667(약 96.7%), Average accuracy(평균 정확도)는 0.977778(약 97.8%)임을 알 수 있다. 

그리고 Micro-averaged precision(전체 평균 정도)는 0.966667이고, Macro-averaged precision(라벨별 각 합의 평균)은 0.962963이다.

마지막으로 Micro-averaged recall(전체 평균)은 0.96667,  Macro-averaged recall(각 열의 산술 평균)은 0.958333이다.

이것으로 Overall accuracy, Micro-averaged precision, Micro-averaged recall은 모두 같음을 알 수 있다.


Confusion Matrix를 보면 setosa와 virginica는 100%의 정확도로 모두 잘 분류하였고, versicolor는 87.5%의 정확도로 분류하였으며 나머지는 virginica로 분류했음을 확인할 수 있다.

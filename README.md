# ML Object Detection

## Sagemaker Built-in Algorithm


- Base network로 VGG와 Resnet 선택
- Sigle shot multibox detector (SSD)구조를 이용
- Transfer Learning 지원 (Freeze layer 선택)
- Momentum, weight_decay등 하이퍼라라미터 조정
- Deep NN을 이용해 이미지 안의 객체 발견 및 분류
- 출력은 사각형 Bounding box와 분류 결과의 신뢰도로 구성

![image](https://user-images.githubusercontent.com/52392004/213848094-cffb9333-fdf0-41db-9580-84deb7b83e89.png)


<img src="https://user-images.githubusercontent.com/52392004/213848192-20c6e8fc-7639-48a5-b927-355b6d0ada53.png" width="800">


## Reference 

[Amazon SageMaker 오버뷰 - 강성문](https://www.youtube.com/watch?v=jF2BN98KBlg)

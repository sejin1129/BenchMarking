# VGG16
이미지모델 벤치마킹 저장소입니다.

# 하이퍼 파라미터
batch_size = 32
 - 다른 사람들의 여러 사용 결과를 확인한 결과 32로 설정했을 때 좋은 값을 기록했다고 함
epoch = 10
 - 오버피팅지점을 확인하기 위해 더 늘릴예정
optimizer = SGD
 - optimizer 를 Adam으로 할 경우 loss 가 2% 이하로는 떨어지지 않아 Accuracy 가 10% 를 기록
 - 반면 SGD의 경우 loss가 1% 이하로 떨어지며 Accuracy 또한 급격히 높아짐을 확인

[1,  1563] loss: 2.374
[2,  1563] loss: 1.615
[3,  1563] loss: 1.277
[4,  1563] loss: 1.050
[5,  1563] loss: 0.899
[6,  1563] loss: 0.761
[7,  1563] loss: 0.649
[8,  1563] loss: 0.553
[9,  1563] loss: 0.466
[10,  1563] loss: 0.397
Finished Training
Accuracy for class: plane is 80.3 %
Accuracy for class: car   is 91.5 %
Accuracy for class: bird  is 54.1 %
Accuracy for class: cat   is 57.0 %
Accuracy for class: deer  is 85.3 %
Accuracy for class: dog   is 62.8 %
Accuracy for class: frog  is 82.2 %
Accuracy for class: horse is 85.0 %
Accuracy for class: ship  is 85.5 %
Accuracy for class: truck is 85.1 %

# loss-epoch 그래프
![image](https://user-images.githubusercontent.com/113009722/228559751-046ce036-fc25-4802-b97b-b84d699ebc68.png)

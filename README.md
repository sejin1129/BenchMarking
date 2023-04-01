# 1.VGG16

### 하이퍼 파라미터
 - batch_size = 32
 >다른 사람들의 여러 사용 결과를 확인한 결과 32로 설정했을 때 좋은 값을 기록했다고 함
 - epoch = 20
 >오버피팅지점을 확인하기 위해 더 늘릴예정
 - optimizer = SGD
 >optimizer 를 Adam으로 할 경우 loss 가 2% 이하로는 떨어지지 않아 Accuracy 가 10% 를 기록
 >반면 SGD의 경우 loss가 1% 이하로 떨어지며 Accuracy 또한 급격히 높아짐을 확인

### 결과
 >1 epoch 당 training loss 와 validation loss 가 출력됨을 확인

![image](https://user-images.githubusercontent.com/113009722/228732274-9359708c-4f10-41e6-9102-a78ee3598e1e.png)

![image](https://user-images.githubusercontent.com/113009722/228732382-d3950679-67cd-4e2f-9996-ddb56a676650.png)


### loss-epoch 그래프
 >training 과 validation 의 loss-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/228732483-a15e4354-9188-46b0-a7fa-9e10996b8be6.png)


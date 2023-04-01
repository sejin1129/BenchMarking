# 1.VGG16

### 하이퍼 파라미터
 - batch_size = 32
 >다른 사람들의 여러 사용 결과를 확인한 결과 32로 설정했을 때 좋은 값을 기록했다고 함
 - epoch = 30
 - optimizer = SGD
 >optimizer 를 Adam으로 할 경우 loss 가 2% 이하로는 떨어지지 않아 Accuracy 가 10% 를 기록
 >반면 SGD의 경우 loss가 1% 이하로 떨어지며 Accuracy 또한 급격히 높아짐을 확인

### 측정그래프
 > loss-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229266913-4e43e544-cd0a-4118-bf04-475aaed38d22.png)


 > accuracy-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229266920-97f7d489-78ab-4320-abe5-afee557a251a.png)




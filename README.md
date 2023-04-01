# 1.VGG16

### 하이퍼 파라미터
 - batch_size = 32
 >다른 사람들의 여러 사용 결과를 확인한 결과 32로 설정했을 때 좋은 값을 기록했다고 함
 - epoch = 30
 - optimizer = SGD
 >optimizer 를 Adam으로 할 경우 loss 가 2% 이하로는 떨어지지 않아 Accuracy 가 10% 를 기록
 >반면 SGD의 경우 loss가 1% 이하로 떨어지며 Accuracy 또한 급격히 높아짐을 확인

### 측정그래프
- loss-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229266913-4e43e544-cd0a-4118-bf04-475aaed38d22.png)


- accuracy-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229266920-97f7d489-78ab-4320-abe5-afee557a251a.png)

- 그래프상 좋은 epoch : 7 or 11 

### F1-SCORE
 - 0.8896

---
# 2.ShuffleNet_v2_1_0

### 하이퍼 파라미터
 - batch_size = 128
 - epoch = 20
 - optimizer = Adam

### 측정그래프
- loss-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229273705-c38d1697-bc5a-4117-9f49-9d43eb1647c6.png)

- accuracy-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229273742-ee5e905f-fce8-4fa2-803b-dc6de5ebd970.png)

- 그래프상 좋은 epoch : 7 or 10

### F1-SCORE
- 0.7584

### Run-Time : 17min

# 2.ShuffleNet_v2_1_0(1)

### 하이퍼 파라미터
 - batch_size = 64
 - epoch = 40
 - optimizer = Adam

### 측정그래프
- loss-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229280301-2e58b99c-717b-46d7-ad42-c0ca380fa96d.png)

- accuracy-epoch 그래프

![image](https://user-images.githubusercontent.com/113009722/229280325-ab46a70c-1720-4ed4-a716-080ed344eff9.png)

- 그래프상 좋은 epoch : 18 or 21

### F1-SCORE
- 0.6330

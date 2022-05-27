# DNNMiniProject

## Chest-Xray-Pneumonia
- 정상 폐와 폐렴에 걸린 폐의 흉부 엑스레이 이미지를 가지고 진단을 할 수 있는 딥러닝 모델을 만드는 프로젝트

## 최종 모델/파라미터

|Model|LR|BatchSize|Loss Function|Optimizer|Scheduler|Epoch|
|--|--|--|--|--|--|--|
|VGG16 (Transfer)|0.0001|16|CrossEntropy|Adam with betas=[0.9,0.99]|ReduceOnPleateau|30|

- Chest-xray-pneumonia 캐글 노트북
- 캐글에 original 파일에 있는 노트북을 업로드 후 chest-xray-pneumonia 데이터 add한 뒤 돌리기

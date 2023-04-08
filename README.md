# personalproject_anomaly_detection /Conv Autoencoder 이용한 이상치 탐지
![image](https://user-images.githubusercontent.com/121914727/230733369-9e0fd313-ff91-49f3-b400-eedcae2fec77.png)
- SKAB : 이상치 탐지를 위한 테스트 벤치 시계열 데이터셋(sensor)
- TF Keras two-layered 1d Convolutional Autoencoder / batch_size=32, 100 epochs, lr=0.001, window_size=60
![image](https://user-images.githubusercontent.com/121914727/230733759-4edea525-e620-47c8-88dd-720469e4ef5d.png)
&rarr; 실제보다 미리 이상치 분류함으로서 예지보전 성능

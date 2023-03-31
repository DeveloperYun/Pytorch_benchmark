# Alexnet

## 하이퍼 파라미터
 - batch_size = 32
 - epoch = 30
 - optimizer = SGD
 - learning rate = 0.001

 ## 결과
 ### 학습결과(수치)
Training : [1,  1250] loss: 1.042 accuracy: 0.640  
Validation : [1,   157] loss: 0.613 accuracy: 0.670  
Training : [2,  1250] loss: 0.517 accuracy: 0.821  
Validation : [2,   157] loss: 0.496 accuracy: 0.822  
Training : [3,  1250] loss: 0.396 accuracy: 0.864  
Validation : [3,   157] loss: 0.406 accuracy: 0.863  
Training : [4,  1250] loss: 0.318 accuracy: 0.888  
Validation : [4,   157] loss: 0.385 accuracy: 0.884  
Training : [5,  1250] loss: 0.262 accuracy: 0.910  
Validation : [5,   157] loss: 0.382 accuracy: 0.902  
Training : [6,  1250] loss: 0.217 accuracy: 0.923  
Validation : [6,   157] loss: 0.371 accuracy: 0.913  
Training : [7,  1250] loss: 0.182 accuracy: 0.937  
Validation : [7,   157] loss: 0.360 accuracy: 0.926  
Training : [8,  1250] loss: 0.150 accuracy: 0.949  
Validation : [8,   157] loss: 0.375 accuracy: 0.935  
Training : [9,  1250] loss: 0.131 accuracy: 0.955  
Validation : [9,   157] loss: 0.379 accuracy: 0.940  
Training : [10,  1250] loss: 0.107 accuracy: 0.962  
Validation : [10,   157] loss: 0.388 accuracy: 0.946  
Training : [11,  1250] loss: 0.092 accuracy: 0.967  
Validation : [11,   157] loss: 0.372 accuracy: 0.951  
Training : [12,  1250] loss: 0.077 accuracy: 0.973  
Validation : [12,   157] loss: 0.384 accuracy: 0.956  
Training : [13,  1250] loss: 0.064 accuracy: 0.978  
Validation : [13,   157] loss: 0.449 accuracy: 0.958  
Training : [14,  1250] loss: 0.055 accuracy: 0.981  
Validation : [14,   157] loss: 0.417 accuracy: 0.963  
Training : [15,  1250] loss: 0.050 accuracy: 0.983  
Validation : [15,   157] loss: 0.416 accuracy: 0.965  
Training : [16,  1250] loss: 0.043 accuracy: 0.985  
Validation : [16,   157] loss: 0.416 accuracy: 0.966  
Training : [17,  1250] loss: 0.046 accuracy: 0.984  
Validation : [17,   157] loss: 0.421 accuracy: 0.966  
Training : [18,  1250] loss: 0.035 accuracy: 0.988  
Validation : [18,   157] loss: 0.485 accuracy: 0.968  
Training : [19,  1250] loss: 0.032 accuracy: 0.989  
Validation : [19,   157] loss: 0.426 accuracy: 0.971  
Training : [20,  1250] loss: 0.030 accuracy: 0.989   
Validation : [20,   157] loss: 0.454 accuracy: 0.970    
Training : [21,  1250] loss: 0.026 accuracy: 0.992  
Validation : [21,   157] loss: 0.451 accuracy: 0.972    
Training : [22,  1250] loss: 0.023 accuracy: 0.992  
Validation : [22,   157] loss: 0.424 accuracy: 0.974  
Training : [23,  1250] loss: 0.023 accuracy: 0.992  
Validation : [23,   157] loss: 0.524 accuracy: 0.971  
Training : [24,  1250] loss: 0.020 accuracy: 0.994  
Validation : [24,   157] loss: 0.440 accuracy: 0.975  
Training : [25,  1250] loss: 0.016 accuracy: 0.995  
Validation : [25,   157] loss: 0.483 accuracy: 0.975  
Training : [26,  1250] loss: 0.023 accuracy: 0.993  
Validation : [26,   157] loss: 0.456 accuracy: 0.974  
Training : [27,  1250] loss: 0.014 accuracy: 0.996    
Validation : [27,   157] loss: 0.476 accuracy: 0.976   
Training : [28,  1250] loss: 0.014 accuracy: 0.995    
Validation : [28,   157] loss: 0.509 accuracy: 0.974  
Training : [29,  1250] loss: 0.014 accuracy: 0.995  
Validation : [29,   157] loss: 0.473 accuracy: 0.976  
Training : [30,  1250] loss: 0.019 accuracy: 0.994  
Validation : [30,   157] loss: 0.461 accuracy: 0.975  

 ### loss graph
![download](https://user-images.githubusercontent.com/81633639/229085805-2afd84b9-e53f-4cdd-8f34-d374fcc7bbcc.png)

### class 별 accuracy
Accuracy for class: plane is 93.0 %  
Accuracy for class: car   is 95.6 %  
Accuracy for class: bird  is 88.0 %  
Accuracy for class: cat   is 81.6 %  
Accuracy for class: deer  is 89.0 %  
Accuracy for class: dog   is 81.9 %  
Accuracy for class: frog  is 92.1 %  
Accuracy for class: horse is 93.4 %  
Accuracy for class: ship  is 90.0 %  
Accuracy for class: truck is 93.7 %  

### class graph
![download](https://user-images.githubusercontent.com/81633639/229086076-5a905fbd-cafe-4888-91e5-8ccdf9f0e691.png)

### f1-score
Test F1 score: 0.9109

## 결론
Alexnet 모델은 epoch 26 에서 최적의 결과가 나옴 (정확도 기준)

***
# efficientnet_b0

## 하이퍼 파라미터
 - batch_size = 4  
 >배치사이즈를 4보다 크게 주면 memory (gpu ram) 에러가 나버림. 따라서 현재 환경에서 최대 배치사이즈는 4였음
 - epoch = 30
 - optimizer = SGD
 - learning rate = 0.001

 ## 결과
 ### 학습결과(수치)
Training : [1, 10000] loss: 0.729 accuracy: 0.768  
Validation : [1,  1250] loss: 0.348 accuracy: 0.792  
Training : [2, 10000] loss: 0.315 accuracy: 0.895  
Validation : [2,  1250] loss: 0.266 accuracy: 0.898  
Training : [3, 10000] loss: 0.213 accuracy: 0.930  
Validation : [3,  1250] loss: 0.215 accuracy: 0.930  
Training : [4, 10000] loss: 0.159 accuracy: 0.946  
Validation : [4,  1250] loss: 0.213 accuracy: 0.943  
Training : [5, 10000] loss: 0.123 accuracy: 0.959  
Validation : [5,  1250] loss: 0.206 accuracy: 0.954  
Training : [6, 10000] loss: 0.095 accuracy: 0.969  
Validation : [6,  1250] loss: 0.205 accuracy: 0.963  
Training : [7, 10000] loss: 0.080 accuracy: 0.973  
Validation : [7,  1250] loss: 0.200 accuracy: 0.967  
Training : [8, 10000] loss: 0.066 accuracy: 0.978  
Validation : [8,  1250] loss: 0.207 accuracy: 0.970  
Training : [9, 10000] loss: 0.057 accuracy: 0.980  
Validation : [9,  1250] loss: 0.199 accuracy: 0.973  
Training : [10, 10000] loss: 0.050 accuracy: 0.984  
Validation : [10,  1250] loss: 0.187 accuracy: 0.976  
Training : [11, 10000] loss: 0.043 accuracy: 0.985  
Validation : [11,  1250] loss: 0.195 accuracy: 0.977  
Training : [12, 10000] loss: 0.037 accuracy: 0.988  
Validation : [12,  1250] loss: 0.203 accuracy: 0.979  
Training : [13, 10000] loss: 0.032 accuracy: 0.990  
Validation : [13,  1250] loss: 0.186 accuracy: 0.982  
Training : [14, 10000] loss: 0.030 accuracy: 0.990  
Validation : [14,  1250] loss: 0.190 accuracy: 0.982  
Training : [15, 10000] loss: 0.029 accuracy: 0.990  
Validation : [15,  1250] loss: 0.183 accuracy: 0.982  
Training : [16, 10000] loss: 0.027 accuracy: 0.991  
Validation : [16,  1250] loss: 0.189 accuracy: 0.983  
Training : [17, 10000] loss: 0.025 accuracy: 0.992  
Validation : [17,  1250] loss: 0.193 accuracy: 0.983  
Training : [18, 10000] loss: 0.024 accuracy: 0.992  
Validation : [18,  1250] loss: 0.203 accuracy: 0.983  
Training : [19, 10000] loss: 0.022 accuracy: 0.993  
Validation : [19,  1250] loss: 0.196 accuracy: 0.984  
Training : [20, 10000] loss: 0.016 accuracy: 0.995  
Validation : [20,  1250] loss: 0.189 accuracy: 0.986  
Training : [21, 10000] loss: 0.018 accuracy: 0.994  
Validation : [21,  1250] loss: 0.199 accuracy: 0.985  
Training : [22, 10000] loss: 0.016 accuracy: 0.995  
Validation : [22,  1250] loss: 0.212 accuracy: 0.985  
Training : [23, 10000] loss: 0.015 accuracy: 0.996  
Validation : [23,  1250] loss: 0.210 accuracy: 0.986  
Training : [24, 10000] loss: 0.015 accuracy: 0.995  
Validation : [24,  1250] loss: 0.196 accuracy: 0.986  
Training : [25, 10000] loss: 0.014 accuracy: 0.995  
Validation : [25,  1250] loss: 0.199 accuracy: 0.986  
Training : [26, 10000] loss: 0.013 accuracy: 0.996  
Validation : [26,  1250] loss: 0.207 accuracy: 0.986  
Training : [27, 10000] loss: 0.013 accuracy: 0.996  
Validation : [27,  1250] loss: 0.215 accuracy: 0.986  
Training : [28, 10000] loss: 0.013 accuracy: 0.996  
Validation : [28,  1250] loss: 0.198 accuracy: 0.987  
Training : [29, 10000] loss: 0.012 accuracy: 0.997  
Validation : [29,  1250] loss: 0.198 accuracy: 0.988  
Training : [30, 10000] loss: 0.011 accuracy: 0.997  
Validation : [30,  1250] loss: 0.219 accuracy: 0.987  

### loss graph
![download](https://user-images.githubusercontent.com/81633639/229193457-a49766d8-a5aa-4a55-8730-b5ba035a6025.png)

### class 별 accuracy
Accuracy for class: plane is 95.5 %  
Accuracy for class: car   is 97.0 %  
Accuracy for class: bird  is 92.0 %  
Accuracy for class: cat   is 91.4 %  
Accuracy for class: deer  is 93.1 %  
Accuracy for class: dog   is 90.2 %  
Accuracy for class: frog  is 93.7 %  
Accuracy for class: horse is 97.4 %  
Accuracy for class: ship  is 95.7 %  
Accuracy for class: truck is 96.2 %  

### class graph
![download](https://user-images.githubusercontent.com/81633639/229193575-e6b7fccd-c956-4d3b-83a2-dbac4319af1e.png)

### f1-score
Test F1 score: 0.9588

## 결론
efficientnet_b0 모델은 epoch 27 에서 최적의 결과가 나옴 (정확도 기준)

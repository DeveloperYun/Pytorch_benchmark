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

***
# mnasnet0_5

## 하이퍼 파라미터
 - batch_size = 16
 >batch size = 32, epoch = 30 으로 했을 때 GPU RAM(8.7/15) 이었고 그래프 상으로 유의미한 결과가 나오지 않았음. 
 - epoch = 80
 - optimizer = SGD
 - learning rate = 0.001

 ## 결과
 ### 학습결과(수치)
Training : [1,  2500] loss: 3.185 accuracy: 0.236  
Validation : [1,   313] loss: 1.866 accuracy: 0.268  
Training : [2,  2500] loss: 1.614 accuracy: 0.457  
Validation : [2,   313] loss: 1.392 accuracy: 0.472  
Training : [3,  2500] loss: 1.305 accuracy: 0.554  
Validation : [3,   313] loss: 1.166 accuracy: 0.563  
Training : [4,  2500] loss: 1.131 accuracy: 0.615  
Validation : [4,   313] loss: 1.020 accuracy: 0.621  
Training : [5,  2500] loss: 1.013 accuracy: 0.649  
Validation : [5,   313] loss: 0.921 accuracy: 0.656  
Training : [6,  2500] loss: 0.939 accuracy: 0.679  
Validation : [6,   313] loss: 0.847 accuracy: 0.685  
Training : [7,  2500] loss: 0.865 accuracy: 0.702  
Validation : [7,   313] loss: 0.790 accuracy: 0.707  
Training : [8,  2500] loss: 0.813 accuracy: 0.722  
Validation : [8,   313] loss: 0.746 accuracy: 0.726  
Training : [9,  2500] loss: 0.775 accuracy: 0.734  
Validation : [9,   313] loss: 0.708 accuracy: 0.739  
Training : [10,  2500] loss: 0.737 accuracy: 0.746  
Validation : [10,   313] loss: 0.670 accuracy: 0.750  
Training : [11,  2500] loss: 0.702 accuracy: 0.760  
Validation : [11,   313] loss: 0.654 accuracy: 0.763  
Training : [12,  2500] loss: 0.673 accuracy: 0.768  
Validation : [12,   313] loss: 0.627 accuracy: 0.771  
Training : [13,  2500] loss: 0.651 accuracy: 0.777  
Validation : [13,   313] loss: 0.604 accuracy: 0.780  
Training : [14,  2500] loss: 0.629 accuracy: 0.785  
Validation : [14,   313] loss: 0.587 accuracy: 0.788  
Training : [15,  2500] loss: 0.616 accuracy: 0.790  
Validation : [15,   313] loss: 0.574 accuracy: 0.792  
Training : [16,  2500] loss: 0.594 accuracy: 0.796  
Validation : [16,   313] loss: 0.556 accuracy: 0.798  
Training : [17,  2500] loss: 0.579 accuracy: 0.801  
Validation : [17,   313] loss: 0.545 accuracy: 0.804  
Training : [18,  2500] loss: 0.562 accuracy: 0.809  
Validation : [18,   313] loss: 0.537 accuracy: 0.811  
Training : [19,  2500] loss: 0.550 accuracy: 0.814  
Validation : [19,   313] loss: 0.522 accuracy: 0.816  
Training : [20,  2500] loss: 0.536 accuracy: 0.815  
Validation : [20,   313] loss: 0.505 accuracy: 0.818  
Training : [21,  2500] loss: 0.531 accuracy: 0.820  
Validation : [21,   313] loss: 0.498 accuracy: 0.823  
Training : [22,  2500] loss: 0.521 accuracy: 0.821  
Validation : [22,   313] loss: 0.495 accuracy: 0.823  
Training : [23,  2500] loss: 0.504 accuracy: 0.827  
Validation : [23,   313] loss: 0.485 accuracy: 0.828  
Training : [24,  2500] loss: 0.498 accuracy: 0.830  
Validation : [24,   313] loss: 0.470 accuracy: 0.832  
Training : [25,  2500] loss: 0.489 accuracy: 0.831  
Validation : [25,   313] loss: 0.470 accuracy: 0.833  
Training : [26,  2500] loss: 0.475 accuracy: 0.837  
Validation : [26,   313] loss: 0.464 accuracy: 0.838  
Training : [27,  2500] loss: 0.476 accuracy: 0.837  
Validation : [27,   313] loss: 0.453 accuracy: 0.840  
Training : [28,  2500] loss: 0.461 accuracy: 0.843  
Validation : [28,   313] loss: 0.451 accuracy: 0.843  
Training : [29,  2500] loss: 0.456 accuracy: 0.844  
Validation : [29,   313] loss: 0.450 accuracy: 0.844  
Training : [30,  2500] loss: 0.449 accuracy: 0.846  
Validation : [30,   313] loss: 0.445 accuracy: 0.847  
Training : [31,  2500] loss: 0.449 accuracy: 0.846  
Validation : [31,   313] loss: 0.431 accuracy: 0.849  
Training : [32,  2500] loss: 0.433 accuracy: 0.851  
Validation : [32,   313] loss: 0.427 accuracy: 0.853  
Training : [33,  2500] loss: 0.433 accuracy: 0.852  
Validation : [33,   313] loss: 0.429 accuracy: 0.853  
Training : [34,  2500] loss: 0.424 accuracy: 0.853  
Validation : [34,   313] loss: 0.424 accuracy: 0.854  
Training : [35,  2500] loss: 0.417 accuracy: 0.857  
Validation : [35,   313] loss: 0.416 accuracy: 0.857  
Training : [36,  2500] loss: 0.416 accuracy: 0.858  
Validation : [36,   313] loss: 0.420 accuracy: 0.858  
Training : [37,  2500] loss: 0.411 accuracy: 0.860   
Validation : [37,   313] loss: 0.411 accuracy: 0.860  
Training : [38,  2500] loss: 0.402 accuracy: 0.862  
Validation : [38,   313] loss: 0.409 accuracy: 0.862  
Training : [39,  2500] loss: 0.396 accuracy: 0.864  
Validation : [39,   313] loss: 0.401 accuracy: 0.864   
Training : [40,  2500] loss: 0.399 accuracy: 0.865  
Validation : [40,   313] loss: 0.393 accuracy: 0.865  
Training : [41,  2500] loss: 0.389 accuracy: 0.867  
Validation : [41,   313] loss: 0.397 accuracy: 0.866  
Training : [42,  2500] loss: 0.386 accuracy: 0.868  
Validation : [42,   313] loss: 0.392 accuracy: 0.868  
Training : [43,  2500] loss: 0.379 accuracy: 0.870  
Validation : [43,   313] loss: 0.384 accuracy: 0.870  
Training : [44,  2500] loss: 0.376 accuracy: 0.871  
Validation : [44,   313] loss: 0.384 accuracy: 0.871  
Training : [45,  2500] loss: 0.374 accuracy: 0.872  
Validation : [45,   313] loss: 0.377 accuracy: 0.872  
Training : [46,  2500] loss: 0.368 accuracy: 0.873  
Validation : [46,   313] loss: 0.378 accuracy: 0.873  
Training : [47,  2500] loss: 0.364 accuracy: 0.875  
Validation : [47,   313] loss: 0.376 accuracy: 0.875  
Training : [48,  2500] loss: 0.357 accuracy: 0.878  
Validation : [48,   313] loss: 0.372 accuracy: 0.878  
Training : [49,  2500] loss: 0.360 accuracy: 0.876  
Validation : [49,   313] loss: 0.367 accuracy: 0.876  
Training : [50,  2500] loss: 0.355 accuracy: 0.878  
Validation : [50,   313] loss: 0.369 accuracy: 0.878  
Training : [51,  2500] loss: 0.354 accuracy: 0.878  
Validation : [51,   313] loss: 0.369 accuracy: 0.878  
Training : [52,  2500] loss: 0.351 accuracy: 0.879  
Validation : [52,   313] loss: 0.359 accuracy: 0.879  
Training : [53,  2500] loss: 0.346 accuracy: 0.881  
Validation : [53,   313] loss: 0.363 accuracy: 0.880  
Training : [54,  2500] loss: 0.334 accuracy: 0.885  
Validation : [54,   313] loss: 0.361 accuracy: 0.883  
Training : [55,  2500] loss: 0.336 accuracy: 0.886  
Validation : [55,   313] loss: 0.352 accuracy: 0.885  
Training : [56,  2500] loss: 0.336 accuracy: 0.885  
Validation : [56,   313] loss: 0.352 accuracy: 0.885  
Training : [57,  2500] loss: 0.334 accuracy: 0.886  
Validation : [57,   313] loss: 0.352 accuracy: 0.884  
Training : [58,  2500] loss: 0.330 accuracy: 0.888  
Validation : [58,   313] loss: 0.351 accuracy: 0.887  
Training : [59,  2500] loss: 0.322 accuracy: 0.889  
Validation : [59,   313] loss: 0.351 accuracy: 0.888  
Training : [60,  2500] loss: 0.316 accuracy: 0.892  
Validation : [60,   313] loss: 0.348 accuracy: 0.890  
Training : [61,  2500] loss: 0.319 accuracy: 0.889  
Validation : [61,   313] loss: 0.346 accuracy: 0.888  
Training : [62,  2500] loss: 0.312 accuracy: 0.892  
Validation : [62,   313] loss: 0.343 accuracy: 0.891  
Training : [63,  2500] loss: 0.315 accuracy: 0.891  
Validation : [63,   313] loss: 0.338 accuracy: 0.890  
Training : [64,  2500] loss: 0.313 accuracy: 0.892  
Validation : [64,   313] loss: 0.339 accuracy: 0.891  
Training : [65,  2500] loss: 0.309 accuracy: 0.893  
Validation : [65,   313] loss: 0.340 accuracy: 0.892  
Training : [66,  2500] loss: 0.307 accuracy: 0.894  
Validation : [66,   313] loss: 0.334 accuracy: 0.893  
Training : [67,  2500] loss: 0.305 accuracy: 0.896  
Validation : [67,   313] loss: 0.330 accuracy: 0.895  
Training : [68,  2500] loss: 0.304 accuracy: 0.896  
Validation : [68,   313] loss: 0.332 accuracy: 0.894  
Training : [69,  2500] loss: 0.305 accuracy: 0.895  
Validation : [69,   313] loss: 0.331 accuracy: 0.894  
Training : [70,  2500] loss: 0.296 accuracy: 0.898  
Validation : [70,   313] loss: 0.333 accuracy: 0.896  
Training : [71,  2500] loss: 0.291 accuracy: 0.901  
Validation : [71,   313] loss: 0.327 accuracy: 0.898  
Training : [72,  2500] loss: 0.292 accuracy: 0.899  
Validation : [72,   313] loss: 0.328 accuracy: 0.896  
Training : [73,  2500] loss: 0.289 accuracy: 0.901  
Validation : [73,   313] loss: 0.331 accuracy: 0.899  
Training : [74,  2500] loss: 0.291 accuracy: 0.898  
Validation : [74,   313] loss: 0.322 accuracy: 0.898  
Training : [75,  2500] loss: 0.283 accuracy: 0.902  
Validation : [75,   313] loss: 0.325 accuracy: 0.900  
Training : [76,  2500] loss: 0.284 accuracy: 0.903  
Validation : [76,   313] loss: 0.325 accuracy: 0.901  
Training : [77,  2500] loss: 0.280 accuracy: 0.902  
Validation : [77,   313] loss: 0.324 accuracy: 0.900  
Training : [78,  2500] loss: 0.280 accuracy: 0.904  
Validation : [78,   313] loss: 0.324 accuracy: 0.902  
Training : [79,  2500] loss: 0.271 accuracy: 0.907  
Validation : [79,   313] loss: 0.320 accuracy: 0.904  
Training : [80,  2500] loss: 0.278 accuracy: 0.904  
Validation : [80,   313] loss: 0.318 accuracy: 0.901  

### loss graph
![download](https://user-images.githubusercontent.com/81633639/229273186-46f6e0fd-0322-40ba-b687-ad9c275bebee.png)

### class 별 accuracy
Accuracy for class: plane is 86.9 %  
Accuracy for class: car   is 92.9 %  
Accuracy for class: bird  is 85.1 %  
Accuracy for class: cat   is 75.3 %  
Accuracy for class: deer  is 86.0 %  
Accuracy for class: dog   is 82.9 %  
Accuracy for class: frog  is 90.7 %  
Accuracy for class: horse is 89.7 %  
Accuracy for class: ship  is 91.6 %  
Accuracy for class: truck is 92.8 %  

### class graph
![download](https://user-images.githubusercontent.com/81633639/229273213-2843d313-ef9d-4fa9-a760-13c546853b1e.png)

### f1-score
Test F1 score: 0.9132

## 결론
mnasnet0_5 모델은 epoch 80 에서 최적의 결과가 나옴 (정확도 기준)

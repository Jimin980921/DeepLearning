## 딥러닝 스터디 모음  

### Gan (Generative Adversarial Network)  
<img src="https://user-images.githubusercontent.com/57060127/90776546-2f074980-e335-11ea-8c4e-f385f449f096.JPG" width=50%>
<br>

생성자(__Generator__), 판별자(__Discriminator__)의 경쟁을 통해 더 나은 모델을 생성  

- [Gan_study](https://github.com/Jimin980921/DeepLearning_study/blob/master/Gan_study.ipynb)= https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8935337 논문요약  
- [Gan_Mnist](https://github.com/Jimin980921/DeepLearning_study/blob/master/Gan_Mnist.ipynb)= Mnist 데이터를 가지고, noise(난수 생성방법)로 가짜이미지 생성, discriminator로 이미지 식별 예제  
<br>

---------------------------------------------
## fruit_objection_detection  
개발환경: python3, tensorflow-Object Detection API  
<img src="https://user-images.githubusercontent.com/57060127/95289524-dddff480-08a5-11eb-9905-0279594d3e09.JPG" width=30%>
<br>


--------------------------------------------------
## image segmentation  
- segmentaion 01
  - 단일 사물 , 배경 합성하기  
  <img src="https://user-images.githubusercontent.com/57060127/94826863-b969bf80-0442-11eb-9ea0-60daccf8a4b9.JPG" width="80%">  

  - 합성 결과   
  <img src="https://user-images.githubusercontent.com/57060127/94826865-ba025600-0442-11eb-8a15-3e739a1631c4.JPG" width="40%">
<br>
<br>

- segmentaion 02  
  - 여러 사물, 배경 합성하기  
    원본  
    <img src="https://user-images.githubusercontent.com/57060127/94830388-7c9fc780-0446-11eb-850c-2aa9eacec683.JPG" width="50%">  
  <br>
  
  
    여러 사물 labeling  
    <img src="https://user-images.githubusercontent.com/57060127/94830539-a22cd100-0446-11eb-9abe-3d66fdfed6ba.JPG" width="50%">  
   <br>
   
   
  - 원본에서 특정사물만 모자이크하기  
  <img src="https://user-images.githubusercontent.com/57060127/94830648-c12b6300-0446-11eb-95cc-7a76e429cea7.JPG" width="50%">  
   <br>
   <br>

응용 app: [어플 연동](https://github.com/Jimin980921/darame)


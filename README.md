# Khuda_Project_StyleGAN2
StyleGAN2를 이용한 게임 속 축구 선수 얼굴 이미지 생성 프로젝트입니다. <br>

---
## 논문 리뷰
"Analyzing and Improving the Image Quality of StyleGAN" 논문 리뷰를 진행했다.<br>
StyleGAN2의 전체적인 모델 구조 및 기존 StyleGAN과의 차별점 등을 알아보았다.
![StyleGAN2](https://github.com/eu2525/Khuda_Project_StyleGAN2/assets/49024115/ca3461bd-850a-47ec-a194-3d3abfc83ffd)


---
## 프로젝트 진행
데이터 셋으로는 인스타그램 _refifa, downtospawn 님의 게시물 이미지를 크롤링해 수집했습니다.
<img src="https://github.com/eu2525/Khuda_Project_StyleGAN2/assets/49024115/9ccb8872-3478-4ef8-9ef7-fbf9ef7731f8" width="40%"> <img src="https://github.com/eu2525/Khuda_Project_StyleGAN2/assets/49024115/4f82636a-0bfd-436c-a414-2bbb62f3b148" width="40%"> <br>
Haar-based Cascade를 이용해 Face Detection을 진행, 정사각형 형태로 얼굴 이미지 분리 후 1024*1024 크기로 resize를 했다.
<img src="https://github.com/eu2525/Khuda_Project_StyleGAN2/assets/49024115/b9cf8f5b-e442-4363-9cac-a38ba8706f8a" width="40%"> <img src="https://github.com/eu2525/Khuda_Project_StyleGAN2/assets/49024115/470389eb-9f48-422c-9825-c93ec53eb18e" width="40%"> 
이미지 생성으로는 StyleGAN2를 이용했습니다.

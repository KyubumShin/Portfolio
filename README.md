# 쥬쥬의 옷장 프로젝트





## [Demo Page - 바로가기](https://frida.rora.es/)
**AWS 지원기간이 끝나서 가격이 싼 서버로 이동하여 스펙이 부족한 상황이라 약 60초정도의 시간이 소요됩니다.**
## 1. 진행기간
* 1차 진행기간 : 2021.8.15 ~ 2021.09.17 
  * 모델 학습 및, 기본 틀 제작
* 2차 진행기간 : 2021.09.18 ~ 2021.10.17
  * 진행했던 프로젝트를 docker image build 및 gitlab pipeline을 이용한 CI/CD
## 2. 프로젝트에 사용된 기술 스택 및 모델
* 모델
  1. StarGAN
  2. U2net : human segment
  3. MHP(Multi Human Parsing) human parsing
* 사용된 스택  
![](./image/stack.PNG)
## 3. 이 프로젝트에 기여한 부분
* 모델 선정
* 학습 데이터 가공 방식 선정 및 데이터 가공
* starGAN training
* StarGAN, U2net의 모듈화 및 docker image 생성
## 5. 어려웠던점
* 처음으로 하는 딥러닝 협업 프로젝트였기 때문에 
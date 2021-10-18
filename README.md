# 쥬쥬의 옷장 프로젝트





## [Demo Page - 바로가기](https://frida.rora.es/)
**현재 AWS 지원기간이 끝나서 가격이 싼 서버로 이동하여 하드웨어 스펙이 부족한 상황이라 연산에 약 60초정도의 시간이 소요됩니다.**
## 1. 진행기간
* 1차 진행기간 : 2021.8.15 ~ 2021.09.17 
  * 모델 학습 및, 기본 틀 제작
* 2차 진행기간 : 2021.09.18 ~ 2021.10.17
  * 진행했던 프로젝트의 docker image build 및 gitlab pipeline을 이용한 CI/CD 체험
## 2. 프로젝트에 사용된 모델 및 기술 스택 
* 모델
  1. StarGAN v2 : multi domain Image transfer
     * https://github.com/clovaai/stargan-v2
  2. U2net : human segment model
     * https://github.com/xuebinqin/U-2-Net
  3. MHP(Multi Human Parsing) : human parsing model
     * https://github.com/ZhaoJ9014/Multi-Human-Parsing  
* 사용된 모델 구조
![](./image/models.PNG)

* 사용된 스택  
![](./image/stack.PNG)
* Bitbucket에서 CI/CD를 시행할 때 어려움이 많아 gitlab으로 이전하였습니다.
* 협업, 이슈 관리툴로 Jira를 사용하였고, 문서 작성이 필요할시에는 Confluence를 같이 사용하였습니다.
* 그외의 화상, 음성미팅은 Discord와 Slack을 사용하였습니다.
## 3. 이 프로젝트에 기여한 부분
* 아이디어 제공
* 모델 선정
* 학습 데이터 가공 방식 선정 및 데이터 가공
* starGAN training
* StarGAN, U2net의 모듈화 및 docker image 생성
## 4. 프로젝트를 진행하면서 어려웠던점
* 처음으로 하는 딥러닝 협업 프로젝트인데다가, 시간, 물리적 제한과 + 지식수준을 고려하지않고 계획을 세워 프로젝트가 진행되는 도중에 프로젝트의 방향성이 여러번 바뀌게 되었습니다.
* 데이터 관련 문제
  * 기존 stargan에서 학습시켰던 Celab-HQ, AFHQ는 얼굴이라는 카테고리에 속하는 데이터셋이기 때문에 눈, 코, 입이 비슷한 위치에 존재하여 정형화 된 데이터셋을 보여주었지만. fashion 카테고리에 존재하는 데이터들은 포즈, 옷의 패턴, 색등 이 같은 카테고리의 옷일지라도 정말 다양한 특징들을 보여주었기 때문에 데이터를 정제할 필요가 있었습니다.
## 5. 평가
* 처음 진행했던 프로젝트로 결고 많은 시간이 주어진것은 아니었지만, 만족할만한 결과가 나오지는 않았습니다. 
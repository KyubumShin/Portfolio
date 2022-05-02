## 프로젝트 List
1. [OCR Data Centric Competition]()
   * 기간 : 2022.04.14 ~ 2022.04.21  
   * 개요 : 데이터 부분 만을 수정하여 OCR task 중 글자 검출 부분 모델 학습. 최종 순위 7위 / 19팀
   * 기여 부분
     * 팀 내의 Data Guideline 작성
     * 자체 labeling 데이터 셋 검수 및 클랜징
     * 오픈 데이터 확보 및 데이터의 타당성 결정
     * Augmentation 실험 설계  

2. [재활용 쓰레기 Object Detection]()
   * 기간 : 2022.03.21 ~ 2022.04.07
   * 개요 : 쓰레기 분리수거를 위한 Object Detection Task 모델 구현. 최종 순위 4위 / 19팀
   * 기여한 부분 
     * EDA를 통한 Metrics의 타당성에 대한 의문 제기 후 coco mAP 수정
     * mmDetection을 이용한 Swin Cascade RCNN 모델 학습
     * Class Imbalance를 해결하기 위한 Oversampling 구현(OpenCV 이용)
     * 모델 실험 설계

<<<<<<< HEAD
3. [Mask Classification]()
   * 기간 : 2022.02.23 ~ 2022.03.03
   * 개요 : 마스크 착용 상태 분류 Classification Model 구현. 최종순위 5위 / 48팀
   * 기여한 부분
     * 나이, 성별, 마스크 착용상태를 동시에 판단하는 Task에서 나이, 성별, 마스크를 분류하여 3개의 모델로 학습 제안
     * pytorch lightning과 timm을 이용한 Baseline 코드 작성
     * 모델 실험 설계

4. [Programmers K-Digital-Training ai 데브 코스 최종 프로젝트]()
   * 기간 : 2021.8.15 ~ ~ 2021.10.17
   * 개요 : StarGAN을 이용한 옷 변환 모델 생성
   * 기여한 부분
     * 계획 단계(주제 선정, 주요 모델 선정)
     * 학습 데이터 가공 방식 선정 및 학습 데이터 가공
     * StarGAN 모델 학습
     * U2net의 모듈화 및 docker image building



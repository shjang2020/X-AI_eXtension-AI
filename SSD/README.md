# 🛠️ SSD (Single Shot MultiBox Detector)

이 프로젝트는 SSD(Single Shot MultiBox Detector) 모델을 구현하고 평가하는 프로젝트입니다. PyTorch를 사용하여 모델을 구축하고, CUDA를 활용하여 GPU 가속을 지원합니다. OpenCV는 이미지 처리에 사용되며, Visdom은 학습 진행 상황을 시각화하는 데 사용됩니다.

## 📋 프로젝트 개요

### 1. 사용 기술
- Python
- PyTorch
- CUDA
- OpenCV
- Visdom

### 2. 구현 내용
- VGG 기반 네트워크와 multibox 레이어를 사용한 SSD 아키텍처 구현
- 데이터 로딩 및 학습 파이프라인 설정
- 학습된 모델의 평가 및 PASCAL VOC 메트릭을 사용한 성능 측정

### 3. 주요 기능
- 단일 단계 검출
- 다중 스케일 처리
- 실시간 객체 검출

### 4. 응용 분야
- 객체 검출
- 자율주행
- 보안 시스템

## 📄 논문 요약
- SSD 모델의 주요 개념 및 아키텍처에 대한 설명
- VGG 네트워크와 추가 레이어를 활용한 객체 검출 기법
- 학습 및 평가 과정에서의 성능 최적화 방법 
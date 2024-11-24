# Co-Teaching 구현

## 소개
- 이 프로젝트는 Co-Teaching 논문을 참고하여 노이즈 레이블 환경에서 효과적으로 학습할 수 있는 딥러닝 모델을 구현한 코드입니다. 두 개의 신경망이 서로 "깨끗한" 데이터를 선택하고 학습하는 Co-Teaching 알고리즘을 Python과 PyTorch로 구현하였습니다.

- 논문: Co-teaching: Robust Training of Deep Neural Networks with Extremely Noisy Labels

## 주요 기능
- Co-Teaching 알고리즘 구현
- CIFAR-10, CIFAR-100, MNIST 데이터셋 지원
- 노이즈 유형(pairflip, symmetric) 및 노이즈 비율 설정 가능
- 학습 결과 시각화 (손실 및 정확도 그래프)

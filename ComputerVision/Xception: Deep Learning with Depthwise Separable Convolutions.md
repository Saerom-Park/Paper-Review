# Xception: Deep Learning with Depthwise Separable Convolutions(2017)

> - Authors: Franc¸ois Chollet, Google, Inc.
> - 생성일: 2022년 03월 28일 오후 6:38
> - 태그: Classification

## Summary
- 제안된 아키텍처인 Xception은 "eXtreme Inception"의 약자로, depthwise separable convolution을 residual connection과 함께 linear stacking한 구조임
- 본 논문은 CNN의 feature map에서 cross-channel correlations와 spatial correlations를 완전히 분리하여 매핑할 수 있음을 가정
- Depthwise Separable Convolution은 Inception 모듈과 유사한 특성을 갖고 있음에도 일반 Conv layer만큼 사용하기 쉽기 때문에, 향후 CNN 아키텍처 설계의 초석이 될 것으로 기대됨
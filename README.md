# Autumn-Annual-Conference-of-IEIE-2023
  
# (전자공학회) 2023년도 추계학술대회 논문 - 이미지 패치 기반 에너지 모델을 활용한 산업 이미지 이상 탐지(저자 박기완)
  
**초록**  
본 연구에서는 산업 이미지 데이터에서의 이상 감지(Anomaly detection)를 위한 이미지 패치 기반 Energy based model(EBM)을 제시한다. 비지도 학습 방식을 사용하는 EBM은 학습에 사용한 정상 데이터와 다른 분포를 가진 이상 데이터에 대해 높은 값을 도출하여 이상 감지가 가능하게 한다. 하지만 산업 데이터에서 기존의 에너지 모델은 세부적인 특징을 잘 잡아내지 못하였다. 따라서 본 연구에서는 image level이 아닌 patch level로 학습함으로써 정보 소실 문제를 해결하였다. 실험 결과, baseline 에너지 모델에 비해 평균 11.5%의 성능 향상이 있었으며 비교군인 생성 모델보다 간단한 모델 구조로 비슷한 성능을 달성할 수 있었다.
  
### 포스터 발표 자료  
![박기완-포스터](https://github.com/rldhks0543/Master_Thesis_-_Industrial-Image-Anomaly-Detection-Using-Image-Patch-based-Energy-Based-Model/assets/114603826/bd031978-0888-4e90-93f7-bbc598eb1fcb)

### 💡 성장 경험

**모델 분석 능력의 중요성**

- 단순히 생각하던 아이디어와 실제 모델의 결과는 괴리가 있다는 점을 알 수 있었고 이 도출된 실험 결과를 기반으로 또 모델을 발전시킬 수 있다는 점을 배울 수 있었습니다. 모델이 학습할 데이터를 패치 단위로 활용하여서 세부적인 특징은 잘 잡아낼 수 있었지만, 이미지 고유의 위치정보가 손실되며 전체적인 변형은 잘 감지하지 못하게 되었습니다. 따라서 전체 이미지를 학습한 EBM과 앙상블 함으로써 더 성능이 좋은 모델(학위 논문 모델)로 발전시킬 수 있었던 경험이었습니다.

**의사전달 방법의 중요성**

- 프로젝트를 청자에게 설명할 때 나의 눈높이와 청자의 눈높이의 차이를 인식하고 그 눈높이를 맞추어야 원활한 의사소통이 가능하다는 점을 배울 수 있었습니다. 청자가 단계를 밟아가며 이해할 수 있도록 큰 틀을 설명한 뒤, 이후의 더 세부적인 큰 틀을 설명하는 방식으로 설명하였습니다. 예를 들어, "이 모델의 목적은 이미지 이상탐지를 위한 모델이다." -> "여러 이상탐지 방법 중 비지도 학습 방식을 활용하는 EBM을 활용하였다." -> "비지도 학습 방식이란.. EBM이란.."의 방식을 예로 들 수 있습니다. 이 방식을 통해 설명 도중 청자들의 끄덕임을 확인 할 수 있었고, 이러한 소통방식이 내 프로젝트를 설명하는 데 있어서 중요한 포인트라는 점을 깨달을 수 있었습니다.

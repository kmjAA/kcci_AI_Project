# 부처핸섬(BHS)

## '손'쉬운 화상 회의 지원 시스템
코로나19 이후 비대면 화상 회의와 수업의 증가로 사생활 보호의 중요성이 부각되었다. 이와 관련하여 사용자가 여러 손 동작을 통해 화상 회의와 수업 중 개인의 프라이버시를 효과적으로 관리할 수 있는 시스템 개발를 목표로 설정했다.

제스처를 통해 블러 처리, 배경 합성, 얼굴 필터 등 사생활 보호 기능을 직관적으로 조작할 수 있는 기능을 제공하여 사용자가 개인 정보를 보다 안전하게 관리할 수 있도록 지원하는 것이 목표이다.
 <br>
  </br>
## 프로젝트 주제
기능 복잡성 : 줌'의 가상 아바타, 가상 배경 화면 등 프라이버시 보호 기능은 찾기 어려움

사용자 어려움 : 중장년층이나 학생들이 복잡한 기능을 파악하고 사용하는 데 어려움

사생활 침해 : 화상 회의 중 사생활이 무방비하게 노출

손 동작 제어 : 다양한 프라이버시 보호 기능을 간단한 손 동작만으로 실행할 수 있는 시스템 개발 필요
  <br>
  </br>
# Project Team
![image](https://github.com/user-attachments/assets/0127369c-372c-434a-b200-6d418b5439ad)
 <br>
  </br>
## Project 일정
<img width="728" alt="image" src="https://github.com/user-attachments/assets/b412d483-2ab7-4742-91a7-3009cf678fcd">
   <br>
    </br>
    
## Technologies Stack
![image](https://github.com/user-attachments/assets/69c424f4-e3be-4033-b8ba-dd17c8474cd4)
   <br>
  </br>
# 주요 기능
![image](https://github.com/user-attachments/assets/6ff4cf9f-f7aa-489e-97ed-db9be2b942fb)
   <br>
  </br>
## 데이터 셋 구축
![image](https://github.com/user-attachments/assets/e083d292-d6f4-4565-ac47-d0c5f41d7887)
![image](https://github.com/user-attachments/assets/a6008269-d3c6-41a2-91a1-0e0521c5100b)
  <br>
  </br>
## 모델 성능 그래프 (loss / epoch)
![image](https://github.com/user-attachments/assets/4ac2d8d2-4ea0-4fc3-ab7f-f9c8390844a0)
- 처음 몇 에포크 동안 손실값이 크게 변동하고, 정확도도 불안정하게 변하는 걸 볼 수 있다.

- 대략 50번째 에포크까지는 학습 정확도와 검증 정확도가 비슷하게 증가했다.

- 특정 에포크에서 손실이 갑자기 급증하고, 정확도도 급격히 떨어지는 현상이 관찰되는데, 모델이 특정 배치에서 이상값(outliers)을 만났거나, 학습률이 너무 높아 모델이 과적합된 것으로 추정한다.




# 시연 영상

https://github.com/user-attachments/assets/7b3d6203-9b23-40eb-aaa5-153c78c95be5


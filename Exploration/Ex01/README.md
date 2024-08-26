# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박연우.
- 리뷰어 : 이준범.


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 9-1
          1. code에는 문제가 없다.
          2. learning rate가 너무 낮아서 학습이 너무 느리게 되고 있다. learning rate를 초반에 크게 잡았다가 나중에 작게 잡아서 최적              화를 해야 한다.
          3. 
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
      9-1
      ![image](https://github.com/user-attachments/assets/ad665121-bbc6-4a99-88d0-adb44c672262)
      Class를 이용해서 Linear Regression을 구현한 부분이다.
      - 주석은 적절하게 달려 있습니다.
      - 코드의 기능, 존재 이유, 작동 원리 등에 대한 기술은 조금 미흡합니다.
      - 주석을 보고 코드가 잘 이해가 됩니다.
  
      9-2
      - 코드를 아직 미완성해서 아직 리뷰를 하기에는 적절하지 않다.
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 9-1에서는 error는 발생하지 않았지만 learning rate의 조절이 필요할 것 같습니다.
      ![image](https://github.com/user-attachments/assets/c710e41d-26c8-4f2e-a748-849d846dfbe5)

    - 프로젝트
      ![image](https://github.com/user-attachments/assets/0f4ea550-2598-4b4a-9048-640278166a7d)
        - gradient에 대한 코드가 잘 작성이 되어 있습니다.
     
    - 9-2에서 에러가 난 부분은 아래와 같습니다.(코드 미완성)
      ![image](https://github.com/user-attachments/assets/13dc8c26-d760-426c-b26e-1c99ecd20aff)
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 회고는 잘 작성을 했습니다.
      ![image](https://github.com/user-attachments/assets/5523dc4d-ba82-4262-92dd-126942353b30)

    - 코드 플로우를 그리지 않았는데 구조도나 흐름도를 그리면 더 좋을 것 같습니다.
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수한 것 같습니다. 사실 이 부분에 대하여 잘 모르겠습니다.
    - Class 함수를 통하여 객체 지향적 프로그래밍으로 코드를 작성했습니다.


# 회고(참고 링크 및 코드 개선)
```
일단 9-1의 경우 코드 작성이 매우 잘 되었습니다. 다만 추가적인 실험에 대한 것이 있다면 좋을 것 같습니다. 첫번째 코드의 경우 learning rate만 적절하게 조절하면 학습이 잘 될 것 같습니다.
```

# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박연우
- 리뷰어 : 김국화

# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 1번 공백과 특수문자 처리, 토크나이징, 병렬데이터 구축의 과정
        - <img width="863" alt="image" src="https://github.com/user-attachments/assets/1996aebf-ced4-492e-9624-043d34129ab8">
        - <img width="826" alt="image" src="https://github.com/user-attachments/assets/9d556faf-75c0-4f69-866b-a80d4c4a4f29">
        - 2번 구현한 트랜스포머 모델이 한국어 병렬 데이터 학습 시 안정적으로 수렴
        - <img width="727" alt="image" src="https://github.com/user-attachments/assets/b886cee4-b9a1-45fb-8350-ade16fd7b850">
        - 3번 한국어 입력문장에 맥락에 맞는 한국어로 답변을 리턴: 일부 어색하긴 하지만 꽤나 적절하게 답변을 리턴함
        - <img width="466" alt="image" src="https://github.com/user-attachments/assets/632922d2-7033-4660-84a0-a09f4418940e">

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 레이어 구성 및 역할을 간단하게 기재해 이해하기 쉽게 작성함
        - <img width="793" alt="image" src="https://github.com/user-attachments/assets/96343c87-fe1f-4e93-8163-16eee55ed9be">

        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 한국어 전처리 에러 원인 및 해결 과정 기록
        - <img width="705" alt="image" src="https://github.com/user-attachments/assets/2f75cb27-a9ff-4cbd-b128-e081f998b59d">
        - EPOCH, MAX_LENGTH 파라미터를 변경해가며 여러 실험 진행
        - <img width="863" alt="image" src="https://github.com/user-attachments/assets/d0a0fa6d-2eb3-4e18-9fb8-d05cf2497120">

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 회고 기록
        - <img width="894" alt="image" src="https://github.com/user-attachments/assets/5c906229-1c6c-4ee8-b13e-5973e12762ac">

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 여러 모델의 결과를 평가하기 위해 결과 출력 함수를 작성해서 간결하고 효율적인 코드 작성
        - <img width="726" alt="image" src="https://github.com/user-attachments/assets/87ea28fe-00b8-48fe-a6a9-b4881a5bc1f8">



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
- 여러가지 실험을 진행해주셔서 결과를 비교해보는 재미가 있었습니다.
- MAX__LENGTH는 생각치않았던 변수여서 신기했어요!  좋은 실험 감사합니다. 
```

# 똑똑한 중고차 project
<img width="1156" alt="스크린샷 2021-01-27 오후 7 58 51" src="https://user-images.githubusercontent.com/58969584/105982557-c9389e00-60da-11eb-851d-35474891fe6b.png">
## modeling Question
### 1. log가 필요한 이유
- 가격이나 상품의 종류 등 중요한 정보를 변경할 때 그 이력을 저장하지 않으면 seller나 buyer와의 각종 이슈에서 확인할 방법이 없다고 생각합니다.
- 그리고 이력 데이터를 모아서 사용자 분석하기에도 용이하고 생각합니다.
### 2. 선분이력 vs 점이력
### 3. seller table
- 내 생각에는 가입시 account_type이 정해지는 경우에는 account_type table이 따로 있을거라고 생각합니다.
- seller table 생성 해야 하는지
- account도 이력관리를 한다면 그 이유는 무엇인가요? 수정사항? 데이터로 사용자층 관리하기?

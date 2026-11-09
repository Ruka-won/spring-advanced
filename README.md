# SPRING ADVANCED

과제를 해결하기 위한 흐름의 순서를 텍스트로 간단하게 정리 하였습니다.

---
### 0. Level 0 : ApplicationContextException 해결
- directory 생성을 해서 resources 등록
- DB 연동 및 secret key 생성을 통해 해결

### 1. Level 1 : ArgumentResolver
- ArgumentResolver 개념을 이해
- 어떤 부분이 연관 되어있는 지 확인
- 연관을 지어주기 위한 어노테이션 사용 및 MvcConfig 흐름 이해 및 클래스 생성

### 2. Level 2 : Code refactoring
- Early Return 예외처리되기전 실행되는 코드 구조 흐름 순서 변경
- if-else 구조 개선 (else 부분 삭제)
- Validation (@Valid 사용 및 Dto에서 어노테이션 사용을 통한 검증)

### 3. Level 3 : N + 1
- EAGER vs LAZY 장단점 및 개념 이해
- @EntityGraph 개념 이해
# GitHub 명령어
### 1. 설정과 초기화
- 전역 사용자명/이메일 구성하기
  - git config - -global user.name “Your name”
  - git config - -global user.email “Your email address”
  
- 저장소별 사용자명/이메일 구성하기 (해당 저장소 디렉터리로 이동후)
  - git config user.name “Your name”
  - git config user.email “Your email address”
  
- 전역 설정 정보 조회
  - git config - -global - -list
  
- 저장소별 설정 정보 조회
  - git config - -list
  
- Git의 출력결과 색상 활성화하기
  - git config - -global color.ui “auto”
  
- 새로운 저장소 초기화하기
  - mkdir /path/newDir
  - cd /path/newDir
  - git init


# planwithRefactoring
스프링부트3으로 planwith 리팩토링

PlanWith
PlanWithRefactoring은 스프링(Spring) 구버전으로 개발된 웹 애플리케이션을
스프링 5 최신 버전, MariaDB, Docker, NGINX로 리팩토링한 예제 프로젝트입니다.

1. 개요
PlanWith는 사용자들이 일정, 여행계획등을 작성할때 여러명에서 동시에 채팅하면서
재미있게 작성할 수 있도록 하는 애플리케이션입니다.
기존 스프링 구버전 프로젝트를 현대적 환경으로 이관하려고 합니다.

2. 주요 기능
동시채팅기능, 일정관리, 지도, 여행 계획 AI 지원, 반응형 UI 지원

3. 기술 스택
- Backend
- springBoot 3.5.6
- MariaDB
- Docker
- NGINX

       +--------+        +--------+      +----------+
       | NGINX  |----->  | Spring |<---> | MariaDB  |
       +--------+        +--------+      +----------+

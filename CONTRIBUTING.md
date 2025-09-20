# Git 워크플로우

이름 규칙
기능이나 목적을 명확히
main(배포), develop(개발 통합),
feature/gnb(기능), release/v1.0.1(배포 준비), hotfix/bug-135(긴급 수정) 등

단기간 유지
장기 브랜치는 병합 복잡도 증가
feature/gnb 브랜치와 feature/login 브랜치가 merge 없이 장기간 나눠져 있을 경우,
두 브랜치를 병합할 시점에 다양한 지점에서 충돌의 가능성이 높음

정기 동기화
메인 브렌치와 자주 병합

main/ 배포용 최종버전 / 제품 출시 후 안정 버전 관리
release/* 배포 준비 / 버전 1.0 배포 전 테스트
hotfix/* 긴급 수정 / 버그 긴급 패치
develop/ 개발 중 통합 버전 / 기능 병합 후 테스트
feature/* 새 기능 개발  / 로그인 기능 추가

# docs - 프로젝트 문서

위시리스트 프로젝트의 산출물 문서를 단계별 폴더로 나누어 보관합니다.
고객 요청과 작성 규칙은 [guides/](../guides/)에 있습니다.

## 폴더 구조
|폴더|내용|
|--|--|
|01_requirements/|요구사항 명세와 기능명세서|

## 01_requirements 문서
|파일|내용|관련 이슈|
|--|--|--|
|requirements-list.md|기능·비기능 요구사항 ID와 이름 목록|#4|
|functional-requirements.md|기능 요구사항 상세|#5|
|nonfunctional-requirements.md|데이터, 보안, 사용성, 시스템환경 요구사항 상세|#6|
|feature-spec.md|기능을 동작 단위로 나눈 기능명세서(F-01~F-20)|#7|

## 읽는 순서
고객 요청(guides/customer-request.md) → requirements-list.md → functional-requirements.md, nonfunctional-requirements.md → feature-spec.md

## ID 체계
|문서|ID 형식|
|--|--|
|고객 요청|NEEDS_01, C1|
|기능 요구사항|User-001, Wish-001, Admin-001|
|비기능 요구사항|Data-001, Sec-001, UI-001, SYS-001|
|기능|F-01|
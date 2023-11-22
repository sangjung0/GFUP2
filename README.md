# 졸준위 프로젝트 GFUP

1. 프로젝트 소개
   프로젝트 개요: 프로젝트의 목적, 범위, 핵심 기능 등에 대한 개요를 작성합니다.
   기술 스택: 사용된 기술 스택과 각 기술의 역할을 설명합니다.

2. 아키텍처
   시스템 아키텍처: 시스템의 전체적인 아키텍처를 다이어그램이나 설명을 통해 제공합니다.
   패키지 구조: 패키지의 계층 구조 및 각 계층의 책임과 역할을 설명합니다.

3. 설정 방법
   환경 설정: 개발, 테스트, 프로덕션 환경의 설정 방법을 상세히 기술합니다.
   빌드 및 배포: 프로젝트를 빌드하고 배포하는 방법을 설명합니다.

4. API 문서
   엔드포인트 설명: API 엔드포인트와 각각의 역할, 사용 방법을 설명합니다.
   요청 및 응답 예시: 각 엔드포인트의 요청과 응답 예시를 제공합니다.

5. 데이터 모델
   Entity 설명: 데이터베이스 테이블과 매핑되는 엔터티와 그 구조를 설명합니다.
   DTO 설명: 데이터 전송을 위한 객체와 각 필드의 역할을 설명합니다.

6. 팀원 및 역할
   팀 구성원 소개: 팀 구성원들과 각자의 역할, 책임을 소개합니다.

7. 주요 이슈 및 결정 사항
   주요 이슈: 프로젝트 진행 중 발생한 주요 이슈와 해결 방법을 기록합니다.
   결정 사항: 프로젝트의 중요한 결정 사항과 그 이유를 설명합니다.

8. 참고 자료
   참고 문서: 참고한 문서, 블로그, 라이브러리 등에 대한 링크 또는 정보를 제공합니다.

```
├─main
│  ├─java
│  │  └─com
│  │      └─example
│  │          └─gfup2
│  │              │  Gfup2Application.java
│  │              │  
│  │              ├─config
│  │              │  ├─configuration
│  │              │  ├─filter
│  │              │  ├─security
│  │              │  └─swagger
│  │              ├─domain
│  │              │  └─member
│  │              │      ├─controller
│  │              │      ├─dto
│  │              │      ├─entity
│  │              │      ├─repository
│  │              │      └─service
│  │              └─global
│  └─resources
│      │  application.properties
│      │
│      ├─static
│      └─templates
└─test
    └─java
        └─com
            └─example
                └─gfup2
                        Gfup2ApplicationTests.java
```
# reCco

- [reCco](https://recco.vercel.app) (배포 링크)
- reCco는 누구보다 당신을 위해 고민하며 화장품을 찾다 지친 당신을 도와줄 꼬에요

## 1. 프로젝트 소개

- 자신에게 맞는 화장품을 알려주는 화장품 추천 서비스

- 포지션별 기술스택
  - 프론트엔드
    - React
    - Next.js
    - Redux
    - Styled-Component
  - 백엔드
    - Python 3.9
    - FastAPI
    - MySQL 5.7
    - Docker
    - NginX
  - 데이터분석
    - python 3.8
    - textrank
    - pororo

## 2. 프로젝트 기획 배경

- 화장품 서비스 배경
  - 화장품의 시장규모 성장
  - 제품이 다양해지고 소비자의 성향의 따른 선택 증가
  - 기능성 화장품 소비 증가
  - 마스크 사용으로 인한 피부 민감성 증가

## 3. 서비스 주요 기능 설명

- 메인 페이지

  - reCco 소개
  - reCco 철학

- 추천 페이지

  - 고객 맞춤 상품 추천
    - 추천을 원하는 카테고리 선택
    - 추천을 원하는 키워드를 선택
    - 키워드를 비교하며 원하는 상품 추천

- 검색 페이지

  - 카테고리, 키워드, 성분별 다양한 상품 검색
  - 최신순, 이름순, 가격순으로 정렬 기능
  - 검색 결과에서 상품 키워드를 제공하여 다양한 정보 확인 가능
    - 카테고리
      - 세부 카테고리별 상품 검색 가능
    - 키워드
      - 검색 히스토리를 통하여 고객의 검색기록 확인 가능
      - 검색 자동완성 기능을 통하여 검색 가능한 키워드 확인 가능
      - 상품명, 브랜드명, 성분명으로 개별적 검색
    - 성분
      - 원하는 성분별 검색
      - 피하는 성분별 검색

- 상세 페이지

  - 화장품의 상세 정보
  - 익명 리뷰를 통해 다양한 경험 공유
    - 사진 업로드를 통해 상품 정보 공유
    - 리뷰 수정, 삭제를 비밀번호로 관리

- 상품 보관
  - 원하는 상품을 자유롭게 저장하여 상품 비교
  - 상품 추가, 삭제를 통해 자유롭게 커스텀

## 4. 프로젝트 구성도

- [와이어프레임](https://whimsical.com/onetop-KvEYZNLaXBoVpCeUHzFJR4)

## 5. 프로젝트 팀원 역할 분담

| 이름   | 담당 업무              |
| ------ | ---------------------- |
| 이재근 | 팀장/인공지능 개발     |
| 조병민 | 데이터분석/백엔드 개발 |
| 김민석 | 백엔드 개발            |
| 김현하 | 프론트엔드 개발        |
| 박근백 | 프론트엔드 개발        |

**멤버별 responsibility**

1. 멤버 1: 팀장/프론트엔드 담당

- 기획 단계: 구체적인 설계와 지표에 따른 프로젝트 제안서 작성
- 개발 단계: 팀원간의 일정 등 조율 + 프론트 or 백엔드 or 인공지능 개발
- 수정 단계: 기획, 스크럼 진행, 코치님 피드백 반영해서 수정, 발표 준비

2. 멤버 2: 백엔드 담당

- 기획 단계: 큰 주제에서 문제 해결 아이디어 도출, 와이어프레임 작성
  와이어프레임을 기반으로 한 ERD 작성.
- 개발 단계: 와이어프레임을 기반으로 작성한 ERB를 토대로 DB 작성.
  이후 각 상황에 맞는 API 작성.
- 수정 단계: 피드백 반영해서 DB,API등의 백엔드 설계 수정.

3. 멤버 3: 인공지능 담당

- 기획 단계: 큰 주제에서 문제 해결 아이디어 도출, 와이어프레임 작성
- 개발 단계: 와이어프레임을 기반으로 인공지능 모델 구현, 모델 학습 진행
- 수정 단계: 피드백 반영해서 모델 정확도 향상

- 팀 규칙

  - 스크럼

    - 팀장이 텐션 올리기!!!!
    - ~~화요일 ~ 토요일 오전 10시~~ 2주차까지 오후 2시로 변경
    - 자유롭게 의견을 말하기
    - 스크럼 종료시 활기찬 화이팅으로 마무리
    - 모든 스크럼 내용 기록하기

  - Git Lab

    - 브런치별 코드 관리

      > master : 배포 & 코드 리뷰를 위한 브런치\
      > develop : 개발된 코드의 리뷰와 오류를 확인하기 위한 브런치\
      > feature : 각 포지션별 코드를 개발하기 위한 브런치\
      > feature*back*(기능) : 백엔드 코드를 개발하기 위한 브런치\
      > feature*front*(기능) : 프론트엔드 코드를 개발하기 위한 브런치

    - 커밋 컨벤션
      > feat: 새로운 기능 추가\
      > fix: 버그 수정\
      > docs: 문서 수정\
      > style: 코드 포맷팅, 링팅, 세미콜론 누락, 콘솔로그 삭제, 코드 변경 X\
      > refractor: 코드 리팩토링\
      > chore: 빌드 업무 수정, 패키지 매니저 수정

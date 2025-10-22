---
layout: post
title: 썸타임 (Sometime) - 지역 대학생 소개팅 앱
---

# 썸타임 (Sometime)

![Status](https://img.shields.io/badge/Status-LIVE-success) ![Period](https://img.shields.io/badge/Period-2024~현재-blue)

**Tech Stack:** React Native, Nest.js, PostgreSQL, Redis, AWS, Naver Cloud

**서비스:** [sometimes](https://info.some-in-univ.com/)

## Overview

교내 창업 동아리 '한밭모'에서 시작하여 **썸타임**사비스로 고도화하여, **초기창업패키지 딥테크**에 선정된 지역 기반 대학생 소개팅 앱입니다. Next.js 기반 초기 버전을 React Native와 Nest.js로 성공적으로 리팩토링하여 현재 운영 중이며, 서비스 유지 3개월에 유저 5000명 + 확보 및 실제 매출을 발생시키고 있습니다.

## Key Achievements

- **초기창업패키지 딥테크 선정** - 정부 지원 사업 선정으로 법인 성장 기반 마련
- **Next.js → React Native + Nest.js 마이그레이션** - 성능과 확장성을 고려한 기술 스택 전환 성공
- **App Store & Play Store 정식 출시** - 실제 사용자 대상 서비스 운영 중
- **실제 매출 발생** - 비즈니스 모델 검증 완료

## Technical Highlights

### 1. 백엔드 핵심 기능 개발

- **대학교 이메일 인증 시스템** - Redis expire 기능을 활용한 시간 제한 인증으로 보안성과 UX 동시 확보
- **PASS 본인인증 로그인** - NHN KCP 및 PortOne 연동, React Native 환경에서 네이티브 모듈 통합
- **실시간 알림 시스템** - 결제 및 회원가입 승인 요청 시 Slack 자동 알림으로 팀 생산성 향상

### 2. 어드민 & 자동화

- 회원가입 승인 시스템 및 관리자 페이지 구현으로 효율적인 회원 관리
- Slack 연동 자동화로 팀 커뮤니케이션 효율성 극대화

### 3. 앱 빌드 & QA

- **Android 네이티브 빌드 이슈 해결** - React Native AOS 빌드 시 C/C++ 오류 디버깅 및 Gradle 최적화
- **iOS 앱 심사 대응** - App Store 배포 프로세스 관리 및 출시 초기 버그 QA

## What I Learned

**비즈니스 가치와 기술적 완성도의 균형** - 동아리실에서 주 7일 숙식하며 개발했던 경험을 통해 초기 성장의 속도와 장기적인 코드 품질 사이의 트레이드오프를 체득했습니다. 이 경험은 AI를 생산성 도구로 활용하되 최종 책임은 개발자가 지는 개발 철학을 세우는 계기가 되었습니다.

---

[← Back to Projects](/#projects)

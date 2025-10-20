---
layout: post
title: 신사타 (Shinsata) - 레거시 코드 개선
---

# 신사타 (Shinsata)

![Period](https://img.shields.io/badge/Period-2025.03-blue) ![Type](https://img.shields.io/badge/Type-Kmong%20외주-orange)

**Tech Stack:** Spring Boot 3, PostgreSQL, Docker, AWS

## Overview

여러 개발자의 손을 거쳐 **핵심 기능이 작동하지 않던 프로젝트**를 인수받아 분석, 수정, 배포한 외주 프로젝트입니다. 문서화되지 않은 레거시 코드를 역추적하고 Docker 환경에서 덤프 DB를 활용해 안전하게 디버깅하여 성공적으로 복구했습니다.

## Key Achievements

- **작동하지 않던 핵심 기능 복구** - 여러 개발자가 남긴 일관성 없는 코드베이스를 분석하여 문제 해결
- **Docker 기반 로컬 환경 구축** - 덤프 DB 파일을 Docker Compose로 로드하여 프로덕션 데이터를 안전하게 테스트
- **AWS 배포 및 안정화** - 수정된 코드를 AWS 환경에 배포하고 모니터링 체계 구축
- **클라이언트 만족도 달성** - 기한 내 안정적인 서비스 복구로 높은 평가 획득

## Technical Highlights

### 1. 레거시 코드 분석 및 복구
- 문서 없이 코드만으로 비즈니스 로직 역추적
- 디버깅 도구와 로그 분석을 통한 체계적인 문제 파악
- 전체 재작성 대신 핵심 문제부터 점진적 개선으로 리스크 최소화

### 2. Docker 실무 활용
- Docker Compose로 PostgreSQL 덤프 DB를 로컬에 로드하여 재현 가능한 테스트 환경 구성
- 볼륨 마운트를 통한 데이터 관리 및 로컬-프로덕션 환경 일관성 유지

### 3. GPT 의존 개발의 위험성 체득
이전 개발자들이 GPT로 생성한 코드를 이해 없이 사용하여 일관성 없는 구조와 작동하지 않는 기능들이 방치된 상태였습니다. 이 경험을 통해 **AI는 보조 수단일 뿐, 개발자의 이해와 검증이 핵심**임을 깨달았고, 이후 썸타임 프로젝트에서 코드 리뷰 문화를 정착시키는 계기가 되었습니다.

---

[← Back to Projects](/#projects)

# SOAP (Simple Object Access Protocol)

SOAP는 **XML 기반의 메시징 프로토콜**로, **웹 서비스 간 데이터 교환**을 위한 표준이다.

## 📌 주요 특징
- **XML 형식의 메시지 사용**
- **HTTP, SMTP, TCP 등 다양한 프로토콜 지원**
- **WS-Security 등의 보안 기능 포함 가능**

## 🌐 SOAP vs REST 비교
| 특성 | SOAP | REST |
|------|------|------|
| **데이터 형식** | XML | JSON, XML, HTML 등 |
| **프로토콜** | 다양한 프로토콜 사용 | 주로 HTTP 기반 |
| **성능** | 무겁고 속도가 느림 | 가볍고 빠름 |
| **보안** | WS-Security 지원 | HTTPS, OAuth 기반 보안 |

---

# REST (Representational State Transfer)

REST는 **웹 기반 API 설계를 위한 아키텍처 스타일**로, HTTP 프로토콜을 기반으로 한다.

## 📌 REST의 6가지 원칙
1. **클라이언트-서버 구조** (Client-Server)
2. **무상태성** (Stateless)
3. **캐시 가능성** (Cacheable)
4. **계층화 시스템** (Layered System)
5. **코드 온 디맨드 (선택 사항)** (Code on Demand)
6. **일관된 인터페이스 (Uniform Interface)**

## 🔥 REST API 주요 메서드
| 메서드 | 설명 |
|--------|------|
| **GET** | 데이터 조회 |
| **POST** | 데이터 생성 |
| **PUT** | 데이터 전체 수정 |
| **PATCH** | 데이터 부분 수정 |
| **DELETE** | 데이터 삭제 |

---

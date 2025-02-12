# Kerberos

## 정의

**Krberos**는 네트워크 환경에서 **사용자 인증을 안전하게 수행**하는 **중앙 집중형 인증 프로토콜**이다.

MIT에서 개발했으며, **대칭키 암호화**와 **티켓(ticket) 기반 인증**을 사용하여 **패스워드 도난 및 재사용 공격을 방지**한다.

## 구성요소

* **AS (Authentication Server, 인증 서버)**
  * 사용자 인증 & TGT 발급

* **TGS (Ticket Granting Server, 티켓 발급 서버)**
  * 서비스 티켓 발급

* **SS (Service Server, 서비스 서버)**
  * 서비스 제공 및 티켓 검증

* **KDC (Key Distribution Center, 키 분배 센터)**
  * AS + TGS 역할 (중앙 인증 서버)

* **Client**
  * 서비스 요청 및 인증 진행
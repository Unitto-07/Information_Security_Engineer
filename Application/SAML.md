# SAML (Security Assertion Markup Language)

SAML은 **웹 기반 Single Sign-On(SSO)을 위한 XML 기반 인증 및 권한 부여 표준**이다.

## 📌 SAML의 핵심 개념
- **SSO(Single Sign-On) 지원** → 한 번 로그인으로 여러 서비스 접근 가능
- **XML 기반 인증 및 권한 부여**
- **IdP(Identity Provider)와 SP(Service Provider) 간 인증 정보 교환**

## 🔄 SAML 인증 프로세스
1. 사용자가 SP(AWS 등)에 접근
2. SP가 IdP(Google 등)로 인증 요청
3. IdP에서 로그인 후 **SAML Assertion(인증 정보)** 생성
4. SAML Assertion을 SP로 전달
5. SP가 검증 후 로그인 완료
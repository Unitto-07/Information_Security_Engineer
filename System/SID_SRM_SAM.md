## 🔑 **SID (Security Identifier, 보안 식별자)**  
- **Windows에서 사용자, 그룹, 컴퓨터 등을 식별하는 고유한 값**  
- 각 계정은 생성될 때 **고유한 SID를 할당**받으며, 계정이 삭제되면 같은 SID를 다시 사용할 수 없음  
- **형식:** `S-1-5-21-xxxxxxxxxx-xxxxxxxxxx-xxxxxxxxxx-xxxx`  
- 예제:  
  ```text
  S-1-5-21-3623811015-3361044348-30300820-1013
  ```  
- **활용:** 파일, 폴더, 레지스트리 등에 대한 **권한 부여 및 보안 정책 적용**  

---

## 🔒 **SRM (Security Reference Monitor, 보안 참조 모니터)**  
- **Windows의 커널 보안 구성 요소**  
- **모든 보안 및 접근 제어 결정을 담당**하며, 시스템 리소스 보호 역할 수행  
- **ACL(Access Control List) 기반으로 접근 권한 검사**  
- **주요 역할:**  
  - 사용자 요청이 리소스 접근 권한을 가지고 있는지 확인  
  - SID와 ACL을 비교하여 허용/거부 결정  
  - 로깅 및 보안 이벤트 기록  

---

## 📁 **SAM (Security Account Manager, 보안 계정 관리자)**  
- **Windows의 사용자 계정 및 로그인 정보를 관리하는 데이터베이스**  
- `C:\Windows\System32\Config\SAM` 파일에 저장되며, 해시된 비밀번호를 포함  
- 로컬 계정 정보만 저장하며, 도메인 환경에서는 **Active Directory(AD)**가 관리  
- **해킹 대상이 되기 쉬우므로 보안이 중요**  
- **보호 방법:**  
  - NTLM 해싱을 통해 비밀번호 저장  
  - `samdump2`, `mimikatz` 같은 도구를 통해 공격 가능  

---

## ✅ **정리**  
| 용어 | 설명 |
|------|------|
| **SID** | 사용자를 식별하는 고유한 보안 식별자 |
| **SRM** | Windows 커널의 보안 정책을 담당하는 모듈 |
| **SAM** | 사용자 계정 및 로그인 정보를 저장하는 데이터베이스 |

---
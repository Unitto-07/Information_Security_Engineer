# PAM (Pluggable Authentication Module): 착탈형 인증 모듈

## 구조

| Module type | Control Flag | Module Name | Module Arguments |
|-------------|--------------|-------------|------------------|

## Module Type

### 1. auth

- 사용자에게 비밀번호를 요청하고 입력받은 정보가 맞는지 검사하는 모듈

### 2. account

- 명시된 계정이 현재 조건에 유효안 인증 목표인지 검사하는 것으로 계정에 대한 접근통제 및 계정 정책을 관리하는 모듈


### 3. password

- 사용자가 인증정보를 변경할 수 있도록 비밀번호 갱신을 관장하는 모듈

### 4. session

- 사용자가 인증을 받기 전과 후에 수행해야 할 일을 정의하는 모듈


## Control Flag

- 
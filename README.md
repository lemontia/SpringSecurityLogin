# SpringSecurityLogin

# 스프링 시큐리티 로그인 샘플

### JPA 로 개발
### Mariadb, Mysql 등으로 설정 중.
### DB정보는 resources/application.yml 파일에서 수정가능
- spring.datasource  << 에서 수정가능

### 회원가입, 로그인 구현
- 이메일 / 비밀번호 방식으로 회원가입/로그인 기능 구현
- 회원가입 중 이미 등록되어 있는 이메일일 경우 로그인 처리

### 비로그인, 로그인 권한으로 인해 들어갈 수 있는 페이지 샘플 구현

### ROLE 에 따라 접근 가능한 페이지 분리.
- 현재 ADMIN 권한은 이메일로 구분하여 주는것으로 설정되어 있음
- 상황에 따라 수정가능
-- 련파일: kr.demonic.config.security.CustomUserDetailService.authorities()

# ExampleProject

springboot lecture for my friend :)

---

## Goals

### v1 Initial Setting  
- create springboot project
- intellij 세팅
- gradle
  - 라이브러리 추가
  - test 제외
- intellij local option
  - Run - Edit Configurations
    - VM options
      - `-Djava.net.preferIPv4Stack=true`
    - active profile
      - `local`
    - hotswap
        - on update actions - `hot swap....`
        - on forame deactivations - `update cleasses ansd resources`
- application.yml 작성
- .gitignore 추가
- spring sercurity config
- index.html 생성
- 어플리케이션 실행

### v2 게시판 만들기
- Object Concept
  - dto
  - vo(domain)
  - entity
- mybatis
- mvc
  - Controller - Service - Mapper
  - vo
  - jsp
### v3 JPA 마이그레이션
- JPA
  - SpringDataJpa
  - QueryDSL
  - vo -> dto, entity
- mvc
  - Controller - Service - Repository
  - dto / entity
  - timelyf

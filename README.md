# fastweb
- 나만의 Rest Web 프로젝트 ~

## 구조
- Java 17 (Azul Zulu)
- Spring Boot 3.4.0
- gradle

### 폴더
- common
  - 스프링 사용자 인프라 스트럭처 빈 관련 폴더
- biz 
  - 스프링 사용자 애플리케이션 빈 관련 폴더
  - 비즈니스 로직 생성
- web
  - 웹 제공 부분으로 biz를 활용
  - 웹 컨트롤러 비즈니스 서비스로 웹 서비스 생성
``` 
./fastweb/src
├── main
│   ├── java
│   │   └── com
│   │       └── standard
│   │           └── fastweb
│   │               ├── FastwebApplication.java
│   │               ├── biz
│   │               │   └── service
│   │               │   └── repository
│   │               ├── common
│   │               │   ├── annotation
│   │               │   ├── aspect
│   │               │   │   └── advice
│   │               │   ├── config
│   │               │   ├── enums
│   │               │   ├── exceptions
│   │               │   ├── filter
│   │               │   ├── interceptor
│   │               │   ├── model
│   │               │   │   └── dto
│   │               │   └── utils
│   │               └── web
│   │                   ├── controller
│   │                   ├── model
│   │                   │   ├── request
│   │                   │   └── response
│   │                   └── service
│   └── resources
│       └── application.properties
└── test
    └── java
        └── com
            └── standard
                └── fastweb
                    └── FastwebApplicationTests.java
``` 


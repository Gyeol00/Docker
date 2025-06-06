# 🐳 Docker Practice

Docker 및 Docker Compose를 활용하여 웹서버, Java 애플리케이션, 데이터베이스를 컨테이너화하는 실습 프로젝트입니다. 각 실습은 Docker 사용법과 애플리케이션 배포 흐름을 익히는 데 목적이 있습니다.

---

## Practice 1 - Apache 웹 서버 컨테이너화

* Apache HTTP 서버(httpd)를 Docker 이미지로 사용하여 간단한 정적 웹페이지(index.html)를 제공하는 실습입니다.
* Dockerfile을 통해 서버 구성 및 정적 파일 복사를 자동화합니다.
* 웹 브라우저를 통해 Apache 서버에 접근하여 결과를 확인할 수 있습니다.

---

## Practice 2 - Spring Boot 애플리케이션 배포

* OpenJDK 기반 Docker 이미지에 Spring Boot 애플리케이션 JAR 파일을 배포하는 실습입니다.
* Dockerfile을 통해 JAR 파일을 컨테이너에 복사하고, 애플리케이션을 실행합니다.
* 외부 포트를 통해 웹 애플리케이션에 접근 가능합니다.

---

## Practice 3 - MySQL 데이터베이스 컨테이너 구성

* Docker Compose를 이용해 MySQL 단독 데이터베이스 컨테이너를 실행합니다.
* 환경 변수로 데이터베이스 이름, 사용자, 비밀번호 등을 설정합니다.
* 로컬 디렉토리와 연동된 볼륨을 통해 데이터가 지속적으로 저장되도록 구성합니다.

---

## Practice 4 - Spring Boot + MySQL 통합 서비스 구성

* Spring Boot 애플리케이션과 MySQL 데이터베이스를 Docker Compose로 함께 실행하는 실습입니다.
* 각각의 컨테이너는 같은 네트워크로 연결되어 통신할 수 있습니다.
* 애플리케이션 컨테이너는 DB 컨테이너에 의존하며, 데이터베이스가 준비된 후 실행됩니다.
* 실제 프로젝트에서 흔히 사용되는 구성으로, 실무 감각을 익히는 데 유용합니다.

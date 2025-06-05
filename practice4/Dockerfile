# openjdk 베이스 이미지 (기본 환경)
FROM openjdk:17

# JAR_FILE 변수 선언
ARG JAR_FILE=./*.jar

# JAR 파일 메인 디렉터리 복사
COPY ${JAR_FILE} app.jar

# 시스템 진입 (실행 명령)
# CMD "java -jar app.jar"
ENTRYPOINT ["java", "-jar", "app.jar"]
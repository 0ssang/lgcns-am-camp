# 도커 이미지와 버전 명세
FROM golang:1.23.6

# 실행 후 컨테이너에 디렉토리 생성
RUN mkdir /goapp

# 호스트의 디렉토리의 파일을 생성한 컨테이너의 디렉토리로 복사
COPY main.go /goapp

# 컨테이너가 실행 될 때, 다음과 같은 인자들을 구동시켜줌
CMD ["go", "run", "/goapp/main.go"]
도커 파일 기본 개념
==========

Dockerfile
----------

## 개요
    Docker 이미지(image)화 하는 텍스트 정보 파일.
    Dockerfile 기록된 명령문을 순차적으로 수행하여 이미지를 생성.
## 위치
    프로젝트 최상위 디렉터리 Dockerfile 위치
## 문법	
    # 주석(Comment)
    명령어(INSTRUCTION) 인자(arguments)

## 용어
|명령어|용도|
|:---|:---|
|**FROM**|base 이미지 설정|
|**WORKDIR**|작업 디렉터리 설정|
|**RUN**|이미지 빌드 시 커맨드 실행|
|**ENTRYPOINT**|이미지 실행 시 항상 실행되야 하는 커맨드 설정|
|**COPY/ADD**|이미지의 파일 시스템으로 파일 또는 디렉터리 복사|
|**ENV**|환경 변수 설정|
|**ARG**|빌드 시 넘어올 수 있는 인자 설정|
|**EXPOSE**|컨테이너가 리스닝할 포트 및 프로토콜 설정|
|**CMD**|이미지 실행 시 디폴트 커맨드 또는 파라미터 설정|


## dockerignore
* 도커 빌드시 제외 할 정보

.dockerignore
	.git
	.md

## docker-compose

docker-compose.yml







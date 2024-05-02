# heartee-api-server
카카오톡 연애 상담 서비스, Heartee 백엔드 서버입니다. 

## Core Features
- 사용자가 업로드한 카카오톡 스크린샷에서, 대화 내역을 텍스트로 추출 (feat. Google API)
- 사용자의 대화 내역을 별도 chatGPT API 서버에 요청하여, 대화 내역에 대한 분석 결과 조회

## Tech Stack
- DB : PostgreSQL
- Server : Spring boot, Spring, Java
- Infrastructure : Docker & Docker-compose, AWS

## Running
### local DB
> docker compose -f docker-compose.local.yml up

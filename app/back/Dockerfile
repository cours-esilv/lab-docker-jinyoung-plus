# 베이스 이미지 선택
FROM python:3.8-slim

# 작업 디렉토리 설정
WORKDIR /app

# 현재 디렉토리의 파일을 작업 디렉토리로 복사
COPY . /app

# 의존성 설치
RUN pip install -r requirements.txt

# 애플리케이션 실행
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]

# 🕸️ Webcrawl Practice

웹크롤링 & API 학습 훈련을 위한 연습용 저장소입니다.  
Python 가상환경(`v_crawl`)에서 Requests, BeautifulSoup, Selenium, Scrapy, FastAPI 등을 사용해봅니다.  

---

## 📂 폴더 구조 (예정)
```

crawl/
├── requirements.txt   # 패키지 목록
├── 01\_requests\_bs4/   # Requests + BeautifulSoup 실습
├── 02\_selenium/       # 동적 페이지 크롤링
├── 03\_scrapy/         # 구조화된 크롤링
└── 04\_fastapi/        # API 서버 실습


````

---

## 🚀 시작하기

### 1. 가상환경 준비
```bash
python3 -m venv ~/venvs/v_crawl
source ~/venvs/v_crawl/bin/activate
````

### 2. 필수 패키지 설치

```bash
pip install -r requirements.txt
```

### 3. 예제 실행

```bash
cd 01_requests_bs4
python simple_crawl.py
```

---

## 🎯 학습 목표

* `requests` + `BeautifulSoup`으로 정적 웹 크롤링
* `selenium`으로 동적 페이지 크롤링
* `scrapy`로 구조화된 크롤러 개발
* `fastapi`로 수집 데이터 API 제공

---

## 📌 참고

이 저장소는 개인 학습/실습용으로 제작되었습니다.

```


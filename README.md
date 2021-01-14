# ft_server

---

## 목차

[1. 웹 서버란 무엇일까?]()

- [1-1. 웹 서버의 탄생]()
- [1-2. 웹 서버의 역할]()
- [1-3. 웹 서버의 종류]()
- [1-4. NGINX 설치하기]()
- [1-5. NGINX 설정하기]()
- [1-6. NGINX 구동하기]()
- [1-7. NGINX 확장하기]()

[2. Docker란 무엇일까?]()

- [2-1. Docker의 탄생]()
- [2-2. Docker의 역할]()
- [2-3. Docker 설치하기]()
- [2-4. Docker 이해하기]()
- [2-5. Docker 구동하기]()
- [2-6. Docker 이미지 빌드하기]()
- [2-7. Dockerfile 작성하기]()

## 1. 웹 서버란 무엇일까?

### 1-1. 웹 서버의 탄생

**1989년 3월**
유럽 입자 물리 연구소(CERN)의 **팀 버너스 리**(Sir Tim Berners-Lee)가 **하이퍼텍스트**를 사용하여 과학자들 간의 **정보 교환을 간편하게 하는 프로젝트**를 제안했습니다.

**1990년**
그리고 팀 버너스 리는 두 개의 프로그램을 개발했습니다.

- WorldWideWeb라고 불리는 **웹 브라우저**
- 세계 최초의 **웹 서버**

![640px-First_Web_Server](https://user-images.githubusercontent.com/19530862/104561502-da20f280-568a-11eb-9d32-766ee93ed2c2.jpg)

**1991년 ~ 1994년**
초기 World Wide Web는 정보 교환의 단순성과 효율성을 바탕으로 다른 많은 운영체제로 포팅되었고, 과학계, 대학교 그리고 산업계까지 영향력을 넓혔습니다.

**1994년**
팀 버너스 리는 다양한 기술(HTTP, HTML 등)의 개발을 **표준화**하여 규정하기 위해 [W3C](https://www.w3.org/)(World Wide Web Consortium)을 구성했습니다.

![W3C](https://user-images.githubusercontent.com/19530862/104562823-333d5600-568c-11eb-999b-cad358f0e946.png)

출처 : [Wikipedia](https://en.wikipedia.org/wiki/Web_server#History)

### 1-2. 웹 서버의 역할

**하드웨어 측면**

- 웹 서버는 **웹 서버 소프트웨어**와 **웹 사이트의 컴포넌트 파일**(HTML, 이미지, CSS, Javascript)들을 저장하는 컴퓨터입니다.
- 웹 서버는 인터넷에 연결되어 웹에 연결된 다른 기기들이 **웹 서버의 데이터**(컴포넌트 파일)**을 주고받을 수 있도록 합니다.**

**소프트웨어 측면**

- 웹 서버는 웹 사용자가 어떻게 호스트 파일들에 **접근하는지를 관리**합니다. 아래에서 다룰 웹 서버는 HTTP 프로토콜을 사용하는 서버이고, HTTP 서버는 **URL**(웹 주소)과 **HTTP**(브라우저와 웹 서버가 정보를 주고받기 위해 사용하는 프로토콜)**를 이해하는 소프트웨어입니다.**

![web_server](https://user-images.githubusercontent.com/19530862/104557523-b8bd0800-5684-11eb-98f9-c8f2d3e90089.png)

> **브라우저가 HTTP를 통해 웹 서버로 파일을 요청합니다. 요청이 올바른 웹 서버(하드웨어)에 도달하였을 때, HTTP 서버(소프트웨어)는 요청된 파일을 HTTP를 이용해 브라우저로 보내줍니다.**

출처 : [MDN Web Docs](https://developer.mozilla.org/ko/docs/Learn/Common_questions/What_is_a_web_server)

### 1-3. 웹 서버의 종류

![webserver_graph](https://user-images.githubusercontent.com/19530862/104565292-69c8a000-568f-11eb-9f58-c8dddd911041.png)
![webserver_rank](https://user-images.githubusercontent.com/19530862/104565311-73ea9e80-568f-11eb-8aba-88f8171e47e6.png)

### 1-4. NGINX 설치하기

### 1-5. NGINX 설정하기

### 1-6. NGINX 구동하기

### 1-7. NGINX 확장하기

## 2. Docker란 무엇일까?

### 2-1. Docker의 탄생

### 2-2. Docker의 역할

### 2-3. Docker 설치하기

### 2-4. Docker 이해하기

### 2-5. Docker 구동하기

### 2-6. Docker 이미지 빌드하기

### 2-7. Dockerfile 작성하기

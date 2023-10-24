# WireShark Packet Analysis
2020년 1학기 컴퓨터네트워크 Project: WireShark Packet Capture and Analysis

## 📢 프로젝트 소개
WireShark Packet 분석을 통해 프로토콜을 이해하는 프로젝트입니다.

## 📆 개발 기간
2020.03.28 ~ 2020.04.15

## 🔑 Content

### 1. Summarize the content of DNS request response message.

- DNS 표준 포트인 포트5 33번으로 Capture filter 검색한 후 DNS 요청을 보내고 응답 코드를 분석한다.

### 2. Check TCP connection setup process before HTTP.

- HTTP를 확인하기 위해서 Capture filter port를 8080으로 검색하고 TCP 연결을 확인한다.

### 3. Summerize the contents and meaning for the HTTP request and response message for the first time.

- Request message, Header line, Response message를 분석한다.

### 4. Data transfer process

- TCP connection (Three way Handshaking) 과정에서의 데이터 전송을 분석한다.

### 5. Analyze whether persistent or non-persistent connection.
- HTTP는 Non-persistent Connections으로 연결을 매번 끊고 새로 연결하는 방식을 취하기 때문에 시간과 비용적인 측면에서 비효율적이었다. 이를 해결하기 위해 HTTP1.1부터는 Keep-Alive의 기능을 제공한다. 
- 이 실험에서는 HTTP1.1를 사용한다. 즉, persistent connection(지속연결)이다.

### 6. Write what protocols other than HTTP and DNS appear.

- 파일 전송 프로토콜(File Transfer Protocol, FTP)이 있다. FTP는 TCP/IP 프로토콜을 가지고 서버와 클라이언트 사이의 파일 전송을 하기 위한 프로토콜이다. 파일 전송 프로토콜은 TCP/IP 프로토콜 테이블의 응용 계층에 속한다. 명령 연결(21)과 데이터 전송용 연결(20)이 가능하다.
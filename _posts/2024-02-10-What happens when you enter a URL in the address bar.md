---
layout: post
title:  "What happens when you enter a URL in the address bar"
date:   2024-02-10
categories:
---

# What happens when you enter a URL in the address bar?

브라우저에 주소를 입력하면 다음과 같은 일련의 과정이 일어납니다:

1. 사용자 입력: 브라우저 주소 표시줄에 웹 페이지의 URL(Uniform Resource Locator)을 입력합니다.
2. DNS 조회: 브라우저는 입력된 URL의 호스트명을 해석하기 위해 DNS(Domain Name System) 서버에 쿼리를 보냅니다. DNS는 호스트명을 해당 호스트의 IP 주소로 변환하는 역할을 합니다.
3. 서버 연결: 브라우저는 얻어진 IP 주소를 사용하여 웹 서버에 연결을 시도합니다. 이때 일반적으로 사용되는 포트는 80(HTTP) 또는 443(HTTPS)입니다.
4. HTTP 요청: 브라우저는 웹 서버에게 웹 페이지나 리소스를 요청하는 HTTP(Hypertext Transfer Protocol) 요청을 보냅니다. 이 요청은 사용자 에이전트(브라우저)와 서버 간의 통신을 위한 규약을 정의합니다.
5. 서버 응답: 웹 서버는 요청받은 페이지 또는 리소스에 대한 응답을 생성하고, 이를 브라우저로 전송합니다. 응답은 HTML, CSS, JavaScript 및 기타 리소스로 구성될 수 있습니다.
6. 페이지 렌더링: 브라우저는 받은 응답을 해석하고, 웹 페이지를 렌더링합니다. 이 과정에는 HTML 문서의 파싱, CSS 스타일 적용, JavaScript 실행 등이 포함됩니다.
7. 페이지 표시: 최종적으로 브라우저는 렌더링된 웹 페이지를 사용자에게 표시합니다.

이러한 과정을 통해 사용자는 브라우저를 통해 입력한 주소에 해당하는 웹 페이지를 볼 수 있습니다.

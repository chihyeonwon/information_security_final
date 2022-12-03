# information_security_final

## 4장 웹보안

1. 최초의 네트워크는?
```
ARPA
```
2. 다음과 같이 URL을 통해 요청 데이터에 대한 인수를 전송하는 HTTP Request방식은?
```
www.wishfree.or.kr/list.php?page=1&search=test
```
GET방식

3. 동적인 웹 페이지를 위한 서버 측 웹 스크립트 언어가 아닌것은?
```
동적 웹 페이지 서버 측 웹 스크립트 언어 : JSP, PHP, 자바스크립트   
아닌 것 : ASP(Application Service Provider) : 인터넷을 이용해 응용프로그램을 임대, 관리하는 사업자 <-> SaaS : 개인이나 회사가 소프트웨어를 필요한만큼 임대하는 것 요즘은 ASP에서 SaaS로 넘어가는 추세   
```
4. 구글에서 특정 도메인이 들어 있는 사이트에 대한 정보를 수입할 때 사용하는 검색 인자는?
```
site : 특정 도메인으로 지정한 사이트에서 검색하려는 문자열   
filetype : 특정 파일 유형에 한해 문자열   
inurl : 페이지 URL에 검색하는 문자열   
```
5. 구글 검색 엔진에서 검색할 수 없도록 하기 위해 만드는 파일은?
```
robots.txt
```
6. 7.SQL 삽입 공격이 가능한 경우에 대해 간단히 설명하시오.
```
Where 조건문 앞에 'or''='을 입력하거나 'or''='--으로 주석처리 표시 또는 'or''1='1 결과적으로 참이 되는 경우를 쓴다.
```
8. 웹 서버의 세션 관리 측면에서 사용자 데이터를 이용한 인증으로 인해 발생할 수 있는 문제점을 간단히 설명하시오.
```
공격자가 세션인증을 그대로 사용하고 UserNo 값만 변경하여 다른 계정으로 로그인한 것처러 웹 서비스를 사용할 수 있다.
```
9. 웹 사이트에서 각각의 개인을 구별하기 위해 클라이언트에 저장해두는 것은?
```
쿠키 cookie
```
10. XSS 취약점 공격을 수행하는 단계를 순서대로 나열하시오.
```
임의의 XSS 취약점이 존재하는 서버에 XSS 코드를 작성하여 저장한다.   
공격자가 작성해둔 XSS 코드에 웹 서비스 사용자가 접근한다.   
웹 서버는 사용자가 접근한 XSS 코드가 포함된 게시판의 글을 전달한다.   
사용자 시스템에서 XSS 코드가 실행된다.   
XSS 코드가 실행된 결과는 공격자에게 전달되고 공격자는 공격을 종료한다.
```
11. 파일 다운로드 시 디렉터리를 탐색하여 파일을 다운로드하는 것을 막기 위해 필터링해야 하는 문자열은?
```
..나 /
```
12. PASS
13. 파일 목록을 열람할 수 있는 취약점은?
```
디렉터리 리스팅(Directory Listing)
```
14. 리버스 텔넷에 대해 간단히 설명하시오.
```
웹 해킹으로 시스템 권한을 획득한 후 해당 시스템에 텔넷과 같이 직접 명령을 입력하고 확인할 수 있는 셸을 획득하기 위한 방법입니다.
```
15. 다음 중 웹 취약점을 보완하는 방안으로 적절하지 않은 것은?
```
취약점을 보완하는 방안 3가지   
특수 문자 필터링, 서버 통제 적용, 지속적인 세션 관리   
   
취약점 보완으로 적절하지 않은 방안   
클라이언트 통제 적용 : 클라이언트 기반으로 통제하면 웹 프록시를 통해 웹 브라우저로 가는데 이 때 변조가 발생할 수 있기 때문
```
16. 다음 중 CSRF 취약점의 특징이 아닌것은?
```
CSRF란 Cross-Site Request Forgery로 서버에 사용자가 악성 코드를 요청하는 방식   
특정 소수가 아닌 불특정 다수를 대상으로 하며   
원래 의도된 기능이 아닌, 데이터의 변경, 삭제 등이 가능해진다.   
XSS에서 진보한 공격이라고 보는 의견이 있다.   
또 XSS는 클라이언트에서 사용자가 요청하는 반면 CSRF는 서버에서 사용자가 악성코드를 요청한다.
```
17. HTTP 요청 메서드가 아닌 것은?
```
HTTP 요청 메서드 : GET, POST, PUT   
HTTP 요청 메서드가 아닌 것 : PUSH
```
18. 다음에서 설명하는 웹 공격 기법은?
```
게시판의 글에 원본과 함께 악성 코드를 삽입하여, 글을 읽을 경우 악성 코드가 실행되도록해서 클라이언트의 정보를 유출하는 클라이언트에 대한 공격 기법
   
답은 XSS(Cross Site Scripting) 공격
```


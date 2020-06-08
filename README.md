# DotNetMVC
ASP.Net을 이용한 MVC 예제를 연습합니다.

[닷넷 가이드](https://docs.microsoft.com/ko-kr/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-3.1&tabs=visual-studio-code "마소 가이드")

* 웹앱 생성
```javascript
dotnet new mvc -o MvcMovie
code -r MvcMovie
```

* 앱 실행 → 개발인증서를 신뢰해준다.
```javascript
dotnet dev-certs https --trust
```
1) 디버그 없이 실행(ctrl + F5)해주거나

2) 명령어로 실행
```javascript
dotnet run
```

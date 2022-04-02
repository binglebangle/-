# HTTP는 무엇일까요?
## HTTP (Hyper Text Transfer Protocol)
>HTML 문서와 같은 리소스들을 가져올 수 있도록 해주는 프로토콜   
웹에서 이뤄지는 모든 데이터 교환의 기초   
클라이언트 - 서버 프로토콜 이라고도 불림
> ## 클라이언트 - 서버 프로토콜?
>   > 수신자 측에 의해 요청이 초기화되는 프로토콜   
하나의 완전한 문서는 텍스트, 레이아웃 설명, 이미지, 비디오, 스크립트 등 불러온 하위 문서들로 재구성 됨
## 특징 
> ### HTTP는 무상태 프로토콜이다
> 서버가 두 요청 간에 어떠한 상태나 데이터를 유지하지 않음   
>클라가 서버에게 “저녁에 치킨먹자”고 말했고 서버가 “그래”라고 답했다.
저녁이 되어 클라는 서버에게 “먹으러 가자”고 말했고 서버는 대답했다. “뭘?”
> ### HTTP는 일반적으로 TCP/IP 프로토콜을 사용하는 응용 프로토콜이다
> 컴퓨터 간에 데이터를 전송할 수 있도록 하는 장치로 인터넷을 이용하여 정보(데이터)를 주고받는 기능을 가진 프로토콜
> ### HTTP는 간단하다
> ### HTTP는 비연결성 프로토콜이다
> 요청과 응답의 방식으로 작동함   
> 응답 속도가 빠름

## 동작방식
> 클라이언트가 브라우저를 통해서 어떠한 서비스를 URL을 통해 서버에 요청하면 서버에서는 해당 요청에 대한 결과를 응답하는 형태로 동작함   
> 브라우저(클라이언트)는 항성 요청을 보내는 개체로 HTTP요청 내에서 응답받은 지시 사항들을 변환하고 해석하여 사용자에게 명확한 응답을 표시함

> ### HTTP 요청 메소드
> - GET
> > 특정 리소스를 받기 위한 요청
> - POST
> > 리소스를 생성하거나 컨트롤러를 실행하는 데 사용
> - PATCH
> > 변경 가능한 리소스의 부분 업데이트에 사용   항상 리소스 식별 정보를 포함해야 한다
> - DELETE
> > 특정 리소스를 제거하는 데 사용
> - HEAD
> > 클라이언트가 본문 없이 리소스에 대한 헹더만 검색하는 경우에 사용   
> -  OPTIONS
> > 클라이언트가 서버의 리소스에 대해 수행 가능한 동작을 알아보기 위해 사용   
<img scr = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fc7mI3U%2FbtqWX45M76d%2FgGoVLK6rcUJhekrxMcq6a1%2Fimg.png">
> ### HTTP 응답 메소드
> - 1xx informational response(조건부 응답)   
> - 2xx Success(성공)   
> - 3xx Redirection(리다이렉션, 경로 재지정)   
> - 4xx Client Error(클라이언트 오류)   
> - 5xx Server Error(서버 오류)    
<img scr = "https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FCmjnf%2FbtqWTYTN3X1%2F34p8xLsQtEIk0xMzyjIw8k%2Fimg.png">
---
sort: 2
---

# gpt api project


챗Gpt의 시대에 나도 전공자로서 뭐라도 만들어야겠다고 생각했다.    

방법)    

```note
도메인 하나를 구입한다. (할인: 1년에 500원).    
Openai 페이지에서 api key를 받아온다.   
해당 키로 chatgpt api를 이용하여 답변을 리턴하는 python 코드를 작성한다.    
네트웍에 연결된 라즈베리파이에 flask웹서버 코드를 python으로 작성한다.    
공유기 관리자로 들어가 5000번 포트를 외부ip에서 포트포워딩 설정한다.    
웹서버에 gpt api 코드를 얹어서 기동한다.    
로컬 웹서버 ip를 도메인 구입한 사이트에서 연결한다.    

```
 
몇단계를 빼먹은듯 하지만 쉽다면 쉽고 어렵다면 어려운 토이 프로젝트.    
응용해서 다른것을 해볼 수 있다는게 중요하다.

![image](https://user-images.githubusercontent.com/48585035/231929569-0f5c5d52-819f-40cb-8976-8a8b76e2d6ab.png)    
![image](https://user-images.githubusercontent.com/48585035/231929593-17f885d3-77bc-4abf-9ec8-4f88a3095ef9.png)

결과 페이지:    
[www.chobyungwoo.shop:5000](http://wew.chobyungwoo.shop:5000)

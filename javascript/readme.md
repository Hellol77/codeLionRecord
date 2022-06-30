## DOM

문서 객체 모델(The Document Object Model, 이하 DOM) 은 HTML, XML 문서의 프로그래밍 interface 이다. DOM은 문서의 구조화된 표현(structured representation)을 제공하며 프로그래밍 언어가 DOM구조에 접근할 수 있는 방법을 제공하여 그들이 문서 구조, 스타일, 내용 등을 변경 할 수 있게 돕는다. DOM은 nodes와 objects로 문서를 표현한다. 이들은 웹 페이지를 스크립트 또는 프로그래밍 언어들에서 사용될 수 있게 연결시켜주는 역활을 담당한다.

document.getElementById('id값')

document.getElementsByTagName('태그 이름')

document.getElemetsByClassName('class 값')

---

document.querySelector('css선택자')

document.querySelectorAll('css선택자')

---

innerHTML

classList

---

Event : 어떤'사건'을 발생 시키는 것

Event type : 이벤트의 종류를 나타내는 문자열

---

EventTarget.addEventListener('eventType',function,useCapture)

---

data 어트리뷰트와 dataset 프로퍼티

---

동기 : 직렬적으로 순서대로

비동기 : 병렬적으로 먼저 끝나는대로.

fetch("").then().then() : 비동기

---

promise : 비동기로 처리해야하구나

promise 상태 :

1. pending: 프로미스 처리중

2. fulfilled : 프로미스 이행(정상처리완료)

3. Rejected : 프로미스 실패(처리완료 하지만 비정상적으로)

---

비구조화 할당

const {name,age} = me

const a =obj.a
const b =obj.b

const {a,b} = obj

---

spread : ... obj는 obj , array 는 array로만

... : 내용물을 spread하겠다.

---

api : application programming interface

REST API : url은 정보의 자원을 표현해야한다. 자원에 대한 행위는 http method(get,post,put,delete)로 표현한다.

---

POST : POST를 통해 해당 url를 요청하면 리소스를 생성합니다.
GET : GET를 통해 해당 리소스를 조회, 리소스를 조회하고 해당 도큐먼트에 대한 자세한 정보를 가져온다.

---

Fetch : js의 내장 라이브러리 IE 지원 x 일부기능 부족

Axios : 외부 라이브러리 모듈 설치 필요, 크로스 브라우징 가능, Response timeout 처리 등 다양한 기능 존재

---



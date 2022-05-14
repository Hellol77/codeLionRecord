pip install requests

request.get : get 요청을 보내는 기능




client 요청하는 존재

server 응답을 하는 존재

from bs4 import BeautifulSoup
BeautifulSoup(response.text, 'html.parser')

type : 타입을 확인

open("daum.html","w",encoding="UTF-8") : html파일 만들기 

print(soup.findAll('a',"link_favorsch")) : 모든 a태그출력 그리고 class가 link_favorsch가 있는 것만 출력

from datatime import datatime 실시간 출력을 위해 모듈 사용

print(datetime.today().strftime("%Y년 %m월 %d일의 실시간 검색어 순위입니다.\n"))

search_rank_file.write(str(rank)+"위:"+result.get_text()+"\n") : 파일에 쓰는 작업

headers : 우린 로봇이 아니야 알려주는

headers=headers

---

API = application programming interface

api를 사용한다 :  누군가 만들어 놓은 기능을 사용한다.

api key : 누가 사용하는지 전달해주는 원하는 데이터 얻을 수 있게

---

gooletrans 라이브러리 : 언어 감지 및 번역


언어감지

1. 번역기를 만든다

2. 언어감지를 원하는 문장을 설정

3. 언어를 감지한다.

언어번역

1. 번역기를 만든다

2. 번역을 원하는 문장을 설정한다.

3. 번역을 원하는 언어를 설정한다.

4. 번역한다.

---

from googletrans import Translator

translator=Translator()

translator.detect(sentence) : 언어 감지

.lang : 무슨 언어인지

.translate(text,dest,src) : (번역을 원하는 문장, 어떤 언어로 번역할 것인지, 소스 텍스트(생략가능) )

.text를 사용해 결과 출력
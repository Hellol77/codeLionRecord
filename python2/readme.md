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

headers : 우린 로봇이 아니야

headers=headers


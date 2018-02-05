inhun_discord_chat_bot
============

- - -

모듈 설명
 -------------

> 모두 인헌고등학교 기준 입니다.
>
> 인헌고등학교 홈페이지를 기반으로 만들었습니다.

datematch.py 는 날짜를 홈페이지에 보낼 값으로 바꿔 줍니다.
ㄴ이유: 학교 홈페이지 사이트 구조가 많이 심각

scrapture.py 는 홈페이지에서 정보를 긁어와 필터링 해줍니다.


- - -

요구 사항
---------
- inhun_bot.py (main)
  - __python 3.4.2+__
  - __discord.py__
  - __aiohttp__ library
  - __websocket__ library
  - __datetime__ library

- scrapture.py
  - __requests__ library
  - __BeautifulSoup4__ library
  - __regex__ library

- - -

실행
-----------

>python3 inhun_bot.py

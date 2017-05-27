# kikka
hikvision 

http://www.hikvision.msk.ru/forum/26-3729-1 - описание


Залить ip диапазоны в scan.txt


"bash kikka start scan.txt"  - отсканит массканом диапазоны и пройдет по ним wget'oм

Дополнительные фунцкии:

scan

brute - wget по списку ip из res.txе

rec  $IP - циклически скачивает картинку в rec_IP/  Пример ./kikka rec 127.0.0.1



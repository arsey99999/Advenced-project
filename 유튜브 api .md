
가상환경(mysite)에 유튜브 라이브러리 pip해야함
pip install pytube
pip install google-api-python-client

그러고 나서 (mysite)에 mygration
python manage.py makemigrations
python manage.py migrate 

후 youtube_api\scripts가서 긁어오는 동작 키기 
(mysite) d:\projects\mysite>cd youtube_api\scripts
(mysite) d:\projects\mysite\youtube_api\scripts>python fetch_videos.py

다시 mysite로 나와서 서버 키고 확인 
(mysite) d:\projects\mysite>python manage.py runserver

http://127.0.0.1:8000/youtube/ 주소 치고 들어가서 확인 

# kjh_20223144

## 20223144 ***김준휘*** 오픈소스SW개론 과제


+ **리눅스 명령어에서...**

|명령어|설명|
|:---|:---|
|top|실시간으로 CPU사용률을 체크해주는 명령어|
|ps|현재 실행준인 프로세스 목록을 보여주는 명령어|
|jobs|작업의 상태를 표시하는 명령어|
|kill|프로세스를 종료시키는 명령어|

1) top

리눅스에서 top을 칠 경우 아래 화면 같이 나옴

<img src="https://user-images.githubusercontent.com/106733778/171848386-f06cb756-68ba-44f0-b17e-bcce2bf09ac2.png" width="1920" height="1080">

page down 프로세스의 다음페이지

page up 프로세스의 이전페이지

shift + p CPU 사용률이 높은 프로세스 순서대로 표시

shift + m 메모리 사용률이 높은 프로세스 순서대로 표시

shift + t 프로세스가 돌아가고 있는 시간 순서대로 표시
등등

2) ps

리눅스에서 ps를 칠 경우 아래 화면 같이 나옴

<img src="https://user-images.githubusercontent.com/106733778/171851281-ffea8cf5-c02b-4111-86ce-f451c1ac064c.png" width="1920" height="1080">

ps -e 모든 프로세스를 출력해준다
ps -f 풀 포맷으로 보여준다
ps -l 김 포맷으로 보여준다
ps p, ps -p 특정 PID의 프로세스를 보여준다
ps -u 특정 사용자의 프로세스를 보여준다

3) jobs


+ **vim 에디터에서...**

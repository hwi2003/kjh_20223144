# kjh_20223144

## 20223144 ***김준휘*** 과제


## + **리눅스 명령어에서...**

|명령어|설명|
|:---|:---|
|top|실시간으로 CPU사용률을 체크해주는 명령어|
|ps|현재 실행준인 프로세스 목록을 보여주는 명령어|
|jobs|작업의 상태를 표시하는 명령어|
|kill|프로세스를 종료시키는 명령어|

### 1) top

리눅스에서 top을 입력  경우 아래 화면 같이 나옴

<img src="https://user-images.githubusercontent.com/106733778/171848386-f06cb756-68ba-44f0-b17e-bcce2bf09ac2.png" width="1920" height="1080">

page down 프로세스의 다음페이지

page up 프로세스의 이전페이지

shift + p CPU 사용률이 높은 프로세스 순서대로 표시

shift + m 메모리 사용률이 높은 프로세스 순서대로 표시

shift + t 프로세스가 돌아가고 있는 시간 순서대로 표시
등등

### 2) ps

리눅스에서 ps를 입력 할 경우 아래 화면 같이 나옴

<img src="https://user-images.githubusercontent.com/106733778/171851281-ffea8cf5-c02b-4111-86ce-f451c1ac064c.png" width="1920" height="1080">
|옵션|설명|
|:---|:---|
|ps -e| 모든 프로세스를 출력해준다|
|ps -f| 풀 포맷으로 보여준다|
|ps -l| 김 포맷으로 보여준다|
|ps p, ps -p| 특정 PID의 프로세스를 보여준다|
|ps -u| 특정 사용자의 프로세스를 보여준다|

### 3) jobs

|상태|설명|
|:---|:---|
|Running|작업이 계속 진행중임|
|Done|작업이 완료되어 0을 반환|
|Stopped|작업이 일시중단|

|옵션|설명|
|:---|:---|
|jobs -l| 프로세스 그룹 ID를 state필드 앞에 출력|
|jobs -n| 프로세스 그룹  중에 대표 프로세스 ID를 출력|
|jobs -p| 각 프로세스 ID에 대해 한 행씩 출력|

### 4) kill

프로세스 죽이는 명령어

kill [OPTION] [PID]

kill -l을 통해 옵션을 알 수 있습니다

<img src="https://user-images.githubusercontent.com/106733778/171854342-149283b1-bfc8-42c7-8e82-980ed8862266.png" width="1920" height="1080">

기본값은 -15(-term)입니다

## + **vim 에디터에서...**

커맨드 모드상태에서

'q'를 누른다

a~z 사이 문자를 눌른다 ***매크로 기록 시작***

매크로 내용제작

커맨드 모드로 돌아와서 'q'를 눌른다 ***매크로 기록 끝***

커맨드 모드 상태에서 @+a~z를 입력 ***매크로 작동***

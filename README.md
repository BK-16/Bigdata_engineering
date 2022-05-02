# https-github.com-BK-16
## 빅데이터 엔지니어링 실습 과제 2
### 제출 자료 : 
1. Git 로컬 저장소(압축)
2. 원격저장소 url
### 과제
(1) Github 에 rock_paper_scissors 라는 이름의 원격저장소 생성
- 주소 예시) https://github.com/Jonghyuk-Kookmin/rock_paper_scissors.git
- Public 저장소로 생성
(2) 각자 원하는 경로(예: 바탕화면)에 ‘rps’라는 이름의 폴더를 생성하고, eCampus 홈페이지에서
rock_paper_scissors.py 다운로드 받아 생성 폴더에 위치시킨 후, 로컬저장소 생성
(3) 다운로드 받은 rock_paper_scissors.py 이 포함된 첫 번째 커밋 생성
- 커밋 메시지 : 첫 번째 커밋
(4) 현재까지 작업한 내용을 Github ‘rock_paper_scissors’ 원격 저장소에 푸시
(5) 브랜치 생성 후 생성한 브랜치로 체크아웃
- 브랜치 이름 : feature/player
(6) eCampus 에서 player.py 파일을 다운받아, 구현되어 있는 코드 전부(Player 클래스, 상수, import
문)를 복사하여 rock_paper_scissors.py 에 덮어씌워 아래와 같은 코드가 담긴 파일 생성
(7) rock_paper_scissors.py 의 수정이 반영된 커밋 진행
- 커밋 메시지 : Player 클래스 구현
(8) 원격 저장소에 새롭게 생성 및 변경된 feature/player 브랜치 푸시
(9) master 브랜치로 체크아웃 한 후, 아래 그림과 같이 상수를 정의하고 이러한 변경이 반영된 두 번째
커밋 생성
- 커밋 메시지 : 가위 바위 보 상수 추가
(10) 원격 저장소에 master 브랜치 푸시
(11) feature/player 브랜치를 master 브랜치를 기준으로 병합(master 브랜치에 feature/player
브랜치의 변경사항 반영, 충돌이 발생한다면 feature/player 의 변경사항을 반영)하고 커밋
- 만약 충돌이 발생했다면, 커밋 메시지는 자동 생성되는 메시지 그대로 사용
(12) 원격 저장소에 master 브랜치 푸시

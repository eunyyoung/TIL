# TIL day01

> Git 특강 1일차

## 1. CLI 기초

#### [GUI와 CLI]
**GUI (Graphic User Interface)** : 그래픽을 통해 사용자와 컴퓨터가 상호 작용하는 방식
**CLI (Command Line Interface)** : 터미널을 통해 사용자와 컴퓨터가 상호 작용하는 방식



#### [경로]
**루트 디렉토리 (/)**
	- 모든 파일과 폴더를 담고 있는 최상위 폴더

**홈 디렉토리 (~)**
 - 현재 로그인 된 사용자의 홈 폴더를 의미
 - Mac의 경우 /Users/현재 사용자 계정을 의미

    *#폴더와 디렉토리는 거의 같은 의미로 사용되므로  의미의 구분이 무의미함.*

**절대경로**

**상대경로**
#### [터미널 명령어]
1. 폴더 만들기
mkdir CLI
mkdir 'multi campus' (띄어쓰기 구분)

2. 터미널 초기화 : ctrl + L

3. 파일 및 폴더의 목록
   ls
   ls -a : 숨김까지 모두
   ls -l : 자세히 보기
   ls -a -l
   ls -l -a
   ls -al
4. 폴더 이동
   cd CLI
   . 은 내 자신
   .. 은 부모(상위)
   cd ~ : 홈으로 이동 (cd)
   cd /c/Users/student/CLI/
5. 파일 만들기
   touch a.txt
   touch a.txt b.txt c.txt
6. 파일과 폴더 지우기
   rm a.txt (파일 지우기)
   rm -r test (폴더 지우기)	*-r : recursive 재귀적*


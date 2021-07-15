# 블록체인 특강

2021.07.14



## 1. 환경설정

### 1. chocolatey(choco)설치

url: https://chocolatey.org/

[Chocolatey](https://chocolatey.org/) 는 Mac OS X 의 [Homebrew](http://brew.sh/index_ko.html) 나 Linux 의 yum, apt-get 같은 역할을 수행하는 [NuGet](https://www.nuget.org/) 기반의 윈도우용 패키지 관리자입니다.

1. Powershell을 관리자 모드로 실행

2. `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))` 명령어 입력

### 2. Windows 터미널 설치

윈도우 터미널을 더욱 편리하고 캐주얼하게 업데이트

1. Powershell을 재실행

2. `choco install microsoft-windows-terminal` 명령어 입력



### 3. Virtualbox 설치

URL: https://www.virtualbox.org/

설치가이드: https://xxsiyoung.tistory.com/2

1. `choco install virtualbox` 명령어 실행



### 4. Vagrant 설치

URL: https://www.vagrantup.com/





2021.07.15

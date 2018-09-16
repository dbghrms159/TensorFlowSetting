# TensorFlowSetting
TensorFlow 

# Python 설치 및  pip설치 
    window 버전 
      1.http://www.python.org/ 링크에 가서  python 최신 버전을 설치를 한다.
      2.환경변수 설정
        내컴퓨터 우 클릭 > 속성 > 고급 시스템 설정 > 고급 탭 > 환경변수 > 팝업 
        path 값에 python 위치 추가 (ex. C:\Users\<사용자계정>\AppData\Local\Programs\Python\Python37-32 & C:\Users\<사용자계정>\AppData\Local\Programs\Python\Python37-32\Scripts)
        잘 됬는지 확인 하기 위해 cmd창에 python 명령어 입력해보면된다.
      3.pip를 설치하기위해 cmd 창에서 easy_install pip 명령어 입력
      
  
    mac 버전
      1. python을 설치
      2. 터미널에  sudo python get-pip.py 명령어 입력
      3. 버전 확인 pip -V 명령어 

# Anaconda 설치
    1. https://repo.continuum.io/archive/Anaconda3-4.2.0-Windows-x86_64.exe 링크를 누르면 다운로드가 된다.
    2. 설치 하다 Just Me 를 All Users 로 바꿔주고 next 누른다 

# TensorFlow 설치
    1. pip 업그레이드 python -m pip install --upgrade pip 명령어 실행
    2. conda 환경 만들기 conda create -n tensorflow python=3.5 명령어 실행 (엑세스 거부시 cmd 관리자 권한으로 실행)
    3. TensorFlow 설치하기 activate tensorflow 명령어 실행하면 (tensorflow) > 이렇게 되는데 pip install tensorflow 명령어 실행

# TensorFlow Test
<br>
![image](https://user-images.githubusercontent.com/38156821/45592113-e5bb5c00-b99f-11e8-91d8-f7be39aa905f.png)
<br>

# Error note
    Your CPU supports instructions that this TensorFlow binary was not compiled to use: AVX2
    원인 최신 CPU에서 신규 명령어를 지원하니 바젤이라는 빌드 시스템을 이용하여 빌드하여 사용하기 바란다는 의미 window 에서 빌드하기 힘듬 리눅스 추천 

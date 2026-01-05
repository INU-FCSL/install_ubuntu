
# Install_ubuntu
How to install Ubuntu


- 작성 : 박정우
- 작성일 : 25/12/06
- 단계 : 초안 (추후 변경될 수 있음)
  
가능하면 VM(가상머신)말고, 듀얼부팅 모드로 설정하길 추천

## 1.SD카드 준비 (최소 16GB)
## 2.ubuntu 이미지 파일 다운로드
연구실 및 로보컵 기준 22.04 LTS Desktop 이미지 파일 다운로드

https://releases.ubuntu.com/jammy/

*상황에 따라 버전이 다를 수 있음. 버전에 맞게 다운로드 

## 3. 이미지 파일 SD카드에 넣기
**Etcher**, **rufus** 를 이용하여 이미지 파일은 SD에 굽기

+ Etcher : https://etcher.balena.io/

+ rufus : https://rufus.ie/ko/

## 4. 설치하고자 하는 노트북 or 데스크탑에 SD카드 플러그
SD카드 리더기 혹은 usb포트 확장자를 이용해서 SD카드를 인식

재부팅시 bios에 들어가서 입력된 SD카드를 부팅 설정.

*bios 진입 버튼(del,F12,F11)은 메인보드사에 따라 다르니 구글에 검색해서 확인

### 디스크 관리
디스크 한개로 window와 ubuntu를 동시에 돌리는 것이기 때문에 디스크 파티션 관리가 중요. (**잘못하면 윈도우 날아갈 수 있음**)

자동으로 설치 용량을 잡아주기는 하지만 가능하면 window에서 파티션을 나누고 ubuntu를 설치하는 것이 best

참고 영상 - https://www.youtube.com/watch?v=KR_A_qjzSmY&list=PL0xYz_4oqpvhj4JaPSTeGI2k5GQEE36oi&index=2


## 5. Ubuntu 설치 완료 및 기본 설정

앞으로 우리는 ROS2를 작업하기 위해서 간단한 세팅을 진행할 예정.

https://www.youtube.com/watch?v=z5tXW9davEQ&list=PL0xYz_4oqpvhj4JaPSTeGI2k5GQEE36oi&index=3

위의 링크를 타고 기본적인 ubuntu 세팅 및 ROS2 기본 강의 진행.

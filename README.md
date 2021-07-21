`CALL 0x706f7274666f6c696f`
-----------------------------

# 👨‍💻 **About Me**

- **Contact Info**
  - Email : choi.junyoung.20.04@gmail.com
  - Name : 최준영 / Choi Junyoung
  - Blog : https://jun-project-lab.github.io/

고등학교에서 **네트워크**를 전공하였으며 현재는 **정보보안**을 공부하고 있습니다. 정보보안 중 관심있는 분야는 Reversing Engineering과 System Hacking 입니다. 향후 ZeroDay 취약점 등을 찾아낼 수 있는 연구원을 목표로 공부하고 있습니다. 

* * *

# 🛠️ **Skills**

- Programing Language

> **Basic**
```
- 해당 언어의 기초에 대해 알고 있으며 간단한 예제에 대해서 동작 방식을 해석할 수 있음.
```

<img alt="Java" src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white"/> <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/> <img alt="Shell Script" src="https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white"/>

> **Intermediate**
```
- 해당 언어를 사용하여 간단한 목적의 프로그램을 제작 및 기본적인 해석이 가능함.
- 다양한 라이브러리, 심화적인 기술에 대해서는 부족한 점이 있음.
```

<img alt="C" src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white"/> <img alt="PHP" src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white"/> <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img alt="Python" src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white"/>

- Application

> **Intermediate**
```
- Service를 구축하기 위한 기본적인 설정법을 알고 있으며 요구사항에 맞춰 옵션 설정이 가능함.
```

<img alt="Apache" src="https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white"/> <img alt="Nginx" src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"/> <img alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"/> <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"/>

- Network

> **Basic**
```
- Router, Switch, Firewall 등을 사용하여 네트워크 환경 구성이 가능함.
```
<img alt="Cisco" src="https://img.shields.io/badge/Cisco-003545?style=for-the-badge&logo=cisco&logoColor=white&color=blue"/>

* * *

# 🖥️ **Experience**

- ShellCode 변형

pwnable 문제 풀이를 진행할 때, 기존 `/bin/sh`를 실행하는 25 Byte shellcode에서 setreuid를 통해 권한 상승을 추가할 필요가 있었습니다. 따라서 Assembly 언어를 통해 코드 수정을 시도하였습니다.
Shellcode를 목적에 맞게 변형하며 Linux system call table과 관련된 내용들도 새로 배울 수 있었으며 32bit와 64bit 운영체제에서 차이가 있음도 알 수 있었습니다. [[ShellCode 변형 블로그 글](https://jun-project-lab.github.io/system/FTZ-shellcode/)]

- Python Thread

wargame 문제를 풀이할 때 주어진 hash 값과 일치하는 값을 Rainbow table을 제작하여 찾아낼 필요가 있었습니다. Hash의 생성 규칙을 분석하였을 때 매우 큰 범위의 Rainbow table을 제작할 필요가 있었으며 Python을 사용하여 스크립트를 작성하여도 오랜 시간이 걸릴 수 밖에 없었습니다. 따라서 이러한 시간 소요를 최소화 하기 위해 threading 모듈을 사용하여 분할하여 작업할 수 있도록 코드를 수정하였고 보다 수월하게 결과를 얻을 수 있었습니다. [[Python Rainbow Table 블로그 글](https://jun-project-lab.github.io/crypto/webhacking.kr-old-4th-writeup/)]

- Analyzing about relation of TLS and canary

Master Canary를 학습하던 중 `fs:0x28`과 관련된 offset에 대한 궁금증이 생겼고 이에 대해 조사하고자 하였습니다. 그러나 곤련된 답을 명쾌하게 얻을 수 있는 자료를 찾는 것에 생각보다 큰 어려움을 겪고 제대로 이해한 것이 맞는지에 대한 개념 증명을 위해 간단한 분석을 진행하였습니다. 자료를 찾는 도중 x86 환경에서 canary에 대해 분석한 게시글이 있었으나 x86-64 환경과는 차이가 있는 부분이 있었기에 해당 차이점들을 비교하며 분석글을 작성하였습니다. [[Analyzing Canary 블로그 글](https://jun-project-lab.github.io/system/Analyze-Canary-x86-64/)]

<!--
블로그 카테고리, 파이썬 익스플로잇 코드, 어셈블리 코드 등
-->

* * *

# 🎓 **Education**

- 2018.03 ~ 2021.01 인천전자마이스터고 정보통신기기과 졸
- 2021.03 ~ 2021.06 K-Shield 주니어 정보보호 관리진단 교육 과정 수료

* * *

# 📝 **Certificate**

- 2019.05 정보기기운용 기능사 취득
- 2021.06 정보처리 산업기사 취득
- 2021.06 정보보안 산업기사 취득

* * *

# 🏆 **Prize**

- 2019.08 Cisco NetRiders Competition Korea 2019 대상
- 2020.06 인천광역시 기능경기대회 IT네트워크시스템 1위
- 2020.09 전국기능경기대회 IT네트워크시스템 장려
- 2021.04 인천광역시 기능경기대회 사이버보안 1위

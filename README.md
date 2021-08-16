Portfolio
-----------------------------

# 👨‍💻 **About Me**

- **Contact Info**
  - Email : choi.junyoung.20.04@gmail.com
  - Name : 최준영 / Choi Junyoung
  - Blog : https://jun-project-lab.github.io/

고등학교에서 **네트워크**를 전공하였으며 현재 **시스템 해킹**에 대해 공부하고 있습니다. 꾸준히 기술을 갈고 닦아 IoT, Connected Car와 같이 일상 속에서의 보안 취약점을 찾아내어 이를 예방하는데 도움을 줄 수 있는 연구원이 되고 싶습니다.

* * *

# 🛠️ **Skills**

- Programming Language

> C 언어를 시작으로 다양한 프로그래밍 언어를 접해볼 수 있었습니다. Pwnable 문제를 풀며 다양한 case를 접하며 C 언어에 대한 이해도 향상되는 기회를 가졌습니다. 또한 exploit code를 작성하는데 python이 자주 사용되는 만큼 이에 대한 실력도 기를 수 있었습니다.

<img alt="C" src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white"/> <img alt="Python" src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white"/>

- Application

> 네트워크를 공부할 당시 Linux 환경에서 다양한 Web/Application 서비스 구축에 대해 공부한 경험이 있습니다. 이 과정에서 웹 서비스들의 동작에 대해 학습할 수 있었고, Database, SQL Query 등도 공부할 수 있었습니다.

<img alt="Apache" src="https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white"/> <img alt="Nginx" src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"/> <img alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"/> <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"/>

- Network

> Network의 이론부터 하나의 망을 구축하기까지 시뮬레이션 프로그램 뿐만 아니라 실제 Cisco 사의 Router, Switch 등의 장비를 이용한 실습도 진행하였습니다. 방화벽 장비를 이용한 실습을 진행할 때는 여러 프로토콜을 ACL을 사용하여 제어하며 FTP의 Acctive와 Passive mode의 차이점 등 더 깊이있는 내용을 학습할 수 있었습니다.

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

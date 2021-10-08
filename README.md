Portfolio
-----------------------------

# 👨‍💻 **About Me**

- **Contact Info**
  - Email : choi.junyoung.20.04@gmail.com
  - Name : 최준영 / Choi Junyoung
  - Blog : https://jun-project-lab.github.io/

* * *

# 🛠️ **Skills**

- Programming Language

> **C 언어**를 통해 프로그래밍에 대한 전반적인 개념과 기초를 학습하였습니다. 이후 web, pwnable, reversing 등 여러 wargame 문제를 보다 빠르게 풀기 위해 **python**을 이용하여 exploit code를 작성하는 법을 공부하였습니다.

<img alt="C" src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white"/> <img alt="Python" src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white"/>

- Pwnable

> BOF, FSB, ROP와 같은 기법들의 이론을 학습한 뒤 해당 기법들을 적용하여 wargame 문제를 풀어보며 견문을 넓히고 있습니다.

- Tools

> IDA, Ghidra, gdb 등을 활용하여 wargame 및 CTF 문제를 해결하며 각 도구들에 대한 사용법 및 숙련도를 높이고 있습니다.

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
- 2020.09 55회 전국기능경기대회 IT네트워크시스템 장려
- 2021.04 인천광역시 기능경기대회 사이버보안 1위
- 2021.10 56회 전국기능경기대회 사이버보안 동메달

* * *

# 🚩 **CTF**

- 2021 pbjarCTF 167th

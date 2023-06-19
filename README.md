## 개발 목적
2021 년 택배 현장에 배송 기사들이 분류 작업을 하는 것에 대한 문제가 두각되면서, 여러 택배 회사에서 인력 대비 고효율을 얻을 수 있는 분류 로봇 시스템 도입을 검토했습니다. 
실제 시스템을 구성하기 전, S/W 적 시뮬레이션을 해볼 수 있는 _물류 분류 로봇 시뮬레이션_ 과 시뮬레이션에서 사용할 맵을 디자인하는 _맵 디자이너_ 를 만들었습니다.

# Simulator
맵 디자이너에서 저장한 맵 파일을 읽어와 시뮬레이션하여 결과를 그래프로 보여주는 프로그램
## 사용 기술
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white">
## 주요 기능
- 맵 정보 미리보기
- 시뮬레이션
  - 실시간 로봇 정보 보여주기
  - 셀 정보 보여주기
- 시뮬레이션 결과
  - 결과표
  - 로봇 당 물류 처리량 그래프
  - 단위 시간 당 물류 처리량 그래프

## 시뮬레이션 알고리즘
<img width="300" height="400" alt="simul1" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/80f5cccc-6e75-4641-a8d8-fe659310d84a">
<img width="400" height="200" alt="simul2" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/7dfd5550-087a-4647-9211-e5fd7dc41082">

## 미리 보기
<img width="472" height="300" alt="6" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/28e18506-84a7-4a83-a1ef-af172a569891">
<img width="472" height="300" alt="7" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/cbb405e1-4fcf-455a-8b45-84659e4c6c2e">
<img width="472" height="300" alt="8" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/913d7f21-033b-49b7-a4ec-6984938642ae">
<img width="472" height="300" alt="9" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/d58ced31-96b3-41af-a3d7-a9d4b1d85dad">
<img width="472" height="300" alt="10" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/70e20975-427b-464e-8ef4-aea0e8ce5e9c">
<img width="472" height="300" alt="11" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/5bb05e2d-3410-43ec-9617-e0b1ffae9b4f">
<img width="472" height="300" alt="12" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/7988a644-ce6e-4b97-8f79-6a8cb36e3d8a">

## 사용 흐름
<img width="700" height="100" alt="0" src="https://github.com/Dormammu-Capstone/simulation/assets/74133818/fc76ed1c-b9a1-4ba0-86a4-c7bfa9043bf0">

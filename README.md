## About ME

- 혁신을 찾아 매일 발전하는 개발자 정래현입니다.
- Tech stack
	- Languages
		- C, Python, C++, JavaScript(ES6), Typescript, HTML5, CSS3
	- Framework / Library
		- Front-end
			- React.js, Next.js, Styled-component, Sass, Recoil, Flask
	- Server
		- MongoDB
	- Tooling/ DevOps
		- Git(Github), Shell(bash)
	- Environment
		- AWS, Linux, Window, Mac
	- ETC
		- Vim, Obsidian, Jetbrain code editing tools
- Contact
	- Github
		- https://github.com/raehy19
	- Phone
		- 010-5382-7202
	- E-mail
		- raehy19@gmail.com

## 프로젝트 리스트

#### 42GG.kr

- 요약
	- 42 Seoul 내의 탁구대 시설 사용 서비스
- source
	- https://42gg.kr/
	- https://github.com/42organization/42gg.client
	- https://github.com/42organization/softwave.42gg.client
- 프로젝트 목적
	- 클러스터 내 탁구대의 예약 / 경기 매칭 / 경험치 / 랭킹 / 전적 검색을 제공하는 서비스
- 카테고리
	- Web, Frontend
- 사용 언어 및 기술 스택
	- Next.js(React), Typescript, Recoil, Sass, AWS ec2
- 인력 구성 및 기여
	- 2기 Frontend (Next.js 스택 개발) LEAD 역할
		- Softwave
			- 주요 작업인원 총 2명, 보조 작업인원 2명, 주요 작업 인원 중 LEAD 역할
			- 기여도 약 50%
		- 관리자 페이지 리뉴얼
			- 주요 작업인원 4명 중 신입 기수 3명, LEAD 역할로 신입 기수 온보딩 진행
			- 기여도 약 35%
- 작업 기간
	- 코엑스 Softwave 행사 준비
		- 2022.10 ~ 2022.12 (약 5주)
	- 관리자 페이지 리뉴얼
		- 2023.01 ~ 2023.03 (약 10주)

#### 42cursus_minishell

- 요약
	- bash와 같은 쉘 명령어 실행 프로그램 개발
- source
	- https://github.com/raehy19/42cursus_minishell
- 카테고리
	- C Programming, Shell
- 사용 언어 및 스택
	- C
- 프로젝트 목적
	- bash와 같이, shell 명령어를 입력받아 실행하는 프로그램 개발
	- 입력받은 텍스트를 파싱해 명령어 종류 및 |, ||, && 으로 나뉘어진 구조를 트리 구조로 저장하고, 환경변수 치환 및 프로세스 생성, 시그널 처리 등을 논리에 맞게 순차적으로 실행
- 인력 구성 및 기여
	- 2인 프로젝트 - 파싱 파트와 구현 파트
		- 데이터 구조 설계 및 파싱 파트 담당
	- 기여도 50%
- 작업 기간
	- 2023.02 ~ 2022.04 (약 9주)

#### MODISCAN E1

- 요약
	- 직접 제작한 3D 스캐너 기기로 물체를 3D 스캔해 마인크래프트 지도 공간 상에 표현
- source
	- https://github.com/raehy19/MODISCAN_E1
- 카테고리
	- Robotics, 3D graphics
- 사용 언어 및 스택
	- Python, Modi Kit(luxrobo), Minecraft api
- 프로젝트 목적
	- 접촉식 3D 스캐너 제작
	- luxrobo의 modi kit를 활용하여, 하드웨어를 CAD로 설계해 3D프린터로 출력
	- 스캔된 물체를 마인크래프트를 이용해 3D 공간에 표현
- 인력 구성 및 기여
	- 하드웨어 설계 및 제작 2인 / 소프트웨어 개발 1인
		- 소프트웨어 개발 역할
	- 기여도 35%
- 작업 기간
	- 2021.10 ~ 2022.12 (약 8주)

#### Minimal expression generator

- 요약
	- minterm expression을 입력으로 받아, sum of products 형태의 minimal expression을 계산하는 프로그램
- 카테고리
	- Electronic Enginering - Digital Logic Circuit, Algorithm
- 사용 언어 및 스택
	- Python
- 프로젝트 목적
	- Quine mccluskey method 를 사용하여 논리식을 최소화하도록 계산하는 프로그램
- 작업 기간
	- 2021.12 ~ 2021.12 (약 1주)
- 인력 구성 및 기여
	- 개인 프로젝트
	- 기여도 100%

#### animated_facial_expression_conference-Server

- 요약
	- 안드로이드앱 - 유니티 서버 - 파이썬 서버 구조의 얼굴 인식 기반 캐릭터 화상 회의 서비스
- source
	- https://github.com/raehy19/animated_facial_expression_conference-Server/blob/master/project_report.pdf
- 카테고리
	- Backend, Face recognition
- 사용 언어 및 스택
	- Python, Flask, OpenCV, MongoDB
- 프로젝트 목적
	- 지속되는 비대면 수업으로 사생활 침해 문제 발생을 우려해, 이를 개선할 수 있도록 화상 화면을 얼굴을 인식하는 캐릭터 이미지로 공유하는 화상 회의 플랫폼 개발
	- 시퀀스
		- 안드로이드앱에서 카메라로 실시간 이미지를 파이썬 서버로 전송
		- 파이썬 서버에서 dlib을 이용해 받은 이미지의 face randmark를 추출, 추출된 데이터를 유니티 서버로 전송
		- Unity Server에서 Randmark기반 모델링을 거쳐 캐릭터 이미지를 생성해 다시 파이썬 서버로 전송
		- 파이썬 서버는 캐릭터 이미지를 다시 안드로이드 어플리케이션으로 전송
		- 안드로이드 어플리케이션에서 이미지 표기
- 인력 구성 및 기여
	- 3인 프로젝트 - 각각 파이썬 서버, 안드로이드 앱, 유니티 서버 담당
		- Python 서버 개발 역할
			- 개인 노트북으로 서버 실행
			- 공유기 포트포워딩 및 도메인 구입하여 배포
	- 기여도 35%
- 작업 기간
	- 2021.10 ~ 2022.12 (약 8주)

#### Scalable Object Detection on Embedded Devices using Weight Pruning and Singular Value Decomposition

- 요약
	- Object Detection 모델 스터디 및 저사양 임베디드 기기에서 Object detection task 수행을 위한 모델 경량화 방법에 대한 탐색
- Report
	- https://arxiv.org/pdf/2303.02735.pdf
- 카테고리
	- AI
- 사용 언어 및 스택
	- Python, Yolo model
- 프로젝트 목적
	- 딥러닝 이론 스터디
	- 데이터셋을 정해 Object Detection 모델을 선정해 학습
	- 학습된 모델을 라즈베리 파이에서의 객체 탐지가 가능하도록 경량화하는 방법 탐색 및 적용
- 작업 기간
	- 2023.0 ~ 2022.04 (약 2주)
- 인력 구성 및 기여
	- 2인 프로젝트
	- 기여도 50%

#### 2 degrees of freedom robot arm

- 요약
	- 아두이노 이용 2자유도 로봇팔
- source
	- https://github.com/raehy19/2_degrees_of_freedom_robot_arm
- 카테고리
	- Robotics
- 사용 언어 및 기술 스택
	- Arduino
- 프로젝트 목적
	- 3D 프린터 출력물과 모터를 이용해 로봇팔 제작
	- 2자유도 로봇팔의 집게가 base와의 수평과 수직 목표거리를 입력하면 그 지점으로 이동될 수 있도록 로봇팔 제어 프로그램 작성
	- 집게를 제어해 물체를 잡을 수 있도록 함
- 작업 기간
	- 2022.04 ~ 2022.04 (약 2주)
- 인력 구성 및 기여
	- 2인 프로젝트
	- 기여도 50%

#### Shortest Pathfinding Project

- 요약
	- 학교 인근(신촌) 지도를 불러와 최단 경로 길찾기 경로를 시각화해 보여주는 프로그램
	- 다익스트라 알고리즘을 이용
- source
	- https://github.com/raehy19/Shortest_Pathfinding_Project
- 카테고리
	- Data struct, Algorithm
- 사용 언어 및 기술 스택
	- C++
- 프로젝트 목적
	- 사용자에게 위치와 가게 이름을 입력받아 최단 경로 길찾기 결과를 제공하고, 그 결과를 지도 이미지에 선으로 시각화하여 보여 주는 프로그램
- 작업 기간
	- 2021.05 ~ 2021.06 (약 2주)
- 인력 구성 및 기여
	- 개인 프로젝트
	- 기여도 100%

## Education

- 연세대학교 전기전자공학부 재학
	- 2020.03 ~
- 42 Seoul Cadet
	- 2022.07 ~

## 기타 활동

- 제 71대 연세대학교 전기전자공학부 학생회장 (공학 6반)
	- 2020.11 ~ 2021.11
- 연세대학교 로봇동아리 로보인
	- 2020.03 ~
- 연세대학교 드론동아리 연세드론
	- 2021.09 ~
- 피오르팀 입시 컨설턴트
	- 2022.12 ~ 2023.01




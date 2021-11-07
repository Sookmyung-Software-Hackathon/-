# [팀21] SMSWH 2021 기획서

# 팀21

컴퓨터과학전공 2010248 김서연 - 팀장

컴퓨터과학전공 2012611 나유진

IT공학전공 2015110 신경원

### ❄산출물 주소

[https://lookforyoursookmyung.netlify.app/](https://lookforyoursookmyung.netlify.app/)

### ❄분야

웹 프론트

## ❄서비스 개요

---

'숙명의 숙명'을 키워드로, 

아직 자신의 숙명을 알지 못하는 예비 숙명인들을 위해 자신의 성향에 맞는 학과를 찾을 수 있도록 테스트를 진행한다. 각 계열마다 20개의 문항지를 제시하고, 테스트 결과와 함께, 해당 학과에 대한 정보를 제공한다.

## ❄서비스 목적

---

예비 눈송이의 '숙명의 숙명'찾기에 도움을 주고자한다.

예비 눈송이의 적성에 맞는 학과를 추천하고, 학과에서 요구되는 역량, 입학 전 준비하면 좋을 것들,  학과에서 배우는 내용, 진학 후 경험할 수 있는 학과활동, 전공별 눈송이 캐릭터 등을 소개한다.

## ❄핵심 기술 및 주요 기능

---

❄❄활용 기술

html, css, javascript

❄❄주요 기능

- 기기별로 최적화된 화면 크기를 제공
- 메인 화면에서 전공별 눈송이 사진을 랜덤으로 표시하여 숙명여자대학교의 전공을 개관
- 문제 진행 상황을 알리는 상단바
- 사용자의 답변에 따라 가장 적합한 전공 추천
- 추가 정보를 얻기 위한 링크 제공
- 손쉬운 공유를 위한 버튼 제공
- 

## ❄기대 효과

---

- 숙명여자대학교를 희망하는 학생들 중 전공에 대한 정보가 부족한 학생에게 학과에 대한 핵심적인 정보를 제공할 수 있다.
- 특정학과에 꼭 들어맞는 성향외에도 자신의 성향을 복합적으로 판단하여 가장 잘맞는 전공이 무엇인지 파악하는데 도움을 줄 수 있다.

## ❄페이지 구성(시나리오)

---

첫 화면(main section) > 질문을 제시하고 답변받기(qna section) > 학과 정보 출력(result section)

1. 사용자가 웹페이지 링크로 접속하면 테스트 제목과 간단한 소개글을 확인한다.

1-1.  화면 중앙에 랜덤으로 전공별 눈송이 캐릭터를 제시하여 간단하게 어떤 학과가 있는지 파악한다.

1. 하단의 '나의 숙명 찾기' 버튼을 클릭하면 사용자의 이름을 입력받는 대화상자가 나타난다.

2-1.  이름 입력받기를 취소하면 다시 main section이 나타난다.

1. 이름을 입력받으면 사용자가 관심 있는 계열을 입력받는 대화상자가 나타난다.

3-1. 계열 입력받기를 취소하면 다시 main section이 나타난다.

3-2. 제시된 보기 이외에 다른 값을 입력받으면 값이 잘못되었다는 창을 보여주고 다시 입력받는다.

1. 사용자가 입력한 계열에 맞는 문제를 제시하고 답변을 받는다.
- 학과 점수에 대한 리스트를 미리 만들어 놓고 해당하는 학과의 점수만 올린다.
1. 가장 높은 점수를 받은 학과의 이름, 표제, 눈송이 캐리턱, 간단한 정보와 학과 홈페이지 링크, 링크 복사 버튼을 제시한다.

5-1. 학과 홈페이지 링크를 클릭하면 숙명여대 학교 페이지의 대학 챕터로 이동한다.

5-2. 링크 복사 버튼을 클릭하면 전공 테스트 링크를 복사한다.

## ❄ 시연영상




https://user-images.githubusercontent.com/91943160/140654946-1fc53cb4-c008-44ad-a73e-57bdff865687.mp4



[대표 이미지]
<img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F513c596f-5dfe-490f-923a-2f40fd8f9658%2FUntitled.png?table=block&id=fe0a94fb-407e-441a-b0d9-b70a678ef956&spaceId=46893005-a3d8-4104-82d2-29cae068e951&width=2000&userId=c4ad560d-d5be-4c58-a250-7be34ce655d8&cache=v2">

❣ [시연바로가기](http://takealook.ekg.kr)

🔗 [Backend github repository](https://github.com/streetnyangfighter/takealook_backend)


<br>

## 😺 서비스 기획 의도
### `Take a Look! (떼껄룩)`은 길고양이와 사람의 공존을 위한 길고양이 도감 웹서비스입니다.
#### ❓🤷‍♂️ "길고양이를 왜 돌봐야 하나요? 저는 고양이를 싫어하는데요!"
- 길고양이 개체수를 조절하고 소음/악취/환경 훼손 등의 길고양이 관련 문제를 해결하려면, 적절한 먹이주기 및 중성화 등의 길고양이 돌봄 활동이 필수적입니다.
- Take a Look!은 `길고양이 돌봄에 관한 체계화된 정보를 공유`하고 `건강한 길고양이 돌봄 문화를 활성화`하여 지역사회 문제를 해결하는 데 일조합니다.

#### ❓💁‍♀ "고양이가 아파 보여서 약을 먹여야 할 것 같은데.. 누가 이미 먹이지는 않았을까?"
- 길고양이 특성상 불특정 다수가 무작위로 돌봄을 제공할 수밖에 없어 올바르지 못한 처치가 이루어질 위험성이 항상 존재했습니다.
- `같은 고양이를 돌보는 이웃들과 도감을 공유`하게 함으로써 길고양이 돌보미들이 느꼈던 불편함을 해소하고 시의적절한 돌봄이 제공될 기회를 높일 수 있습니다.


<br>
## 👨‍👧‍👧 팀원 /역활
- [홍길동1](https://github.com/A) : 백엔드 개발, AWS 배포 관리 (백엔드 서버, DB)
- [홍길동2](https://github.com/B) : 백엔드 개발, AI 모델 설계
- [홍길동3](https://github.com/C) : 프론트엔드 개발
-
<br>

## 🗓 개발 기간
2022.10.17 ~ 2022.10.21 

<br>

## ⚙ 개발 환경 / 사용 기술
- Front-end : <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">  <img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">

- Back-end : <img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white"> 

- AI Inference : <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white"> <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 

- DB : <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 

- Deployment : <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">

- IDE : <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white"> <img src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white">

- Communication Tools : <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white"> <img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">



<br>

## 🧬 서비스 구조 / Advaced Feature(강조 기능 3개 정도)
![image](https://user-images.githubusercontent.com/87870107/148776503-d27b8924-a731-47d7-ac05-43e3fae3299b.png)

## 기능1
- 

- OAuth2.0 프로토콜을 사용한 Google, Kakao 로그인
- 소셜로그인 정보로 회원 정보 수정 가능
  - 닉네임 중복 여부 확인 가능
  - 회원 사진 정보 수정 가능
- 내가 작성/좋아요 누른 글 리스트 모아보기
  - '더보기' 클릭시 내가 작성/좋아요 누른 전체 글 카드 형식으로 조회
- 내 도감에 등록된 고양이, 내가 작성한 글에 대한 변경사항 알람 제공
  - 아직 클릭하지 않은 알람 수 상단에 🔔아이콘과 함께 표시
  - 현시점으로부터 역순으로 '~ 시간 전' 표시

<br>

![image](https://user-images.githubusercontent.com/87870107/148776590-4f0fbf7e-204e-4274-acaa-2110c0bd29a9.png)


## 기능2

- 내가 돌보는 길고양이를 내 도감에 등록해서 관리 가능
- 고양이 등록시, **`다른 사용자가 이미 해당 고양이를 등록해놓았다면 그 도감을 공유할 수 있도록 AI 기반 유사 고양이 리스트 제공`** 
  - 사용자가 등록한 고양이 사진으로부터 딥러닝 기반 얼굴 인식 → 고양이 얼굴 랜드마크 표시 
  - 정확도 향상을 위해 랜드마크를 사용자가 직접 검수 및 수정할 수 있는 장치 마련
  - 인식된 얼굴 랜드마크를 기준으로 이미지 전처리 후, 기존에 등록된 고양이 이미지들과 유사도 비교
  - 이미지 유사도 및 추가 정보(고양이 최근 발견 위치, 털패턴 종류)를 바탕으로 유사도 점수 책정, 높은 순으로 리스트 제공  
- 제공된 리스트 중 **등록하려는 고양이와 일치한다고 판단**되는 경우, **해당 고양이를 바로 내 도감에 추가하여 기존 돌보미들과 정보 공유** 가능
- 제공된 리스트 중 등록하려는 고양이가 없는 경우, 새로운 고양이로 내 도감에 등록 가능

<br>

![image](https://user-images.githubusercontent.com/87870107/148776670-da77f072-4411-45a1-aa9c-449c311ad922.png)

### 기능 3
- 고양이 관리에 대한 모든 정보는 해당 고양이를 함께 돌보는 이웃들과 공유 가능
  - 사진
  - 현재 건강상태
  - 최근 발견 위치(지도에 마커로 표시)
  - 돌봄 이력 (밥/간식/약 급여/병원치료 등)
  - 입양 혹은 사망 여부
- **`다른 사용자가 등록한 고양이와 일치하는 줄 알고 내 도감에 추가했는데 알고보니 다른 고양이였던 걸로 판단되는 경우, 다른 고양이로 재등록`** 가능
  - 고양이 최초 등록시와 마찬가지로 AI 기반 유사 고양이 리스트 다시 제공
  - 리스트 중 다른 고양이를 내 도감에 추가하거나 아예 새로운 고양이로 내 도감에 재등록 가능 
  
 <br>

![image](https://user-images.githubusercontent.com/87870107/148776717-0dffe4be-c271-4136-9091-79538669cf78.png)
<br>

## 🎞 시연 영상
[![Take a Look! 서비스 시연 영상](https://user-images.githubusercontent.com/74531573/147846465-4ddcbedb-4a8a-43aa-b6f2-04ec3e0c2b3c.png)](https://www.youtube.com/watch?v=NgvGsDKbvok)

## 🦈 JobAT(잡앗) 🦈 [[Demo Video]](https://youtu.be/_OWhFOPmMwI)  [[시연 링크]](URL 넣는 곳)





## ✅ Project Information ( [TAVE 13기 후반기 프로젝트](https://blog.naver.com/t-ave) )

<img src="https://github.com/Job-AT/jobat-final/blob/main/MD_images/intro.png" style="width: 70%;">

- 사용자의 이력서 및 채용공고 기반 면접 질문 생성 프로그램
- 사용자의 답변에 대한 피드백 및 꼬리물기 면접 서비스 제공
- 효과적인 기업면접 대비 서비스





## 💬 BackGround

<img src="https://github.com/hang-o/temp_store/blob/main/jobat_communication.png" style="width: 40%;">

- 실제 면접에서는 항상 예상치 못한 질문이 들어오기 마련입니다.
- 그럴 때마다 저는 제가 예상치 못한 질문들을 실제 면접의 형태로 제공해주는 서비스가 있었으면 좋겠다고 생각 했습니다.
- 이런 생각으로 실제 자기소개서와 취업 공고를 바탕으로 맞춤 면접 서비스를 제공하는 이번 잡앗을 기획하게 되었습니다.

<img src="https://github.com/hang-o/temp_store/blob/main/jobat_langchain.png" style="width: 50%;">

- LLM을 이용한 어플리케이션 구축하기 위해 필요한 기능은 다음과 같습니다.
  - 대화의 이전 메세지를 저장
  - Knowledge base로부터 context 전달
  - 외부 API 와의 연결
 
- 랭체인은 위의 기능을 빠르고 간편하게 구현할 수 있기에 이를 활용하였습니다.


## 🛠️ Service Architecture

<img src="https://github.com/Job-AT/jobat-final/blob/main/MD_images/flow.png" style="width: 70%;">

1. 사용자의 자기소개서를 임베딩

2. 자동 채용공고 크롤링 및 요약

3. 자기소개서와 채용공고의 유사도를 계산하여 면접 예상 질문 생성


<img src="https://github.com/hang-o/temp_store/blob/main/jobat_interview.png" style="width: 50%;">





## 💟 Team Members
| 윤종석(13기) | 이다희(12기) | 석지현(13기) | 정은지(12기) | 정수인(13기) | 조승우(13기) |
|:---:|:---:|:---:|:---:|:---:|:---:|
|ദ്ദി¯•ω•¯ )|(◞˃ᆺ˂)◞|( ﾌ 'θ ')ﾌ|Σ(‘◉⌓◉’)|≽^-⩊-^≼|n_o|
|<a href = "https://github.com/JJadeYoon"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|<a href = "https://github.com/daheeleestudy"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|<a href = "https://github.com/Seok-JH"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|<a href = "https://github.com/bbobburi"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|<a href = "https://github.com/SooinJung"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|<a href = "https://github.com/hang-o"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|

#### 사용 기술 스택
<div>
  <img src="https://img.shields.io/badge/langchain-81C147?style=for-the-badge&logo=langchain&logoColor=black">
  <img src="https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=black">
  <img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=black">
  <img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=black">
  <img src="https://img.shields.io/badge/selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=black">
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=black">
</div>
  
<img src="https://github.com/Job-AT/jobat-final/blob/main/MD_images/techstack.png" style="width: 50%;">


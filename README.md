## 👋 YNWA!! "부족한 부분을 보완하고 이를 강점으로 발전시키는 오인성입니다."
Android 모바일 앱 개발을 지망하고 있습니다. 대학교 재학 시절 3개의 안드로이드 앱 개발 프로젝트를 경험하였습니다. 최근에는 Compose UI와 MVVM, MVI 개발에 관심이 많아서 공부하고 있습니다.

모바일 개발뿐만 아니라 알고리즘과 CS 기본기를 높이기 위해서 노력하고 있습니다. 또한 문제를 해결하기 위해서라면 무슨 어떤 것이든 적극적인 자세로 공부하고 개발하기 위해서 노력합니다.

제가 생각하는 개발에 있어서 가장 중요한 가치는 "공유"라고 생각합니다. 처음 개발을 시작하면서 제가 지금까지 오는 데까지 있어서 수없이 많은 사람에게 도움을 받고, 배웠습니다. 그래서 지금은 현재 제가 스스로 배우고, 알게 된 내용을 블로그를 통해서 최대한 기록을 하여 많은 사람에게 도움이 되기 위해서 노력하고 있습니다.

## Info
```kotlin
@Composable
fun Info() {
    Column(
        modifier = Modifier
            .padding(horizontal = 24.dp)
            .fillMaxWidth()
            .fillMaxHeight()
    ) {
        Text(
            text = "Oh In Seong - Android Developer"
        )

        Text(
            text = "1996.06.21"
        )

        Text(
            text = "HSU 18 Computer Engineering (2018.03 ~ 2024.02)"
        )
    }
}

@Preview(showBackground = true)
@Composable
fun InfoPreview() {
    MyApplicationTheme {
        Info()
    }
}
```
📧Gmail : [ohinsung64@gmail.com](mailto:ohinsung64@gmail.com)<br>
🐱Github : [https://github.com/ois0886](https://github.com/ois0886)<br>
📚Study Blog : [https://superohinsung.tistory.com/](https://superohinsung.tistory.com/)

## Technical Skills
### Language
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/JAVA-007396.svg?style=for-the-badge&logo=JAVA&logoColor=black"> 

### Framework
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=Android&logoColor=white"/> 

### Tools
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"/> <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white"> <img src="https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=Android%20Studio&logoColor=white"> <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=for-the-badge&logo=IntelliJ%20IDEA&logoColor=white"> <img src="https://img.shields.io/badge/Firebase-FFCA28.svg?style=for-the-badge&logo=Firebase&logoColor=white"> 

## Projects (Descending Order)
<details>
<summary>Bong Shop(재능마켓)</summary>
<br>

![Thumbnail](https://github.com/GrapeBongBong/Android/assets/58154638/a2f7aab4-991d-4180-a038-9c16b4e2f064) <br>

[깃허브 바로가기](https://github.com/GrapeBongBong/Android) <br>

### Project period
- 2022.12 ~ 2023.06(6개월)<br>

### Fact
- 총 4명의 인원(Server 2명, Android 1명, IOS 1명)이 팀을 구성하여 시작하게 된 6개월 졸업 작품
- 실제 프로젝트 기획부터 디자인까지 직접 만들며, 요구사항을 실제로 작성하며 스프린트를 진행함.

<!--
### Lesson
- iOS는 Human Interface Guidelines를 준수하여 강조된 사용자 경험과 디자인 가이드라인이 존재하며, Android의 경우 Material Design 가이드라인을 따르며, 다소 다른 사용자 경험을 제공. 이에 프로젝트에 있어서 동일한 디자인을 제공하기 위하여 Ui를 맞춰나가는 작업을 진행함.
- 서버와의 협업을 통해서 채팅 기능을 구현. 이를 통해서 실시간 통신과 WebSocket에 대한 것들을 공부.
-->

### TechStack
- Coroutine
- Paging3
- View Binding
- ViewModel
- Hilt
- Dagger
- Glide
- Retrofit2
- OkHttp3

</details>

<details>
<summary>POCS 블로그</summary>
<br>

[깃허브 바로가기](https://github.com/hansung-pocs/blog-android) <br>

### Project period
- 2022.07 ~ 2022.09(3개월)<br>

### Refoctor period
- 2022.09 ~ 2022.10(1개월)<br>

### Fact
- 초기 11명의 규모에서 프로젝트를 진행함. (백엔드 2명, 안드로이드 2명, 프론트엔드 5명, PM 2명)
- 프로젝트를 위한 안드로이드 학습기간 2주를 거친 후에 스프린트 8주 + 유지보수 기간 3주를 통해서 실제 앱을 구글 앱 스토어에 출시함.
- 기본적인 안드로이드 기술 스택 뿐만 아니라 [클린 아키텍처](https://superohinsung.tistory.com/74)와 [MVVM](https://superohinsung.tistory.com/66)을 공부해서 실제로 프로젝트를 적용하고 이를 블로그에 글로 게시함.

<!--
### Lesson
- 학습과 프로젝트에 있어 중요한 것은 과정을 기록하는 것에 있음을 깨달음.
- 팀프로젝트를 진행함에 있어서 나 자신이 팔로워 보다는 리더형에 가까운 사람임을 깨달았고, 그럼에도 아직은 부족한 리더라는 것을 알게됨.
- 안드로이드 파트에서 팀장을 맡아서 다른 팀(Server, Front)와 대화를 하는 법을 배움
- 팀원들의 자율성을 끌어내기 위한 법을 고민하게 됨.
-->

### TechStack
- Coroutine
- Paging3
- View Binding
- ViewModel
- Compose
- Hilt
- Dagger
- Glide
- Retrofit2
- OkHttp3
- Espresso
- Github Action(CI/CD)

</details>
<br>

## Education

### 한성대학교 컴퓨터공학부 (2018.03 ~ 2024.02) 
자료구조 / 알고리즘 / 객체지향 프로그래밍(C++, Java) / 운영체제 / 소프트웨어 공학 / 안드로이드 프로그래밍 / 인공지능 / 설계 패턴 / iOS 프로그래밍 / 데이터베이스 <br>
<br>

## Others

### POCS
한성대학교 학술 소모임 POCS <br>
활동 기한 : 2022.07 ~ (ING) <br>
Android 멘토로서 1년간 활동하며 총 4개의 스터디(알고리즘 스터디, 자바 스터디, 코딩테스트 대비 스터디, 면접 스터디)를 운영함. <br>

### DC&M
한성대학교 전공 동아리 DC&M <br>
활동 기한 : 2022.07 ~ (ING) <br>
동아리를 활동하며 Android 스터디를 운영함. <br>

### 코드프레소 
기한 : 2023.10 ~ (ING) <br>
2023 코드프레소 웹 개발 컨테스트를 통하여 참여하게 됨. <br>
국민 내일 배움 카드를 사용하여 코드프레소에서 제공한 웹 개발 강의(Java, Spring, Git, SQL)를 수강하고 있음. 
<br>
<br>
<!-- 여기는 나중에 추가
## Certifications
SQLD

컴퓨터 활용능력 1급

OPIC IL
-->

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ois0886&show_icons=true&theme=dark)

[![Solved.ac프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=ois0886)](https://solved.ac/ois0886)<img src="http://mazandi.herokuapp.com/api?handle=ois0886&theme=warm"/>

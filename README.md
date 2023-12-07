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
<summary>Bong Shop(재능마켓) Android Part</summary>
<br>

![Thumbnail](https://github.com/GrapeBongBong/Android/assets/58154638/a2f7aab4-991d-4180-a038-9c16b4e2f064) <br>

[깃허브 바로가기](https://github.com/GrapeBongBong/Android) <br>

한성대학교 캡스톤 디자인(졸업 작품)에 출품하였던 프로젝트입니다.
재능 교환 마켓 앱 어플리케이션은 기존에 재능과 재화를 교환하던 방식에서 벗어나 재능과 재능을 교환하는 서비스입니다. 자신이 가지고 있는 재능을 통해 상대에게 재능을 가르치고 상대의 재능을 배울 수 있는 기회를 제공합니다.
이를 통해서 실제로 서비스를 기획하고 디자인하는 것부터 공부할 수 있었으며, 팀원들과 6개월간의 노력으로 앱 서비스를 완성할 수 있는 좋은 기회였습니다.

### Project period
- 2022.12 ~ 2023.06(6개월)<br>

### Fact
- 총 4명의 인원(Server 2명, Android 1명, IOS 1명)이 팀을 구성하여 시작하게 된 6개월 졸업 작품
- 실제 프로젝트 기획부터 디자인까지 직접 만들며, 요구사항을 실제로 작성하며 스프린트를 진행함.

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
<summary>디딤돌 프로젝트</summary>
<br>

![Thumbnail](https://github.com/ois0886/ois0886/assets/58154638/4254d82a-6541-49b8-bd49-eba06dfcdb12)

[깃허브 바로가기](https://github.com/HSU-Didimdol/Android_PickNumber)

대학교 전공동아리에서 외부 회사와의 협업을 제작한 예약, 사이트 방문, 빠른 길 찾기가 가능한 지능형 온라인 예약 시스템 안드로이드 어플리케이션입니다.
NaverMapAPI SearchView를 활용하여 앱을 제작하며 실제 회사에서 어떠한 방식으로 협업이 이루어지는지 알 수 있는 좋은 기회였습니다.

### Project period
- 2023.01 ~ 2023.06(6개월) <br>

### Fact
- NaverMap Api를 Android 연결 및 사용
- Marker를 이용하여 사용자 현재 위치에 따른 주변 가게 위치 표시
- SearchView를 이용한 검색관련 목록 표시

### TechStack
- Coroutine
- View Binding
- ViewModel
- Glide
- Retrofit2
- OkHttp3

</details>

<details>
<summary>POCS 블로그 Android Part</summary>
<br>

![Thumbnail](https://github.com/ois0886/ois0886/assets/58154638/3a53e31a-485b-4c82-8551-0b29e5507dcf) <br>

[깃허브 바로가기](https://github.com/hansung-pocs/blog-android) <br>

전공 소모임 POCS회원들을 위한 어플리케이션 입니다. 다수의 인원이 들어간 만큼 앱을 출시하는 등의 좋은 성과를 얻어낼 수 있었습니다.
처음 안드로이드 프로젝트이자 안드로이드의 다양한 기술 스택등을 공부할 수 있었던 좋은 기회였습니다.

### Project period
- 2022.07 ~ 2022.08(2개월)<br>

### Refoctor period
- 2022.09(1개월)<br>

### Fact
- 초기 11명의 규모에서 프로젝트를 진행함. (백엔드 2명, 안드로이드 2명, 프론트엔드 5명, PM 2명)
- 프로젝트를 위한 안드로이드 학습기간 2주를 거친 후에 스프린트 8주, 리팩토링 4주를 통해서 실제 앱을 구글 앱 스토어에 출시
- 확장성을 고려한 [클린 아키텍처](https://superohinsung.tistory.com/74)와 [MVVM](https://superohinsung.tistory.com/66) 사용 및 이를 사용하기 위한 스터디를 개최하여 블로그에 기록
- 부분적 Compose를 이용한 UI 개발
- Server Part와 협업을 통한 Retrofit을 이용한 개발
- Github Action을 이용한 CI/CD 구축
- 유닛 테스트 및 UI 테스트 작성
- Hilt를 이용한 의존성 주입 통해서 Domain, Data, Presentation Layer 분리

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
자료구조 / 알고리즘 / 객체지향 프로그래밍(C++, Java) / 운영체제 / 소프트웨어 공학 / 안드로이드 프로그래밍 / 인공지능 / 설계 패턴 / iOS 프로그래밍 / 데이터베이스 / 데이터마이닝 <br>
<br>

## Others

### POCS
한성대학교 학술 소모임 POCS <br>
활동 기한 : 2022.07 ~ 2023.12 <br>
Android 멘토로서 1년간 활동하며 총 4개의 스터디(알고리즘 스터디, 자바 스터디, 코딩테스트 대비 스터디, 면접 스터디)를 운영함. <br>

### DC&M
한성대학교 전공 동아리 DC&M <br>
활동 기한 : 2022.07 ~ 2023.12 <br>
동아리를 활동하며 Android 스터디를 운영함. <br>

### 코드프레소 
기한 : 2023.10 ~ 2023.12 <br>
2023 코드프레소 웹 개발 컨테스트를 통하여 참여하게 됨. <br>
국민 내일 배움 카드를 사용하여 코드프레소에서 제공한 웹 개발 강의(Java, Spring, Git, SQL)를 수강하였습니다.
<br>
<br>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ois0886&show_icons=true&theme=dark)

[![Solved.ac프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=ois0886)](https://solved.ac/ois0886)<img src="http://mazandi.herokuapp.com/api?handle=ois0886&theme=warm"/>

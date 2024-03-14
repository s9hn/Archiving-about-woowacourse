# 우아한테크코스 5기 안드로이드 학습 과정

## Lv1. 코틀린 & 객체 지향 프로그래밍

|  <center>Mission</center> |  <center>Repository</center>| <center>PR 1</center> |<center>PR 2</center> |
|:--------:|:--------:|:--------:|:--------:|
|**자동차경주 - 온보딩**|[kotlin-racingcar](https://github.com/s9hn/kotlin-racingcar/tree/s9hn)|[1단계](https://github.com/woowacourse/kotlin-racingcar/pull/53)|[2단계](https://github.com/woowacourse/kotlin-racingcar/pull/78)|
|**로또 - TDD, OOP**|[kotlin-lotto](https://github.com/s9hn/kotlin-lotto/tree/s9hn)|[1단계](https://github.com/woowacourse/kotlin-lotto/pull/18)|[2단계](https://github.com/woowacourse/kotlin-lotto/pull/57)|
|**블랙잭 - 코틀린다운, FP**| [kotlin-blackjack](https://github.com/s9hn/kotlin-racingcar/tree/s9hn)|[1단계](https://github.com/woowacourse/kotlin-blackjack/pull/10)|[2단계](https://github.com/woowacourse/kotlin-blackjack/pull/60)|
|**오목 - 안드로이드, DB**| [kotlin-omok](https://github.com/s9hn/kotlin-omok/tree/s9hn)|[1, 2단계](https://github.com/woowacourse/kotlin-omok/pull/18)|[3, 4단계](https://github.com/woowacourse/kotlin-omok/pull/47)|

  
### 📖 WHAT I LEARNED

- 코틀린을 활용한 객체지향 프로그래밍을 학습했어요.
  - [SOLID](https://s2ehun.tistory.com/6), [객체 지향 생활 체조 원칙](https://s2ehun.tistory.com/5)을 준수하려 노력했어요.
- 페어프로그래밍과 [TDD](https://s2ehun.tistory.com/2)를 활용해 진행했어요.
  - Junit을 활용해 단위 테스트를 작성했어요.
- 정적 팩토리 메서드 패턴, 상태 패턴, MVC 패턴 등 다양한 디자인 패턴을 구현했어요.
- 안드로이드 프레임워크의 기초를 학습했어요.
  - SQLite를 활용해 데이터베이스를 구축할 수 있어요.


<hr>

## Lv2. 안드로이드 기초 & 심화

|  <center>Mission</center> |  <center>Repository</center>| <center>PR 1</center> |<center>PR 2</center> |
|:--------:|:--------:|:--------:|:--------:|
|**영화 티켓 예매 - 안드로이드 기초**|[android-movie-theater](https://github.com/s9hn/android-movie-theate/tree/s9hnr)|[1, 2단계](https://github.com/woowacourse/android-movie-theater/pull/12)|[3, 4단계](https://github.com/woowacourse/android-movie-theater/pull/50)|
|**영화 극장 선택 - 안드로이드 심화**|[android-movie-ticket](https://github.com/s9hn/android-movie-ticket/tree/s9hn)|[1, 2단계](https://github.com/woowacourse/android-movie-ticket/pull/25)|[3, 4단계](https://github.com/woowacourse/android-movie-ticket/pull/54)|
|**쇼핑 장바구니 - 데이터 로딩, 상태 관리**| [android-shopping-cart](https://github.com/s9hn/android-shopping-cart/tree/s9hn)|[1, 2단계](https://github.com/woowacourse/android-shopping-cart/pull/13)|[3, 4단계](https://github.com/woowacourse/android-shopping-cart/pull/50)|
|**쇼핑 주문 - 협업, 비동기**| [android-shopping-order](https://github.com/s9hn/android-shopping-order/tree/s9hn)|[1단계](https://github.com/woowacourse/android-shopping-order/pull/11)|[2단계](https://github.com/woowacourse/android-shopping-order/pull/48)|

  
### 📖 WHAT I LEARNED
#### 2-1
- 안드로이드 기초에 대해 학습했어요.
  - Intent, Context, 안드로이드 4대 컴포넌트, Activity Lifecycle
- savedInstanceState를 통한 상태관리로 화면 회전에 대응할 수 있어요.
- Serializable, Parcelable 직렬화 라이브러리의 차이와 구현 방식을 학습했어요.
- Espresso, Robolectric을 통해 UI 테스트를 경험했어요.
- 도메인 모듈 분리를 통해 단위테스트를 작성했어요.
- ListView와 RecyclerView를 자유롭게 다룰 수 있어요.
#### 2-2
- 안드로이드 심화에 대해 학습했어요.
  - Fragment, Broadcast Receiver, DataBinding
- AlarmManager, SharedPreference를 구현했어요.
- MVC -> MVP 패턴 리팩터링을 경험했어요.
- 테스트 더블을 사용하기 위해 Mockk을 구현할 수 있어요.
#### 2-3
- 데이터 로딩 전략을 수립할 수 있어요.
  - Pagination, Load More, Infinite Scroll의 차이와 구현 방식을 알고 있어요.
- Glide 라이브러리를 사용해 캐싱 전략 및 후처리 구현을 학습했어요.
- Presenter 단위 테스트를 작성했어요.
- 스크롤 뷰, 리사이클러 뷰 최적화를 위한 방법들을 학습했어요.
- Http Client로 okhttp3를 학습했어요.
- MockWebServer를 구축할 수 있어요.
- Repository Pattern에 대해 이해하고 구현할 수 있어요.
- LiveData 적용 리팩터링 및 테스트를 학습했어요.
#### 2-4
- 백엔드와 협업을 경험했어요.
- 핸들러, 메시지 큐, 루퍼에 대해 학습했어요.
- MockWebServer, okhttp3 -> 외부 API, Retrofit2로 리팩터링을 진행했어요.
- Service(Foreground, Background, Bount)에 대해 학습했어요.
- View LifeCycle을 학습하고 뷰 최적화 방법들을 학습했어요.
- MVVM 패턴에 대해 학습하고 발표했어요.

<hr>

## Lv3. 프로젝트

|  <center>Mission</center> |  <center>Repository</center>|
|:--------:|:--------:|
|**프로젝트 협업**|[201 Created](https://github.com/201-Created-Study/2023-yigongil)|
  
### 📖 WHAT I LEARNED

- 협업에 필요한 소프트 스킬에 대해 배웠어요.
- 다양한 깃 관리 전략들을 학습했어요.
- 초기 기획 프로세스를 직접 경험해볼 수 있었어요.


<hr>

## Lv4. 바퀴를 재발명하는 이유 DI & 뷰 챌린지

|  <center>Mission</center> |  <center>Repository</center>| <center>PR 1</center> |<center>PR 2</center> |<center>PR 3</center> |
|:--------:|:--------:|:--------:|:--------:|:--------:|
|**만들면서 배우는 DI**|[android-di](https://github.com/s9hn/android-di/tree/s9hn)|[1단계](https://github.com/woowacourse/android-di/pull/24)|[2, 3단계](https://github.com/woowacourse/android-di/pull/38)|[4단계](https://github.com/woowacourse/android-di/pull/64)|
|**뷰 챌린지**|[android-paint](https://github.com/s9hn/android-paint/tree/s9hn)|[1단계](https://github.com/woowacourse/android-paint/pull/5)|[2단계](https://github.com/woowacourse/android-paint/pull/48)|[3단계](https://github.com/woowacourse/android-paint/pull/61)|

  
### 📖 WHAT I LEARNED
#### 4-1
- 서비스 로케이터 패턴의 수동 DI를 구현했어요.
- Reflection을 사용해 자동 DI를 직접 구현하는 과정을 경험했어요.
- Robolectric을 사용한 ViewModel 테스트를 학습했어요.
- Hilt와 Koin을 학습했어요.
- LifeCycle Aware Components에 대한 DefaultLifecycleObserver를 경험했어요.

#### 4-2
- 공식 문서의 권장 아키텍처에 대해 이해했어요.
  - UiState, UDF
- View Lifecycle, 뷰 계층 구조, 뷰 최적화에 대해 학습했어요.
- 반응형 UI(portrait, landscape/Dark Mode)에 대응할 수 있어요.
- 다양한 뷰 성능 측정 방법에 대해 학습했어요.
- Layout Inspector, GPU 렌더링 & GPU Overdraw 검사, Tracing, Microbenchmark
- Compose를 활용해 간단한 UI를 구현할 수 있어요.

<hr>

## 글쓰기 미션

|  <center>Mission</center> |  <center>Repository</center>|
|:--------:|:--------:|
|**글쓰기**|[woowa-writing-5](https://github.com/s9hn/woowa-writing-5/tree/s9hn)|

<hr>

## 스터디

|  <center>Subject</center> |  <center>Repository</center>|
|:--------:|:--------:|
|**CS 스터디**|[2023-BookOverFlow](https://github.com/woowacourse-study/2023-BookOverFlow/tree/s9hn)|
|**책읽기 스터디**|[2023-fun-readBook-AN](https://github.com/woowacourse-study/2023-fun-readBook-AN/tree/s9hn)|

<hr>

## 테코톡

|  <center>Subject</center> |  <center>URL</center>|
|:--------:|:--------:|
|**MVVM**|[산군의 MVVM](https://www.youtube.com/watch?v=JdSwZzdUHrA&t=234s&pp=ygUL7IKw6rWwIG12dm0%3D)|

<hr>

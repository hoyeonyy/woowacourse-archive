# 우아한테크코스 기록

> ## 우아한테크코스란?

우아한형제들에서 주관하는 개발자 교육 프로그램  
우아한테크코스 과정은 요구사항이 주어지고 요구사항을 달성하는 방법을 스스로 고민하는 미션 기반으로 진행  
모든 미션은 최소 단위의 협업인 페어 프로그래밍으로 진행  
하드 스킬 뿐만 아니라 글쓰기, 유연성 강화 스터디 등의 소프트 스킬 교육 제공  

## 💪 활동 기간 

> 프리코스 : 2023.10.19 ~ 2023.11.15 <br>
> 본과정 : 2024.02.13 ~ 2024.11.29

## ✏ 활동 기록

### 👨🏻‍🏫 10분 테코톡

```markdown
'10분 테코톡'이란 우아한테크코스 과정을 진행하며 크루(수강생)들이 동료들과 학습한 내용을 공유하고 이야기하는 시간입니다.
서로가 성장하기 위해 지식을 나누고 대화하며 생각해보는 시간으로 자기 주도적인 성장을 지향하는 우아한테크코스의 문화 중 하나입니다.
```
![image](https://github.com/user-attachments/assets/c2203e9f-2d03-4c34-bff9-7fadd776632d)

[[10분 테코톡] 호기의 blocking VS non-blocking, sync VS async](https://youtu.be/cmBFGSrHKnM?si=p3gWIcVr25nTa_Iz)

---

## ⭐ Team Project ⭐

> 모여봐요 우리들의 다락방, 모우다 🏡 <br>
> 회사나 학교 등의 단체 내에서 모임을 만들고 참여할 수 있는 커뮤니티 서비스입니다. <br>
> 👉 [Repository](https://github.com/woowacourse-teams/2024-mouda) 
> 👉 [프로젝트 소개](https://sites.google.com/view/woowacourse-demo-6th/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8/%EB%AA%A8%EC%9A%B0%EB%8B%A4?authuser=0) 


##### ⭐ Keyword : Feeback Service, Maintenance

```markdown
함께 서비스를 개발하고 운영하는 경험을 한다.
가용성을 고려해 아키텍처를 설계한다.
사용자에게 피드백을 받고 서비스를 개선한다.
```

| Sprint  | Period  | Functions |
|---------|-------------|------------------|
| 6차 스프린트 | `2024-09-30` ~ `2024-11-01` | - 사용자 유치를 위한 서비스 고도화 <br> - [사용자 인증 구현](https://successful-jeep-771.notion.site/42126114cd434bbf80a791dbb54ef11b) <br> - [로그인 방식 변경으로 인한 재가입 유도](https://successful-jeep-771.notion.site/91fc7766dd4d44c6ad7345f5df7dff2c) <br> - [무중단 배포](https://successful-jeep-771.notion.site/127bb446019880a7b4e1ecbf089cd1eb) <br> - 사용자 프로필 조회와 이미지 업로드  <br>  - 프로메테우스와 그라파나를 사용한 모니터링 시스템 구축|
| 5차 스프린트 | `2024-09-03` ~ `2024-09-27` | - 사용자 피드백 반영 <br> - [데이터베이스 인덱스 적용](https://successful-jeep-771.notion.site/9f553e338a0044128255e4a22ce04f32) <br> - [서비스 내 모든 쿼리 분석](https://successful-jeep-771.notion.site/17e7c90fc31545d5a98009d42c218f69) <br> - 비즈니스 레이어와 구현 레이어를 분리하여 가독성 개선 |  
| 4차 스프린트 | `2024-08-10` ~ `2024-08-23` | - [FCM을 사용한 알림 구현](https://successful-jeep-771.notion.site/Firebase-11dbb446019881579c40e9c8e182d0c3) <br> - 도메인 주소 생성과 HTTPS 적용 <br> - 프로덕션 환경 구축과 CI/CD <br> [중복 모임 참여 문제 해결](https://successful-jeep-771.notion.site/b61b018a80e5454980d6f813aaa28cd7?p=11dbb446019881eb80a1e1b6fbc3419e&pm=s)|
| 3차 스프린트 | `2024-07-27` ~ `2024-08-09` | - [Logback을 사용한 애플리케이션 로깅](https://successful-jeep-771.notion.site/Logback-b69ceb05f312486bb809460afe24dac5) <br> -[Swagger를 사용한 API 문서화](https://api.mouda.site/swagger-ui/index.html) <br> -[모임 구성원 간의 채팅 기능 구현](https://successful-jeep-771.notion.site/11dbb446019881d39db6f55ab7fcec10) <br> - CloudWatch를 사용한 모니터링 대시보드 구축|
| 2차 스프린트 | `2024-07-13` ~ `2024-07-26` | - 서비스 MVP 개발 <br> - [Github Actions를 사용한 CI/CD](https://successful-jeep-771.notion.site/Github-Actions-11dbb4460198812a927ccac7d8b4d9c0?pvs=73) <br> - [Docker를 사용한 개발 서버 배포](https://successful-jeep-771.notion.site/Docker-1deaae3dfb7b44fb9e60db369c0166ca?pvs=73) |
| 1차 스프린트 | `2024-07-02` ~ `2024-07-12` | - 서비스 기획 <br> - [개발(코드 컨벤션 등) 문서](https://github.com/woowacourse-teams/2024-mouda/wiki/%EB%B0%B1%EC%97%94%EB%93%9C-%EC%BD%94%EB%93%9C-%EC%BB%A8%EB%B2%A4%EC%85%98) <br> -[기술 스택 선택 및 이유](https://github.com/woowacourse-teams/2024-mouda/wiki/%EB%B0%B1%EC%97%94%EB%93%9C-%EA%B8%B0%EC%88%A0-%EC%8A%A4%ED%83%9D) <br> -[Git 컨벤션](https://github.com/woowacourse-teams/2024-mouda/wiki/Git-%EC%BB%A8%EB%B2%A4%EC%85%98)|


### 1️⃣ Level1 
##### ⭐ Keyword : Java, OOP, CleanCode, TDD, UnitTest, DB

```markdown
학습 내용
- 자바 프로그래밍 언어에 대한 핵심 개념을 익혀 프로그래밍한다.
- 읽기 좋은 코드를 구현하는 것이 왜 중요한지 이해하고 코드를 개선해 읽기 좋은 코드로 변경한다.
- 자신이 구현한 코드에 대해 단위 테스트와 리팩토링을 경험한다.
- 데이터베이스를 활용한 콘솔 애플리케이션을 개발한다.
```

<table>
    <tr>
        <th>미션 이름</th>
        <th>학습 키워드</th>
        <th>Step</th>
        <th>기간</th>
        <th>미션 PR</th>
    </tr>
    <tr>
        <td rowspan="2">🚗자동차 경주</td>
        <td rowspan="2">단위 테스트</td>
        <td>Step1</td>
        <td>2024.02.13 ~ 02.15</td>
        <td><a href="https://github.com/woowacourse/java-racingcar/pull/684">PR</a></td>
    </tr>
    <tr>
        <td>Step2</td>
        <td>2024.02.16 ~ 02.19</td>
        <td><a href="https://github.com/woowacourse/java-racingcar/pull/753">PR</a></td>
    </tr>
    <tr>
        <td rowspan="2"> ⛑ 사다리 타기</td>
        <td rowspan="2">TDD</td>
        <td>Step1</td>
        <td>2024.02.20 ~ 02.22</td>
        <td><a href="https://github.com/woowacourse/java-ladder/pull/260">PR</a></td>
    </tr>
    <tr>
        <td>Step2</td>
        <td>2024.02.23 ~ 03.04</td>
        <td><a href="https://github.com/woowacourse/java-ladder/pull/396">PR</a></td>
    </tr>
    <tr>
        <td rowspan="2"> 🃏 블랙잭</td>
        <td rowspan="2">Clean Code</td>
        <td>Step1</td>
        <td>2024.03.05 ~ 03.08</td>
        <td><a href="https://github.com/woowacourse/java-blackjack/pull/637">PR</a></td>
    </tr>
    <tr>
        <td>Step2</td>
        <td>2024.03.09 ~ 03.18</td>
        <td><a href="https://github.com/woowacourse/java-blackjack/pull/743">PR</a></td>
    </tr>
    <tr>
        <td rowspan="3">♟ 체스 미션</td>
        <td rowspan="3">OOP, DB</td>
        <td>Step1,2</td>
        <td>2024.03.19 ~ 03.21</td>
        <td><a href="https://github.com/woowacourse/java-chess/pull/652">PR</a></td>
    </tr>
    <tr>
        <td>Step3</td>
        <td>2024.03.22 ~ 04.01</td>
        <td><a href="https://github.com/woowacourse/java-chess/pull/758">PR</a></td>
    </tr>
    <tr>
        <td>Step4</td>
        <td>2024.03.22 ~ 04.01</td>
        <td><a href="https://github.com/woowacourse/java-chess/pull/798">PR</a></td>
    </tr>
</table>



### 2️⃣ Level2
##### ⭐ Keyword : Spring Boot, JPA, HTTP, Authorization, Third-Party API, Infra

```markdown
웹 애플리케이션을 개발하며 웹 백엔드 개발자의 기본 역량을 쌓는다.
주어진 요구사항에 맞춰 기능을 추가/변경하며 애플리케이션을 발전시켜 나간다.
클라우드 환경에 배포를 하여 사용자에게 서비스할 수 있는 최소한의 상태로 만든다.
웹 애플리케이션 구현을 위해 필요한 새로운 기술을 학습한다.
이 과정에서 효과적으로 새로운 기술을 익힐 수 있는 본인만의 학습 방법을 찾는 시도를 한다.
웹 프로그래밍 과정에서도 읽기 좋은 코드, 유지보수하기 좋은 코드를 작성하는 경험을 한다.
```

<table>
    <tr>
        <th>미션 이름</th>
        <th>학습 키워드</th>
        <th>미션 PR</th>
    </tr>
    <tr>
        <td rowspan="2">방탈출 예약 관리</td>
        <td rowspan="2">SpringBoot Application 실행하기</td>
        <td><a href="https://github.com/woowacourse/spring-roomescape-admin/pull/58">[1-3단계] API 생성하기</a></td>
    </tr>
    <tr> 
        <td><a href="https://github.com/woowacourse/spring-roomescape-admin/pull/157">[4-9단계] Spring Bean과 Layered Architecture</a></td>
    </tr>
    <tr>
        <td rowspan="2">방탈출 사용자 예약</td>
        <td rowspan="2">기능 추가에 대한 애플리케이션 발전</td>
        <td><a href="https://github.com/woowacourse/spring-roomescape-member/pull/2">[1-3단계] 예외 처리 및 새로운 기능 추가</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/spring-roomescape-member/pull/139">[4-6단계] 사용자 인증 인가</a></td>
    </tr>
     <tr>
        <td rowspan="2">방탈출 예약 대기</td>
        <td rowspan="2">JPA 사용 및 레이어 테스트</td>
        <td><a href="https://github.com/woowacourse/spring-roomescape-waiting/pull/47">[1-2단계] JDBC에서 JPA로 전환 및 연관관계 설정</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/spring-roomescape-waiting/pull/113">[3-4단계] 엔티티 설계와 서비스 테스트</a></td>
    </tr>
    <tr>
        <td rowspan="2">방탈출 결제 및 배포</td>
        <td rowspan="2">Third-Party API 도입과 테스트</td>
        <td><a href="https://github.com/woowacourse/spring-roomescape-payment/pull/16">[1단계] FeignClient를 사용해 토스 결제 구현</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/spring-roomescape-payment/pull/89">[2-4단계] 결제 정보 저장에 따른 ERD 설계, API 문서 자동화 및 배포</a></td>
    </tr>
</table>



### 4️⃣ 레벨 4 - 프레임워크 라이브러리 깊게 이해하기 (2024.09.03 ~ 2024.11.01)  
##### ⭐ Keyword : Tomcat, MVC, JDBC, DB Replication, Cache

- 프레임워크와 라이브러리를 직접 코드로 구현해보며 기술의 상세를 탐구
- Tomcat, Spring MVC 그리고 Jdbc를 직접 구현
- DB 복제와 캐시 등 서비스 고가용성을 위한 기술을 학습, 복제 지연문제와 캐시 정책 등 수반되어야 하는 고려지점을 탐구

<table>
    <tr>
        <th>미션 이름</th>
        <th>학습 키워드</th>
        <th>미션 PR</th>
    </tr>
    <tr>
        <td rowspan="4">Tomcat 구현하기</td>
        <td rowspan="4">WAS, HTTP, Cookie & Session, Thread</td>
        <td><a href="https://github.com/woowacourse/java-http/pull/527">[1단계] HTTP 요청과 응답을 처리하는 WAS 구현</a></td>
    </tr>
    <tr> 
        <td><a href="https://github.com/woowacourse/java-http/pull/624">[2단계] 비지니스 코드 추가하기 </a></td>
    </tr>
    <tr> 
        <td><a href="https://github.com/woowacourse/java-http/pull/663">[3단계] WAS / HTTP / 비즈니스 코드 분리 </a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/java-http/pull/728">[4단계] 스레드 풀 설정과 스레드 안정성</a></td>
    </tr>
    <tr>
        <td rowspan="3">MVC 프레임워크 구현하기</td>
        <td rowspan="3">MVC, Reflection, IoC와 DI, Servlet, Servlet Container</td>
        <td><a href="https://github.com/woowacourse/java-mvc/pull/707">[1단계] MVC 프레임워크 구현하기</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/java-mvc/pull/764">[2단계] 어노테이션 기반 컨트롤러 매핑</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/java-mvc/pull/800">[3단계] 컨트롤러에서 객체 반환 시 JSON으로 응답하기 위한 JsonView </a></td>
    </tr>
     <tr>
        <td rowspan="4">JDBC 라이브러리 구현하기</td>
        <td rowspan="4">DB 커넥션 풀, Transaction, AOP</td>
        <td><a href="https://github.com/woowacourse/java-jdbc/pull/676">[1단계] JdbcTemplate 구현 </a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/java-jdbc/pull/774">[2단계] JdbcTemplate 코드 리팩토링 </a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/java-jdbc/pull/818">[3단계] 트랜잭션 커밋 롤백 구현</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/java-jdbc/pull/904">[4단계] 트랜잭션 동기화로 트랜잭션 코드를 비즈니스 로직과 분리 </a></td>
    </tr>
    <tr>
        <td rowspan="1">인프라 아키텍처 설계</td>
        <td rowspan="1">요구사항에 맞추어 쇼핑몰 인프라 아키텍처 설계</td>
        <td><a href="https://github.com/woowacourse/infra-architecture-4/discussions/6#discussioncomment-10953924">요구사항과 아키텍처 설계</a></td>
    </tr>
    <tr>
        <td rowspan="2">DB 복제와 캐시</td>
        <td rowspan="2">복제 지연, 캐시, 잠금</td>
        <td><a href="https://github.com/woowacourse/java-coupon/pull/83"> [1단계] 데이터베이스 분리로 인한 복제 지연 해결</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/woowacourse/java-coupon/pull/145">[2단계] 캐시를 사용한 쿠폰 조회 성능 개선</a></td>
    </tr>
</table>








## 🫡 Soft Skill 

주변에 흔들리지 않고 나만의 속도를 찾기

<table>
        <th>미션 이름</th>
        <th>레벨</th>
        <th>주제</th>
    </tr>
    <tr>
        <td rowspan="5">✒ 글쓰기 미션</td>
        <td>레벨 1</td>
        <td><a href="https://github.com/hoyeonyy/woowa-writing/blob/level2/README.md">나만의 속도 찾기</a></td>
    </tr>
    <tr>
        <td>레벨 2</td>
        <td><a href="https://github.com/hoyeonyy/woowa-writing/blob/level2/level2.md">우선순위 정하기</a></td>
    </tr>
    <tr>
        <td>레벨 3</td>
        <td><a href="https://github.com/hoyeonyy/woowa-writing/blob/level3/level3.md">만족스러운 결과는 무엇일까?</a></td>
    </tr>
</table>


## ✏️ 스터디
- ORM에 의존하여 DB를 도외시하지 않기 위한 스터디 [Real MySQL 8.0 스터디](https://github.com/woowacourse-6th-checks-choco/RealMySql)

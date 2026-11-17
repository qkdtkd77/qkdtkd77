### 안녕하세요, 백엔드 개발자를 준비하는 김태민입니다

베이스를 연주합니다. 밴드에서 베이스는 눈에 잘 띄지 않지만, 리듬을 단단하게 받쳐 줘야 다른 악기가 마음껏 연주할 수 있습니다.
백엔드도 같다고 생각합니다. 사용자가 의식하지 않아도 안정적으로 동작하는 서버를 만들고, 그 근거를 설명할 수 있는 개발자가 되고 싶습니다.

- 기능을 만드는 데서 끝내지 않고, **왜 그렇게 설계했는지** 기록합니다.
- 측정하지 않은 성능 개선은 말하지 않습니다.

<br>

### Tech Stack

**Backend**
<br>
Java, Spring Boot, Spring Security, Spring Data JPA

**Database**
<br>
MySQL, H2

**Collaboration**
<br>
Git, GitHub Issues와 PR, CodeRabbit 코드 리뷰

<br>

### Project

**[LessonLog](https://github.com/qkdtkd77/lessonlog)**
<br>
음악 레슨 선생님이 학생과 레슨 일지를 관리하는 서비스

직접 레슨을 하면서 손으로 일지를 쓰기 불편했던 경험에서 시작했습니다.

- JWT 인증, 역할(ADMIN, TEACHER) 기반 인가, 사용자별 데이터 소유권 검증
- 회원과 학생 soft delete, 탈퇴 계정의 기존 토큰 차단
- 수업이 끝나는 시간대에 요청이 몰리는 상황을 가정한 부하 테스트 진행 중

<br>

### Contact

- Email: qkdtkd77@gmail.com

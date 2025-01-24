# 💡첵스초코 - Real Mysql

## 🚀 진행 방식

1. **스터디 진행 방식**
    
    - 스터디 시간에 발표자를 랜덤으로 선정한다.
    - 발표자가 당일 스터디를 리드하여 진행하고 다른 스터디원들은 질문을 한다.
    - 스터디에서 나온 질문들을 스터디원들에게 할당하여 Discussion에 토의한다.
    
2. **주간 스터디 세션:**
    
    매주 **화요일, 금요일 오후 4시**, 주에 2번의 스터디를 진행한다.

3. **규칙**

   - 자신에게 할당된 디스커션에 답변을 하지 않는 경우 벌금 5000원
   - 주어진 범위의 책을 읽어오지 않은 경우 벌금 5000원

# System Design Interview

- [책 링크](http://www.yes24.com/Product/Goods/102819435)

## 📆 기간

- 일정 : 2024. 10 ~ 2025.01
- 매주 화요일, 금요일 오후 4시

## 학습 내용


<table>
   <tr>
       <th>챕터</th>
       <th>토론 내용</th>
   </tr>
   <tr>
       <td rowspan="11">11장. 쿼리 작성 및 최적화</td>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/34">SELECT 절의 서브 쿼리는 ROWS 수만큼 서브 쿼리를 동작시킬까?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/35">스칼라 서브쿼리와 상관 서브 쿼리는 각각 무엇인가?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/36">세미조인은 과거에 왜 안티패턴이었고 현재는 어떠한 문제가 개선되었는가?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/30">WHERE 조건에 OR이 있을 경우 각각의 컬럼에 인덱스가 걸려있다면 인덱스를 타나?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/31">where a = 4 and b = 9 일때, a, b가 멀티 칼럼 인덱스가 아니라 단일 인덱스로 각각 걸려있다면 인덱스를 어떻게 타나?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/33">지연된 조인은 어떤 최적화를 가져오는 걸까?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/32">limit, offset 최적화 방식은 어떤 것이 있을까?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/27">MySQL의 DATETIME 타입과 TIMESTAMP의 차이가 뭔가요?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/29">NOT 연산자를 사용하면 인덱스를 탈까 말까?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/28">IN절을 사용하면 성능 최적화가 되는 이유가 뭔가요?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/14">자동증가락이 있음에도 불구하고 PK값이 점프해서 저장되는 현상이 발생하는 이유는?</a></td>
   </tr>
   <tr>
       <td rowspan="5">8장. 인덱스</td>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/25">PK를 인조식별자로 두는 것과 업무적으로 의미 있는 값으로 설정하는 방식의 비교</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/26">JSON 데이터 타입이 사용되는 예시 상황과 중요도 조사</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/24">클러스터링 인덱스 조회가 세컨더리 인덱스 조회보다 빠른 이유는 무엇인가?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/23">클러스터링 인덱스의 리프노드는 데이터를 가지고 있는가 물리 주소의 참조를 가지고 있는가?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/20">인덱스에서 키 값의 부분일치를 찾을 때 값의 앞부분을 기준으로만 검색할 수 있는 이유는 무엇인가?</a></td>
   </tr>
   <tr>
       <td rowspan="7">5장. 트랜잭션과 잠금</td>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/22">MySQL의 RR(Repeatable Read)격리 수준이 Phantom Read 문제를 방지하는 과정</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/18">insert를 할 때 리두로그를 바라보았다면 굳이 팬텀리드 문제를 고려하지 않아도 되었을텐데, 그러지 않은 이유가 무엇일까?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/15">innodb에서 index기반으로 락을 거는 이유는?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/16">코드레벨에서 읽기 전용 작업의 내부로직의 처리시간이 긴 경우 readOnly=true 를 안붙이는 것이 이득이지만, 그럼에도 불구하고 readOnly=true가 득이 되는 경우는?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/19">왜 InnoDB 스토리지 엔진은 세컨더리 인덱스가 클러스터 인덱스를 한번 더 거치도록 설계했을까?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/21">인덱스가 없을 때 테이블이 전부 잠길 수 있는 이유는 무엇인가?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/17">오라클은 MySQL을 인수하지 않았나요?, 왜 기본 격리수준이 다를까요?</a></td>
   </tr>
   <tr>
       <td rowspan="8">4장. 아키텍처</td>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/11">MySQL 에서 스레드 캐시와 스레드 풀의 차이는 무엇인가?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/12">MySQL 스레드들은 어디에 속하는 개념인가?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/13">InnoDB 에서 포그라운드 스레드는 어떤역할을 담당하나?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/8">트랜잭션 격리 수준과 락의 차이</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/9">InnoDB의 쓰기 지연 vs JPA의 쓰기지연</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/10">Gap Lock, Named Lock이란?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/6">외래키를 사용했을때의 단점 (feat 잠금)</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/7">낙관적 락과 MVCC의 차이</a></td>
   </tr>
   <tr>
       <td rowspan="5">2장. 설치와 설정</td>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/3">인플레이스 업그레이드, 논리적 업그레이드</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/5">MySQL 서버에 접속할 때 프로토콜은 http와 https 중 무엇이 적당할까?</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/2">MySQL 소켓 통신과 tcp 통신의 차이</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/4">MySQL 5.7 과 8.0 의 계정 생성의 차이</a></td>
   </tr>
   <tr>
       <td><a href="https://github.com/orgs/woowacourse-6th-checks-choco/discussions/1">MySQL에서 localhost 와 127.0.0.1 의 차이는 무엇일까?</a></td>
   </tr>
</table>

## 📜 진행방식

- 발표자는 매주 수요일 00시 전에 발표자료를 PR 로 올립니다.
- 그 외 인원은 월요일 00시 전에 각 장마다 질문 혹은 중요하다고 생각되는 부분을 Issue 로 남겨주세요.
- 발표에 대한 내용은 아래를 참고해주세요.
- 발표가 모두 끝나면 10분 내외의 회고를 진행합니다.
- 회고에 대한 내용은 아래를 참고해주세요.

## 🖥 발표

- 발표는 일주일에 2챕터씩 진행하며, 각 챕터 마다 발표자가 배정이 됩니다.
- 발표자는 발표자료를 만드는 작업을 진행합니다.
- 시작 시 발표자는 발표자료를 이용해 발표를 진행합니다.
- 발표자는 그 주에 올라온 Issue 를 리뷰하며 다 같이 논의합니다.

## 📚 Github 저장소

- PR에 대한 머지는 직접 운영진이 할 예정입니다.
- 발표자료의 파일명은 아래와 같이 해주세요.

```java
[X주차]_X장_제목_이름
```

- PR을 올려주실때는 포크 저장소를 이용해주세요.
- PR은 발표자료 파일명과 동일하게 올려주세요.
```java
[X주차]_X장_제목_이름
```

- Issue 는 아래와 같이 제목을 작성해주세요.
```java
[X주차]_X장_제목_이름
```

## 👨‍👩‍👧‍👦 회고

- 1주일 동안 책을 읽으면서 느낀점, 발표를 보고 느낀점 들을 자유롭게 이야기 해주시면 됩니다.
- 자유롭게 각자 하고 싶은 말을 하면 되니 부담 가지실 필요는 없습니다.

## 💰 보증금 및 벌금

- 보증금 2만원을 첫 시작 때 운영진에게 입금합니다.
- 발표자료를 기한 내에 PR하지 않은 경우 벌금으로 차감됩니다.
- 벌금은 4000원입니다.
- 마지막 모임에서 남은 금액에 대해 환급을 받는다.
- 모든 벌금은 마지막 모임 시, 오프라인 모임 시 사용됩니다.(스터디룸 비 및 회식 비)
- 중도 하차하신 분은 보증금을 돌려주지 않습니다.

## 기타

- 커뮤니케이션을 위해 Slack을 사용합니다.

## Q&A

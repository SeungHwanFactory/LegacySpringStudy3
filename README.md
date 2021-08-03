# LegacySpringStudy3
페이징 처리 공부


- language: 자바(Java)
- Framework: 스프링(Spring)
- DataBase: OracleDB
- tools: sts-3.9.13.RELEASE
- jdk: 1.8

---
## 📖 전체적인 흐름

* order by의 문제
* 인덱스
* ROWNUM, 인라인뷰
* MyBatis와 스프링에서 페이징 처리
  * MyBatis 처리 및 테스트 케이스 작성
  * 컨트롤러, 서비스 수정
* 페이징 화면 처리
  * 페이징 처리 시 필요한 정보
    * 현재 페이지 번호
    * 이전, 다음
    * 시작번호, 끝번호
  * 페이징 처리를 위한 클래스 설계
  * JSP에서 페이지 번호 출력
  * 조회 페이지
    * 페이지 번호 유지
    * 수정/삭제 페이지 처리 후 이동
    * 수정/삭제 페이지에서 목록 페이지로 이동
  * MyBatis에서 전체 데이터의 개수 처리
---

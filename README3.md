- Persistence : 영속성
- ORM : Object-Relational Mapping : 객체와 DB의 테이블이 매핑을 이루는 것
- JPA : Java Persistence API : 자바 ORM기술에 대한 API 표준 명세
  ( 중요한 핵심기술이지만 사용이 한정적 ) 
- Hibernate : JPA를 사용하기 위해 JPA를 구현한 ORM 프레임워크중 하나.( ORM프레임워크 중 가장 성숙한 프레임워크 )
- JDK : Java Development Kit : 자바 개발키트
- JVM : Java Virtual Machine : 자바 가상머신
- JRE : Java Runtime Environment : 자바 런타임 환경
- OOP : Object-Oriented Programming : 객체지향 프로그래밍
- JDBC : Java Data Base Connection : JAVA언어를 통해 DB에 접근할 수 있는 프로그래밍
- API : Application Programming Interface : 미리 작성된 코드, 비슷한 주제를 가진 패키지들로 구성
- SDK : Standard Development Kit : 모든 개발언어의 소프트웨어 개발 킷
       (Software Development Kit)
- IDE : Integrated Development Environment : 통합 개발 환경
- GUI : Graphical User Interface : 그래픽 사용자 인터페이스
- Entity : 데이터 베이스에 저장하기위해 유저가 정의한 클래스 == Domain
- 영속성 컨텍스트 : Entity를 영구 저장하는 환경 : 애플리케이션과 DB사이에서 객체를 보관하는 가상의 데이터베이스 역할
		-앤티티 매니저를 통해 앤티티를 저장하거나 조회하면 앤티티 매니저는- 
			    -영속성 컨텍스트에 앤티티를 보관 및 관리-
- dialect : 방언, 사투리 : hibernate 내에서 특정 DB별 의존적인 SQL을 사용할 때를 대비하여 선언하여줌.
	ex ) H2 : <property name="hibernate.dialect" value="org.hibernate.dialect.H2Dialect" /> 선언
- JPQL : Java Persistence Query Language : 클래스와 필드를 대상으로 쿼리를 작성
        JPA는 이 JPQL에 따라 SQL문을 작성하여 DB테이블의 데이터를 가져옴.
- parameter : 매개변수 : 함수의 정의부분에 나열되어 있는 변수.
- argument : 전달인자 : 함수를 호출할 때 전달되는 실제 값.
- SQL : Structured Query Language : RDBMS의 데이터를 관리하기 위해 설계된 특수 목적의 프로그래밍 언어.
- RDBMS :  Relational DataBase Management System : 관계형 데이터베이스 관리 시스템 : 테이블간에 서로 연관 되어있음
- DBMS : DataBase Management System : 데이터베이스 관리 시스템 : 테이블간에 연관이 없음
- Query : 데이터베이스에 정보를 요청하는 것. : Query(질문) 라는 뜻 그대로 DB에 데이터를 요청(질문) 함.

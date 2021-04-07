# JSP 강의평가 웹 사이트 개발하기

##### [Dongbin Na_GitHub](https://github.com/ndb796)

#### [동빈나_YouTube](https://www.youtube.com/channel/UChflhu32f5EUHlY7_SetNWw)

[2강 - JSP 개발환경 구축 및 테스트 (JSP Lecture Evaluation Service Development Tutorial #2)](https://www.youtube.com/watch?v=JCTB9GxD3ig)

[3강 - MySQL과 JSP 연동 및 실습 (JSP Lecture Evaluation Service Development Tutorial #3)](https://www.youtube.com/watch?v=1Wuwl57cXvw)

###### -- 주석

※ 대소문자 상관없음

![create_database_tutorial](https://github.com/jiyeong1004/JSP_Login/blob/main/image/create_database_tutorial.png)

###### -- **** : root

###### -- TUTORIAL 데이터베이스 생성
##### CREATE DATABASE TUTORIAL;

###### -- TUTORIAL 데이터베이스 사용
##### USE TUTORIAL;

###### -- TUTORIAL 데이터베이스에 있는 테이블들을 보여줌 (비어있음)
##### SHOW TABLES;

---

![create_table_user](https://github.com/jiyeong1004/JSP_Login/blob/main/image/create_table_user.png)

###### -- USER 테이블 생성
##### CREATE TABLE USER;

###### -- TUTORIAL 데이터베이스에 있는 테이블들을 보여줌 (USER 테이블 하나만 생성됨)
##### SHOW TABLES;

---

![insert_into_user](https://github.com/jiyeong1004/JSP_Login/blob/main/image/insert_into_user.png)

###### -- USER 테이블에 있는 userID에는 1, userPassword에는 123 삽입
##### INSERT INTO USER VALUES('1', '123');

###### -- USER 테이블에 있는 모든 값을 보여줌
##### SELECT * FROM USER;

---

![select_userID_from_user](https://github.com/jiyeong1004/JSP_Login/blob/main/image/select_userID_from_user.png)

###### -- USER 테이블에 있는 userID의 값만 보여줌
##### SELECT userID FROM USER;

---

![select_from_user](https://github.com/jiyeong1004/JSP_Login/blob/main/image/select_from_user.png)

###### -- USER 테이블에 있는 모든 값을 보여줌(jsp로 실행해서 값을 넣음)
##### SELECT * FROM USER;


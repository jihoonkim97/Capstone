# elasticsearch와 추천 알고리즘을 이용한 자격증 웹 사이트 #


### 1. 프로젝트 수행목적

1-1. **프로젝트 정의**
  
  elasticsearch와 추천 알고리즘을 이용한 자격증 정보 제공 웹 사이트

1-2. **프로젝트 목표**

  * 자격증 정보 수집
  
   		크롤링을 이용하여 여러 자격증 사이트에서 제공하는 자격증 정보 수집, 제공

  * 사용자별 적합한 자격증 추천
  
  		특징이 비슷한 타 사용자의 자격증 열람 기록을 토대로 사용자에게 적합한 자격증 추천

  * 사람들이 함께 본 자격증 추천
  
  		열람중인 자격증을 본 사람들이 조회했던 자격증 상위 조회수 순으로 추천

  * 검색 엔진 구현
  
  		Elasticsearch를 이용한 검색 엔진 구현


### 2. 프로젝트 개요

2-1 **프로젝트 설명**
   - 크롤링을 이용해 수집한 자격증을 사용자들이 입력한 관심 분야에 기반하여 각각의 사용자에 맞게 추천하고, elasticsearch를 이용한 검색 엔진으로 원하는 자격증을 검색해 열람한 자격증 정보를 Web으로 보여준다.


2-2. **프로젝트 구조**

![최종프로젝트구조](https://user-images.githubusercontent.com/81609885/122360933-c22f0100-cf91-11eb-8d61-2abafb1cf7fe.png)


2-3. **관련기술 및 개발도구**

**관련기술:**

- Elasticsearch/Logstash
- Spring Boot
- Spring Data JPA/Hibernate
- Thymeleaf
- Crawling(Jsoup)

**개발도구:**

- IntelliJ
- Gradle
- MySQL


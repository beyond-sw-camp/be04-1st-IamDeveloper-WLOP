# be04-1st-IamDeveloper-WLOP
## Team Members
김재현, 백동현, 서승엽, 이드보라, 윤재은, 조수빈

![WLOP LOGO](https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/3d064349-0410-4504-b1cc-0c0855986f81)

# 1. 프로젝트 기획서

<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/1b14eb7e-4587-4c7d-a44d-259119c3bb79" alt="시장조사"  width="600" height="400"/>

**💫프로젝트 개요**

    - 한국인 4명 가운데 1명이 반려동물을 키우는 반려인구 1500만 시대가 열렸다고 한다. 이에따라 반려동물
    시장도 성장하고 있는데, 한국농촌경제연구원에 따르면, 2015년 1조9천억원 규모였던 국내 반려동물 시장이
    올해는 23년에는 4조5786억원에 이르고, 2027년에는 6조원 규모까지 성장할것으로 보고있다.
    - 주변에 반려동물과 함께 갈수있는 식당이나, 숙박업소 그리고 반려동물들을 위한 병원까지 하나씩 지도에서 
    찾기에는 너무 귀찮고 어려울 수 있겠다는 생각에 반려동물과 함께 할수있는 장소들에 대한 정보를 제공하고,
    게시판을 통해 반려동물들을 자랑하고, 정보를 공유하는등의 활동을 할 수 있는 커뮤니티 서비스를 제공한다.

**🐶프로젝트 소개**

     - 우리의 커뮤니티 서비스인 WLOP(we love our pet)은 반려인구가 늘어나는 현대사회에서 하나의 가족으로
     자리잡고 있는 반려동물들과 함께 할 수 있는 병원, 식당, 카페, 숙박업소에 대한 정보를 한눈에 볼 수 있게
     제공하고, 함께 리뷰와 댓글도 남기며 같은 반려인들 끼리 정보도 나누고 무료로 물품도 나눌  수 있는 기능을 제공한다.
     - 우리의 서비스를 통해 많은 반려인들이 하나되고, 즐거운 시간을 보내며 크게는 반려동물에 대한 인식이 좋아짐에 따라
     더 많은 장소를 우리의 반려동물들과 함께 할 수 있는 사회를 만드는데 기여하고자 한다.
----------------------------------------------------------------   
# 2. 업무 흐름도
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/11d7752c-df69-418b-8705-628bee1cedc3" alt="업무흐름도" width="900" height="600"/>

-----------------------------
# 3. 요구사항
  ## 사용자 요구사항 분석
<details>
  <summary>정보게시판</summary>
    <li> 소개글
    
    - 소개글 작성(중요도:상, 난이도: 상)
    - 소개글 수정(중요도:하, 난이도: 하)
    - 소개글 삭제(중요도:하, 난이도: 하)

   <li> 리뷰
    
    - 리뷰 작성(중요도:상, 난이도: 상)
    - 리뷰 수정(중요도:하, 난이도: 하)
    - 리뷰 삭제(중요도:하, 난이도: 하)
    
   <li>댓글
    
    - 댓글 작성(중요도:하, 난이도: 하)
    - 댓글 수정(중요도:하, 난이도: 하)
    - 댓글 삭제(중요도:하, 난이도: 하)
   
   <li> 추천
       
    - 리뷰 추천(중요도:중, 난이도: 하)
    - 리뷰 추천 취소(중요도:하, 난이도: 상)
   
   <li> 신고

    - 신고 작성(중요도:중, 난이도: 하)
    - 신고 철회(중요도:하, 난이도: 하)
</details>

<details>
  <summary>자유게시판</summary>
  <li> 게시글
    
    - 게시물 작성(중요도:중, 난이도: 상)
    - 게시물 수정(중요도:하, 난이도: 하)
    - 게시물 삭제 (중요도:하, 난이도: 하)
    - 게시글 조회(조회수 반영)(중요도:하, 난이도: 상)
  <li> 댓글
  
    - 댓글 작성(중요도:하, 난이도: 하)
    - 댓글 수정(중요도:하, 난이도: 하)
    - 댓글 삭제(중요도:하, 난이도: 하)
    
  <li> 추천
    
    - 게시글 추천(중요도:하, 난이도: 하)
    - 추천 취소(중요도:하, 난이도: 상)
    
  <li> 신고
  
    - 신고 작성(중요도:중, 난이도: 하)
    - 신고 철회(중요도:하, 난이도: 하)
</details>

<details>
  <summary>공지게시판</summary>
  <li> 공지 작성(중요도:중, 난이도: 하)
  <li> 공지 수정(중요도:하, 난이도: 하)
  <li> 공지 삭제(중요도:하, 난이도: 하)
</details>

<details>
  <summary>문의게시판</summary>
 <li> 문의게시물 작성(중요도:하, 난이도: 하)
 <li> 문의게시물 수정(중요도:하, 난이도: 하)
 <li> 문의게시물 삭제(중요도:하, 난이도: 하)
 <li> 문의 답변(중요도:하, 난이도: 중)
</details>

<details>
  <summary>무료나눔게시판</summary>
 <li> 나눔게시글
     
    - 나눔게시글 작성(중요도:중, 난이도: 상)
    - 나눔게시글 수정(중요도:하, 난이도: 하)
    - 나눔게시글 삭제(중요도:하, 난이도: 하)
  <li> 댓글
    
    - 댓글 작성(중요도:하, 난이도: 하)
    - 댓글 수정(중요도:하, 난이도: 하)
    - 댓글 삭제(중요도:하, 난이도: 하)
</details>

<details>
  <summary>회원</summary>
 <li> 회원가입(중요도:상, 난이도: 하)
 <li> 회원탈퇴(중요도:상, 난이도: 상)
 <li> 로그인(중요도:중, 난이도: 하)
 <li> 로그아웃(중요도:중, 난이도: 하)
 <li> 마이페이지
     
    - 회원정보 조회(중요도:하, 난이도: 하)
    - 회원정보 수정(중요도:하, 난이도: 하)
    - 회원등급 조회(중요도:하, 난이도: 하)
    - 작성 게시물 조회(중요도:하, 난이도: 중)
    - 작성 댓글 조회(중요도:하, 난이도: 중)
    - 문의내역 조회(중요도:하, 난이도: 하)
    - 신고내역 조회(중요도:하, 난이도: 하)
    - 사업자 등록(중요도:하, 난이도: 하)
<li> 프로필
    
    - 내소개내용 작성(중요도:하, 난이도: 하)
    - 내소개내용 수정(중요도:하, 난이도: 하)
    - 내소개내용 삭제(중요도:하, 난이도: 하)
    - 내사진 추가(중요도:하, 난이도:상 )
    - 내사진 수정(중요도:하, 난이도: 하)
    - 내사진 삭제(중요도:하, 난이도: 하)
<li> 반려동물 프로필
    
    - 반려동물 프로필 작성(중요도:하, 난이도: 상)
    - 반려동물 프로필 수정(중요도:하, 난이도: 하)
    - 반려동물 프로필 삭제(중요도:하, 난이도: 하)
<li> 휴면회원
    
    - 정상회원 복구(중요도:하, 난이도: 상)
</details>

<details>
  <summary>관리자</summary>
<li> 문의내역 처리(중요도:하, 난이도: 하)
<li> 신고내역 처리(중요도:하, 난이도: 하)
<li> 블랙리스트 처리(중요도:하, 난이도: )
<li> 다이아몬드 회원 등업(중요도:중, 난이도: 하)
<li> 공지 관리(중요도:하, 난이도: 하)
</details>

  
  ## 요구사항 명세서
  <img src="https://github.com/dongh810/Beyond_SW_Camp_Study/assets/105986200/1da4106f-bd5e-4c63-a4d2-1849846c5678" alt="요구사항 명세서 이미지" width="900" height="400"/>
  
---------------------------
# 4. 프로젝트 모델링
  ## 프로젝트 설계 내역
<details>
  <summary>4-1. 개념논리모델</summary>
<img src="" alt="개념논리 모델" width="900" height="400"/>
</details>

<details>
  <summary>4-2. 물리모델</summary>
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/40e16618-8f71-4669-accf-0c720a625277" alt="개념논리모델" width="900" height="400"/>
</details>


----------------------------
# 5. DDL 구문 & 서버 구축(시스템 아키텍처)
<details>
  <summary>5-1. DDL 구문</summary>

```java
CREATE TABLE `WLOP_Member` (
   `member_id`   varchar(255)   NOT NULL PRIMARY KEY,
   `member_pw`   varchar(255)   NOT NULL,
   `member_name`   varchar(255)   NOT NULL,
   `member_address`   varchar(255)NOT NULL,
   `member_call`   varchar(255)   NOT NULL,
   `member_email`   varchar(255)   NOT NULL,
   `member_nick`   varchar(255)   NOT NULL UNIQUE,
   `member_date`   varchar(255)   NOT NULL,
   `report_num`   int   NOT NULL   COMMENT '신고접수 후 관리자가 삭제한 횟수',
   `grade_code`   int   NOT NULL DEFAULT 1,
   `review_count` INT NOT NULL
);

CREATE TABLE `WLOP_Type` (
   `type_code`   int   NOT NULL PRIMARY KEY,
   `type_info`   varchar(255)   NOT NULL
);

CREATE TABLE `Review` (
   `review_code`   int   NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `review_star`   int   NOT NULL,
   `review_content`   VARCHAR(255)   NOT NULL,
   `review_likes`   int   NULL DEFAULT 0,
   `review_date`   VARCHAR(255)   NOT NULL,
   `info_code`   int   NOT NULL,
   `review_writer`   varchar(255)   NOT NULL,
   `use_yn` VARCHAR(255) NOT NULL
);

CREATE TABLE `WLOP_Comment` (
   `comment_code` INT NOT NULL AUTO_INCREMENT PRIMARY KEY, 
   `comment_content`   varchar(255)   NOT NULL,
   `comment_writer`   varchar(255)   NOT NULL,
   `review_code`   int   NULL,
   `share_code`   int   NULL,
   `freeboard` INT NULL, 
   `use_yn` VARCHAR(255) NOT NULL
);

CREATE TABLE `Information` (
   `info_code`   int   NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `info_name`   varchar(255)   NOT NULL,
   `info_address`   varchar(255)   NOT NULL,
   `info_call`   varchar(255)   NOT NULL,
   `info_date`   varchar(255)   NOT NULL,
   `type_code`   int   NOT NULL,
   `info_writer`   varchar(255)   NOT NULL,
   `use_yn` VARCHAR(255) NOT NULL
);

CREATE TABLE `GoodsShare` (
    `goods_code` INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `goods_name`   varchar(255)   NOT NULL,
   `goods_feature`   varchar(255)   NOT NULL COMMENT'상품 설명',
   `goods_date`   varchar(255)   NOT NULL,
   `goods_writer`   varchar(255)   NOT NULL,
   `goods_category`   int   NOT NULL,
   `use_yn` VARCHAR(255) NOT NULL
);

CREATE TABLE `MemberGrade` (
   `grade_code`   int   NOT NULL PRIMARY KEY,
   `grade_content`   varchar(255)   NOT NULL
);

CREATE TABLE `QNA` (
   `Q_id`   int   NOT NULL AUTO_INCREMENT PRIMARY key,
   `Q_content`   varchar(255)   NOT NULL,
   `Q_date`   varchar(255)   NOT NULL,
   `A_content`   varchar(255)   NULL COMMENT '답변 내용',
   `Q_writer`   varchar(255)   NOT NULL
);

CREATE TABLE `Administer` (
   `admin_id`   varchar(255)   NOT NULL PRIMARY KEY,
   `admin_pss`   varchar(255)   NOT NULL,
   `admin_nickname`   varchar(255)   NOT NULL
);

CREATE TABLE `Report` (
   `report_number` INT NOT NULL AUTO_INCREMENT PRIMARY KEY ,
   `report_content`   varchar(255)   NOT NULL,
   `report_date`   varchar(255)   NOT NULL,
   `report_code`   int   NOT NULL,
   `report_now_code`   int   NOT NULL,
   `report_subject`   varchar(255)   NOT NULL,
   `report_writer`   varchar(255)   NOT NULL,
   `freeboard` INT    NULL,
   `goods_code` INT    NULL,
   `review_code` INT  NULL,
   `comment_code` INT  NULL
);

CREATE TABLE `WLOP_Profile` (
   `Member_ID`   varchar(255)   NOT NULL PRIMARY KEY,
   `my_introduce`   varchar(255)   NULL
);

CREATE TABLE `Blacklist` (
   `black_id`   varchar(255)   NOT NULL PRIMARY KEY,
   `black_reason`   varchar(255)   NOT NULL,
   `black_ candidate`   varchar(255)   NULL
);

CREATE TABLE `Report_Type` (
   `Report_code`   int   NOT NULL PRIMARY KEY,
   `report_category`   varchar(255)   NOT NULL
);

CREATE TABLE `Report_Status` (
   `Status_code`   int   NOT NULL PRIMARY KEY,
   `Status_category`   varchar(255)   NOT NULL
);

CREATE TABLE `AnimalCategory` (
   `animal_code`   int   NOT NULL PRIMARY KEY,
   `animal_code_feature`   varchar(255)   NOT NULL
);

CREATE TABLE `Billboard` (
   `freeboard`   int   NOT NULL AUTO_INCREMENT PRIMARY KEY COMMENT '게시판 일련번호',
   `board_content`   varchar(255)   NOT NULL,
   `board_date`   varchar(255)   NOT NULL,
   `board_check`   int   NOT NULL,
   `board_likes`   int   NOT NULL,
   `member_id`   varchar(255)   NOT NULL,
   `use_yn` VARCHAR(255) NOT NULL
);

CREATE TABLE `MemberAdmin` (
   `Member_ID`   varchar(255)   NOT NULL PRIMARY KEY,
   `business_code`   VARCHAR(255)   NOT NULL,
   `blacklist_code`   VARCHAR(255)   NOT NULL,
   `status_code`   int   NOT NULL,
   `connection_date`   varchar(255)   NOT NULL,
   `admin_id`   varchar(255)   NOT NULL
);

CREATE TABLE `WLOP_Status` (
   `status_code`   int   NOT NULL PRIMARY KEY,
   `status_code_feature`   varchar(255)   NOT NULL
);

CREATE TABLE `Pet` (
   `pet_number`   int   NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `pet_id`   varchar(255)   NOT NULL,
   `pet_type`   varchar(255)   NULL,
   `pet_name`   varchar(255)   NOT NULL,
   `pet_birth`   varchar(255)   NULL,
   `pet_sex`   varchar(255)   NULL
);

CREATE TABLE `Notification` (
   `notification_num`   int   NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `notification_text`   varchar(255)   NOT NULL,
   `admin_id`   varchar(255)   NOT NULL
);

CREATE TABLE `Animal_type_category` (
   `type_code`   int   NOT NULL,
   `animal_code`   int   NOT NULL,
   PRIMARY KEY (type_code, animal_code)
);

CREATE TABLE `Goods` (
   `goods_category`   int   NOT NULL PRIMARY KEY,
   `goods_category_feature`   varchar(255)   NOT NULL
);

CREATE TABLE `Photo` (
   `photo_code`   int   NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `photo_name`   varchar(255)   NOT NULL,
   `photo_directory`   varchar(255)   NOT NULL,
   `photo_rename`   varchar(255)   NULL,
   `notification_num` INT  NULL,
   `info_code` INT  NULL,
   `review_code` INT  NULL,
   `pet_number` INT    NULL,
   `pet_id` VARCHAR(255) NULL,
   `goods_code` INT  NULL,
   `freeboard` INT  NULL,
   `Member_ID` VARCHAR(255)  NULL 
);

CREATE TABLE `Likes` (
   `code`   int   NOT NULL AUTO_INCREMENT PRIMARY KEY,
   `content_type`   varchar(255)   NOT NULL COMMENT 'Review or Billboard',
   `review_code`   int,
   `freeboard`   int,
   `member_id`   varchar(255)   NOT NULL,
   FOREIGN KEY (`review_code`) REFERENCES `Review` (`review_code`) ON DELETE CASCADE,
   FOREIGN KEY (`freeboard`) REFERENCES `Billboard` (`freeboard`) ON DELETE CASCADE,
   FOREIGN KEY (`member_id`) REFERENCES `WLOP_Member`(`member_id`)
) ENGINE=InnoDB;

ALTER TABLE `WLOP_Member` ADD CONSTRAINT `FK_MemberGrade_TO_Member_1` FOREIGN KEY (
   `grade_code`
)
REFERENCES `MemberGrade` (
   `grade_code`
);

ALTER TABLE `Review` ADD CONSTRAINT `FK_Information_TO_Review_1` FOREIGN KEY (
   `info_code`
)
REFERENCES `Information` (
   `info_code`
);

ALTER TABLE `Review` ADD CONSTRAINT `FK_Member_TO_Review_1` FOREIGN KEY (
   `review_writer`
)
REFERENCES `WLOP_Member` (
   `member_id`
);


ALTER TABLE `WLOP_Comment` ADD CONSTRAINT `FK_Review_TO_Comment_1` FOREIGN KEY (
   `review_code`
)
REFERENCES `Review` (
   `review_code`
);

ALTER TABLE `WLOP_Comment` ADD CONSTRAINT `FK_Billboard_TO_Comment_1` FOREIGN KEY (
   `freeboard`
)
REFERENCES `Billboard`(
   `freeboard`
);

ALTER TABLE `WLOP_Comment` ADD CONSTRAINT `FK_Member_TO_Comment_1` FOREIGN KEY (
   `comment_writer`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `WLOP_Comment` ADD CONSTRAINT `FK_GoodsShare_TO_Comment_1` FOREIGN KEY (
   `share_code`
)
REFERENCES `GoodsShare` (
   `goods_code`
);

ALTER TABLE `Information` ADD CONSTRAINT `FK_Type_TO_Information_1` FOREIGN KEY (
   `type_code`
)
REFERENCES `WLOP_Type` (
   `type_code`
);

ALTER TABLE `Information` ADD CONSTRAINT `FK_Member_TO_Information_1` FOREIGN KEY (
   `info_writer`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `GoodsShare` ADD CONSTRAINT `FK_Member_TO_GoodsShare_1` FOREIGN KEY (
   `goods_writer`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `GoodsShare` ADD CONSTRAINT `FK_Goods_TO_GoodsShare_1` FOREIGN KEY (
   `goods_category`
)
REFERENCES `Goods` (
   `goods_category`
);

ALTER TABLE `QNA` ADD CONSTRAINT `FK_Member_TO_QNA_1` FOREIGN KEY (
   `Q_writer`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_Report_Type_TO_Report_1` FOREIGN KEY (
   `report_code`
)
REFERENCES `Report_Type` (
   `Report_code`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_Report_Status_TO_Report_2` FOREIGN KEY (
   `report_now_code`
)
REFERENCES `Report_Status` (
   `Status_code`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_wlop_member_TO_Report_3` FOREIGN KEY (
   `report_subject`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_wlop_member_TO_Report_4` FOREIGN KEY (
   `report_writer`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_Billboard_TO_Report_5` FOREIGN KEY (
   `freeboard`
)
REFERENCES `Billboard` (
   `freeboard`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_GoodsShare_TO_Report_6` FOREIGN KEY (
   `goods_code`
)
REFERENCES `GoodsShare` (
   `goods_code`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_Review_TO_Report_7` FOREIGN KEY (
   `review_code`
)
REFERENCES `Review` (
   `review_code`
);

ALTER TABLE `Report` ADD CONSTRAINT `FK_WLOP_Comment_TO_Report_8` FOREIGN KEY (
   `comment_code`
)
REFERENCES `WLOP_Comment` (
   `comment_code`
);

ALTER TABLE `WLOP_Profile` ADD CONSTRAINT `FK_Member_TO_Profile_1` FOREIGN KEY (
   `Member_ID`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `Blacklist` ADD CONSTRAINT `FK_Member_TO_Blacklist_1` FOREIGN KEY (
   `black_id`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `Billboard` ADD CONSTRAINT `FK_Member_TO_Billboard_1` FOREIGN KEY (
   `member_id`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `MemberAdmin` ADD CONSTRAINT `FK_Member_TO_MemberAdmin_1` FOREIGN KEY (
   `Member_ID`
)
REFERENCES `WLOP_Member` (
   `member_id`
);

ALTER TABLE `MemberAdmin` ADD CONSTRAINT `FK_Status_TO_MemberAdmin_1` FOREIGN KEY (
   `status_code`
)
REFERENCES `WLOP_Status` (
   `status_code`
);

ALTER TABLE `MemberAdmin` ADD CONSTRAINT `FK_Administer_TO_MemberAdmin_1` FOREIGN KEY (
   `admin_id`
)
REFERENCES `Administer` (
   `admin_id`
);

ALTER TABLE `Pet` ADD CONSTRAINT `FK_Profile_TO_Pet_1` FOREIGN KEY (
   `pet_id`
)
REFERENCES `WLOP_Profile` (
   `Member_ID`
);

ALTER TABLE `Notification` ADD CONSTRAINT `FK_Administer_TO_Notification_1` FOREIGN KEY (
   `admin_id`
)
REFERENCES `Administer` (
   `admin_id`
);

ALTER TABLE `Animal_type_category` ADD CONSTRAINT `FK_Type_TO_Animal_type_category_1` FOREIGN KEY (
   `type_code`
)
REFERENCES `WLOP_Type` (
   `type_code`
);

ALTER TABLE `Animal_type_category` ADD CONSTRAINT `FK_AnimalCategory_TO_Animal_type_category_1` FOREIGN KEY (
   `animal_code`
)
REFERENCES `AnimalCategory` (
   `animal_code`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_Notification_TO_Photo_1` FOREIGN KEY (
   `notification_num`
)
REFERENCES `Notification`(
   `notification_num`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_Information_TO_Photo_1` FOREIGN KEY (
   `info_code`
)
REFERENCES `Information`(
   `info_code`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_Review_TO_Photo_1` FOREIGN KEY (
   `review_code`
)
REFERENCES `Review`(
   `review_code`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_Pet_TO_Photo_1` FOREIGN KEY (
   `pet_number`
)
REFERENCES `Pet`(
   `pet_number`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_Pet_TO_Photo_2` FOREIGN KEY (
   `pet_id`
)
REFERENCES `Pet`(
   `pet_id`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_GoodsShare_TO_Photo_1` FOREIGN KEY (
   `goods_code`
)
REFERENCES `GoodsShare`(
   `goods_code`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_Billboard_TO_Photo_1` FOREIGN KEY (
   `freeboard`
)
REFERENCES `Billboard`(
   `freeboard`
);

ALTER TABLE `Photo` ADD CONSTRAINT `FK_WLOP_Profile_TO_Photo_1` FOREIGN KEY (
   `Member_ID`
)
REFERENCES `WLOP_Profile`(
   `Member_ID`
);
```

</details>

<details>
  <summary>5-2. 시스템 아키텍처</summary>
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/4ee64be1-d5ec-49eb-859d-25d7b4ed988f" alt="시스템 아키텍처" width="900" height="600"/>
    
</details>   


<details>
  <summary>5-3. 리눅스 데이터베이스 생성 및 연동 확인</summary>
<li> 리눅스 데이터 베이스 생성

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/4f9cb1be-8b1d-4b17-a840-959f918978ba

<li> 서버 외부 접속

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/bbe32a3e-de7b-494b-b0f1-66c4e5774d6a

<li> 서버 구축 사용 설명서

    master server IP = 172.30.1.58
    slave server IP = 172.30.1.55
    #mariadb가 이용하는 3306포트를 허용해주고 방화벽 설정
    # - master
    sudo ufw allow 3306
    sudo ufw enable
    # - slave
    sudo ufw allow 3307
    sudo ufw enable

    #mariadb 접속
    sudo mariadb -u root -r

    #master서버에서 slave서버의 replication 접속 권한 부여
    GRANT REPLICATION SLAVE ON *.* TO 'slave'@'%' IDENTIFIED BY 'slave';

    #master 유저 생성 및 권한 부여

    CREATE USER 'master'@'%' IDENTIFIED BY 'master';
    GRANT ALL PRIVILEGES ON *.* TO 'master'@'%' IDENTIFIED BY 'master';

    #마스터 서버 mariadb의 50-server.cnf 파일에서 마스터서버의 정보 입력
    sudo vi /etc/mysql/mariadb.conf.d/50-server.cnf
    -------------------------------------------------------------------------
    server-id = 1
    log_bin = /var/log/mysql/mysql-bin.log
    expire _logs_days = 10
    max_binlig_size = 100M
    -------------------------------------------------------------------------


    #입력이 끝나면 mariadb를 재시작
    sudo systemctl restart mariadb

    #슬레이브 서버 mariadb의 50-server.cnf파일 에서 슬레이브서버의 정보 입력
    sudo vi /etc/mysql/mariadb.conf.d/50-server.cnf

    port = 3307 (외부 접속 시 master와 slave를 구분하기 위해 포트를 다르게 설정)
    -------------------------------------------------------------------------
    server-id = 2
    relay_log = mysql-relay-bin
    log_slave_updates = 1
    read_only = 1
    -------------------------------------------------------------------------


    #입력이 끝나면 mariadb를 재시작
    sudo systemctl restart mariadb

    #마스터서버에서  mysql-bin파일명과 position 확인
    show master status;
    +------------------+----------+--------------+------------------+
    | File             | Position | Binlog_Do_DB | Binlog_Ignore_DB |
    +------------------+----------+--------------+------------------+
    | mysql-bin.000002 |      658 |              |                  |
    +------------------+----------+--------------+------------------+
    #슬레이브서버에서 마스터 서버와 연동하기위해 먼저 슬레이브를 정지시킴
    stop slave;

    #슬레이브서버에서 마스터서버에 대한 정보 기입
    change master to 
    master_host='172.30.1.58',
    master_port=3306, 
    master_user='master', 
    master_password='master',
    master_log_file='mysql-bin.000002', 
    master_log_pos=658;

    #정보가 들어갔으면 슬레이브를 다시 작동시켜줌
    start slave;

    #슬레이브가 마스터서버와 제대로 연동이 되었는지 확인
    show slave status;
    MariaDB [(none)]> show slave status \G;
    *************************** 1. row ***************************
    Slave_IO_State : Waiting for master to send event
    Master_Host : 172.30.1.58
    Master_User : replication
    Master_Port : 3306
    Connect_Retry : 60
    Master_Log_File : mysql-bin.000002
    Read_Master_Log_Pos : 658
    Relay_Log_File : mysql-relay-bin.000002
    Relay_Log_Pos : 871
    Relay_Master_Log_File : mysql-bin.000002
    Slave_IO_Running : Yes 
    Slave_SQL_Running : Yes --Slave_IO_Running, Slave_SQL_Running 부분이 YES이면 정상적으로 작동


    #위 코드를 전부 실행 하였을 시 master서버에서 생성된 데이터가 slave에 나타나는지 확인


    #마스터서버와 슬레이브서버가 연동 된 것을 확인하고나면, 외부에서의 원격접속을 위한 작업을 진행



    #원격접속할 서버에서 공유기 설정으로 들어가 공인IP주소 확인(네이버에서도 확인가능)



    #공유기의 포트포워딩 설정에 들어가 마스터 서버의 접속 포트와 ip를 추가
    #추가적으로 슬레이브 서버도 접속할 수 있게 설정을 추가해준다.


    #마스터와 슬레이브가 같은 포트번호로 포트포워딩이 되어있을경우 선택하여 접속을 할 수 없기 때문에 슬레이브의 포트는 3307로 하여 3306으로 접속하면 master의 ip로
    3307로 접속하면 slave의 ip로 접속 할 수 있게 해줌
    #*외부에서 공인IP주소로 접속할때 포트에 연결된 내부 IP로 연결을 해줌

    #해당 설정이 끝나면 외부 네트워크에서 공인ip를 이용해 서버에 접속이 가능해진다
    

   
</details>

-----------------------------
# 5. 테스트 진행
<details> 
  <summary>테스트 진행 영상 첨부</summary>
   <li> 회원가입
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/54c707aa-d780-47ac-8ed1-5f0884b5e148

   <li> 로그인
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/81a66551-73c3-46ae-b3d2-ea696421eca4

   <li> 마이페이지 탈퇴
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/9eb80734-2b24-496e-90e5-e59f82e41b5d

   <li> 마이페이지 회원정보수정
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/cb62ebe4-0f8d-41be-872c-e94cc090815a
   
   <li> 마이페이지 작성게시물, 작성댓글 조회
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/18032300-bad7-4630-93db-b8b51d87ea86

   <li> 자유게시판 게시물 게시, 수정, 삭제
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/5655c7a8-fd93-4920-8f66-5f721f15570e

   <li> 자유게시판 게시물 추천(동일 게시물 추천X)
   <li> 자유게시판 게시물 검색
   <li> 추천 게시물추천
   <li> 추천 리뷰추천 (중복추천 불가)
   <li> 소개게시판 소개글 내림차순 정렬
   <li> 리뷰게시글 추천수 정렬
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/12ec7876-7412-438e-84bb-b6338519111c

   <li> 관리자페이지 신고게시물 처리
   <li> 관리자페이지 블랙라스트 처리
   <li> 관리자페이지 (등급)자동등업
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/3236a82d-6bcd-49cc-ab41-9b89a8c1a8b9

</details> 
  
<details>
  <summary>테스트케이스 정의서</summary>
  <img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/45d1389e-baf9-48e6-b68d-937f8bc52a6b" alt="테스트케이스 이미지" width="900" height="400"/>
</details> 

----------------------------
# 6. 시스템 아키텍처
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/4ee64be1-d5ec-49eb-859d-25d7b4ed988f" alt="시스템 아키텍처" width="900" height="600"/>

---------------------------
# 7. WBS  
<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/f30549aa-b5cb-4875-8106-a3c999af8f50" alt="WBS" width="900" height="600"/>

---------------------------
# 8. 회의록 및 개인 회고
## 주제선정 및 필요한 테이블 의견 모으기(23/12/29)

<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/d7a13d5e-f167-4ac3-a67e-67e8634e6efd" alt="회의사진" width="300" height="300"/>

> <li> 회의 내용: 단위 프로젝트 주제구상 및 관련 테이블 정보를 모으고 회의를 통해 의견을 나누어봄
> <li> 오늘 해낸것: 주제 선정, ERDcloud 논리모델 구상하기(PK,FK 생각하면서 연결)
> <li> 이슈: 회의를 통해 각자 생각했던 주제에 대해 의견을 나누고 그 중에서 가장 사회적으로 이슈가 되고 있는반려동물을 위한 커뮤니티로 주제를 선정하였음.

## 개념•논리모델 테이블 수정 및 추가(24/01/02)

<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/c1befe5a-d4d5-4d12-8d9c-5e57c15dd55e" alt="회의 사진" width="300" height="400"/>

> <li> 회의 내용: 개념 논리 모델을 수정하고 추가할 테이블이나 컬럼에 대해 의견을 나누며 수정작업 진행함.
> <li> 오늘 해낸것: ERDcloud 수정 및 삭제, 업무흐름도
> <li> 이슈:  금일 각 팀이 준비한 ERD로 개념 및 물리모델 발표가 있어 우리조의 모델의 피드백을 받을 수 있었고 다른팀의 피드백과 아이디어를 통해 ERD를 좀 더 구체화하여 수정할 수 있었음.

## 바커표기법으로 변경 및 문서화작업(24/01/03)

> <li> 회의 내용: ERDcluod에서 모델링한 것을 기반으로 DA#을 사용하여 바커표기법으로 변경하고 프로젝트 기획서(업무흐름도) 및 요구사항 명세서&정의서 작성을 진행했음.
> <li> 오늘 해낸것: 바커 표기법으로 논리모델링 수정, 프로젝트 기획서 작성, 업무흐름도
> <li> 이슈: 바커 표기법으로 진행하면서 테이블 연결의 문제점을 발견할 수 있었고 이를 수정하는 과정에서 테이블 수정 및 추가가 진행되었고 문서화 작업를 통해 프로젝트의 흐름과 진행과정을 정리할 수 있었음.

## 물리모델, 데이터 insert 및 테스트케이스 진행 및 문서화 작업(24/01/05)
> <li> 회의 내용: 3 정규화를 통해 물리모델로 수정하고 테스트케이스를 정하고, 마무리 하지 못한 문서화 작업을 이어서 진행함.
> <li> 오늘 해낸것: 물리모델, 데이터베이스쌓기, 테스트케이스 나누기
> <li> 이슈: 물리모델을 하면서 수정사항이 생겨나면서 한 테이블씩 확인하며 NOTNULL&NULL값을 정확하게 넣고 insert절을 사용해 데이터를 쌓았음. 또 강사님의 피드백을 통해 블랙리스트 처리를 신고마다 관리자가 확인하는 처리결과에수 5번 신고를 받으면 관리자가 확인 후 처리하는 결과로 나올 수 있게 수정함.

## 프로젝트관련 문서 수정 및 프로젝트 산출물 확인(24/01/08)
> <li> 회의 내용: 프로젝트 관련하여 필수 산출물을 문서화하여 github ReadMe에 업로드하며 정리함. 각자 맡은 테스트 케이스 영상으로 만들어 구현한 ReadMe 기능관련해 업로드.
> <li> 오늘 해낸것: DB모델링 마무리, 필수 산출물들 내용 정리하고 GITHUB README에 업로드
> <li> 이슈: 트리거, 인덱스 관련 쿼리문 작동될 수 있도록 수정함.

## 단위 프로젝트 마무리 개인 회고
<li> 회고록

    - 김재현:그냥 주먹구구식으로 하던 대학 프로젝트와는 다르게 , 현업에서는 어떤식으로 진행하는지, 어떤 과정이 왜 필요한지 배우고 프로젝트를 진행하다보니
            더 체계적으로 진행할 수 있었습니다.
            특히 저 혼자서는 절대 해결 못했거나 시간이 엄청 오래걸릴 만한 일도 팀원과 머리를 합치면
            금방 해결할 수 있다는 사실도 알게된 아주 뜻깊은 경험이였습니다!!
    - 백동현: 이곳에와서 처음하는 프로젝트이기도 하고, 만난지 얼마안된 팀원들과 하는거라서 초기에는 방향도 못잡고 어려움이 조금 있었던 것 같았습니다. 하지만 회의를 계속해서 하고 머리를 맞댈수록 방향이 잡혀갔고, 점점 프로젝트가 완성이 되어가는게 너무 신기했습니다.
            제가 좀 막혔을 때, 옆에서 다른 팀원들이 아이디어 내주기도 하고 서로 응원도 해주면서 진행했기 때문에 이 프로젝트가 완성될 수 있었다고 생각합니다. 혼자가 아닌 팀의 중요성을 깨달을 수 있었고, 배웠던 개념들을 직접 프로젝트에 적용하니 더 완벽히 제것으로
            받아들일 수 있었습니다. 너무 좋은 경험이었습니다! 
    - 서승엽:  처음 이 캠프에 들어와서 참여한 프로젝트였는데, 프로젝트 진행과정에서  
             처음으로 리눅스 서버를 구축하고 학교에선 일부밖에 못 해봤던 데이터베이스를 모델링 하고 다루는 과정을 진행하다보니 
             강의시간에 배울때 몰랐던 부분을 배울 수 있었고 다른 팀원분들께서 같이 열심히 참여를 해주셔서 
             별다른 어려움 없이 이 프로젝트를 마칠 수 있었던 것 같습니다. 
    - 이드보라:
    - 윤재은:
    - 조수빈: 처음 배우는 리눅스와 데이터베이스 모델링 및 관리를 배우고,
              팀프로젝트를 통해 부족한 부분을 서로 가르쳐주기도 하며 이론 뿐만 아니라 다양한 실습을 해볼 수 있었던 프로젝트였습니다. 
              혼자 진행했다면 생각해내지 못했을 해결방법들과 아이디어들을 공유하며
              팀프로젝트의 중요성과 장점을 잘 느낄 수 있었던 좋은 기회였습니다.


    


    

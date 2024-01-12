# [ be04-1st-IamDeveloper-WLOP ]
## 👀 Team I am 개발자에5
## 🫂 Team Members [김재현](https://github.com/jaehyeon-SMU), [백동현](https://github.com/dongh810), [서승엽](https://github.com/axe_hand), 이드보라, [윤재은](https://github.com/yunjaeeun), [조수빈](https://github.com/chosoobin37)

![WLOP LOGO](https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/3d064349-0410-4504-b1cc-0c0855986f81)

# 1. 프로젝트 기획서

<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/1b14eb7e-4587-4c7d-a44d-259119c3bb79" alt="시장조사"  width="600" height="400"/>

## 💫프로젝트 개요

    - 한국인 4명 가운데 1명이 반려동물을 키우는 반려인구 1500만 시대가 열렸다고 한다. 이에따라 반려동물
    시장도 성장하고 있는데, 한국농촌경제연구원에 따르면, 2015년 1조9천억원 규모였던 국내 반려동물 시장이
    올해는 23년에는 4조5786억원에 이르고, 2027년에는 6조원 규모까지 성장할것으로 보고있다.
    - 주변에 반려동물과 함께 갈수있는 식당이나, 숙박업소 그리고 반려동물들을 위한 병원까지 하나씩 지도에서 
    찾기에는 너무 귀찮고 어려울 수 있겠다는 생각에 반려동물과 함께 할수있는 장소들에 대한 정보를 제공하고,
    게시판을 통해 반려동물들을 자랑하고, 정보를 공유하는등의 활동을 할 수 있는 커뮤니티 서비스를 제공한다.

## 🐶프로젝트 소개

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
  ## 📍 사용자 요구사항 분석
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

  
  ## 📍 요구사항 명세서
  <img src="https://github.com/dongh810/Beyond_SW_Camp_Study/assets/105986200/1da4106f-bd5e-4c63-a4d2-1849846c5678" alt="요구사항 명세서 이미지" width="900" height="400"/>
  
---------------------------
# 4. 프로젝트 모델링

  ## 📍 프로젝트 설계 내역
<details>
  <summary>개념모델</summary>
<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/0e31542f-3873-4f6e-a929-3e30d67228b8" alt="" width="900" height="400"/>
</details>

<details>
  <summary>논리모델</summary>
<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/85e8a703-27c3-42c6-8710-2b3397b3ff7e"  alt="논리모델" width="900" height="400"/>
</details>

<details>
  <summary>물리모델</summary>
<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/bf2edae6-1030-4060-9349-f15ef80ce9c3" alt="물리모델" width="900" height="400"/>
</details>


--------------------------------------------------
# 5. DDL 구문 & 서버 구축(시스템 아키텍처)
<details>
  <summary>DDL 구문</summary>

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
   `black_candidate`   varchar(255)   NULL
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
  <summary>DML 구문</summary>

```java
INSERT
	 INTO AnimalCategory
  VALUES
(
 1
,'강아지'
);

INSERT
	 INTO AnimalCategory
  VALUES
(
 2
,'고양이'
);

INSERT
	 INTO AnimalCategory
  VALUES
(
 3
,'기타'
);

INSERT
  INTO  MemberGrade
VALUES
  (1, '브론즈')
, (2, '골드')
, (3, '다이아')
, (4, '마스터');

INSERT
  INTO WLOP_Type
VALUES
(1, '식당'),
(2, '카페'),
(3, '숙박'),
(4, '병원'),
(5, '기타');

-- 회원 상태
INSERT INTO WLOP_Status VALUES
(1, '사용'),
(2, '휴면'),
(3, '탈퇴'),
(4, '제재');


INSERT
	 INTO Administer
  VALUES
(
 'chosubin'
,'chocho'
, 'muckbab'
);

INSERT
	 INTO Administer
  VALUES
(
 'kimjaehyeon'
,'kimkim'
, 'cookieholic'
);


INSERT INTO Report_Status VALUES (1, '접수'), (2, '진행중'), (3, '완료');

INSERT INTO Report_Type VALUES (1, '도배'), (2, '욕설'), (3, '허위사실'), (4, '기타');

INSERT INTO Goods VALUES (1, '의류'), (2, '사료/간식/영양제'), (3, '장난감/훈련용품'), (4, '위생/배변/미용/목용용품'), (5, '하우스/이동장/울타리');
-- --------------------------------
INSERT
  INTO WLOP_Member
VALUES 
  ('parkjungman','1234', '박정만', '광주광역시 서구 쌍촌동',
   '010-4482-2349', 'park123@naver.com', '츄르도둑', '2021.01.01', 1, 1 , 0)
, ('yunjaeeun', 'yun123', '윤재은', '서울특별시 관악구 신림동',
   '010-2442-5020', 'yun123@naver.com', '마제소바남', '2023.12.18',1, 4, 0)
, ('leedeubora', 'lee123', '이드보라', '4 Yawkey Way, Boston, MA 02215-3409',
   '010-3096-6369','lee123@gmail.com', '마틸다', '2024.01.04',2, 4, 0)
, ('baekdonghyeon', 'baek123', '백동현','경기도 남양주시 무슨동',
   '010-4234-6905', 'baek123@yahoo.com', '운동갈꺼야', '2023.11.11', 3, 3, 0)
, ('chosubbin', 'cho1234', '조수빈', '서울특별시 서대문구 신촌동', 
   '010-0995-6989','cho123@daum.net', '쥬라기월드', '2023.01.01', 4, 2, 0)
, ('kimjaehyeon', 'kim123', '김재현', '경기도 의정부시 도봉구',
   '010-2340-5309','kim123@kakao.com', '닥쳐말포이', '2022.07.04', 5, 1, 0 )
, ('seoseungyeop', 'seo123', '서승엽', '서울특별시 관악구 신림동',
   '010-2309-3838','seo@naver.com', '게임조아', '2023.07.04', 5, 3, 0)
, ('gwakyungyeong','32sX@NLd!', '곽윤경', '광주광역시 서구 동천동',
   '010-6509-9038', 'v1hdfn@naver.com', '하태서리', '2021.07.03', 3, 1, 0)
, ('kimgyurin', 'dH7bLvumz', '김규린', '서울특별시 관악구 신림동',
   '010-6037-8692', 'i8drit@naver.com', '정다랑어', '2023.12.28',2, 3, 0)
, ('parkgyeongdeok', 'ksFRLpRZm', '박경덕', '서울특별시 종로구',
   '010-7421-0104','lmjava@gmail.com', '물복숭아', '2024.01.04',6, 4, 0)
, ('parkgoeunn', 'bflaCVcJs', '박고은','경기도 양주시 덕계동',
   '010-1590-5234', 'fdxrt2@yahoo.com', '지하천척', '2023.1.11', 2, 3, 0)
, ('baeseongmin', 'zY6kFKHbX', '배성민', '서울특별시 서대문구', 
   '010-1822-7931','mfk5gd@daum.net', '리카솔리', '2023.05.01', 0, 2, 0)
, ('souju','JEjKL60P1', '소우주', '부산 해운대구 해운대해변로 264',
   '010-8983-2100', 'helloItsUnivers@naver.com', 'littleUnivers', '2021.09.03', 4, 1, 0)
, ('sonselim', 'TewJnHAa', '손세림', '서울 용산구 남산공원길 105',
   '010-4231-7311', 'buy1005@naver.com', 'handselim', '2023.1.28',2, 1, 0)
, ('songdongjun', 'VV2se44b', '송동준', '서울 종로구 사직로 161',
   '010-9022-5692','djunsg@gmail.com', '준동송', '2024.11.04',6, 4, 0)
, ('shindaeyoung', 'l5klbbjA', '신대영','서울 종로구 세종대로 172',
   '010-4195-1293', 'Din1@yahoo.com', 'god대영', '2023.1.11', 1, 2, 0)
, ('shindongho', 'ZrzL7SwA', '신동호', '경북 경주시 석굴암로 816', 
   '010-0242-1193','al8@daum.net', '신동ho', '2023.09.01', 0, 2, 0)
, ('leegiyeon', 'MreapV1p', '이기연', '전남 여수시 여서동 산 33-1',
   '010-6560-4859', 'leieion@naver.com', '바늘사초', '2023.09.10',2, 2, 0)
, ('leeyeone', 'qdGtnZ57', '이예원', '대구 북구 구암로 85',
   '010-3653-7100','beoele@gmail.com', '보우타리', '2023.12.06',1, 4, 0)
, ('leejaeone', 'b95ZsXck', '이재원','인천 중구 차이나타운로 47',
   '010-8268-1086', 'je58392@yahoo.com', '벤조카인', '2023.08.02', 1, 3, 0)
, ('leejunhyong', 'mVpqCGcM', '이준형', '강원 강릉시 경포로 365', 
   '010-8849-3460','829hhge@daum.net', '어파인군', '2023.07.12', 4, 2, 0)
, ('limonjae', 'thrT2cDu', '임원재', '충남 보령시 미란다로 298',
   '010-2865-4614', 'oiomnnt8@naver.com', '다분안부', '2023.12.28',4, 1, 0)
, ('jangminseok', 'wA1Z9bX8', '장민석', '서울 송파구 올림픽로 240',
   '010-5207-2296','1m0s11@gmail.com', '파라도스', '2024.03.03',3, 2, 0)
, ('jeongwojin', 'IbF3UIkh', '정우진','강원 속초시 먹거리길 10',
   '010-3190-6588', 'krwink@yahoo.com', '파크스법', NOW(), 6, 2, 0)
, ('jeongtaeone', 'GLA1Yd5a', '정태원', '대전 유성구 대덕대로 708', 
   '010-2857-6945','te6394@daum.net', '마이카나이트', NOW(), 4, 1, 0)
, ('jihyeongeun', 'dH7bLvumz', '지현근', '전북 전주시 완산구 한옥마을길 16-5',
   '010-6363-9509', 'rj83n9n@naver.com','마른새우볶음', '2023.12.28',3, 1, 0)
, ('choijongchan', 'g3pCGWQ8', '최종찬', '경기 남양주시 와부읍 자작나무로 142',
   '010-5238-6061','ciqfnl348@gmail.com', '메소포타미아', '2024.01.04',9, 2, 0)
, ('hansohye', 'Kkz0V0pi', '한소혜','인천 연수구 아트센터대로 165',
   '010-5550-5912', 'f414mce3@yahoo.com', '가문비하늘소', NOW(), 8, 1, 0)
, ('kimyoungseung', 'N2VU8eaT', '김용승', '전남 완도군 화조로 119', 
   '010-7434-8452','yun2489b@daum.net', 'DragonVicroty', '2023.12.18', 0, 1, 0)
, ('choyelin', 'gno423189!', '조예린', '서울 중구 을지로 311',
   '010-8673-1418', 'coein231@gmail.com', '키러소루두', '2021.11.19', 1, 2, 0)
, ('leehyeonwo', '@!nameo2!', '이현우', '서울 동작구 신대방동',
   '010-3491-3904', 'lehyw@nate.com', 'rpwkr', NOW(), 0, 3, 0);

INSERT INTO QNA VALUES(NULL,'이 페이지에 오류가 있는 것 같습니다.',NOW(),NULL,'baekdonghyeon'),
(NULL, '이 페이지는 누가만들었나요??' ,NOW(), '안녕하세요! 이 페이지는 제가 만들었답니다!', 'yunjaeeun');

INSERT
  INTO Information 
VALUES
  (NULL, '츄르맛집', '서울특별시 동작구 신대방동', '010-2341-1551', NOW(), 1, 'seoseungyeop','Y')
, (NULL, '개껌제빵소', '광주광역시 동구 서석동', '062-432-1555', NOW(), 2, 'yunjaeeun','Y')
, (NULL, '캣타워 호텔', '부산광역시 수영구 광안2동', '051-622-4251', NOW(), 3, 'seoseungyeop','Y')
, (NULL, '랩터 전문 병원', '서울특별시 관악구 신림동', '02-595-5891', NOW(), 4, 'yunjaeeun','Y')
, (NULL, '강형욱 유치원', '경상북도 울릉군 울릉읍 저동리', '054-791-0701', NOW(), 5, 'seoseungyeop','Y')
, (NULL, '마라 칼국수', '서울특별시 도봉구 쌍문동', '02-648-9694', NOW(), 1, 'kimjaehyeon','Y')
, (NULL, '기가 커피', '서울특별시 동작구 신대방동', '02-124-8583', '2021.01.01', 2, 'kimyoungseung','Y')
, (NULL, '카멜레온 한의원', '충청남도 논산시', '041-583-4593', '20WLOP23.12.31', 4, 'leehyeonwo','Y')
, (NULL, '잠만보 게스트 하우스', '서울특별시 도봉구 쌍문동', '02-585-3804', '1945.08.15', 3, 'kimjaehyeon','Y');

INSERT INTO Review VALUES
(1, 3, '사장님이 친절해요', 1, '2023_12_30', 1, 'seoseungyeop','Y'),
(2, 5, '장소 깨끗해요', 1, '2024_01_02', 4, 'yunjaeeun','Y'),
(3, 4, '강아지가 좋아해요', NULL, '2024_01_07', 2, 'kimjaehyeon','Y'),
(4, 5, '장소 협소', 1, '2024_01_08', 3, 'kimjaehyeon','Y');

INSERT INTO WLOP_Profile VALUES
('baekdonghyeon','운동갈꺼야'),
('baeseongmin','리카솔리'),
('choijongchan', '메소포타미아'),
('chosubbin','쥬라기월드');

 INSERT INTO Pet VALUES
 (1,'baekdonghyeon','스피츠','별','01.15','암컷'),
 (2,'baekdonghyeon','풍산개','용맹','01.14','수컷'),
 (3,'baekdonghyeon','믹스','앵두','02.15','암컷');

INSERT INTO Notification VALUES
(1,'공지 1번','chosubin'),
(2,'공지 2번', 'kimjaehyeon'),
(3,'공지 3번','kimjaehyeon'),
(4,'공지 4번','chosubin');


INSERT
  INTO Billboard 
VALUES

(1,' 제가 키우고 있는 불법 나무늘보 자랑합니다~','2024-1-3'
,20,2
,'yunjaeeun','Y')
,
(2,' 옆집에서 훔쳐온 강철돼지  자랑합니다~!!','2024-1-4'
,17,3
,'chosubbin','Y')
,
(3,' 보스턴에서 밀수입한 개미핥기 자랑합니다~~','2024-1-4'
,17,3
,'leedeubora','Y')
,
(4,' 저희 원숭이 벤치프레스 할 줄 알아요!!','2024-1-4'
,17,3
,'baekdonghyeon','Y')
,
(5,' 저희 원숭이 벤치프레스 할 줄 알아요!!','2024-1-4'
,17,3
,'baekdonghyeon','Y')
,
(6,' 다시 쥐로 돌아온 스캐버스 자랑합니다! 새끼손가락이 없네요~','2024-1-4'
,17,3
,'kimjaehyeon','Y')
,
(7,' 우리집 고양이가 소주를 마시고 있네요?!','2024-1-4'
,17,3
,'souju','Y')
;

INSERT
  INTO MemberAdmin
VALUES
  ('leehyeonwo','Y', 'N', 1, '2024.01.04', 'chosubin')
, ('choyelin', 'Y', 'N', 2, '2023.07.04', 'chosubin')
, ('kimyoungseung', 'Y', 'N', 3, '2022.01.01', 'chosubin')
, ('hansohye', 'N', 'N', 1, '2022.01.01', 'chosubin');


INSERT INTO Blacklist VALUES
('kimjaehyeon', '허위사실 유포 및 욕설', 'Y');

INSERT INTO GoodsShare VALUES
(1, '키라키라 카샤카샤', '울 집 고양이가 넘 번쩍거리는 걸 싫어해서 안 쓰네용 ㅜㅜ 무나 받으실 분은 연락주세용 !!'
, NOW(), 'baekdonghyeon', 3,'Y');

INSERT INTO WLOP_Comment VALUES
(1, '우리집 판다 정말 데리고 가고 싶네요~', 'baekdonghyeon', 2, NULL, NULL,'Y')
, (2, '와우 유용한 리뷰예요~','baekdonghyeon', 1, NULL, NULL,'Y');

INSERT INTO Report VALUES 
   (NULL, '욕설이 너무심합니다', NOW(), 2,1,'yunjaeeun','baekdonghyeon',1,NULL,NULL,NULL)
,   (NULL, '도배가 너무 심합니다.', NOW(), 1,1,'baekdonghyeon','kimjaehyeon',6,NULL,NULL,NULL)
,   (NULL, '이거 진짜 허위사실이에요!!', NOW(), 3,1,'kimjaehyeon','baekdonghyeon',NULL,NULL,NULL,2);

INSERT INTO Photo VALUES
(1,'사진1','/home/usr/documents/photo','photo1',NULL,NULL,NULL,1,NULL,NULL,NULL,NULL),
(2,'사진2','/home/usr/documents/photo','photo2',NULL,NULL,NULL,2,NULL,NULL,NULL,NULL),
(3,'사진3','/home/usr/documents/photo','photo3',NULL,NULL,NULL,3,NULL,NULL,NULL,NULL),
(4,'사진4','/home/usr/documents/photo','photo4',NULL,1,NULL,NULL,NULL,NULL,NULL,NULL);


```
    
</details>  


<details>
  <summary>시스템 아키텍처</summary>
<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/4ee64be1-d5ec-49eb-859d-25d7b4ed988f" alt="시스템 아키텍처" width="900" height="600"/>
    
</details>   


<details>
  <summary>리눅스 데이터베이스 생성 및 연동 확인</summary>
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


    #마스터와 슬레이브가 같은 포트번호로 포트포워딩이 되어있을경우 선택하여 접속을 할 수 없기 때문에
    슬레이브의 포트는 3307로 하여 3306으로 접속하면 master의 ip로
    3307로 접속하면 slave의 ip로 접속 할 수 있게 해줌
    #*외부에서 공인IP주소로 접속할때 포트에 연결된 내부 IP로 연결을 해줌

    #해당 설정이 끝나면 외부 네트워크에서 공인ip를 이용해 서버에 접속이 가능해진다
    

   
</details>

-----------------------------
# 6. 테스트 진행
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

   <li> 자유게시판 검색 (INDEX 활용)

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/5bc201a6-70e5-4f12-b529-d7f9403bff22

   <li> 자유게시판 타인 게시물 조회 (VIEW 활용)

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/6b7f654f-2b0a-454e-920e-5bb289918c8e

   <li> 추천 누적 및 중복추천 불가 (게시판, 리뷰/ TRIGGER 활용)
	   
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/fec39911-23d5-4dc6-8206-a176dbea58f8
    
   <li> 소개게시판 소개글 내림차순 정렬

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/12ec7876-7412-438e-84bb-b6338519111c

   <li> 소개게시판 게시물 검색

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/3cedc400-9839-4e40-b74f-f9455d70f9d2

   <li> 관리자페이지 신고게시물 처리

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/37f2226f-9404-4c1a-9160-28cc8e89f1b8

   <li> 관리자페이지 블랙리스트 처리(신고 5회 누적시, TRIGGER 활용)

https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/0b996f6a-a077-42cf-8e3b-6a8f4a4bac9b
    
   <li> 관리자페이지 (등급)자동등업 (TRIGGER 활용)
       
https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/149561287/3236a82d-6bcd-49cc-ab41-9b89a8c1a8b9

</details> 
  
<details>
  <summary>테스트케이스 정의서</summary>
  <img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/45d1389e-baf9-48e6-b68d-937f8bc52a6b" alt="테스트케이스 이미지" width="900" height="400"/>
</details>

---------------------------
# 7. WBS  
<img src="https://github.com/beyond-sw-camp/be04-1st-IamDeveloper-WLOP/assets/71023617/f30549aa-b5cb-4875-8106-a3c999af8f50" alt="WBS" width="900" height="600"/>

---------------------------
# 8. 회의록 및 개인 회고
## 💡 주제선정 및 필요한 테이블 의견 모으기(23/12/29)

<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/d7a13d5e-f167-4ac3-a67e-67e8634e6efd" alt="회의사진" width="300" height="300"/>

> <li> 회의 내용: 단위 프로젝트 주제구상 및 관련 테이블 정보를 모으고 회의를 통해 의견을 나누어봄
> <li> 오늘 해낸것: 주제 선정, ERDcloud 논리모델 구상하기(PK,FK 생각하면서 연결)
> <li> 이슈: 회의를 통해 각자 생각했던 주제에 대해 의견을 나누고 그 중에서 가장 사회적으로 이슈가 되고 있는반려동물을 위한 커뮤니티로 주제를 선정하였음.

## 💡 개념•논리모델 테이블 수정 및 추가(24/01/02)

<img src="https://github.com/Bodrami/SWcamp_BORA/assets/149561287/c1befe5a-d4d5-4d12-8d9c-5e57c15dd55e" alt="회의 사진" width="300" height="400"/>

> <li> 회의 내용: 개념 논리 모델을 수정하고 추가할 테이블이나 컬럼에 대해 의견을 나누며 수정작업 진행함.
> <li> 오늘 해낸것: ERDcloud 수정 및 삭제, 업무흐름도
> <li> 이슈:  금일 각 팀이 준비한 ERD로 개념 및 물리모델 발표가 있어 우리조의 모델의 피드백을 받을 수 있었고 다른팀의 피드백과 아이디어를 통해 ERD를 좀 더 구체화하여 수정할 수 있었음.

## 💡 바커표기법으로 변경 및 문서화작업(24/01/03)

> <li> 회의 내용: ERDcluod에서 모델링한 것을 기반으로 DA#을 사용하여 바커표기법으로 변경하고 프로젝트 기획서(업무흐름도) 및 요구사항 명세서&정의서 작성을 진행했음.
> <li> 오늘 해낸것: 바커 표기법으로 논리모델링 수정, 프로젝트 기획서 작성, 업무흐름도
> <li> 이슈: 바커 표기법으로 진행하면서 테이블 연결의 문제점을 발견할 수 있었고 이를 수정하는 과정에서 테이블 수정 및 추가가 진행되었고 문서화 작업를 통해 프로젝트의 흐름과 진행과정을 정리할 수 있었음.

## 💡 물리모델, 데이터 insert 및 테스트케이스 진행 및 문서화 작업(24/01/05)
> <li> 회의 내용: 3 정규화를 통해 물리모델로 수정하고 테스트케이스를 정하고, 마무리 하지 못한 문서화 작업을 이어서 진행함.
> <li> 오늘 해낸것: 물리모델, 데이터베이스쌓기, 테스트케이스 나누기
> <li> 이슈: 물리모델을 하면서 수정사항이 생겨나면서 한 테이블씩 확인하며 NOTNULL&NULL값을 정확하게 넣고 insert절을 사용해 데이터를 쌓았음. 또 강사님의 피드백을 통해 블랙리스트 처리를 신고마다 관리자가 확인하는 처리결과에수 5번 신고를 받으면 관리자가 확인 후 처리하는 결과로 나올 수 있게 수정함.

## 💡 프로젝트관련 문서 수정 및 프로젝트 산출물 확인(24/01/08)
> <li> 회의 내용: 프로젝트 관련하여 필수 산출물을 문서화하여 github ReadMe에 업로드하며 정리함. 각자 맡은 테스트 케이스 영상으로 만들어 구현한 ReadMe 기능관련해 업로드.
> <li> 오늘 해낸것: DB모델링 마무리, 필수 산출물들 내용 정리하고 GITHUB README에 업로드
> <li> 이슈: 트리거, 인덱스 관련 쿼리문 작동될 수 있도록 수정함.

-------------------------------------

## 🌈 단위 프로젝트 마무리 개인 회고
<li> 회고록

    🐉 김재현
        그냥 주먹구구식으로 하던 대학 프로젝트와는 다르게 , 현업에서는 어떤식으로 진행하는지, 어떤 과정이 왜 필요한지 배우고
        프로젝트를 진행하다보니 더 체계적으로 진행할 수 있었습니다.
        특히 저 혼자서는 절대 해결 못했거나 시간이 엄청 오래걸릴 만한 일도 팀원과 머리를 합치면
        금방 해결할 수 있다는 사실도 알게된 아주 뜻깊은 경험이였습니다!!
	       
    🐉 백동현
        이곳에와서 처음하는 프로젝트이기도 하고, 만난지 얼마안된 팀원들과 하는거라서 초기에는 방향도 못잡고 어려움이 
        조금 있었던 것 같았습니다. 하지만 회의를 계속해서 하고 머리를 맞댈수록 방향이 잡혀갔고, 점점 프로젝트가 완성이 되어가는게
        너무 신기했습니다.
        제가 좀 막혔을 때, 옆에서 다른 팀원들이 아이디어 내주기도 하고 서로 응원도 해주면서 진행했기 때문에 이 프로젝트가 
        완성될 수 있었다고 생각합니다. 혼자가 아닌 팀의 중요성을 깨달을 수 있었고, 배웠던 개념들을 직접 프로젝트에 적용하니
	    더 완벽히 제것으로 받아들일 수 있었습니다. 너무 좋은 경험이었습니다!
	    
    🐉 서승엽
        처음 이 캠프에 들어와서 참여한 프로젝트였는데, 프로젝트 진행과정에서  
        처음으로 리눅스 서버를 구축하고 학교에선 일부밖에 못 해봤던 데이터베이스를 모델링 하고 다루는 과정을 진행하다보니 
        강의시간에 배울때 몰랐던 부분을 배울 수 있었고 다른 팀원분들께서 같이 열심히 참여를 해주셔서 
        별다른 어려움 없이 이 프로젝트를 마칠 수 있었던 것 같습니다.
	       
    🐉 이드보라
        프로그래밍을 통한 프로젝트와 모든 과정들과 배움들이 생소했기때문에 시작하기 전, 팀에 스스로 도움이 되지 못하는
        마음에 삐그덕 되었던 것 같아 힘든 점도 있었지만 팀이 정한 주제와 관련된 필요한 정보를 모으고, 의견을 나누면서
	    나름대로 할 수 있는 문서들을 찾아 만들며 자신감을 얻을 수 있었습니다. 그 과정을 통해 역할분담의 중요성을
        느꼈고 다음 프로젝트에서는 좀 더 지식배경을 쌓아 다른 산출물들도 도전해보고 싶다는 생각이 들었으며
	    프로젝트를 통해 우리가 사용하는 웹페이지 하나하나씩 많은 데이터와 기술적인 부분이 필요하고 그 관계들이 
        연결되어지면서 모델링이 완성되어지는 것이 신기하면서도 재미를 느꼈습니다. 프로젝트를 진행하면서 수업시간에
        배웠던 내용을 복습하는 기회도 얻을 수 있었고 더불어 막히는 부분에 있어서는 강사님께 도움을 요청해 그 문제를
        해결하고 그 문제를 회상하며 복습할 수 있는 기회가 되었던 것 같아 짧은 시간이었지만 뜻깊은 시간이었습니다.
   
    🐉 윤재은
        이러한 프로젝트 경험이 처음이다보니 민폐 끼치지 않고 잘할 수 있을지 걱정도 많이 했지만
	    팀원들과 회의를 통해 주제를 정하고 협업을 통하여 DB를 차근차근 구축해가는 경험이 새로웠습니다.
        협업 과정에서 실제로 모델링도 해보고 여러 테스트 케이스를 통해 다양한 문법을 사용해보며
	    제가 정확히 알고 있는 내용, 잘 알지 못하는 내용을 판단할 수 있는 경험이 되었고 
        이를 통해 trigger나 procedure 같은 여러 문법을 다시 공부하며 부족함을 채울 수 있는 계기가 되었다.
    
    🐉 조수빈
        처음으로 리눅스와 데이터베이스 모델링 및 관리를 배우고,
        팀프로젝트를 통해 부족한 부분을 서로 가르쳐주기도 하며 이론 뿐만 아니라 다양한 실습을 해볼 수 있었던 프로젝트였습니다. 
        혼자 진행했다면 생각해내지 못했을 해결방법들과 아이디어들을 공유하며 팀프로젝트의 중요성과 장점을 잘 느낄 수 있었던 좋은 기회였습니다.
 

    


    

# Trip Story

---

![트립스토리 표지.png](Trip%20Story%20f375450319f3442ba9082e6d4433222a/%25ED%258A%25B8%25EB%25A6%25BD%25EC%258A%25A4%25ED%2586%25A0%25EB%25A6%25AC_%25ED%2591%259C%25EC%25A7%2580.png)

여행을 떠나는 모든 사람들을 위한 `여행지 정보`, `여행지 리뷰`, `커뮤니티`를 한 번에 확인할 수 있는 서비스

# 웹사이트 주소

[https://ktripstory.herokuapp.com/](https://ktripstory.herokuapp.com/)

---

# 목차

1. **프로젝트 구성도**
2. **웹 서비스 소개**
3. **기술 스택**
4. **주요 기능**
5. **특이사항**
6. **개발 팀 소개**
7. **개발 기간 및 일정**
8. **프로젝트 후기**

---

# 1. 프로젝트 구성도

## **Figma**

![Group 23.png](Trip%20Story%20f375450319f3442ba9082e6d4433222a/Group_23.png)

## **ERD**

![trip (2).png](Trip%20Story%20f375450319f3442ba9082e6d4433222a/trip_(2).png)

# 2. 서비스 소개

![인덱스.PNG](Trip%20Story%20f375450319f3442ba9082e6d4433222a/%25EC%259D%25B8%25EB%258D%25B1%25EC%258A%25A4.png)

**트립 스토리(Trip Story)**는 국내로 여행을 떠나시는 분을 위해 지역별로 인기있는 여행지를 추천해주고, 여행 리뷰를 작성하여 공유할 수 있는 여행 전문 웹 서비스입니다.

---

![제목 없는 프레젠테이션 (1).png](Trip%20Story%20f375450319f3442ba9082e6d4433222a/%25EC%25A0%259C%25EB%25AA%25A9_%25EC%2597%2586%25EB%258A%2594_%25ED%2594%2584%25EB%25A0%2588%25EC%25A0%25A0%25ED%2585%258C%25EC%259D%25B4%25EC%2585%2598_(1).png)

![places_spot4.PNG](Trip%20Story%20f375450319f3442ba9082e6d4433222a/places_spot4.png)

**여행지 정보** 페이지를 통해 `국내 지역별` `인기 여행지`를 추천해주고 `세부 정보`를 확인할 수 있습니다.

도시는 조회수 순으로 TOP3를 추천해주며, 도시 페이지로 들어가면 해당 도시의 사진들과 날씨, 여러 관광지들을 확인 할 수 있습니다.

관광지는 `별점 순`, `댓글 개수 순` TOP3를  추천해줍니다. 마음에 드는 여행지 세부정보 아래에 댓글을 달아 공감을 할 수 있습니다. 댓글에는 별점 기능을 추가하여 해당 지역에 대한 `별점 리뷰`를 등록할 수 있습니다. 댓글의 프로필을 클릭해 `다른 유저의 프로필`을 확인 할 수 있습니다.

---

![제목 없는 프레젠테이션 (2).png](Trip%20Story%20f375450319f3442ba9082e6d4433222a/%25EC%25A0%259C%25EB%25AA%25A9_%25EC%2597%2586%25EB%258A%2594_%25ED%2594%2584%25EB%25A0%2588%25EC%25A0%25A0%25ED%2585%258C%25EC%259D%25B4%25EC%2585%2598_(2).png)

**여행지 리뷰** 페이지를 통해 다녀온 여행지에 대한 리뷰를 남길 수 있습니다.  여러 도시를 골라 리뷰 할 수 있으며, `도시별로 리뷰`를 볼 수도 있습니다. `좋아요 기능`을 통해 리뷰 작성 글에 공감할 수 있습니다. 

---

![제목 없는 프레젠테이션 (3).png](Trip%20Story%20f375450319f3442ba9082e6d4433222a/%25EC%25A0%259C%25EB%25AA%25A9_%25EC%2597%2586%25EB%258A%2594_%25ED%2594%2584%25EB%25A0%2588%25EC%25A0%25A0%25ED%2585%258C%25EC%259D%25B4%25EC%2585%2598_(3).png)

**커뮤니티** 페이지를 통해 질문, 정보 공유 등 서비스 이용자들이 서로 자유로운 소통을 할 수 있습니다.

![제목 없는 프레젠테이션 (4).png](Trip%20Story%20f375450319f3442ba9082e6d4433222a/%25EC%25A0%259C%25EB%25AA%25A9_%25EC%2597%2586%25EB%258A%2594_%25ED%2594%2584%25EB%25A0%2588%25EC%25A0%25A0%25ED%2585%258C%25EC%259D%25B4%25EC%2585%2598_(4).png)

**그 외에** 인덱스 페이지에서 검색창을 통해 관광지와 리뷰를 동시에 검색 가능합니다.

또한 다른 유저의 프로필에 들어가 팔로우를 하고 해당 유저가 쓴 리뷰를 볼 수 있습니다.

# 3. 기술 스택

| Frontend | Backend | Cooperation | Release |
| --- | --- | --- | --- |
| HTML5 | Python | Git | Heroku |
| CSS3 | Django | GitHub | AWS |
| Bootstrap | SQLite | Notion |  |
| JavaScript |  | Discord |  |

# 4. 주요 기능

- `회원 가입`
- `로그인`
- `CRUD` 가능한 커뮤니티 게보 리뷰 조회수 기능
- `여행 정보` 리뷰 `조회수` 기능
- 커뮤니티 게시글에 `댓글` 작성
- 여행지 정보 `검색`
- 회원끼리 `팔로잉`
- 여행 리뷰에 `좋아요` 기능

# 5. 팀원 및 참고 자료

![Untitled](Trip%20Story%20f375450319f3442ba9082e6d4433222a/Untitled.png)

**김광표 - 팀장**

[Pangpyo - Overview](https://github.com/Pangpyo)

**김준환 - 팀원,발표자**

[hvvany - Overview](https://github.com/hvvany)

**서민수 - 팀원**

[TocDX - Overview](https://github.com/TocDX)

**이동영 -팀원**

[kinzinzz - Overview](https://github.com/kinzinzz)

# 6. 특이사항

![Untitled](Trip%20Story%20f375450319f3442ba9082e6d4433222a/Untitled%201.png)

# 7. 개발 기간 및 일정

1. **개발 기간 : 10/31 ~ 11/07**
2. **개발 일정**
    - 10/31
        - 기능 별 앱 나누기
        - DB 모델 구상
        - 앱 단위로 역할 분담
        - figma를 이용해 templates 구상
        - base templates 및  navbar 작성
        - 버전 관리: GIT
    - 11/01
        - 앱 단위로 models 작성
        - 앱 단위로 templates 작성
        - 버전 관리:GIT
    - 11/02
        - accounts 앱 : 회원 가입 기능 구현
        - places 앱 : CRUD 기능 구현, 기본 db 등록
        - reviews 앱 : CRUD 기능 구현
        - Error 공유
        - 버전 관리:GIT
    - 11/03
        - 앱 단위로 templates 와 기능 테스트
        - Error 공유
        - 버전 관리:GIT
    - 11/04
        - 앱 별로 구체적인 templates 작성
        - 커뮤니티 게시판 CRUD 기능 작성
        - Error 공유
        - 버전 관리:GIT
    - 11/07
        - 기본 db 등록 및 최종 기능 테스트
        - 테스트 오류 수정
        - 배포
        - 버전 관리:GIT
        
         
        

# 8. 프로젝트 후기

## 김광표

- 많은 페이지를 기획하다 보니 혼자 모든 것을 하기는 불가능했다. 팀원들이 있기에 각각 역할 분담을 해가며 프로젝트를 완성 할 수 있었던 것 같다. 또한 일주일 동안 계속해서 깃허브로 협업을 하며 깃허브와 많이 친해질 수 있었고, 직접 배포까지 하니 그간 했던 어떤 프로젝트보다 더 뿌듯했다.
- 초기 기획을 잘 짜면 프로젝트 진행 속도가 더 빨라지고 중간에 막히는 일이 없다는 것 또한 깨달았다.

## 김준환

- 초기 기획부터 실제 배포 까지 해보면서 하나의 웹 페이지를 만들었다니 뿌듯하다. 팀원 모두가 각자 역할에 열심히 임해줘서 잘 마무리된 것 같다. 특히 협업을 하면서 깃과 깃허브에 충돌이 밥먹듯이 일어났는데 그 원인을 하나씩 알아갈 수 있어서 좋았습니다. 제가 부족한 부분도 다른 팀원들 덕에 잘 해결할 수 있었습니다.

## 서민수

- 혼자서 했다면 아마 완성하지 못했을 것이다 아직 실력이 부족하고 구현도 힘든게 많았는데
팀원들이 도와줘서 할 수 있었다.

## 이동영

- 혼자 할 때보다 더 많은 기능 구현을 할 수 있었다.
- 어려운 문제를 팀원이 같이 해결하면서 미처 몰랐던 부분을 배웠다.
- git 사용법이 익숙해졌다.
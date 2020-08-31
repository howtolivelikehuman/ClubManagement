# ClubManagement
University club management application for android

#### 1.Person 수정사항

1. 현재 목표

   ~~검색 기능 추가~~ 프로토타입 완료

   사진 저장시 비트맵 크기 줄이기 
   
   ~~이미 사진이 저장되어 있는 애한테 -> 사진이 없애기, 기본사진으로~~ 완료

   사람 추가할때 그룹 넣는 editText창만 넣어줘 (조회할때도 텍스트뷰로 확인만하게)

   

2. 미래 목표

   (인스타처럼 이름 김만치면 실시간으로 김%인애들들 쭉 뜨게 하고싶은데 어떻게 하는지 모르겠음)
   -> 추가 시에 이미 있는 그룹 or 사람이면 어떡할것인가. (근데 이름 오타시)

   사람일때 -> 그룹추가는 이미 있는 그룹만

   마찬가지로 인원 생성시에도 그룹 추가할때 이렇게 하고 싶음
   
   사진 추가할때 크롭해서 하게 (카카오톡 프로필처럼)

   사람 - 일정의 완벽한 연동

   사람 - 예산의 완벽한 연동



#### 2. 그룹

1. 현재 목표

   대충 그룹추가, 있는 그룹 확인하기 만들었으니

   이제 인원테이블 <-> 연결테이블 <-> 그룹테이블로 그룹이랑 인원 연결 해보겠음 (인원 조회 화면에 그룹도 뜨게 하기)

   조회시에 그룹에 저장되어있는 사람들도 뜨고, 사람 볼때는 얘가 속해있는 그룹도 뜨게.

   라디오버튼으로 있는 그룹 or 사람 다 때려박아서 선택할 수 있게.

   

2. 미래 목표

    (인스타처럼 이름 ㄱ만치면 실시간으로 ㄱ인애들 쭉 뜨게 하고싶은데 어떻게 하는지 모르겠음)

   -> 추가 시에 이미 있는 그룹 or 사람이면 어떡할것인가. (근데 이름 오타시)

   사람일때 -> 그룹추가는 이미 있는 그룹만

   마찬가지로 인원 생성시에도 그룹 추가할때 이렇게 하고 싶음




#### 3. 스케쥴

##### 필수) 달력 화면 (메인)에서 추가된 항목들 뜨게 (네이버 일정과 그냥 똑같이 만들어보리는게 best)

1. 현재 목표

   년 월 일 추가하는 데이트피커 만들기

   스케쥴 추가시 (schedule 객체에 맞게 추가해주기 -> db에 입력하기 편함)
   
   위치 선택시 지도에서 위치를 선택할 수 있게? (Google 맵이 켜지게 (검색도 되게))
   
2. 미래 목표

   인원을 추가시킬 수 있게, 예산 선정

   알림 정도?


#### 4. 예산
객체단위 입/출력
수입 / 지출 구분해서 추가하기
-> 추가해서 리사이클뷰로 띄워주기

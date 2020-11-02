# Classifier
### 실시간 영상처리 기반 상품 분류 시스템 (Product classification system based on real-time image processing)

<img src="/images/full.gif" width="80%">
공주대학교 상공회의소 연계작품 Classifier( 김장희 정재훈 김용주 김영무 박종하 )

### :large_orange_diamond: 작품선정 배경
----------------------------------------------------------

:point_right: 코로나로 인해 과도한 업무량으로 인한 노동자들의 과로사 증가

### :large_orange_diamond: 작품 목표
----------------------------------------------------------
:point_right: 수작업의 비효율성 감소

:point_right: 인건비의 지속적 증가

:point_right: 기계화를 통한 정확성 증가

:point_right: 관리 비용 절감

### :large_orange_diamond: 기능
----------------------------------------------------------
#### :heavy_check_mark: Raspberry Pi
&nbsp;&nbsp;&nbsp; 영상을 통한 상품 분류 및 모터 제어, GUI 및 Database 연동
#### :heavy_check_mark: camera v2
&nbsp;&nbsp;&nbsp; Raspberry Pi에 영상 전송, OpenCV 라이브러리 활용
#### :heavy_check_mark: 장애물 감지 센서
&nbsp;&nbsp;&nbsp; 물체 감지 및 모터 정지, 적외선 제어, TCP/IP 통신
#### :heavy_check_mark: 서보 모터
&nbsp;&nbsp;&nbsp; 불량품 분류, 회전각도 제어

### :large_orange_diamond: 하드웨어 모델구축
----------------------------------------------------------
#### :heavy_check_mark: 하드웨어 다이어그램

<img src="/images/Circuit diagram.png" width="78%">

### :large_orange_diamond: 개발환경 및 수행일정
----------------------------------------------------------
#### :heavy_check_mark: 개발환경

<img src="/images/개발환경.PNG" width="60%">

#### :heavy_check_mark: 수행일정

<img src="/images/수행일정.PNG" width="60%">

### :large_orange_diamond: 시행착오
----------------------------------------------------------
#### :heavy_check_mark: 시행착오 부분

<img src="/images/시행착오.PNG" width="60%">

#### :heavy_check_mark: 해결방안
----------------------------------------------------------
&nbsp;&nbsp;&nbsp; 표본부족으로 인한 과적합오류 --> (해결방안) --> 카테고리를 줄이며 카테고리마다의 표본 갯수 추가

&nbsp;&nbsp;&nbsp; 큰 해상도로 인한 동작시간증가 --> (해결방안) --> OpenCV를 통한 이미지처리


#### :heavy_check_mark: 시연영상
----------------------------------------------------------
<img src="/images/시연영상.gif" width="110%">


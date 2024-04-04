---
title: 2022년 1월 업데이트 히스토리
menuTitle: 2022년 1월
historyHome: 0
yearMonth: 2201
---

<pre>

<bold># 1/28 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 2월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 2월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 2월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 1/20 배포</bold>
=====================
<span class="box jemu">원무</span> - 병원정보 영문팩스번호 항목 추가  (기준정보.병원정보.영문정보 참조)
<span class="box jemu">원무</span> - 접수시간 업데이트룰 변경  (서버일자가 아닌경우 변경되지 않게)
<span class="box jemu">원무</span> - 좌우검사 검사결과 항목 Enter키 동작 변경  (우측 항목 연속 입력되게)
<span class="box jemu">원무</span> - 모바일접수 환자 진료대기목록 정렬 룰 변경  (미방문환자를 아래로 정렬)
<span class="box jemu">원무</span> - 똑닥 예약 기능 추가  (똑닥앱에서 미래일자 예약 가능)
<span class="box chart">진료</span> - 중복처방 메시지 이후 진행불가   bug  (사유코드 기재후 진행 가능)  
<span class="box chart">진료</span> - 컨버전 데이터의 추가수납 동작   bug  (컨버전건일때 추가수납 불가)
<span class="box chart">진료</span> - 진료의와 요양기관기호 불일치  bug  (보안코드 적용)
<span class="box chart">진료</span> - DUR 원내 투약내역 전송 설정 변경  ('일반환자/원내주사제/검사처치수술약제'를 점검대상에 포함되도록 옵션 변경, 1회만 동작)
<span class="box diag">진단서</span> - 영문코로나진단서 발행번호 출력시 잘림 bug  (진단서탭.영문코로나진단서 서식 참조)
<span class="box inspect">심사</span> - 데이터가져오기  OrderMedc 오류  bug  
<span class="box inspect">심사</span> - 수가정보.나이체중별탭  용법창 표시  bug  (SQL 용법옵션일때 동작 패치)
<span class="box inspect">심사</span> - 모음장  용법창 표시  bug  (SQL 용법옵션일때 동작 패치)
<span class="box inspect">심사</span> -  특정내역 MT043  추가 ('국가재난 의료비 지원대상 유형')
<span class="box inspect">심사</span> - 초음파 가산 산정 ('EB401B00' - 6세미만 초음파가산)
<span class="box lab">검안실</span> - 검안현황  날짜선택 버튼 기능 추가  (검안실.검안현황 버튼 참조)
<span class="box lab">검안실</span> - 대기목록 보기옵션 기능 추가  (대기목록.우클릭 대기목록보기옵션 메뉴 참조)
<span class="box other">[CaptureManager]</span> 카테고리 표시 기능 추가  (미니창에서 카테고리 표시 텍스트를 클릭)
<span class="box other">[CaptureManager]</span> LiveUpdate 기능 추가  
<span class="box other">[CaptureManager]</span> ChtNo Sync 기능 추가  (Setup 'Patient Sync' 메뉴 참조)
<span class="box other">[LabViewer]</span> 윈도우가 전체로 실행  bug  (시작바를 덮지 않도록) 
<span class="box other">[LabViewer]</span> 새로고침 버튼 기능 추가  (화면상단 새로고침 아이콘 참조)
<span class="box other">[LabViewer]</span> 화면구성 탭 구성 동작  bug  (EyeView탭 화면설정 메뉴 참조)
<span class="box other">[인터페이스]</span> CRM 연동 기능 변경 (환자정보 생성후 결과파일 CN_UPDATE_ChtNo.txt 생성)
<span class="box other">[디비툴]</span> 팍스로비드정 등록  (청구코드 '648903670')



<bold># 1/18 배포</bold>
=====================
<span class="box jemu">원무</span> - 수납대장에서 후불진료비 표시 bug

<bold># 1/13 배포</bold>
=====================
<span class="box jemu">원무</span> - 좌우검사 새로고침 버튼 너비 변경 (외래접수.좌우검사탭 참조)
<span class="box jemu">원무</span> - 좌우검사항목 설정 메뉴 추가 (외래접수.검사장비실행 버튼 메뉴 참조)
<span class="box jemu">원무</span> - 카드수납.접수메모 표시 동작 bug  (접수메모값 부재시 표시 제외)
<span class="box jemu">원무</span> - 입원정보 입원유형 변경 동작 변경 (입원유형 변경시 청구정보에 일괄 적용)
<span class="box jemu">원무</span> - 마감장 후불진료비 항목 추가
<span class="box jemu">원무</span> - [확인] 마감장 키오스크 0원수납건을 인원수에 포함
<span class="box jemu">원무</span> - 수납대장 진료형태 검색조건 추가
<span class="box jemu">원무</span> - 입원수납 추가수납 버튼 기능 추가
<span class="box jemu">원무</span> - 모바일접수탭 기준일자 검색조건 추가  (외래접수.모바일접수탭 참조)
<span class="box jemu">원무</span> - 수납대장 보험유형 의보100 항목값 추가  (수납대장.보험유형 항목 참조)
<span class="box jemu">원무</span> - 수납대장 클래식SQL 후불진료비 항목 추가 (진료비총액은 후불진료비 포함)
<span class="box chart">진료</span> - 처방창 단가 항목 표시 방법 변경  (진료일자 기준 표시) 
<span class="box chart">진료</span> - 비급여 수가 수량 소수점 불가 알림 옵션 기능 추가  (사용자설정.진료업무.차트저장전점검옵션 참조)
<span class="box chart">진료</span> - 좌우검사 컨텐츠 동작   bug (외래진료.화면디자인.좌우검사 컨텐츠 참조) 
<span class="box diag">진단서</span> - 영문코로나진단서 (진단서탭.영문코로나진단서 서식 참조)
<span class="box diag">진단서</span> - 채용신체검사서(일반) 날짜 픽업 동작  bug  (검사서식탭 참조)
<span class="box inspect">심사</span> - DRG 별도산정내역 표시 UI 변경 (청구서식092 적용)
<span class="box inspect">심사</span> - DRG 청구 조회조건 동작 변경 (환자 픽업 후 포커싱 변경)
<span class="box inspect">심사</span> - EdiView DRG 항목 추가 (청구서식092 적용)
<span class="box inspect">심사</span> - 원외처방 약제  특정내역 JT014 누락  bug  (JT014 - 향정신성 약물 장기처방(조제)사유)
<span class="box inspect">심사</span> - DRG 불러오기 프로그레스 기능 추가  (진행상태 표시되게)
<span class="box inspect">심사</span> - 청구제외 퇴장방지의약품 청구 수록 bug  (원처방이 청구제외인경우 청구 제외)
<span class="box inspect">심사</span> - 비급여 퇴장방지의약품 영수증 출력 bug  (비급여 항목에 수록되게)
<span class="box inspect">심사</span> - 수가정보 라이브러리 가져오기 동작변경  ('HI135' 를 MRI 항목으로 적용)
<span class="box inspect">심사</span> - HA424 금액 산정 오류  (수량 소수점 이하 세째자리에서 사사오입 후 금액 산정)
<span class="box lab">검사실</span> - 수탁검사 미전송내역 미표시 bug  (전송후 처방취소된 오더가 포함된경우 발생하는 증상 패치)
<span class="box lab">검안실</span> - 완료시 진료대기로 변경할 대상이 없습니다 메시지   bug  
<span class="box lab">검안실</span> - 검안오더 모두취소 기능 추가  (검안내역 우클릭 메뉴 참조)
<span class="box lab">검안실</span> - 대기목록 환자별 구분 기능 추가  (환자별 배경색을 구분하여 표시)
<span class="box other">통계</span> - 기간별처방통계 출력물에 검색조건 표시 기능 추가 (진료통계.기간별처방통계 참조)
<span class="box other">통계</span> - 진료과별 수입현황 진료형태 검색조건 추가 (전체/입원/외래 검색조건 추가)
<span class="box other">통계</span> - 키오스크 일자별사용현황 기능 추가 (통계.인원통계탭 참조)
<span class="box other">통계</span> - 키오스크 성별사용현황 기능 추가 (통계.인원통계탭 참조)
<span class="box other">통계</span> - 키오스크 연령별사용현황 기능 추가 (통계.인원통계탭 참조)
<span class="box other">통계</span> - 키오스크 시간별사용현황 기능 추가 (통계.인원통계탭 참조)
<span class="box other">통계</span> - 키오스크 요일별사용현황 기능 추가 (통계.인원통계탭 참조)
<span class="box other">통계</span> - 키오스크 오류발생현황 기능 추가 (통계.인원통계탭 참조)
<span class="box other">[Scan]</span> 별도실행파일 추가 (C:\NixHIS\tool\scan 폴더 참조)
<span class="box other">[Scan]</span> 카테고리 선택 기능 변경 (로컬경로설정.Category 항목 참조)
<span class="box other">[CaptureManager]</span> 카테고리 선택 기능 변경  (설정.CategorySelect 메뉴 참조)
<span class="box other">[LabViewer]</span> LiveUpdate 기능 추가 (실행메뉴.LabViewer 참조)
<span class="box other">[LabViewer]</span> 환자정보 Sync 기능 추가  (차트 FU시 랩뷰어에 Relay)
<span class="box other">[LabViewer]</span> Interface 실행 기능 추가  (차트번호 우측 버튼 참조)
<span class="box other">[LabViewer]</span> 차트에서 LabViewer 실행시 로그인 생략 기능 추가  (실행.LabViewer 메뉴 참조)
<span class="box other">[인터페이스]</span> 캐논 RKF2  (ARK)
<span class="box other">[인터페이스]</span> 탑콘 KR8800  (ARK)
<span class="box other">[KIOSK 5.0]</span> 전시회 모드로 수납수행 옵션 기능 추가  (환경설정.기본.사용옵션 참조)


<bold># 1/4 배포</bold>
=====================
<span class="box jemu">원무</span> - 영문진단서 도장 등록 기능 추가  (기준정보.직원정보.처방전도장서명 버튼 참조)
<span class="box jemu">원무</span> - 상용구정보 퇴사자제외 옵션 기능 추가  (기본자료.상용구정보 참조)
<span class="box jemu">원무</span> - 입원정보 더블클릭시 퇴원일자 변경되는 오류  bug  
<span class="box chart">진료</span> - 외래진료.수납탭 후불진료비 항목 추가  (후불진료비 발생시에만 항목 표시)
<span class="box chart">진료</span> - 처방창 수량 항목에서 이동키 동작 변경  (수량 항목에서 이동키일때 횟수 유지)
<span class="box chart">진료</span> - 처방창 수량 기본값을 공백으로 표시  (수량이 기본 0으로 표시되지 않게)
<span class="box chart">진료</span> - 만성질환 카운트 표시 bug (전년도 차트 리뷰시 카운트 표시 되게)
<span class="box lab">검사실</span> - 검사결과 항목 편집 동작 변경  (검사결과값 모두 선택상태)
<span class="box diag">진단서</span> - 급여제한여부조회서 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box diag">진단서</span> - 의료급여 산정특례 등록(지원) 신청서  날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box diag">진단서</span> - 건강보험산정특례등록신청서  날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box diag">진단서</span> - 채용신체검사서(일반)  날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box inspect">심사</span> - 이전청구내역  년월 이동 버튼 기능 추가  (보험청구.이전청구내역 버튼 참조)
<span class="box other">통계</span> - 후불거래처별처방통계 기능 추가  (진료통계탭 참조)
<span class="box other">[LabViewer]</span> 검안실 기능 추가 (검안실탭 참조)
<span class="box other">[LabViewer]</span> 검안실 검안내역 기능 추가 (검안실탭 검안내역 버튼 참조)
<span class="box other">[LabViewer]</span> 검안실 검안현황 기능 추가 (검안실탭 검안현황 버튼 참조)
<span class="box other">[LabViewer]</span> 검안실 화면구성 옵션 기능 추가 (상단 환경설정 버튼 참조)
<span class="box other">[LabViewer]</span> 펜차팅 화면구성 옵션 기능 추가 (상단 환경설정 버튼 참조)
<span class="box other">[StaffMenu]</span> 물리치료실 잠금 옵션 기능 추가 (StaffMenu.기본.잠금옵션 참조)
<span class="box other">[의료비소득공제]</span> 마이너스 금액 수록 오류 bug  ('-' 수록 규칙 적용)
<span class="box other">[KIOSK 5.0]</span> 0원 수납건의 수납자 수록 bug (수납자 누락 패치)

</pre>
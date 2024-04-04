---
title: 2022년 3월 업데이트 히스토리
menuTitle: 2022년 3월
historyHome: 0
yearMonth: 2203
---

<pre>


<bold># 3/31 배포</bold>
=====================
<span class="box jemu">원무</span> - 입원환자 결과 표시 방법 변경  
<span class="box lab">[LabViewer]</span> EyeView - 숨김 항목값 표시 오류   bug
<span class="box notice">[고시]</span> 2022년 4월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 4월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 4월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 3/26 배포</bold>
=====================
<span class="box inspect">심사</span> - 진찰료 주간오전야간산정 제외 옵션 동작 bug


<bold># 3/24 배포</bold>
=====================
<span class="box jemu">원무</span> - 선수차감 동작   bug  ('카드상계액 항목값이 올바르지 않습니다' 메시지 bug)
<span class="box jemu">원무</span> - 선수차감 일자 선택창 동전버튼 동작   bug  (선수잔액 범위내에서 수록되도록)
<span class="box jemu">원무</span> - 개인정보활용동의 싸인패드설정 전송속도 항목 기능 추가  (외래접수.동의서.싸인패드설정창 참조)
<span class="box chart">진료</span> - 전처방 영상일괄보기 동작 변경  (전처방에서 영상 선택없이 우클릭시 해당일자의 모든 이미지 보기)
<span class="box chart">진료</span> - 처방탭추가 기능 변경  (처방탭추가창에서 분리청구, 위탁진료 제거)
<span class="box chart">진료</span> - 전처방에 표시할 영상 선택 기능 추가  (환경설정.카테고리등록.전처방표시 항목 참조)
<span class="box chart">진료</span> - SQL 용법 사용시 용법코드 기본값 설정 기능 추가  (수가정보.나이체중별탭 참조)
<span class="box chart">진료</span> - 조제시참조사항 'H/재택치료' 출력 누락 bug  (가루약조제 참조사항 발생시 누락되는 증상)
<span class="box lab">[LabViewer]</span> 실행메뉴에 단축키 설명 표시  (상단 실행 버튼 참조)    
<span class="box lab">[LabViewer]</span> 차트번호 포커싱 동작 변경  (차트번호 항목 선택시 전체 선택상태 되게)
<span class="box lab">[LabViewer]</span> 영상 출력 기능 추가  (영상 선택후 우클릭 '출력' 메뉴 참조)
<span class="box lab">[LabViewer]</span> EyeView 검안메모 기능 추가  (EyeView탭 참조)
<span class="box lab">[LabViewer]</span> 타블렛(Windows OS) 연동 기능 추가  (환경설정.Patient Sync 참조)
<span class="box lab">검안실</span> - 검안실오더가 추가 발생시 실시부서진행상태 적용룰 변경  (기존 항목의 오더수행상태 유지)
<span class="box lab">검안실</span> - 좌우검사 저장후 검안오더 완료 기능 추가  (검안실코드창.장비 항목 참조)
<span class="box lab">검안실</span> - 단측검사 결과 표시 기능 추가  (기준정보.좌우검사.장비수정창.양측검사 항목 참조)
<span class="box lab">검안실</span> - 선택환자 검안내역 일괄 보기 기능 추가  (환자 FU후 검안실.검안내역 버튼 참조)
<span class="box lab">검안실</span> - 진료내역창 ESC 창닫기 동작기능 추가
<span class="box other">SCAN</span> - 스캔 저장후 검안오더 완료 기능 추가  (검안실코드창.카테고리 항목 참조)


<bold># 3/21 배포</bold>
=====================
<span class="box jemu">원무</span> - 수납대기목록에서 '수납대상액 0원 일괄 수납' 메뉴 보기  옵션 기능 추가  (사용자설정.수납업무.보기옵션 참조)
<span class="box jemu">원무</span> - 접수증 안내문구 사용자파일 출력 기능 추가  (사용자설정.접수업무.접수증출력옵션 참조)
<span class="box jemu">원무</span> - 감면내용에 감면율 표시 옵션 기능 추가  (환경설정.수납.감면구분옵션 참조)
<span class="box jemu">원무</span> - 외래접수 선수차감 동작 bug  (선수차감 대상내역 표시)
<span class="box jemu">원무</span> - 검안결과 출력 기능 추가  (검안결과줄에서 우클릭 메뉴 참조)
<span class="box jemu">원무</span> - 검사결과지 과별 출력 기능 추가  (검사결과지 출력창 참조)
<span class="box jemu">원무</span> - 외래접수 진료의변경룰 변경  (해당 차트를 의사가 FU전에는 진료의변경 가능)
<span class="box jemu">원무</span> - 외래접수 진료대기창 접수증출력 메뉴 기능 추가  (진료대기목록에서 우클릭 메뉴 참조)
<span class="box jemu">원무</span> - 검안오더창 컬러표시룰 변경  (오더창에서 직전 오더에 컬러 표시)
<span class="box jemu">원무</span> - 전달메모 수신부서 표시룰 적용  (미사용 수신부서 표시 제외)
<span class="box jemu">원무</span> - 외래접수 검안오더 단축키 설정 기능 추가  (화면설정.단축키설정.외래접수 참조)
<span class="box jemu">원무</span> - 접수증 나이 성별 출력 기능 추가
<span class="box chart">진료</span> - 외래진료 묶음처방탭 통합검색 동작 변경  (증상, 상병명칭, 수가명칭 포함 검색)
<span class="box chart">진료</span> - 계산창 수납내역탭 선택값 기억
<span class="box chart">진료</span> - 대기자탭 소트 기능 추가  (대기자, 나이, 접수시간 항목 소트)
<span class="box chart">진료</span> - 외래진료 증상 특이증상 Splitter 너비 저장 기능 추가  
<span class="box chart">진료</span> - 전처방 새로고침시 영상 표시 동작  bug  (진료이후 추가된 영상 표시)
<span class="box chart">진료</span> - 보류 버튼에서 진료비툴팁보기 옵션 기능 추가  (사용자설정.진료업무.보기옵션 참조)
<span class="box chart">진료</span> - 영상창 카테고리탭에서 선택없이 우클릭 동작 변경  (해당 Category 영상만 표시)
<span class="box chart">진료</span> - 영상창 썸네일 선택후 우클릭시 가장앞 이미지 포커싱되게  (영상비교창 동작 참조)
<span class="box chart">진료</span> - 영상창 뷰탭에서 선택영상 삭제 메뉴 기능 추가  ([...] 버튼 메뉴 참조)
<span class="box chart">진료</span> - 영상비교창 영상확대 기능 추가  (마우스휠로 영상확대)      
<span class="box chart">진료</span> - 영상비교창 자동 2분할 동작 변경  (변경후 좌우 표시)
<span class="box chart">진료</span> - 영상비교창 분할모드 메뉴명 변경  (2분할상하, 2분할좌우)
<span class="box chart">진료</span> - 묶음처방 과 검색 오류 수정
<span class="box inspect">심사</span> - 기본자료 묶음처방 통합검색 동작 변경  (증상, 상병명칭, 수가명칭 포함 검색)
<span class="box inspect">심사</span> - 기본자료 모음장 통합검색 동작 변경  (그룹명, 수가코드, 수가명 포함 검색)
<span class="box inspect">심사</span> - '증번호' 항목이 환자정보와 같지 않습니다.  bug  (에러수정 후 점검되지 않게)  
<span class="box inspect">심사</span> - 송신시 송신구분 값 수록 기능 추가  (송신후, 청구통계.월별청구통계.송신구분 항목 참조)
<span class="box inspect">심사</span> - 월별청구통계 요양기관 검색조건 추가  (청구통계.월별청구통계 참조)
<span class="box inspect">심사</span> - DRG 라이브러리 적용룰 변경  (DRG 차상위환자 본부 산정)
<span class="box lab">검안실</span> - 검안항목 명칭룰 변경 ('그룹명>항목명칭' 형식으로 표시)
<span class="box lab">검안실</span> - 검사항목별 완료 버튼 기능 추가  (명칭 항목 우측 참조)
<span class="box lab">검안실</span> - 검사항목 취소 메뉴 기능 추가  (검안항목 우클릭 메뉴 참조)
<span class="box lab">검안실</span> - 검사항목 오더삭제 메뉴 기능 추가  (검안항목 우클릭 메뉴 참조)
<span class="box lab">[LabViewer]</span> 영상소견서 출력  bug
<span class="box lab">[LabViewer]</span> 검사결과 등록창 저장 버튼 단축키 추가  (Insert Key)
<span class="box lab">[LabViewer]</span> 실행 메뉴 기능 추가  (Scan - F3, CaptureManager - F4, PosVision - F5)
<span class="box lab">[LabViewer]</span> 새로고침 툴팁 bug
<span class="box lab">[LabViewer]</span> 화면설정 기록 위치 변경  (변경후 : C:\NixHIS\configuration\ScreenDesign_EyeView.xml)
<span class="box lab">[LabViewer]</span> 수가검색창 동작 bug
<span class="box lab">[LabViewer]</span> F1 색인창 동작 bug
<span class="box lab">[LabViewer]</span> 검사결과 새작성 동작 bug
<span class="box lab">[LabViewer]</span> 검안실 FU 동작 bug
<span class="box other">인터페이스</span> - RKF1 기능 추가
<span class="box other">인터페이스</span> - RKF2 기능 추가


<bold># 3/15 배포</bold>
=====================
<span class="box notice">[고시]</span> 신속항원검사 양성인경우 조제시참고사항 수록 기능 추가


<bold># 3/14 배포</bold>
=====================
<span class="box chart">진료</span> - 감염병발생신고 URL 변경  (바로가기.법정감염병자동신고서.감염병발생신고 메뉴 참조)


<bold># 3/10 배포</bold>
=====================
<span class="box jemu">원무</span> - 수납대기창 감면구분 표시 기능 추가  (외래접수.수납대기창 툴팁 참조)
<span class="box jemu">원무</span> - 기준정보.좌우검사 더블클릭 동작 기능 추가  (장비 또는 항목 수정창 표시)
<span class="box jemu">원무</span> - 좌우검사 검사결과 길이 변경  (변경후 30 byte)
<span class="box jemu">원무</span> - 좌우검사 정렬방법 옵션 기능 추가  (환경설정.접수.좌우검사 참조)
<span class="box jemu">원무</span> - CRM 내원기간 검색조건 동작 변경 (변경후 접수기록 기준)
<span class="box jemu">원무</span> - CRM 내원기간 기간지정한 일자의 저장 동작 bug  
<span class="box jemu">원무</span> - 기초검사 정렬방법 옵션 기능 추가  (환경설정.접수.기초검사 참조)
<span class="box jemu">원무</span> - 안경처방전 출력 기능 추가  (로컬설정.프린터설정.안경처방전 참조, 좌우검사결과 우측 메뉴 참조)
<span class="box chart">진료</span> - AH234(재택치료) 처방시 재진 아닌 경우 알림 기능 추가  ('재진만 가능합니다' 알림)
<span class="box chart">진료</span> - 증상탭(CC탭)에서 증상일괄 입력 기능 추가  (복사할 증상을 Drag)
<span class="box chart">진료</span> - 외래진료 수납탭 날짜 선택 동작 변경  (날짜항목 직접 편집 기능 지원)
<span class="box chart">진료</span> - 외래진료 예약탭 날짜 선택 동작 변경  (날짜항목 직접 편집 기능 지원)
<span class="box chart">진료</span> - 파일백업 자동실행 옵션 기능 추가  (환경설정.백업관리.백업설정 '백업확인없이 자동 실행' 옵션 참조)
<span class="box diag">진단서</span> - 당뇨병환자 소모성재료 진단서 적용비율 항목 소수점 입력되게  (신청서탭 참조)
<span class="box diag">진단서</span> - 건강진단서국가시험면허신청용 용도 미출력 bug  (진단서탭 참조)
<span class="box inspect">심사</span> - 청구심사탭 날짜 선택 동작 변경  (날짜항목 직접 편집 기능 지원)
<span class="box inspect">심사</span> - 감면구분창에서 내용이 길경우 오류   bug  (기준정보.수납관리.감면구분 메뉴 참조)
<span class="box inspect">심사</span> - 심사결과통보서 일괄보기에서 원외처방 심결 표시 기능 추가  (요양급여 심사결과 통보서 일괄보기창 참조)
<span class="box inspect">심사</span> - 청구DB.진료확인번호 승인 동작 변경  (청구DB 에서 진료확인번호 승인 시 진료DB에 적용)
<span class="box inspect">심사</span> - '수가/약품 수량 0' 오류가 '진찰료 산정 착오' 로 표시되는 bug
<span class="box inspect">심사</span> - 작은청구 총괄표 엑셀출력 기능 추가  (작은청구탭 총괄표 버튼 참조)
<span class="box inspect">심사</span> - 청구자료 가져오기 진료확인승인번호 선택 기능 추가  (청구.청구자료가져오기 버튼 참조)
<span class="box inspect">심사</span> - 보험료체납급여제한자 알림 메시지 변경  ('보험료체납급여제한자 / 전액본인부담 후 청구대상' 알림 표시)
<span class="box inspect">심사</span> - 자보청구 조회시 명세서내역 순서   bug  (자보사코드별 정렬)
<span class="box inspect">심사</span> - 청구확인(EdiView) 불러오기 속도 개선  (보험청구.청구확인 버튼 참조)
<span class="box other">공통</span> - 내부 네트워크 IP를 설정하세요 알림 기능추가  (알림 발생시 로컬설정.기본.내부네트워크IP 항목 참조)


<bold># 3/3 배포</bold>
=====================
<span class="box jemu">원무</span> - CRM 내원기간 검색조건 동작 변경  (변경후 : 접수기록 기준)
<span class="box chart">진료</span> - 묶음처방 순서변경 동작 bug


<bold># 3/2 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 3월 수가 등록 (자동 실행)
<span class="box diag">진단서</span> - 코로나 신속항원검사 서식 검사기관 표시 bug  (확인서탭 참조)
<span class="box diag">진단서</span> - 영문진단서 Home Address 입력 길이 변경  (진단서탭 참조)

</pre>

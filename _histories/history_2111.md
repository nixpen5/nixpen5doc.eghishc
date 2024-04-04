---
title: 2021년 11월 업데이트 히스토리
menuTitle: 2021년 11월
historyHome: 0
yearMonth: 2111
---

<pre>

<bold># 11/29 배포</bold>
=====================
<span class="box jemu">원무</span> - 카드수납창에서 원외처방전 출력 오류 수정
<span class="box inspect">심사</span> - 시설등의공동이용진료인 HA424006 단가 산정 bug


<bold># 11/25 배포</bold>
=====================
<span class="box jemu">원무</span> - 영수증 항목텍스트 빈값 오류 수정
<span class="box jemu">원무</span> - 영수증 항목텍스트 변경시 로그 기록 기능 추가
<span class="box chart">진료</span> - 묶음타이틀이 삭제된 내역 표시방법 변경


<bold># 11/24 배포</bold>
=====================
<span class="box jemu">원무</span> - 카드수납창에서 의료급여승인창으로 호출 동작   bug (의료급여승인창 표시되도록) 
<span class="box jemu">원무</span> - 의보100 진료정보변경창 동작 변경 ('의보100을 지원하지 않습니다' 메시지 표시)
<span class="box jemu">원무</span> - 처방전 재출력시 본인부담구분코드 출력룰 변경 (진료확인번호 승인된 본인부담구분코드를 출력)
<span class="box jemu">원무</span> - 접수 저장시 개인정보활용동의 팝업안함 옵션 기능 추가 (로컬설정.개인정보활용동의설정 참조)
<span class="box chart">진료</span> - 차트 보류후 대기자 보기 옵션  기능 추가 (사용자설정.진료업무.열기및저장 > 차트보류후대기자보기옵션 참조)
<span class="box chart">진료</span> - 차트출력 특이증상이 많을때 출력  bug (페이지 밀림증상 패치)  
<span class="box diag">진단서</span> - 근로능력평가용진단서 출력   bug   
<span class="box lab">검사실</span> - 수탁검사 미전송창 환자수 항목 표시  bug  
<span class="box lab">검사실</span> - 미전송 오더내역 정렬   bug (수탁검사 전송 검색창의 정렬순서와 동일하게)
<span class="box lab">검사실</span> - 잠금시 지원부서 대기목록 표시제외 옵션 기능 추가 (StaffMenu.기본 잠금옵션 참조)
<span class="box lab">검사실</span> - 검사결과 참고치 기준 검사결과 입력 기능 추가 (참고치 항목 더블클릭시 결과 항목에 참고치 텍스트 입력)
<span class="box lab">물리치료실</span> - 물리치료현황 연인원 조회 속도 개선  
<span class="box lab">물리치료실</span> - 물리치료현황 실인원 조회 속도 개선  
<span class="box inspect">심사</span> - 향정신성 약품 JT014 수동입력기능 추가 (향정신성 약물을 30일을 초과하여 처방하는 경우)
<span class="box inspect">심사</span> - 수가정보 의약품예외구분 항목에 코드 추가 표시 (의약품예외구분 코드값 표시)  
<span class="box inspect">심사</span> - 수가정보 의약품구분 항목유형 조건 추가 (수가정보.항목유형.의약품구분 참조)
<span class="box inspect">심사</span> - 수가정보 수가구분 항목유형 조건 추가 (수가정보.항목유형.수가구분 참조)
<span class="box inspect">심사</span> - 확인코드 특정내역 미발생  bug (처방속성창.확인코드 항목 참조)
<span class="box inspect">심사</span> - 수가정보 대체코드 동작 bug (입력코드를 처방시 대체코드로 바뀌는 기능)
<span class="box other">통계</span> - 진료비통계 권한 적용 bug (기준정보.역할및권한.권한설정 '진료비통계' 권한 참조) 
<span class="box other">통계</span> - 항목별진료실적통계_진료의 조회 결과 bug (수입통계.항목별진료실적통계 3종 참조)
<span class="box notice">[고시]</span> 장애인건강주치의 시범사업 3단계 (특정기호 S036 수록대상)
<span class="box other">[진료정보교류]</span> 문서를 전송할 수 없습니다.  bug  (전송할 수 없는 처방코드가 존재시 메시지 표시)
<span class="box other">[KIOSK 5.0]</span> 진료카드 바코드 인식 기능 추가 (사용자설정.접수업무.접수증출력옵션 참조)
<span class="box other">[KIOSK 5.0]</span> 접수증 리딩후 수납 기능 (수납 버튼 누르고 바코드가 인쇄된 접수증 리딩)
<span class="box other">[KIOSK 5.0]</span> 키오스크 종료 기능 추가 (로컬설정.KIOSK연동 참조)
<span class="box other">[KIOSK 5.0]</span> 대기인수에 보류환자수 포함 옵션 기능 추가 (환경설정.기본.접수옵션 참조)
<span class="box other">[KIOSK 5.0]</span> 처방전 환자보관용 출력여부 확인 기능 추가 (환경설정.기본.수납옵션 참조)
<span class="box other">[KIOSK 5.0]</span> 영수증 출력여부 확인 기능 추가 (환경설정.기본.수납옵션 참조)


<bold># 11/16 배포</bold>
=====================
<span class="box jemu">원무</span> - 접수시 접수증 출력 (사용자설정.접수업무.접수후접수증출력 항목 참조, 로컬설정.프린터설정.접수증 항목 참조)
<span class="box jemu">원무</span> - 의사스케줄 설정 기능 추가 (원무.스케줄설정창 참조)
<span class="box jemu">원무</span> - 개인정보활용 동의서 와콤 연동 (동의서창.개인정보활용동의설정 동의서서명방법 참조)
<span class="box diag">진단서</span> - 장애진단서(개정:2019.6.4) 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box diag">진단서</span> - 방사선관계종사자 건강진단표 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box diag">진단서</span> - 근로능력평가용진단서 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box diag">진단서</span> - 진료확인서 Value 항목이 최대길이를 초과했습니다   bug  (상병명의 길이가 긴 경우라도 에러메시지 표시되지 않게)
<span class="box lab">검사실</span> - 바코드 크기 변경 기능 추가 (검사실.검사관리.라벨출력설정 용지크기 항목 참조)
<span class="box lab">검사실</span> - 검사결과지 출력  결과 및 참고치 잘리지 않게 (결과, 참고치 항목 너비 조정)
<span class="box lab">검사실</span> - 라벨출력 여부 표시 기능 추가 (옵션 없음)
<span class="box lab">검사실</span> - 검사실 대기목록 라벨출력 여부 표시 기능 추가 (대기목록창 참조)
<span class="box lab">검사실</span> - 수탁검사 결과 수신 동작 변경 (전송기간에 해당하는 결과만 수신)
<span class="box inspect">심사</span> - 혈액투석정액 SamFile 상병 수록 bug
<span class="box inspect">심사</span> - 작은청구.선택환자 내역보기 LastValue 기능 추가
<span class="box other">[KISOK 5.0]</span> 진료의사 8명 제한 기능 변경 (진료의사수 10명까지 지원)
<span class="box other">[KIOSK 5.0]</span> 접수후 알림 화면 추가 (환경설정.접수후알림창 참조)
<span class="box other">[KISOK 5.0]</span> 접수 안내문구 잘림 bug  (특정 폰트에서 안내문구가 잘리지 않게)
<span class="box other">[KIOSK 5.0]</span> 접수증 접수번호 항목 추가 (옵션 없음)
<span class="box other">[KIOSK 5.0]</span> 프로그램이 이미 실행중입니다. (키오스크 중복 실행 방지)
<span class="box other">[KIOSK 5.0]</span> 휴진의사 숨김 옵션 기능 추가 (환경설정.기본.접수옵션 참조)
<span class="box other">[KIOSK 5.0]</span> 포스프린터 전송속도 항목 추가 (로컬설정.기능 참조)
<span class="box other">[KIOSK 5.0]</span> 초재진 산정룰 변경 (만성질환 상병 기준 초재진 적용)
<span class="box notice">[고시]</span> 2022년 1월 점수당단가 (점수당단가 및 공휴일 등록)


<bold># 11/11 배포</bold>
=====================
<span class="box chart">진료</span> - 자보 처방전 요양기관기호 출력  bug
<span class="box other">통계</span> - 제약회사별통계 출력물 표시 방법 변경 (진료통계.제약회사별처방통계 출력물 참조)


<bold># 11/8 배포</bold>
=====================
<span class="box inspect">심사</span> - 일반건강검진, 암검진 동시 발생시 산정 bug


<bold># 11/4 배포</bold>
=====================
<span class="box inspect">심사</span> - AskCust_PK를 위반했습니다. bug (요양기관 다수개인 병원에서 청구시 청구번호 발생 bug)


<bold># 11/3 배포</bold>
=====================
<span class="box diag">진단서</span> - 국민연금장애심사용진단서(개정) 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box inspect">심사</span> - 작은청구 FU 속도 개선
<span class="box other">[KIOSK 5.0]</span> - LiveUpdate 기능 추가


<bold># 11/2 배포</bold>
=====================
<span class="box jemu">원무</span> - 백신 설정창 초기 화면 동작 변경 (외래접수.백신.설정메뉴.백신설정창 참조)
<span class="box jemu">원무</span> - 환불내역 표시방법 변경 (외래수납.상세내역.환불내역탭 참조)
<span class="box jemu">원무</span> - 예약가능인수 알림 기능 추가 (예약창 [...] 버튼 예약가능인수설정창 참조)
<span class="box jemu">원무</span> - 접수목록 키오스크 환자 구분 표시 (접수대기/수납대기에 'K' 구분자 표시)
<span class="box jemu">원무</span> - 키오스크탭 추가 (화면설정.화면디자인.컨텐츠.키오스크 참조)
<span class="box jemu">원무</span> - 수납시 원외처방전 출력 기능 추가 (카드수납/현금수납/상세수납 참조)
<span class="box jemu">원무</span> - 진료비세부산정내역서 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box jemu">원무</span> - 외래 진료비 계산서 영수증 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box chart">진료</span> - 처방전 조제시참고사항 미표시 bug
<span class="box chart">진료</span> - 처방전 출력매수 지정기능 변경 (계산창.원외처방전출력설정.사용자설정 출력매수 항목 참조)
<span class="box diag">진단서</span> - 건강진단서 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box other">[KIOSK 5.0]</span> - 접수/수납/증명서 기능 추가

</pre>
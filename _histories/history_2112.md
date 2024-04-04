---
title: 2021년 12월 업데이트 히스토리
menuTitle: 2021년 12월
historyHome: 0
yearMonth: 2112
---
<pre>

<bold># 12/31 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년도 DRG 기초수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 1월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 1월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 1월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 12/29 배포</bold>
=====================
<span class="box jemu">원무</span> - 기준정보 후불거래처 등록 기능 추가 (기준정보.수납관리 메뉴 참조)
<span class="box jemu">원무</span> - 수가정보 후불거래처 등록 기능 추가 (의약품의 후불단가, 후불거래처 항목 참조)
<span class="box jemu">원무</span> - 외래접수 검안오더 기능 추가 (외래접수.오더버튼 검안오더 메뉴 참조)
<span class="box jemu">원무</span> - 접종내역입력창 날짜 입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box jemu">원무</span> - 진료환불 수납대상 항목   bug  (진료환불 수납대상액 표시 오류 패치)
<span class="box jemu">원무</span> - Scan 로컬경로설정 동작 변경 (외래접수.스캔.환경설정.로컬경로설정 참조)
<span class="box chart">진료</span> - 키오스크 수납중 알림 기능 추가 (진료완료 버튼 클릭시 '키오스크에서 수납중입니다' 메시지 표시)
<span class="box diag">진단서</span> - 진료의뢰서 날짜 입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box diag">진단서</span> - 방사선작업종사자건강진단서 날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box lab">검안실</span> - 검안실 화면 및 기능 추가 (지원부서 검안실 참조)
<span class="box other">통계</span> - 의사별진료비 통계 후불진료비 항목 추가 (진료비통계 참조)
<span class="box other">[WaitCall]</span> 진료보류를 검사중으로 표시 옵션 기능 추가 (환경설정.대기자표시대상 참조)
<span class="box other">[KIOSK 5.0]</span> 이미지 불러오기 룰 변경 (사용자 이미지가 우선 표시되도록)


<bold># 12/28 배포</bold>
=====================
<span class="box chart">진료</span> - 묶음처방 수량 소수점으로 변경시 저장이 안되는 증상 bug (수량 소수점 저장 되게)


<bold># 12/23 배포</bold>
=====================
<span class="box jemu">원무</span> - 마감장 미수발생내역 항목에 수납메모 출력 기능 추가 (미수발생내역 항목 참조)
<span class="box jemu">원무</span> - 외래접수 사용자버튼설정 검안오더 버튼 추가 (외래접수.화면설정.사용자버튼설정 참조)
<span class="box jemu">원무</span> - 수납대장 클래식  진료일자 항목 추가 (외래접수.수납대장 클래식 양식 참조)
<span class="box jemu">원무</span> - 자격조회 약국전용 필드 저장 방법 변경 (자격조회 결과중 오류 포함시 에러 회피)
<span class="box chart">진료</span> - 사용자설정 SCAN영상 표시 기능 추가 (사용자설정.전처방.영상표시 항목 참조)
<span class="box chart">진료</span> - DRG등록 의사만 작성할 수 있습니다 권한룰 변경 (의사 아닌경우에도 입원/DRG 등록 가능)
<span class="box chart">진료</span> - 처방창 오더 일괄 삭제시 오류 bug (처방코드 DoubleClick 후 오더 일괄 삭제 동작)
<span class="box chart">진료</span> - 진료대기목록 검안오더 표시 기능 추가 (검안오더를 'E>' 또는 'E<'로 표시)
<span class="box chart">진료</span> - 의사변경후 전처방 PACS 표시 방법 변경 (진료의변경시 PACS 오더 진료의를 변경)
<span class="box chart">진료</span> - 수가정보 처방옵션 설정 기능 추가 (수가정보 내복약/외용약 선택후 처방옵션 버튼 참조)
<span class="box diag">진단서</span> - 진료소견서  날짜입력 동작 변경 (날짜항목 직접 편집 기능 지원)
<span class="box inspect">심사</span> - 심평원 사전점검 재송신 기능 추가 (재송신 클릭후 재송신 대상 선택 메뉴 팝업)
<span class="box lab">검사실</span> - 수탁검사 전송내역창 상세 표시 동작 변경 (송신일시를 시분초까지 표시)
<span class="box lab">검사실</span> - 수탁검사 전송창 검사건수 항목 추가 (수탁검사 전송이력창 참조)
<span class="box notice">[고시]</span> 산정특례 잠복결핵관련 ('V010' 잠복결핵감염 산정특례 지원대상자)
<span class="box other">[CaptureManager]</span> Area Select 동작 변경 (바깥 테두리 시인성 보완)
<span class="box other">[KIOSK 5.0]</span> 수납 로그 보완 (차트번호, 환자성명, 오류사유 수록 내용 보완)
<span class="box other">[의료비소득공제]</span> 기본 해상도 변경 (최소해상도 1280 * 900)
<span class="box other">[의료비소득공제]</span> 진료비, 미수차감, 환불내역 조회 동작 변경 (2021년도 소득공제 증빙자료 제출 기준)
<span class="box other">[의료비소득공제]</span> 중간저장자료 생성일시 표시방법 변경 (3/6화면 제출 자료 정보 참조)


<bold># 12/16 배포</bold>
=====================
<span class="box jemu">원무</span> - 원무 - 마감장 미수차감내역 항목에 수납메모 출력 기능 추가 (미수차감내역 참조) 
<span class="box jemu">원무</span> - 수납대장 수납메모 표시방법 변경 (수납줄별메모 우선, 부재시 수납메모 수록)
<span class="box jemu">원무</span> - 수납대장 클래식SQL 수납메모 항목 추가 (진료형태 우측 항목 참조)
<span class="box chart">진료</span> - 묶음처방 수량 변경 동작 bug (묶음처방 상세창 참조)


<bold># 12/15 배포</bold>
=====================
<span class="box jemu">원무</span> - Template 읽는중 오류 보완 (펜차트, 동의서 등 서식파일이 깨진 경우 Crush 방지)
<span class="box jemu">원무</span> - 마감장 수납자 검색조건 기능 추가 (수납대장 마감장탭 참조)
<span class="box jemu">원무</span> - 수납후 수납메모저장 기능 추가 (수납완료상태에서 상세수납창 저장 버튼 클릭)
<span class="box chart">진료</span> - M3승인정보와 투약일수 불일치 알림 동작 변경 (정보성 알림으로 변경)
<span class="box chart">진료</span> - 처방창 용법 일괄변경 동작 bug (처방창 용법항목 빈줄에서 용법코드 입력후 enter)
<span class="box chart">진료</span> - 진료대기목록에 키오스크접수 구분 표시 옵션 기능 추가 (사용자설정.진료업무.보기옵션 참조)
<span class="box chart">진료</span> - 특이증상 일괄 리피트 동작 변경 (편집이 용이하도록 각 줄의 뒤에 공백 추가)
<span class="box chart">진료</span> - MT059(문제의약품 유형) 조제시참고사항 출력 기능 추가
<span class="box other">공통</span> - 관리자 권한으로 실행 여부 메시지 기능 추가 (프로그램아이콘.속성창.바로가기탭 고급속성창 참조)
<span class="box inspect">심사</span> - 전자서명 검색동작  bug (진료탭 전자서명 메뉴 참조)
<span class="box inspect">심사</span> - 차트 로그 기록 방법 변경 (오더코드 기록)
<span class="box inspect">심사</span> - 청구 불러오기 속도 일부 개선
<span class="box inspect">심사</span> - MT059 수납대상액 산정룰 변경 (문제의약품유형 감면대상자, 수납대상액 0원)
<span class="box lab">검사실</span> - 전체검사보기에서 검사대기 FU 동작 bug (진료의사별로 검사오더 발생한 경우)
<span class="box other">통계</span> - 진료의별수입통계 할인액 항목 추가 (수입통계탭 참조)
<span class="box other">통계</span> - 월별수입통계 할인액 항목 추가 (수입통계탭 참조)
<span class="box other">통계</span> - 진료과별수입통계 기능 추가 (수입통계탭 참조)
<span class="box other">[SmartCheck]</span> 청구사전심사 엑세스가 거부되었습니다   bug (사전심사결과 생성 대기시간 늘림)
<span class="box notice">[고시]</span> 수가정보 의약품 예외구분코드 기타 항목 추가 (수가정보.예외구분코드 항목 참조)
<span class="box other">[KIOSK 5.0]</span> 보험유형 적용 룰 변경 (전일 자보/산재 진료건 존재시 자격조회 결과와 관계 없이 자보/산재로 접수)
<span class="box other">[KIOSK 5.0]</span> 자격조회 결과 생성 (자격조회후 자격상세정보 생성)


<bold># 12/11 배포</bold>
=====================
<span class="box diag">진단서</span> - 문서번호 생성 bug (문서번호 5자리까지 지원)


<bold># 12/9 배포</bold>
=====================
<span class="box chart">진료</span> - 처방창 Alt + Enter 시 수량이 0으로 수록되는 bug (한 라인 추가 동작)
<span class="box notice">[고시]</span> MT059 로사르탄 문제의약품 유형 추가 (특정내역 MT059 '문제의약품 유형' 참조)
<span class="box other">[KIOSK 5.0]</span> 물리치료 접수 후 수납 미생성 bug


<bold># 12/8 배포</bold>
=====================
<span class="box jemu">원무</span> - 물리치료 리피트시 수량이 0으로 수록되는 bug


<bold># 12/7 배포</bold>
=====================
<span class="box jemu">원무</span> - 접수취소시 대기자콜 호출 동작 bug (진료대기목록.상태 항목 우클릭 참조)
<span class="box jemu">원무</span> - 접수취소후 최종내원일 생성 bug
<span class="box jemu">원무</span> - 최근좌우검사일자 겹침 bug (외래접수.기본정보창 하단 참조)
<span class="box jemu">원무</span> - 진료과별 출력 기능 추가 (진료과탭 선택후 출력 버튼 참조)
<span class="box jemu">원무</span> - JemuDevide에 중복키를 삽입할 수 없습니다 bug (수납시 오류 메시지 패치)
<span class="box chart">진료</span> - 처방창 수량 횟수 빨리 입력시 동작 bug (저장 후 수량이 바뀌는 증상 패치)
<span class="box chart">진료</span> - 계산창 진료기록부만 출력 기능 추가 (계산창.[...] 진료기록부만 출력 메뉴 참조)
<span class="box chart">진료</span> - PointCT CT데이터 내보내기 기능 추가 (전처방.CT내역 우클릭 'CT 데이터 내보내기' 메뉴 참조)
<span class="box chart">진료</span> - 처방전교부번호 중복   bug (특정 상황에서 중복될 수 있는 버그 패치) 
<span class="box inspect">심사</span> - 특정기호 V010 추가 ('V010' 잠복결핵감염자)
<span class="box diag">진단서</span> - 진료확인서1 진료일자 가져오기 동작 변경 (특정 진료과 또는 의사의 진료일자 가져오기 기능 지원)  
<span class="box diag">진단서</span> - 진료확인서2 진료일자 가져오기 동작 변경 (특정 진료과 또는 의사의 진료일자 가져오기 기능 지원)
<span class="box other">[마약류]</span> 마약류통합관리시스템 재인증 완료 (NIMS 정기 인증)
<span class="box other">[KIOSK 5.0]</span> 진료과명 설정 옵션 기능 추가 (로컬설정.의사설정 진료과명 항목 참조)


<bold># 12/2 배포</bold>
=====================
<span class="box jemu">원무</span> - 현금영수증 승인창 취소요청 버튼 위치 변경 (승인요청후 취소요청 버튼이 잘못 눌러지지 않도록)
<span class="box jemu">원무</span> - 카드수납창 상태바 표시 기능 추가 (보험유형, 진료구분 등 진료정보 표시)
<span class="box jemu">원무</span> - 접수증 안내문구 출력 옵션 기능 추가 (사용자설정.접수업무.접수증출력옵션 참조)
<span class="box jemu">원무</span> - 자격조회 출국자 일반 적용 bug ("일반으로 적용합니다." 메시지 추가)
<span class="box jemu">원무</span> - 외래접수 스캔 툴버튼 기능 추가 (외래접수.화면설정.툴버튼설정 스캔 버튼 참조)
<span class="box jemu">원무</span> - Scan(외부영상 저장) 기능 추가 (외래접수.스캔 버튼 참조)
<span class="box jemu">원무</span> - 전달메모 수신부서 주사실 항목 추가 (외래접수 전달메모 툴버튼 참조)
<span class="box chart">진료</span> - 묶음타이틀이 삭제된 내역 표시방법 변경 (묶음내역 편집 불가 증상 해결)
<span class="box chart">진료</span> - 특정기호 V307 추가 ('V307' - 원추각막)
<span class="box chart">진료</span> - 자리비움 아이콘 표시 기능 변경 (진료대기목록.상태항목 우클릭 참조)
<span class="box chart">진료</span> - 전처방 SCAN 영상 기능 추가 (외래접수.스캔 버튼 참조)
<span class="box diag">진단서</span> - 건강진단서 문구 변경 (진단서 서식그룹 참조)
<span class="box diag">진단서</span> - 진단서 출력 후 알림 추가 (출력후 '출력되었습니다' 메시지 표시)
<span class="box inspect">심사</span> - 수납 로그 생성 기능 추가 (수납금액정보 로그 기록)
<span class="box inspect">심사</span> - 수가정보  고시정보 갱신 기능 추가 (수가정보.고시정보탭 고시정보갱신 버튼 참조)
<span class="box inspect">심사</span> - 준용수가 단가 미발생   bug  (준용수가의 경우 정액수가 항목에 단가 기재)
<span class="box lab">검사실</span> - 오더일시 툴팁 표시 기능 추가 (대기환자 목록 툴팁 참조)
<span class="box lab">검사실</span> - 검사결과 한영모드 동작 변경 (마지막 한영상태 유지되게)
<span class="box lab">방사선실</span> - 방사선실코드관리  검색창 항목  bug  (불필요 항목 제거)
<span class="box lab">방사선실</span> - 방사선수가 수량고정 기능 추가 (방사선코드관리.방사선실코드정보 수량고정 항목 참조)
<span class="box lab">주사실</span> - 주사실 화면 추가 (지원부서탭.주사실 메뉴 참조)
<span class="box other">[마약류]</span> 삭제된 투약내역 표시방법 변경 (조제투약내역작성.미전송내역 하단 삭제된투약내역 참조)
<span class="box other">[진료정보교류]</span> ATC코드 부재시 전송룰 변경 (확인 메시지 없이 ATC코드 부재건을 포함하여 전송되도록)
<span class="box other">[KIOSK 5.0]</span> 내시경 글자 잘림 증상  bug (세글자까지 표시되도록)
<span class="box other">[KIOSK 5.0]</span> 물리치료 접수 기능 추가 (로컬설정.의사설정 화면 참조)
<span class="box other">[KIOSK 5.0]</span> 접수증 안내문구 사용 옵션 기능 추가 (로컬설정.기능.출력옵션 참조)
<span class="box other">[KIOSK 5.0]</span> 수납후 주사처방전 발행 옵션 기능 추가 (환경설정.기본.수납옵션 참조)
<span class="box notice">[고시]</span> 자격조회 출국자 보험유형 적용룰 변경 (급여제한여부 항목값 부재시에는 출국자 진료가능)
<span class="box notice">[고시]</span> 코로나 혈액투석 무료 수가 청구 (특정내역 MT043 - '3/02' 기재 대상)

</pre>
---
title: 2022년 6월 업데이트 히스토리
menuTitle: 2022년 6월
historyHome: 0
yearMonth: 2206
---

<pre>

<bold># 6/30 배포</bold>
=====================
<span class="box jemu">원무</span> - 수납대기 진료과/진료의 Header Click 정렬 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.수납대기 화면 참조
2) [진료과], [진료의] 컬럼 Click 시 정렬 기능 수행
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료내역 탭 신상 증상 표시 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료내역] 탭 참조
    - 변경 전 : 슬립 증상 표시, 신상 증상 미표시
    - 변경 후 : 슬립, 신상 증상 모두 표시
</th>
    </tr>
</table>

<span class="box chart">진료</span> - XLay 탭 그룹명칭 Click 시 오류 수정
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[XLay] 탭 참조
2) 초기화된 상태에서 [그룹명칭] 목록 Click 시 프로그램 다운되는 증상 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - SmartCheck 청구 의료급여만 점검시 오류
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 보험청구 화면 참조
2) [조회] 버튼 Click - 청구조회 조건창에서 청구대상.[의료급여 외래/입원] 만 선택 - [확인] 버튼 Click
3) [청구] 버튼 Click - [사전심사(SmartCheck)] 버튼 Click 시 오류 발생하는 증상 패치
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 진단서 병명일괄삭제 메뉴 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 원무.서류발급 화면 참조
2) 진단서 상병창에서 [코드] 칸 Right Click - [병명 일괄 삭제] 메뉴 클릭
</th>
    </tr>
</table>

<span class="box notice">[고시]</span> 2022년 7월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 7월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 7월 치료재료툴 (바로가기.공지사항.미설치툴 참조)

<bold># 6/23 배포</bold>
=====================
<span class="box jemu">원무</span> - 재접수건 취소 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.접수대기 화면 참조
2) 진료기록이 존재하는 재접수 건 Right Click - [접수취소] 메뉴 Click
    - 변경 전 : 접수 취소 불가
    - 변경 후 : 확인 창 팝업 후 접수 취소 진행
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수에서 예약 실행시 예약일자 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[예약] 버튼 Click
    - 변경 전 : 이전에 조회한 예약일자 유지하여 예약장부 팝업
    - 변경 후 : 오늘 일자로 예약장부 팝업
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 묶음처방 수량/횟수/일수 사용 옵션 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[병명 및 처방] 화면 참조
2) 묶음처방 기본값 옵션.[묶음처방 수량/횟수/일수 적용] 항목 선택
3) 차트 불러오기 후 묶음처방 입력
    - 선택해제 상태 : 수량/횟수/일수 [기본값] 으로 적용
    - 선택 상태 : 수량/횟수/일수 [묶음처방 설정값] 으로 적용
</th>
    </tr>
</table>
<span class="box chart">진료</span> - SQL 방식 용법 모음장 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.(SQL)용법입력창 화면 참조
2) SQL 용법 선택 (투여횟수, 처방용법, 매식 간/후/전, 복용시간)
3) [모음장 등록] 버튼 Click - 선택한 용법을 모음장에 추가
4) 대상 모음장 Right Click - [사용자코드 변경] 또는 [삭제] 메뉴 Click 하여 관리
5) 대상 모음장 Double Click 또는 [모음장 적용] 버튼 Click 하여 용법 적용
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 오더창 검사항목 너비 크게 ContextMenu 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.오더창 화면 참조
2) [...] 버튼 Click - [검사항목 너비 크게] 메뉴 선택
    - 선택해제 상태 : [검사항목] 영역 너비 기본
    - 선택 상태 : [검사항목] 영역 너비 넓음
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 수탁기관 공통 설정 사용시 위탁진료 점검 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.계산및산정.수탁검사산정옵션.[기준정보 기준 일괄 적용] 항목 선택
2) 환경설정.수탁기관설정.수탁기관공통설정 [사용] 선택 및 [수탁 요양기관기호] 입력
3) 처방창에서 검사코드 'A' 입력 후 [저장] 버튼 Click
4) 수가정보 화면에서 'A' 코드 조회 후 위탁구분.[수탁검사] 설정
5) 차트 다시 불러오기 시 [수탁검사] 로 적용된 'A' 코드 확인
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 정신과차트 줄바꿈없이 길게 입력시 내용 잘리는 bug
<span class="box chart">진료</span> - 상병창 첫줄 공백상태에서 묶음처방시 상병이 첫줄부터 입력되는 bug


<span class="box lab">검사실</span> - 완료일시 표시 방법 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.실시부서 화면 참조
2) 검사실옵션.[검사실 완료일시 고정] 항목 선택
3) 검사실 화면 우측 하단 [(검사)완료일시] 영역 확인
    - 선택해제 상태 : 검사기록 수정 시 [완료일시] 갱신
    - 선택 상태 : 최초 검사 [완료일시] 로 고정
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 검사결과지 검사완료일시 출력 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사결과지 출력 설정창 및 출력물 참조
2) 검사완료 상태인 경우 [검사완료일시] 추가 표시
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 사전점검 점검결과 메세지 중복 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 점검결과가 중복 표시될 수 있는 증상 패치
2) [차트] 버튼 Click 시 해당 일자의 차트가 2건 이상인 경우 선택창 팝업
</th>
    </tr>
</table>

<span class="box other">통계</span> - 외래진료현황 엑셀내보내기 Crush bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수입통계.[외래진료현황] 화면 참조
2) 결과가 많은 경우 프로그램 다운되는 증상 패치 및 속도 개선
</th>
    </tr>
</table>

<bold># 6/16 배포</bold>
=====================
<span class="box jemu">원무</span> - 차트번호로 수납자검색 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.수납대기, 외래접수.접수대기 화면 참조
2) 대기자 목록 Right Click - [수납자/대기자 검색] 메뉴 Click
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 예약현황 예약경로 검색조건 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 고객관리.예약현황 화면 참조
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료확인번호승인창 차트번호 검색 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납대장의 [진료확인번호승인] 탭 참조
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료환불창 대상 수납 체크 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래수납의 [...] 버튼 Click - [진료환불] 메뉴 Click
2) 선택한 환불 수납 건이 '진료비(보)' 인 경우 '진료비(비)' 내역을 동시 선택 처리
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 환자의 마지막 진료의사 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.접수업무의 기본옵션.[환자의 마지막 진료의사] 옵션 참조
2) 접수확인 창 팝업 시 해당 환자의 마지막 진료의사로 기본 설정
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 상세수납창에서 현금영수증 승인창 팝업기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.수납대기의 [...] 버튼 Click - [현금영수증 환경설정] 메뉴 참조
2) 상세수납 창에서 [수납] 버튼 Click 시 현금영수증 자동발행 옵션에 따라 승인창 팝업
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 건강진단서(국가시험면허신청용) 서식 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진단서.건강진단서 참조
2) 국가시험면허신청용-4 문구 변경
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 카드단말기 연동 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 로컬설정.카드단말기 설정 메뉴 참조
2) 카드단말기 정보 입력 (사업자등록번호, 설치 여부, 단말기 종류, 단말기 포트)
3) 설치 여부 Yes 로 변경 후 상세수납 창의 [수납] 버튼 Click 시 단말기 승인 창 팝업
4) 단말기 설정이 필요하므로 병원 담당자에게 문의하시기 바랍니다.
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 직원정보.검색조건포함 옵션 동작   bug  
<span class="box jemu">원무</span> - 문자발송창 붙여넣기 메뉴 동작  bug  


<span class="box chart">진료</span> - 환자 개인투약이력 조회 기능 추가  (도움말 참조 : <a href="https://nixpen5doc.pointnix.com/docs/main13/sub22/page3">https://nixpen5doc.pointnix.com/docs/main13/sub22/page3</a>)
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.처방창 화면 참조
2) 수가코드 항목 Right Click - [내가 먹는 약 조회] 메뉴 Click
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 수가정보 소절개 처방옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기본자료.수가정보 화면 참조
2) 수가정보 조회 후 상세정보.[처방옵션] 버튼 Click
3) DRG 세부분류 선택 (소절개, 복강경)
4) 처방창에 해당 수가 입력 후, 속성창에서 확인할 수 있습니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 영상비교창 Resize 기능 추가

<span class="box chart">진료</span> - 화면설정 인적정보 간단히보기 메뉴명 변경    
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료의 [화면설정] 메뉴 Click
2-1) 변경 전 : 인적정보 간단히보기
2-2) 변경 후 : 차트정보 간단히보기
</th>
    </tr>
</table>
<span class="box chart">진료</span>  - 계산창 수납 상태를 변경할 수 없습니다 메시지 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료의 [저장] 버튼 Click - 계산창 참조
2) 수납 완료 차트인 경우 [출력] 또는 [진료완료] 버튼 Click 시 메시지 내용 변경
3-1) 변경 전 : 수납 완료된 진료기록입니다. 상태를 변경할 수 없습니다
3-2) 변경 후 : 수납이 완료된 기록입니다. 수납이 변경되지 않습니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 판독소견서 모음장 클래식 화면 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료의 [진료메모] 탭 Click - [판독소견서] 버튼 Click 하여 표시된 화면 참조
2) [모음장] 탭 Click - [...] 버튼 Click - [클래식] 메뉴 Click
</th>
    </tr>
</table>
<span class="box chart">진료</span>  - 탭컨트롤 크게 보기 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료의 [화면설정] 메뉴 Click - [탭 컨트롤 크게보기] Click
2) 선택 시  탭 크기 증가, 탭 명칭 굵게 표시
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 병명 슬립지에서 클릭했을 때 R/O 따라가도록
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료의 [전처방] 탭 참조
2) 상병 Click - 선택된 상병의 배제진단 여부를 유지하여 상병 입력
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 외래진료.대기자 환자 호출시 감염병조회 표시
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료의 [대기] 탭 참조
2) 사용자설정.DUR 의 [외래진료 특정질병조회] 항목 선택
3) 대기자 Double Click 시 감염병 조회 기능 동작
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 수가검색창 메모리 증가   bug  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수가검색 창 반복 팝업 시 프로그램이 종료될 수 있는 증상 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 문제의약품 분리청구 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 상단 [속성] 버튼 참조
2) 문제의약품 특정내역(MT059)을 수록한 후 속성창의 [분리청구] 항목 선택
3) 분리청구된 내역은 청구 시 별도의 명세서로 생성됩니다.
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 직원정보 새로입력시 역할및권한 기본 생성
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.직원정보에서 새 직원 정보 입력 후 [저장] 버튼 Click
2) 면허구분을 기준으로 권한 사용자 자동 등록
2-1) 권한.의사 - 면허.의사
2-2) 권한.간호자 - 면허.간호사, 면허.간호조무사
2-3) 권한.원무 - 면허.방사선사, 면허.임상병리사, 면허.물리치료사, 면허.약사
2-4) 권한.일반사용자 - 면허.영양사, 면허.조리사, 면허.사회복지사, 면허.코디네이터
</th>
    </tr>
</table>

<span class="box other">통계</span> - 기간별처방통계 자동수가 집계 방법 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.기간별처방통계 화면 참조
2) 자동 수가인 경우 청구코드를 기준으로 집계
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 병명 검색창 포커싱 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 서류발급.진단서 화면 참조
2-1) 상병명 [한글] 선택된 경우 [..] 버튼 Click 시 상병검색 창의 한글명칭 항목에 기본 커서 위치
2-2) 상병명 [영문] 선택된 경우 [..] 버튼 Click 시 상병검색 창의 영문명칭 항목에 기본 커서 위치
</th>
    </tr>
</table>
<span class="box diag">진단서</span> - 진단서 발행리스트 정렬 동작  bug  
<span class="box diag">진단서</span> - 신체검사용 채용 신체검사서 기관명 출력   bug  


<span class="box lab">검사실</span> - 대기목록 검색기간 검색기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실의 [대기자] 탭 참조
2) 검색 시작일자, 종료일자 검색 조건 추가
3) 대기자 내역에 [검사일자] 항목 추가
</th>
    </tr>
</table>
<span class="box lab">방사선실</span> - 코드관리 검색 동작   bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 방사선실의 [방사선 관리] 메뉴 Click - [방사선실 코드관리] 메뉴 참조
2) 방사선실 코드 그룹 검색 동작 패치
</th>
    </tr>
</table>

<span class="box other">[고시]</span> 청구SW 보안인증 갱신 및 승인번호 적용

<span class="box other">[LabViewer]</span> 좌우검사 결과지 일자별 출력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[좌우검사] 탭, 외래진료.[좌우검사] 탭, LabViewer.[EyeView] 탭 참조
2) 좌우검사 결과 Right Click - [좌우검사 결과지 일자별 출력(A4)] 메뉴 Click
3) 좌우검사 출력 창에서 대상 일자 선택 후 [출력] 버튼 Click
</th>
    </tr>
</table>

<bold># 6/3 배포</bold>
=====================
<span class="box jemu">원무</span> - 대기자콜 간헐적으로 멈춤 증상 bug


<span class="box inspect">심사</span> - 특정내역 JT005(분만) 수록 방법 변경


<span class="box other">[고시]</span> 2022년 6월 수가 등록 (자동 실행)
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 적용일자 : 2022-06-06
</th>
    </tr>
<tr>
<th style=" border-spacing: 5px; font-weight: normal">2) 신설
   AH077   코로나19 통합 격리관리료-중증 면역저하자-병원
   AH087   코로나19 다인실 격리관리료-병원-1인 격리
   AH088   코로나19 다인실 격리관리료-병원-2인 격리
</th>
    </tr>
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">3) 변경  
   AH038   코로나19 감염병전담요양병원 감염예방·관리료(확진자)
   AH054   코로나19 통합 격리관리료-요양병원
   AH065   감염병전담정신병원 감염예방·관리료-확진환자
   AH225   재택치료 환자관리료-병원
   AH226   재택치료 환자관리료-의원
</th>
    </tr>
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">4) 적용기간 연장
   AH270   재택치료 전화상담·처방형 전화상담 관리료-초진-병원
   AH271   재택치료 전화상담·처방형 전화상담 관리료-초진-의원
   AH272   재택치료 전화상담·처방형 전화상담 관리료-재진-병원
   AH273   재택치료 전화상담·처방형 전화상담 관리료-재진-의원
   AH274   재택치료 의료상담센터형 전화상담 관리료-초진-병원
   AH275   재택치료 의료상담센터형 전화상담 관리료-초진-의원
   AH276   재택치료 의료상담센터형 전화상담 관리료-재진-병원
   AH277   재택치료 의료상담센터형 전화상담 관리료-재진-의원
</th>
    </tr>
</table>

<bold># 6/2 배포</bold>
===================== 
<span class="box jemu">원무</span> - 납입영수증의 총액 항목이 진료비내역서과 불일치   bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 총액, 공단부담액 항목을 영수증과 동일하게 출력
2) 소득공제대상액 항목에 실 수납액을 변경없이 반영
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 원외처방전출력 재발행  동작   bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.출력버튼.원외처방전출력 화면 참조
2) 재발행 항목 체크후 출력시 처방전 상단에  '[재발행]' 표시
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 환불영수증 메모 기재 방법 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료비환불건 영수증출력시 요양기관 임의활용공간에 상세내역 출력
2) 진료비환불금액, 진료비 정산금액, 정산후납부금액 출력
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 모음장 우클릭 동작 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.P/I 모음장탭 참조
2) 모음장 내역을 Click 시 처방창에 증상으로 수록됩니다.
3) 모음장 내역을 RightClick 시 처방창의 선택된 증상에 텍스트가 더해집니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - [진료정보교류] 의료기관선택 조회 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.내역조회.진료정보교류실행 메뉴 참조
2) 기관명 검색시 진료정보교류 대상 병원만 조회
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 차트유실경고 bug 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 차트 기록이 발생하지 않은 상태에서 차트 유실경고 알림이 뜨지 않는 증상 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - IA 청구코드 라이브러리에서 등록시 항목  bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수가정보 라이브러리탭 참조
2) IA101 등 수가를 라이브러리에서 추가시 '응급및회송료' 항목으로 수록
</th>
    </tr>
</table>

</pre>
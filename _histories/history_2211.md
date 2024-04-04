---
title: 2022년 11월 업데이트 히스토리
menuTitle: 2022년 11월
historyHome: 0
yearMonth: 2211
---

<pre>

<bold># 11/30 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 12월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 12월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 12월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 11/24 배포</bold>
=====================
<span class="box jemu">원무</span> - 제약회사별 처방 통계 전체 출력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[제약회사별처방통계] 화면 참조
2) 출력 대상을 선택할 수 있는 항목 추가

<a href="/images{{page.url}}/4.png" target="_blank"><img src="/images{{page.url}}/4.png" alt=""></a><br/>[ 제약회사별 처방 통계 전체 출력 메뉴 화면 ]
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 접수일자와 서버일자가 다를 경우 확인 메시지 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 참조
2) 환자 불러오기 후 [접수] 버튼 Click
3) 접수 확인 창에서 [접수] 버튼 Click 시 서버 일자와 비교
4) 서버 일자와 불일치하는 경우 '접수일자가 오늘이 아닙니다. 계속하시겠습니까?' 메시지 팝업
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료대기창에 예약 표시룰 변경 (과 기준 예약존재 시 컬러 표시)
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료대기] 탭 참조
2) A 진료과에 예약 및 접수한 환자가 B 진료과에 예약 없이 접수한 경우
    - 변경 전 : A, B 접수 건 모두 예약 글자색 표시
    - 변경 후 : A 접수 건만 예약 글자색 표시
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 예진실변경 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료대기] 탭 참조
2) 대기자의 [상태] 항목 값 Right Click 시 [예진실] 목록 메뉴 팝업
3) [예진실] 변경 후 [상태] 항목 표시 확인
4) 외래진료.[대기] 탭의 [상태] 항목에도 동일 표시

<a href="/images{{page.url}}/5.png" target="_blank"><img src="/images{{page.url}}/5.png" alt=""></a><br/>[ 외래접수 예진실변경 기능 화면 ]

<a href="/images{{page.url}}/6.png" target="_blank"><img src="/images{{page.url}}/6.png" alt=""></a><br/>[ 외래진료 예진실변경 기능 화면 ]
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 마약류 외국인 여권번호 미수록 오류
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 차트 불러오기 후 [저장] 버튼 Click
3) 계산 창의 [마약류 처방] 버튼 Click
4) 외국인 환자인 경우 투약 보고 시 여권번호 수록 오류 패치
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 영상 데이터 이동 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 영상 화면 참조
2) 환자 불러오기 후 [..] 버튼 Click - [차트번호 변경] 메뉴 선택
3) 영상 차트번호 변경 창에서 이동 대상 영상 선택 후 [차트번호 변경] 버튼 Click
4) 차트번호 변경 창에서 대상 환자 선택 후 [적용] 버튼 Click

<a href="/images{{page.url}}/7.png" target="_blank"><img src="/images{{page.url}}/7.png" alt=""></a><br/>[ 영상 차트번호 변경 메뉴 화면 ]
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 속성창 위탁진료 변경기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[수가속성] 화면 참조
2) [위탁기관] 항목 우측 [..] 버튼 Click
    - 수탁 전송 상태 :  '수탁전송된 건입니다. 수탁기관을 변경할 수 없습니다.' 메시지 팝업
    - 수탁 미전송 상태 : 수탁기관 선택 창 팝업
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 외래진료 예약탭 예약이행 상태별 컬러 구분 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[예약] 탭 참조
2) 예약 이행 상태인 경우 글자색 구분 표시
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 진료대기목록 툴팁에 보류시간 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[대기] 탭 참조
2) 대기자 목록 Mouse Over 시 진료보류 경과 시간 표시
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 특이증상 스크롤 위치 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[신상] 탭 참조
2) 환자 불러오기 시 특이증상 Scroll 을 맨 아래로 이동
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 요약창 해당월 보기 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[전처방] 화면 참조
2) 진료요약창 옵션.[해당 월 보기] 항목 선택 후 [저장] 버튼 Click
3) 외래진료.[청구] 탭에서 검색일자를 이전 달로 설정 후 [조회] 버튼 Click
4) 대상 진료 Double Click 하여 [전처방] 탭의 진료 요약 목록 확인
    - 옵션 설정 상태 : 불러온 차트 일자의 해당 월에 발생한 진료내역만 표시
    - 옵션 해제 상태 : 전체 진료내역 표시
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 방문간호지시서 서식 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 확인서.[방문간호지시서] 화면 참조
</th>
    </tr>
</table>
<span class="box diag">진단서</span> - 입퇴원확인서 진료과 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 확인서.[입퇴원확인서] 화면 참조
2) 새 작성 시 발행의사 기준 [진료과] 기본 선택 오류 패치
</th>
    </tr>
</table>
<span class="box diag">진단서</span> - 코로나19 신속항원검사 음성확인서 검사결과 변경기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 확인서.[코로나19 신속항원검사 음성확인서] 화면 참조
2) [검사결과] 항목 수정되도록 기능 변경

<a href="/images{{page.url}}/8.png" target="_blank"><img src="/images{{page.url}}/8.png" alt=""></a><br/>[ 코로나19 신속항원검사 음성확인서 서식 화면 ]
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 청구 사전점검 환자 갱신 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 보험청구 화면 참조
2) 명세서에서 사전점검 오류가 발생한 환자 Click
3) 사전점검 창이 열린 상태일경우 선택한 환자의 오류 내역으로 화면 갱신
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 보험청구 청구확인 명세서 컬럼 너비 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 보험청구 화면 참조
2) 명세서에서 [일련번호] 항목 너비 축소, [수진자] 및 [사전점검 오류 건수] 항목 너비 확대
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 가다실 백신 사용시 일반처리 예외 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[열기 및 저장] 화면 참조
2) 차트 저장 옵션.[백신만 발생 시 자동 일반 처리] 항목 선택 후 [저장] 버튼 Click
3) 외래진료 화면에서 환자 불러오기
4) [가다실] 백신만 처방 후 특정기호 F012 입력
5) F012 특정기호 입력된 경우, 차트 저장 옵션.[백신만 발생 시 자동 일반 처리] 가 설정되어 있어도 보험유형.[일반] 으로 적용하지 않음 처리 (예외)
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 원외처방 외용약 횟수적용안함 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[계산 및 산정] 화면 참조
2) 처방옵션.[원외처방 외용약 횟수적용 안함] 항목 선택 후 [저장] 버튼 Click
3) 외래진료, 보험청구의 [처방전 내역] 에 표시된 1회투약량 확인
    - 옵션 설정 상태 (기본) : 1회투약량 = 수량 / 1
    - 옵션 해제 상태 : 1회투약량 = 수량 / 횟수
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 직원 새로입력시 주사용메뉴 기본값 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.[직원정보] 화면 참조
2) 직원 추가 시 면허구분에 따라 주사용메뉴 기본 등록
    - 면허구분.[의사] : 외래진료
    - 면허구분.[방사선사] : 방사선실
    - 면허구분.[물리치료사] : 물리치료실
    - 면허구분.[임상병리사] : 검사실
    - 외 면허구분 : 외래접수
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 의사 등록시 도장 자동 등록 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.[직원정보] 화면 참조
2) 직원 추가 시 면허구분.[의사] 인 경우 처방전 도장 기본 등록
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 차트 삭제 암호기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.[암호관리] 화면 참조
2) 기능명.[차트삭제] 의 암호 입력 후 [저장] 버튼 Click
3) 외래진료 화면에서 차트 불러오기
4) [삭제] 버튼 Click 시 암호 확인 창 팝업
5) 사용자에게 암호 관리자 권한이 필요하며, 기준정보.[역할 및 권한] 에서 등록 가능
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 환경설정 검색결과 표시 방법 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정 창 참조
2) 검색어 입력 후 Enter
3) 우측 검사 결과 영역에 검색어에 해당되지 않는 옵션 보이지 않음 처리 (숨김)
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 방사선 단순촬영 명세서메모 누락 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 환자 불러오기 후 방사선 단순촬영 동일 수가 중복 처방
3) 수가에 서로 다른 특정내역 입력 후 청구 시 미수록 오류 패치
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 심사속도 개선
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) DUR 옵션에 따라 발생할 수 있는 속도 저하 문제 패치
</th>
    </tr>
</table>

<span class="box lab">검사실</span> - 검사코드 직접 입력한 경우 검사결과지 그룹별 정렬 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실 화면 참조
2) 환자 불러오기 후 우측 [..] 버튼 Click - [검사결과지 출력] 메뉴 선택
3) 검사결과지 출력 창에서 조건 설정 후 [출력] 버튼 Click
4) 직접 입력한 검사실 코드인 경우 검사그룹 순으로 표시
</th>
    </tr>
</table>

<span class="box other">통계</span> - 월별청구통계 동일 청구유형 일괄 미송신 변경 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 청구통계.[월별청구통계] 화면 참조
2) [검색] 버튼 Click 후 통계 내역에서 Right Click - [동일 청구유형 일괄 미송신 변경] 메뉴 선택
3) 청구년월, 청구유형, 청구구분을 기준으로 마지막 1건을 제외하고 일괄 미송신으로 변경
</th>
    </tr>
</table>
<span class="box other">[SmartCheck]</span> 진료실 사전점검창에서 필요상병 입력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 차트 불러오기 후 [저장] 버튼 Click
3) 계산 창의 [사전점검] 버튼 Click
4) 사전점검 창 하단의 [필요상병] 탭 목록 Double Click 시 차트에 대상 상병 입력

<a href="/images{{page.url}}/9.png" target="_blank"><img src="/images{{page.url}}/9.png" alt=""></a><br/>[ [SmartCheck] 진료실 사전점검창에서 필요상병 입력 화면 ]
</th>
    </tr>
</table>
<span class="box other">[WaitCall]</span> 예진실 지원
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[진료과/의사] 화면 참조
2) [의사/예진실] 항목 우측 [돋보기] 아이콘 버튼 Click
3) 의사/예진실 선택 창에서 [예진실] 항목 선택 후 [확인] 버튼 Click
4) [저장] 버튼 Click 후 대기자콜 재실행
5) 차트 프로그램에서 예진실 변경 시 대기자콜에 대상 환자 표시

<a href="/images{{page.url}}/10.png" target="_blank"><img src="/images{{page.url}}/10.png" alt=""></a><br/>[ [WaitCall] 예진실 표시 화면 ]
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> 2023년 점수당단가 / 공휴일


<bold># 11/10 배포</bold>
=====================
<span class="box chart">진료</span> - 수납대기 목록에 0원 수납 표시 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[진료업무] 화면 참조
2) 보기옵션.[수납대기 목록에 0원 수납 표시] 항목 선택 후 [저장] 버튼 Click
3) 외래진료.[수납] 탭의 환자 목록 확인
    - 설정 상태 : 0원 수납 환자 표시
    - 설정 해제 : 0원 수납 환자 미표시
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 영문예방접종증명서2 양식변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 증명서.[영문예방접종증명서2] 화면 참조
2) 상단 문구 변경 및 백신 아래 줄 선 표시
</th>
    </tr>
</table>

<span class="box other">통계</span> - 진료통계.기간별처방통계 주상병 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[기간 별 처방 통계] 탭 참조
2) [주상병명] 항목 추가
    - 변경 전 : [진료과], [진료의], [차트번호] .. [보험유형]
    - 변경 후 : [진료과], [진료의], [차트번호] .. [보험유형], [주상병코드], [주상병명]
</th>
    </tr>
</table>
<span class="box other">통계</span> - 내원경로별환자현황 통계 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 인원통계.[내원경로 별 환자 현황] 탭 참조
</th>
    </tr>
</table>
<span class="box other">통계</span> - 기간별처방통계 투여량 오류 bug  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[기간 별 처방 통계] 탭 참조
2) 퇴장방지 의약품인 경우 [투여량] 항목이 증가되어 표시되는 오류 패치
</th>
    </tr>
</table>

<span class="box lab">방사선실</span> - 메디컬스탠다스 ResOrderTab방식 PACS 오더 취소 오류 패치
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[전처방] 탭 참조
2) 오더 취소 시 PACS Cancel Order 수록 규칙 변경
</th>
    </tr>
</table>

<span class="box other">[KIOSK 5.0]</span> 수납 후 세부산정내역서 출력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[기본] 화면 참조
2) 수납 옵션의 [수납 후 진료비 세부산정내역서 출력], [진료비 세부산정내역서 출력여부 확인] 항목 선택 후 [저장] 버튼 Click
3) 진료비 수납 후 [진료비 세부산정내역서] 출력물 선택

<a href="/images{{page.url}}/1.png" target="_blank"><img src="/images{{page.url}}/1.png" alt=""></a><br/>[ 진료비 세부산정내역서 선택 화면 ]

<a href="/images{{page.url}}/2.png" target="_blank"><img src="/images{{page.url}}/2.png" alt=""></a><br/>[ 진료비 세부산정내역서 출력물 화면 ]
</th>
    </tr>
</table>

<span class="box other">[NTalk]</span> 원내 메신저 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[N Talk 설정] 화면에서 [사용] 항목 선택 및 파일 업로드 경로 지정 후 [저장] 버튼 Click
2) 로컬설정.[기본] 화면에서 [내부 네트워크 IP] 항목 입력 후 [저장] 버튼 Click
3) 로컬설정.[N Talk 설정] 화면에서 [프로그램 시작 시 자동 실행] 항목 선택 후 [저장] 버튼 Click
4) 프로그램 재실행하여 NTalk 화면 확인
<a href="/images{{page.url}}/3.png" target="_blank"><img src="/images{{page.url}}/3.png" alt=""></a>
[ NTalk 메신저 화면 ]
</th>
    </tr>
</table>

<bold># 11/08 배포</bold>
===================== 
<span class="box notice">[고시]</span> 2022년 11월 2차 약가 등록 (자동 실행) 


<bold># 11/03 배포</bold>
===================== 
<span class="box jemu">원무</span> - 재접수시 확인창
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면에서 환자 불러오기 후 [접수] 버튼 Click
2) 접수창에서 [접수] 버튼 Click
3) 동일한 의사로 접수한 건이 존재하는 경우 재접수 진행 확인 창 팝업
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 접수구분 검진연동시 일반적용 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[접수] 화면 참조
2) 초재진.[접수구분 검진 연동 시 일반 적용] 항목 선택 후 [저장] 버튼 Click
3) 외래접수 화면에서 환자 불러오기 후 [접수] 버튼 Click
4) 접수창에서 [검진연동] 에 해당하는 접수구분을 선택 시 보험유형.[일반] 자동 선택
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 대기자를 보류로 변경 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료대기] 탭 참조
2) 대기 목록 Right Click 하여 [진료진행상태 변경] 메뉴 선택
    - 진료 보류 상태 : [진료대기] 상태로 변경하는 메뉴 표시
    - 진료 대기 상태 : [진료보류] 상태로 변경하는 메뉴 표시
</th>
    </tr>
</table>

<span class="box chart">진료</span> - '-전체-' 선택한 상태에서 묶음 편집 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[Rt] 화면 참조
2) [진료과] 또는 [의사] 항목이 '전체' 로 선택되어 있는 경우 묶음 편집 오류 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 요일반검사 체크시 서비스 제외
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 본인부담구분.[서비스] 가 아닌 수가를 기준으로 요일반검사 적용하도록 기능 변경
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 인슐린 원외주사 처방 시 총처방일수 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 인슐린 원외처방일수가 총처방일수에 반영되도록 오류 패치
</th>
    </tr>
</table>

</pre>
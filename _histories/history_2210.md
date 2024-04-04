---
title: 2022년 10월 업데이트 히스토리
menuTitle: 2022년 10월
historyHome: 0
yearMonth: 2210
---

<pre>

<bold># 10/31 배포</bold>
==================== 
<span class="box lab">검사실</span> - 바코드 순서번호 출력 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실 화면 참조
2) 상단 [검사관리] 버튼 Click 후 [라벨 출력 설정] 메뉴 선택
3) 검사 라벨출력 설정 창에서 [순서] 출력 항목 선택 후 [저장] 버튼 Click
4) 환자 불러오기 후 [라벨 출력] 버튼 Click
5) 검사 라벨지 우측 하단의 [오더순서] 확인
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 엑셀내보내기 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실 화면 참조
2) 상단 [검사관리] 버튼 Click 후 [검사실코드 관리] 메뉴 선택
3) 검사실 코드 그룹 목록 우측 [...] 버튼 Click 후 [엑셀 내보내기] 메뉴 선택
4) [그룹코드] 항목 추가 확인
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 바코드매수 자동 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검사실 화면 참조
2) 환자 불러오기 후 출력매수.[자동] 항목 선택 - [라벨 출력] 버튼 Click
3) 오더그룹 개수 기준 검사 라벨지 출력
4) 재출력 또는 오더그룹 부재 시 기본 1매 출력
</th>
    </tr>
</table>
<span class="box lab">방사선실</span> - PACS 명칭 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[PACS] 화면 참조
2) 명칭 옵션.[기본 명칭 형식] 항목 추가
    - 기존 항목 : 수가명_촬영방법
    - 추가된 항목 : 그룹명_오더명_촬영방법
3) 명칭 옵션.[US, ES 명칭 형식] 항목 추가
    - 기존 항목 : 수가명_수가코드_촬영방법, 수가코드_수가명_촬영방법
    - 추가된 항목 : 그룹명_오더명_촬영방법
</th>
    </tr>
</table>
<span class="box other">인터페이스</span> - 메디컬스탠다스 ResOrderTab방식 PACS 인터페이스

<span class="box notice">[고시]</span> 2022년 11월 수가 등록 (자동 실행) 
<span class="box notice">[고시]</span> 2022년 11월 약가 등록 (자동 실행) 
<span class="box notice">[고시]</span> 2022년 11월 치료재료툴 (바로가기.공지사항.미설치툴 참조) 


<bold># 10/19</bold>
=====================
<span class="box jemu">원무</span> - 영수증에 카드번호, 승인번호 출력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래수납 화면 참조
2) 환자 불러오기 후 [수납내역] 탭에서 카드 단말기 승인 요청이 발생한 대상 수납 Double Click
3) [영수증] 버튼 Click 후 외래 진료비 계산서·영수증 창에서 [출력] 버튼 Click
4) [요양기관 임의활용공간] 항목에 카드 결제 정보(카드번호, 승인번호) 표시

<a href="/images{{page.url}}/1.png" target="_blank"><img src="/images{{page.url}}/1.png" alt=""></a>[ 카드번호가 출력된 영수증 화면 ]
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 미수차감 할인 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[수납] 화면 참조
2) 감면구분 사용여부.[수납] 항목 선택 후 [저장] 버튼 Click
3) 외래수납 화면에서 환자 불러오기
4) [...] 버튼 Click 후 [미수 차감] 메뉴 Click
5) 미수차감 창에서 대상 수납 선택 후 [확인] 버튼 Click
6) 수납상세 창에서 [감면구분] 및 [할인금액] 항목 입력
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 입원 납입확인서 외래로 표시되는 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 참조
2) 환자 불러오기 후 [출력] 버튼 Click - [진료비 납입 확인서] 메뉴 Click
3) 납입확인서 창 내역에 입원이 아닌 외래로 표시되는 오류 패치
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 미수추가 보험유형 선택기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래수납 화면 참조
2) [...] 버튼 Click 후 [미수 추가] 메뉴 Click
3) 미수 추가 창에 [보험유형] 항목 추가
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - DRG 세부산정내역서 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) DRG 화면 참조
2) 환자 불러오기 후 [...] 버튼 Click - [진료비세부산정내역서 출력] 메뉴 Click
3) DRG 세부산정내역 출력물 확인
4) 외래접수 화면 참조
5) 환자 불러오기 후 [출력] 버튼 Click - [진료비내역서 출력] 메뉴 Click
6) DRG 세부산정내역 발행 목록 확인

<a href="/images{{page.url}}/2.png" target="_blank"><img src="/images{{page.url}}/2.png" alt=""></a>[ DRG 진료비세부산정내역서 출력물 화면 ]
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 전처방 작은그림 위치 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[전처방] 화면 참조
    - 변경 전 : [병명], [처방], [작은그림(영상)]
    - 변경 후 : [병명], [작은그림(영상)], [처방]
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 특이증상 스크롤 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[증상 및 특이증상] 탭 참조
2) 증상/특이증상 기본 입력 옵션.[빈 줄 추가] 항목 선택 후 저장 버튼 Click
3) 외래진료 화면에서 환자 불러오기 시 증상/특이증상 내용에 여러 줄의 공백 추가 (스크롤 표시)
4) 필요 시 스크롤하여 증상/특이증상 내용을 가릴 수 있음
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 영문처방전 서식 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 확인서.[영문처방전] 화면 참조

<a href="/images{{page.url}}/3.png" target="_blank"><img src="/images{{page.url}}/3.png" alt=""></a>[ 영문처방전 출력물 화면 ]
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 고유식별번호보유량 외국인 보유량 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 관리자.[고유식별번호 보유량] 탭 참조
2) [외국인 주민번호 보유량] 항목 확인
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 만성질환상병 초재진구분 자동 등록 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기본자료.[상병정보] 탭 참조
2) 만성질환 상병 불러온 후 [초재진구분] 항목 확인
3) 차트 실행 시 만성질환 상병인 경우 [초재진구분] 자동 등록
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 조제시 참고사항에 특정기호 출력 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 특정기호 선택 시 계산창.[조제시 참고사항] 항목에 특정기호 표시
3) 특정기호 제거 후 재저장 시 계산창.[조제시 참고사항] 항목에 특정기호가 표시되는 오류 패치
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 수납대상액 변경 허용 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[수납] 화면 참조
2) 진료실 수납 옵션.[수납대상액 변경 허용] 항목 선택 후 [저장] 버튼 Click
3) 외래진료 화면에서 차트 불러오기
    - 선택 상태 : 계산창.[수납대상액] 변경 가능
    - 선택 해제 상태 : 계산창.[수납대상액] 변경 불가
4) 기본값은 수납대상액 변경 허용임
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 청구심사 삭제 환자 심사 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 심사 화면 참조
2) 삭제한 환자의 진료가 심사 점검되는 오류 패치
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 청구자료 가져오기 로그 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 보험청구 화면 참조
2) 상단 [청구자료 가져오기] 버튼 Click
3) 대상 청구 자료 조건 설정 후 [가져오기] 버튼 Click 시 Log 상세히 기록
    - 변경 전 : [진료정보]
    - 변경 후 : [청구대상], [진료정보]
</th>
    </tr>
</table>

<span class="box lab">검사실</span> - 검사결과에 그룹명표시 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[실시부서] 화면 참조
2) 검사항목 보기 옵션 중 [검사결과에 그룹명 표시] 항목 선택 후 [저장] 버튼 Click
3) 검사결과 화면 내 항목 명칭 표시 변경
    - 선택 상태 : [검사그룹명]>[검사명]
    - 선택 해제 상태 : [검사명]
4) 검사결과지 표시 변경

<a href="/images{{page.url}}/4.png" target="_blank"><img src="/images{{page.url}}/4.png" alt=""></a>[ 검사결과에 그룹명 표시 설정 후 오더창 화면 ]

<a href="/images{{page.url}}/5.png" target="_blank"><img src="/images{{page.url}}/5.png" alt=""></a>[ 검사결과에 그룹명 표시 설정 후 오더창 화면 ]

<a href="/images{{page.url}}/6.png" target="_blank"><img src="/images{{page.url}}/6.png" alt=""></a>[ 검사결과에 그룹명 표시 설정 후 오더창 화면 ]
</th>
    </tr>
</table>

<span class="box other">[Interface]</span> - 아름누리 연동 기능 추가


<bold># 10/7 배포</bold>
=====================
<span class="box other">[Interface]</span> NixPen 5.0 외래 서비스 API V2.0 (일부 병원만 해당됩니다.)

</pre>

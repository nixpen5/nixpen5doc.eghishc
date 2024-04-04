---
title: 2022년 8월 업데이트 히스토리
menuTitle: 2022년 8월
historyHome: 0
yearMonth: 2208
---

<pre>

<bold># 8/31 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 9월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 9월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 9월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 8/25 배포</bold>
=====================
<span class="box jemu">원무</span> - 입원 현금영수증 승인 동작 변경
<span class="box jemu">원무</span> - 수납대장 클래식 SQL 출력 기능 추가
<span class="box inspect">심사</span> - 낮병동 특정내역창에서 입원일자 기본 수록


<bold># 8/18 배포</bold>
=====================
<span class="box chart">진료</span> - 수가정보 산정기준 기준일수 점검 동작 bug 패치


<bold># 8/17 배포</bold>
=====================
<span class="box chart">진료</span> - U07.1 상병 사용시 처방전 조제시 참고사항에 코로나19 출력 기능 추가
<span class="box other">[KIOSK 5.0]</span> - 키오스크에서 SRP770 접수증 출력 기능 추가


<bold># 8/4 배포</bold>
=====================
<span class="box jemu">원무</span> - 외래접수시 DRG 산정구분 적용룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 참조
2) DRG 입원 기록이 존재하는 환자를 불러온 후 [접수] 버튼 Click
3) 외래진료.[신상] 탭의 [산정구분] 항목 확인
    - 변경 전 : 산정구분.[DRG] 선택 상태
    - 변경 후 : 산정구분 미선택 상태
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 접수시 선택기관 타병원 선택 환자 알림 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 참조
2) 자격조회.[선택기관 타병원] 이용에 해당하는 환자를 불러온 후 [접수] 버튼 Click
3) 접수확인 창 팝업 시 '선택기관, 타병원 선택 환자입니다.' 메시지 알림
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 접수 시 자격조회 미수행 알림 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[접수] 화면 참조
2) 점검 옵션.[접수 시 자격조회 미수행 알림] 항목 선택 후 [저장] 버튼 Click
3) 외래접수 화면에서 자격조회 수행하지 않은 환자를 불러온 후 [접수] 버튼 Click
4) 접수확인 창에서 보험유형.[일반] 선택 후 [접수] 버튼 Click
5) '자격조회를 수행하지 않은 환자입니다. 보험 유형을 확인하세요. 보험유형을 일반으로 적용하시겠습니까?' 확인 창 팝업
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 환자성명 변경 후 저장시 확인 메시지 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 참조
2) 불러온 환자의 [환자성명] 변경 후 [저장] 버튼 Click
    - 변경 전 : 신상 정보 저장
    - 변경 후 : '환자성명이 변경되었습니다. 저장하시겠습니까?' 확인 메시지 팝업
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 차트출력 화면 표시 오류
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[차트출력] 창 참조
2) 차트 내역 항목명 표시줄이 간헐적으로 표시되지 않는 오류 패치
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료비 계산서ㆍ영수증 신서식 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[외래 진료비 계산서 영수증] 창 참조
2) [출력] 버튼 Click 하여 영수증 확인
3) 기존 선별급여, 포괄수가진료비, 선택진료료이외 항목텍스트 변경
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료확인번호승인탭에서 진료확인번호취소 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납대장.[진료확인번호승인] 탭 참조
2) 진료확인번호 승인 내역 Double Click
3) 승인 후 보험유형.[건강보험] 으로 변경된 경우 승인 취소 불가 오류 패치
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 수납마감 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 참조
2) [화면설정] 버튼 Click - [툴 버튼설정] 메뉴 선택
3) [수납마감] 버튼을 사용영역으로 Drag 한 후 [저장] 버튼 Click
4) 우측 상단 [수납마감] 버튼 Click
5) 수납 마감 창에서 대상 일자 선택 후 [수납마감/마감취소] 버튼 Click
6) [일괄 수납마감] 버튼 Click 시 일자 범위를 지정하여 일괄 [수납마감/마감취소] 적용 가능
7) [수납마감] 일자에서 수납 변경 불가 알림
    - 접수 : 수납 변경 불가 시 '수납마감된 일자입니다. 수납을 진행할 수 없습니다.' 메시지 알림
    - 진료 : 추가 수납 불가 시 '수납마감 상태입니다. 수납이 발생하지 않습니다.' 메시지 알림
8) 수납마감된 일자로 미수추가, 진료외수납, 선수수납 등 추가 수납 발생 불가
9) 수납관리자 권한이 필요하며, 기준정보.[역할및권한] 화면에서 설정 가능
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 특정내역 건수가 많은 차트 조회 속도 개선
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 특정내역 건수가 많은 환자 불러오기 시 속도 느림 이슈 패치
    - 변경 전 : 발생된 모든 특정내역 불러오기
    - 변경 후 : 진료일자 기준 직전 1년 간의 특정내역 불러오기
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 수술확인서 코드출력 항목 값 유지
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진단서.[수술확인서] 화면 참조
2) 상병내역 우측 상단 [(상병)코드출력] 항목 선택 상태 유지
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 외래진료 수납탭 재접수 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[수납] 탭 참조
2) 수납 내역 Right Click - [재접수] 메뉴 클릭
3) 외래진료.[대기] 탭에서 재접수 내역 확인
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 묶음처방 우클릭으로 처방 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[Rt] 탭 참조
2) 묶음처방의 [코드] 항목에서 Right Click
    - 변경 전 : 메뉴 팝업 (묶음처방 편집/추가)
    - 변경 후 : 진료중 차트에 접힘 상태로 처방
3) 묶음처방 편집 시에는 [명칭] 항목에서 Right Click
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 정보성 처방점검 알림 옵션과 상관없이 심사시 정보성 오류 점검
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 차트 저장 전 점검 옵션.[정보성 처방점검 알림] 항목 선택 해제
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 상병정보 청구제외 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기초정보.[상병정보] 화면 참조
2) 코드정보.[청구제외] 항목 선택 후 [저장] 버튼 Click
3) [상병코드 일괄적용] 버튼 Click 시 동일 상병코드에 일괄 [청구제외] 적용 가능
4) 청구 시 제외 상병코드 확인
    - 청구제외 상병이 '주상병' 인 경우 : 청구제외 하지 않은 부상병을 '주상병' 으로 적용
    - 청구제외 상병에 '특정기호' 가 적용된 경우 : 청구 포함
5) 청구제외 상병 일괄 확인
    - 우측하단 상병검색창에서 [...] 더보기 버튼 Click
    - [청구제외상병 불러오기] 메뉴 Click
    - 청구제외 상병 일괄 확인
</th>
    </tr>
</table>

<span class="box other">통계</span> - 환자별사용량통계 클릭시 외래진료 차트로 이동 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[환자별사용량통계] 탭 참조
2) 환자 목록 Double Click 하여 해당 진료 차트로 이동
</th>
    </tr>
</table>
<span class="box other">통계</span> - 검색조건에 퇴사자 포함 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[(통계)기본] 화면 참조
2) [검색조건에 퇴사자 포함] 항목 선택 [저장] 버튼 Click
3) 통계화면의 검색조건.[진료과] 목록 확인
    - 선택해제 상태 : 퇴사자 기준 검색 불가
    - 선택 상태 : 퇴사자 기준 통계 검색 가능
</th>
    </tr>
</table>

<span class="box other">[Scan]</span> 최근추가목록 조회건수별 정렬 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) [파일등록] 탭 참조
2) [최근 추가 목록] 의 영상 정렬 방식 변경
    - 변경 전 : 등록일자 순
    - 변경 후 : 등록일자 역순 (최근일자 영상을 먼저 표시)
</th>
    </tr>
</table>

<span class="box notice">[고시]</span> 재택치료 의료상담센터형 전화상담 관리료-야간·공휴 및 의원급 토요일 진료 수가 신설
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 의료상담센터 운영기관 대상 [야간·공휴 및 의원급 토요일] 전화상담 관리료 추가
    - 병원, 정신병원. 요양병원·한방병원·치과병원 내 의과 : AH266
    - 의원, 보건의료원 내 의과 : AH267
2) AH266, AH267 : 환자 본인부담금 면제 (전액 공단 부담)
3) 조제 시 참고 사항에 [코로나19확진] 수록
</th>
    </tr>
</table>

<bold># 8/1 배포</bold>
=====================
<span class="box notice">[고시]</span> 재택치료(AH270~AH277) 8월 1일 이후 본인부담 면제


</pre>
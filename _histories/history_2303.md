---
title: 2023년 3월 업데이트 히스토리
menuTitle: 2023년 3월
historyHome: 0
yearMonth: 2303
---

<pre>

<bold># 3/31 배포</bold>
=====================
<span class="box notice">[고시]</span> 2023년 4월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2023년 4월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2023년 4월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 3/30 배포</bold>
=====================
<span class="box jemu">원무</span> - 미수금발생내역조회창에서 수납자 검색 조건 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납대장.[미수금발생내역조회] 탭 참조
2) 검색조건.[수납자] 항목 추가
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 마감장 수납자 다중 선택 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납대장.[마감장] 탭 참조
2) 검색조건.[수납자] 항목 다건 선택 가능하도록 기능 변경
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 전달메모 삭제기능
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 전달메모 창 참조
2) 메모 우측 상단 [작성자명] 추가 표시
3) 모든 사용자가 메모 삭제 가능하도록 기능 변경
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래수납 0원수납 일괄수납 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[수납대기] 탭 참조
2) 대기자 Right Click - [수납대상액 0원 일괄 수납] 메뉴 선택
3) 진료비총액이 발생하지 않은 0원 수납 건만 수납 처리
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 똑닥 이중접수 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료대기] 탭 참조
2) 동일한 똑닥 접수 건이 중복 생성될 수 있는 오류 패치
</th>
    </tr>
</table>

<span class="box chart">진료</span> - DUR 병용금기 점검결과가 정보성일경우 사유 입력 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) DUR 점검 결과 창 참조
2) 병용금기 의약품 점검 결과 확인 후 [확인] 버튼 Click
3) 정보성 점검인 경우 사유 입력 생략
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 수가검색창에서 포커싱 위치가 일정하지 않는 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 약수가 검색 창 참조
2) 간헐적으로 검색조건.[청구코드] 에 포커싱되는 오류 패치
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 특정상병환자조회창 상병범위 지정 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 특정상병 환자 조회 창 참조
2) 상병 범위를 지정할 수 있도록 검색 조건에 [상병시작코드], [상병종료코드] 항목 추가

<a href="/images{{page.url}}/10.jpg" target="_blank"><img src="/images{{page.url}}/10.jpg" alt=""></a><br/>[ 특정상병환자조회창 화면 ]
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 특정상병환자조회창 조회결과에 특정내역 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 특정상병 환자 조회 창 참조
2) 상병 별 환자 검색 결과에 [특정내역] 항목 추가
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - IA101 특정내역 미수록
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 청구 확인 창 참조
2) 의뢰수가(예. IA101)에 대한 특정내역이 발생되지 않는 오류 패치
</th>
    </tr>
</table>

<span class="box other">통계</span> - 항목별진료실적통계 초음파 검색 오류
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수입통계.[항목별 진료실적 통계 - 진료의] 탭 참조
2) 검색 결과에 초음파수가(예. EB401)가 집계되지 않는 오류 패치
</th>
    </tr>
</table>

<span class="box other">WaitCall</span> - 진료실 3개 템플릿 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[템플릿] 탭 참조
2) [13. 진료실x3 (미디어 없음)] 템플릿 선택 후 [저장] 버튼 Click
3) 대기자콜 재실행

<a href="/images{{page.url}}/11.png" target="_blank"><img src="/images{{page.url}}/11.png" alt=""></a><br/>[ 진료실 3개 템플릿 추가 화면 ]
</th>
    </tr>
</table>
<span class="box other">WaitCall</span> - 진료실 4개 템플릿 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[템플릿] 탭 참조
2) [14. 진료실x4 (미디어 없음)] 템플릿 선택 후 [저장] 버튼 Click
3) 대기자콜 재실행

<a href="/images{{page.url}}/12.png" target="_blank"><img src="/images{{page.url}}/12.png" alt=""></a><br/>[ 진료실 4개 템플릿 추가 화면 ]
</th>
    </tr>
</table>
<span class="box other">WaitCall</span> - 진료실 1개 DID 템플릿 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[템플릿] 탭 참조
2) [10. 하단 2열 진료실x1] 템플릿 선택 후 [저장] 버튼 Click
3) 대기자콜 재실행

<a href="/images{{page.url}}/13.png" target="_blank"><img src="/images{{page.url}}/13.png" alt=""></a><br/>[ 진료실 1개 DID 템플릿 추가 화면 ]
</th>
    </tr>
</table>


<bold># 3/7 배포</bold>
=====================
<span class="box jemu">원무</span> - 예약창 전화예약 우클릭 접수 메뉴 동작 bug 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 예약 화면 참조
2) 전화 예약 건 Right Click - [접수(외래접수)] 메뉴 선택
3) 예약 정보 기준 신환 등록 후 외래접수 화면으로 이동
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 접수구분 항목 변경 ContextMenu 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.[접수구분] 화면 참조
2) 접수구분 등록 후 [저장] 버튼 Click
3) 외래접수.[진료대기] 탭 참조
4) 대기자 목록에서 [접수구분] 항목 Right Click 시 등록된 접수구분 목록 표시
5) 대상 [접수구분] 선택하여 변경 적용

<a href="/images{{page.url}}/1.png" target="_blank"><img src="/images{{page.url}}/1.png" alt=""></a><br/>[ 접수구분 항목 변경 메뉴 기능 추가 화면 ]
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 대기자표시 옵션중 나이 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[대기자] 화면 참조
2) 대기자표시.[나이(성별나이/생년월일)] 항목 선택 후 [저장] 버튼 Click
3) 외래접수.[진료대기] 탭 참조
4) 대기자 목록에서 [나이] 항목 표시 확인
	- [성별나이] 항목이 선택된 경우 : 예) 'F/59'
	- [생년월일] 항목이 선택된 경우 : 예) '1963년 1월 1일'
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 똑닥 모바일접수건 진료실 매핑 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.[직원정보] 화면 참조
2) 대상 의사의 똑닥정보.[진료실] 항목 선택 후 [저장] 버튼 Click
	- 참고 : 선택한 진료실은 다른 의사의 진료실과 중복될 수 없음
3) 환자가 똑닥에서 의사 선택 후 예약
4) 외래접수.[진료대기] 탭의 대기자 목록에서 [진료과], [진료의] 항목 확인
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 급여제한여부 내용 표시
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 급여제한자인 경우 세부 분류 정보(보험류체납금여제한자/외국인보험류체냡금여제한자) 표시
	- 수진자 자격 확인 창 : 산정특례 내역에 '급여제한 ([세부 분류 정보])' 수록
	- 접수 확인 창 : 상단에 '알림 : 급여제한 ([세부 분류 정보]) 환자입니다.' 메시지 표시
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 영수증 엑셀 출력 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래 진료비 계산서 영수증 창, 입원 수납 창 참조
2) 상단 [출력] 메뉴 선택 - [영수증 엑셀 출력] 메뉴 선택
3) 엑셀 출력물 확인

<a href="/images{{page.url}}/2.png" target="_blank"><img src="/images{{page.url}}/2.png" alt=""></a><br/>[ 영수증 엑셀 출력 화면 ]
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 수납대장 진료형태항목에 DRG 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납 대장 창 참조
2) 검색조건.[진료형태] 항목에 'DRG' 추가
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 예진실 변경 ContextMenu 위치변경 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[대기] 탭 참조
2) 대기자 목록 Right Click - [예진실 변경] 을 [재호출] 메뉴 위로 위치 이동
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 속성창 주야간 항목 텍스트 변경 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[속성 창(F4)] 화면 참조
2) [주야간] 항목 표시 변경
3) 변경 전후
	- 주간 >> 산정안함
	- 야간 >> 야간(50%)
	- 심야 >> 야간,토요,공휴(30%)
	- 공휴 >> 공휴(50%)
</th>
    </tr>
</table>
<span class="box chart">진료</span> - DUR 처방사유 단축코드 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) DUR 점검결과 창 참조
2) [처방 사유코드] 항목 우측에 [최근 사용 처방 사유코드] 버튼 목록 표시 (최대 3건)
3) [최근 사용 처방 사유코드] 버튼 Click 하여 일괄 적용

<a href="/images{{page.url}}/3.png" target="_blank"><img src="/images{{page.url}}/3.png" alt=""></a><br/>[ DUR 처방사유 단축코드 동작 화면 ]
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 용법항목 우클릭시 주야간설정 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[진료차트] 탭 참조
2) 처방 내역 중 의약품이 아닌 건 [용법] 항목 우측 [..] 버튼 Click 시 속성 창 표시
3) 속성 창(F4) 에서 [주야간] 항목 선택
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 용법텍스트 직접 입력 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[진료차트] 탭, 묶음처방 입력 창 참조
2) 처방 내역의 [용법내용(텍스트)] 항목 Double Click 시 용법정보 입력 창 팝업
3) 용법 옵션.[기본] 인 경우에만 동작
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 보험유형.일반일 때 조합유형 점검 기능 삭제  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 보험유형.[일반] 환자 진료 정보 불러오기
3) [저장] 버튼 Click 
4) 조합유형 또는 사업장기호가 입력되지 않은 경우 기능 동작 변경
	- 변경 전 : 차트 점검 창 팝업 - 조합유형 또는 사업장기호 확인 오류 메시지 표시
	- 변경 후 : 계산 창 팝업 (차트 점검 창 팝업되지 않음)
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 야간,토요,공휴(30%) 가산 오전 적용룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 계산창 화면 참조
2) 진료시간이 진료시작시간 이전인지 확인
3) 야간,토요,공휴(30%) 해당 수가 입력
4) 계산 창에서 가산 적용 여부 확인
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 수가명이 없는 경우 점검 동작 bug 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 심사 화면 참조
2) 명세서 메모 수가에 수가명이 입력되지 않은 경우 점검 누락 점검 오류 패치
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - DRG 특례 산정 bug 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) DRG.[명세서내역] 탭 참조
2) DRG 특례 환자의 [본인부담] 금액 계산 오류 패치
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 처방 일괄변경 수가명 검색조건 제거
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 보험청구 화면 참조
2) 우측 상단 [도구] 메뉴 선택 - [처방 일괄 변경] 메뉴 선택
3) 변경 전/후 처방정보 입력 후 [대상확인] 버튼 Click
4) 대상(불일치) 목록 검색 시 [수가명] 항목 제외
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 장애진단서 진료기관 및 의사 입력 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진단서.[장애진단서] 화면 참조
2) [진료기관 및 의사] 항목 직접 입력 기능 추가
</th>
    </tr>
</table>

<span class="box lab">검안실</span> - 추가오더시 대기순서 변경 옵션 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[실시부서] 화면 참조
2) 오더 표시 옵션의 [추가 오더 시 대기 순서로 변경] 항목 선택 후 [저장] 버튼 Click
3) 진료실에서 검안오더 추가 수행
4) 검안실 대기목록에서 대기순서 확인
</th>
    </tr>
</table>
<span class="box lab">검안실</span> - 대기 목록 정렬 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검안실.[대기자] 탭 참조
2) 대기자 목록 Right Click - [대기 목록 정렬 옵션(대기 순서 (역)순)] 메뉴 항목 선택
3) 검안실 대기목록에서 대기순서 확인

<a href="/images{{page.url}}/4.png" target="_blank"><img src="/images{{page.url}}/4.png" alt=""></a><br/>[ 검안실 대기 목록 정렬 옵션 메뉴 화면 ]
</th>
    </tr>
</table>
<span class="box lab">검안실</span> - 추가오더 컬러 구분 표시 기능 추가  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검안실.[대기자] 탭 참조
2) 추가 오더 건인 경우 대기자 목록 내 [차트번호] 항목 글자색 구분 표시

<a href="/images{{page.url}}/5.png" target="_blank"><img src="/images{{page.url}}/5.png" alt=""></a><br/>[ 추가오더 컬러 구분 표시 적용 화면 ]
</th>
    </tr>
</table>

<span class="box other">통계</span> - 월별수입통계 백대백본인부담금, 백대백미만총액 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수입통계.[월별 수입 통계] 탭 참조
2) [전액본인부담], [전액미만총액] 항목 추가
</th>
    </tr>
</table>
<span class="box other">통계</span> - 수입통계.진료의별수입통계 항목 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수입통계.[진료의별 수입 통계] 탭 참조
2) [진료과], [신환수], [구환수] 항목 추가
</th>
    </tr>
</table>
<span class="box other">통계</span> - 기간별처방통계 항목 위치 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료통계.[기간별 처방 통계] 탭 참조
2) [일이란구분], [본인부담구분] 을 [청구코드] 항목 뒤로 위치 이동
	- 변경 전 순서 : [코드] - [일이란구분] - [본인부담구분] - [처방명칭] - .. - [청구코드]
	- 변경 후 순서 : [코드] - [처방명칭] - .. - [청구코드] - [일이란구분] - [본인부담구분]
</th>
    </tr>
</table>
<span class="box other">통계</span> - 인원통계.타의사기록보기 권한 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.[역할 및 권한] 화면 참조
2) 인원통계.[타 의사 기록보기] 권한 해제 후 [저장] 버튼 Click
3) 인원통계.[연령 별 환자현황] 탭 참조
4) [타 의사 기록보기] 권한이 허용되지 않은 경우 검색조건.[진료과(진료의)] 항목 변경 불가
	- 참고 : 모든 인원통계에 적용됩니다
</th>
    </tr>
</table>
<span class="box other">통계</span> - 수납 세무서용 통계 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수입통계.[월별 세무통계] 탭 참조

<a href="/images{{page.url}}/6.png" target="_blank"><img src="/images{{page.url}}/6.png" alt=""></a><br/>[ 월별 세무통계 화면 ]
</th>
    </tr>
</table>

<span class="box other">LabViewer</span> - 안과검사장비 프로그램 실행방법 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환자 조회 후 우측 [검사 장비] 버튼 Click
2) 실행 중인 검사 장비 프로그램 종료 후 재실행
</th>
    </tr>
</table>
<span class="box other">LabViewer</span> - 검사프로그램 실행 버튼 동작 변경 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 화면 초기화 상태에서 우측 [검사 장비] 버튼 Click
2) 차트번호가 입력되어 있는 경우 해당 정보를 검사 장비 프로그램에 전달
</th>
    </tr>
</table>
<span class="box other">LabViewer</span> - 검사일자 기본 선택 옵션 기능 추가  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) [EyeView] 탭 참조
2) 좌측 검사일자 목록 Right Click - [기본 선택 옵션(전체/마지막 일자 보기)] 메뉴 선택
3) 환자 불러오기 시 설정에 따라 검사일자 목록 선택 동작
	- [전체 일자 보기] : 전체 검사 기본 선택 상태
	- [마지막 일자 보기] : 최근 검사 건 기본 선택 상태

<a href="/images{{page.url}}/7.png" target="_blank"><img src="/images{{page.url}}/7.png" alt=""></a><br/>[ EyeView 마지막 일자 보기 옵션으로 적용 후 화면 ]
</th>
    </tr>
</table>
<span class="box other">LabViewer</span> - 태블릿에서 세로모드 지원 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 가로/세로 모드에 따라 최대화 동작하도록 기능 추가

<a href="/images{{page.url}}/8.png" target="_blank"><img src="/images{{page.url}}/8.png" alt=""></a><br/>[ 태블릿 세로모드 화면 ] 
</th>
    </tr>
</table>
<span class="box other">LabViewer</span> - 화면 Style 옵션 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 우측 상단 [환경설정] 메뉴 선택
2) 화면설정의 EyeView 스타일.[PEN] 항목 선택 후 [저장] 버튼 Click
3) [EyeView] 또는 [EyeView - 크게보기] 탭 화면 스타일 참조

<a href="/images{{page.url}}/9.png" target="_blank"><img src="/images{{page.url}}/9.png" alt=""></a><br/>[ EyeView PEN 스타일 옵션 적용 화면 ]
</th>
    </tr>
</table>

<span class="box other">WaitCall</span>  - 똑닥 예약환자 대기자콜 표시 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 대기자 목록 화면 참조
2) 미방문 똑닥 대기자를 '예약' 상태로 표시
</th>
    </tr>
</table>

<span class="box other">SmartCheck</span>  - ESC 종료 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사전점검 창에서 ESC 시 창 닫기 수행
</th>
    </tr>
</table>

<span class="box other">인터페이스</span>  - ARK-510A (NIDEK) LAN방식 연동 기능 추가
<span class="box other">인터페이스</span>  - NT530P (NIDEK) LAN방식 연동 기능 추가


<span class="box notice">[고시]</span> DRG 점검표 개정 (2023년 3월 진료분부터) 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) DRG.[점검표] 탭 참조
2) 하단 [4. 안과계 질병군(비급여렌즈 사용 수정체 수술) 수술 전 진료의 점검 사항] 항목 추가
- 2023년 3월 1일 진료분부터 적용
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> [의료급여] 코로나19 진단검사 진료비 청구방법 변경 고시
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 계산 창 참조
2) 보험유형.[의료급여1종] 환자 불러오기 후 코로나19 수가 입력
3) '의료급여1종 코로나19 진단검사 분리청구 대상자에 해당되는 경우 [예(Y)] 를 선택하십시오.' 메시지 팝업
4) [예(Y)] 버튼 Click 시 계산 창의 [본인부담코드] 우측 [M099] 항목 선택 상태
5) 청구 확인 창에서 대상 진료 특정내역 수록 확인
- 2023년 2월 15일 진료분부터 적용, 의료급여비용 청구는 2023년 2월 24일부터 가능
</th>
    </tr>
</table>
</pre>
---
title: 2022년 9월 업데이트 히스토리
menuTitle: 2022년 9월
historyHome: 0
yearMonth: 2209
---

<pre>

<bold># 9/30 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 10월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 10월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 10월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 9/29 배포</bold>
=====================
<span class="box other">주사실</span> - 주사처방전 X05-40d 프린터 모델 출력 기능 추가


<bold># 9/28 배포</bold>
=====================
<span class="box jemu">원무</span> - 예약시간 단위 구분선 보기 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[예약설정] 화면 참조
2) [예약시간 단위 구분선 보기] 항목 선택 후 [구분선 단위(30분/60분)] 설정

<a href="/images{{page.url}}/1.jpg" target="_blank"><img src="/images{{page.url}}/1.jpg" alt="" /></a>[ 예약시간 단위 구분선 설정 화면 ]

3) 예약 화면에서 구분선 표시 적용 확인

<a href="/images{{page.url}}/2.jpg" target="_blank"><img src="/images{{page.url}}/2.jpg" alt="" /></a>[ 예약시간 단위 구분선 표시 화면 ]
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료환불창에서 키오스크 수납건 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래수납 화면 참조
2) [...] 버튼 Click 후 [진료 환불] 메뉴 Click - 진료환불 창 팝업
3) 키오스크 수납 건인 경우 [구분] 항목에 '키오스크' 표시
4) 키오스크 수납 건인 경우에도 환불 가능하도록 기능 지원
    - 단, 대상이 단 건 수납인 경우에만 환불 대상으로 선택 가능

<a href="/images{{page.url}}/3.jpg" target="_blank"><img src="/images{{page.url}}/3.jpg" alt="" /></a>[ 진료환불창에 키오스크 표시 화면 - 단건 ]

<a href="/images{{page.url}}/4.jpg" target="_blank"><img src="/images{{page.url}}/4.jpg" alt="" /></a>[ 진료환불창에 키오스크 표시 화면 - 다건 ]
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 접수시 선택기관 타병원 선택 환자 알림
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 참조
2) 자격조회.[선택기관 타병원] 이용에 해당하는 환자를 불러온 후 [접수] 버튼 Click
3) 접수확인 창 팝업 및 '선택기관, 타병원 선택 환자입니다.' 메시지 알림
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 차트출력 입원 상병 누락 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 의무기록.[차트] 화면 참조
2) 차트 출력 시 입원 상병 표시되지 않는 증상 패치
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - DRG 선별급여 10원 차이 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 산정구분.[DRG] 인 경우 선별급여 10원 차이가 발생하는 증상 패치
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 수납후 현금영수증 발행 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납 상세 창 화면 참조
2) 수납 상태(대기/완료)와 무관하게 현금영수증 승인 동작하도록 기능 변경
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 수납상세창에서 다중 수납건 알림 및 상세창으로 전환 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[수납대기] 화면 참조
2) 수납 내역 선택 후 [상세수납] 버튼 Click
3) 대상 일자에 다른 수납 건이 존재하는 경우 우측 상단에 [일자 별 수납 건수] 버튼 표시

<a href="/images{{page.url}}/5.jpg" target="_blank"><img src="/images{{page.url}}/5.jpg" alt="" /></a>[ 일자별 수납 건수 표시 화면 ]

4) [일자 별 수납 건수] 버튼 Click 하여 수납 내역 창 팝업

<a href="/images{{page.url}}/6.jpg" target="_blank"><img src="/images{{page.url}}/6.jpg" alt="" /></a>
[ 일자별 수납내역 창 화면 ]

5) 내역 중 수납 건 Double Click 하여 수납상세 정보 불러오기 기능 지원
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 차트출력 시 상병월별 옵션 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 의무기록.[차트] 화면 참조
2) 대상 차트를 선택하여 출력 시, 선택하지 않은 일자의 상병 기록이 포함되는 증상 패치
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 환불 발생 건에서 추가수납 발생하지 않도록 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 환불이 발생한 차트 불러오기
3) 진료 내역 변경 후 [진료완료] 버튼 Click 시 추가 수납 발생하지 않도록 기능 변경
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 현금영수증 신분확인 구분 옵션 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[현금영수증] 화면 참조
2) [신분확인구분(주민번호/핸드폰번호/자진발급/현금영수증카드/사업자등록번호)] 항목 선택
3) 현금 영수증 발행 창 팝업 시 설정한 [신분확인구분] 으로 기본 선택 동작
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 당일 예약 존재 시 알림 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[열기 및 저장(외래접수/외래진료)] 화면 참조
2) [당일 예약 존재 시 알림] 항목 선택
3) 외래접수/외래진료 화면에서 환자 불러오기 시 '오늘 예약되어 있는 환자입니다.' 메시지 알림
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 원외처방전 일괄출력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수 화면 상단 [출력] 버튼 참조
2) [원외처방전 일괄출력] 메뉴 Click - 원외처방전 일괄 출력 창 팝업
3) 대상 범위 등 출력 조건 설정 후 [출력] 버튼 Click
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 진료확인번호 승인결과 창에 진료형태, 승인번호 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료확인번호 승인 결과 창 화면 참조
2) [진료형태], [승인번호] 항목 추가 표시
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 진료과 표시 방법 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료대기] 화면 참조
2) [의사별 대기현황] 버튼 Click 하여 대기현황 조회 창 팝업
3) 의사가 존재하지 않는 진료과가 표시되지 않도록 기능 변경
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 처방창 증상 순서 이동 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[진료차트] 탭 참조
2) 증상 줄의 [코드] 영역 Right Click - [순서이동] 메뉴 Click
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 검진바우처 처방옵션 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기본자료.[수가정보] 화면 참조
2) 상세정보 우측 [처방옵션] 버튼 Click - [검진바우처] 항목 선택
3) 외래진료 화면에서 해당 수가 처방
4) 대상 수가가 검진바우처에 해당될 경우 검진바우처 자동 설정
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 전처방 자격조회 표시룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 전처방 자격조회 표시 기준 변경
    - 변경 전 : 최근 일자 기준 자격조회 정보 표시
    - 변경 후 : 불러온 차트 진료일자 기준 자격조회 정보 표시
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 묶음처방 편집 시 증상 단축코드 입력 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[증상 및 특이증상] 화면 참조
2) 증상 편집 옵션.[단축코드 사용(증상/특이증상 모음장)] 항목 설정
3) 편집할 묶음처방 상세 창 열기
4) [증상] 에 단축코드 입력 후 Enter Key 입력 시 내용 불러오기 동작
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 외래진료 묶음 탭에 금액 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.[병명 및 처방] 화면 참조
2) 묶음처방 옵션의 [금액 표시] 항목 선택
3) 외래진료.[Rt] 탭에 [금액] 항목 추가
    - 변경 전 : [코드], [명칭]
    - 변경 후 : [코드], [명칭], [금액]
4) 묶음처방 별 금액은 의약품을 제외하고 종별 가산을 고려하지 않으므로 실제와 상이할 수 있습니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 외래진료 단축키 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료 화면 참조
2) 상단 [화면설정] 버튼 Click 후 [단축키 설정] 메뉴 선택
3) 단축키 내역 중 외래진료.[수납내역] 단축키 동작 오류 패치
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 계산창 명세서내역 더블클릭 동작 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[계산창] 화면 참조
2) [진료비내역] 내용 Double Click 시 [명세서내역] 탭으로 이동
3) [명세서내역] 내용 Double Click 시 [진료비내역] 탭으로 이동
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 영상 문서 파일 썸네일에 카테고리 표시 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 영상 화면 참조
2) 좌측 썸네일 목록 중 문서 영상 파일에 [카테고리명] 표시
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 영상 PDF 삭제 기능 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 영상 화면 참조
2) 좌측 썸네일 목록 중 문서 영상 파일 선택
3) [...] 버튼 Click - [선택영상 삭제] 메뉴 Click 시 삭제 수행
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 외래진료 보류 버튼 클릭시 증상 빈줄 증가 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[진료신상] 탭 참조
2) 차트 불러오기 후 [보류] 또는 [저장] 버튼 Click 시 증상에 빈 줄이 누적되는 오류 패치
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 병동탭 입원진료 이동 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.[병동] 탭 참조
2) 병동 내역 Double Click 시 [입원진료] 화면으로 이동
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 완료된 오더 삭제시 권한 확인 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[진료] 화면 참조
2) 오더 변경 옵션의 [완료된 오더 삭제 시 권한 필요] 항목 선택 후 [저장] 버튼 Click
3) 외래진료 화면에서 차트 불러오기
4) 완료 처방 줄 삭제 시도 시 [차트관리자] 권한 확인하여 메시지 팝업
    - 권한이 부여된 경우 : '실시부서에서 완료한 처방입니다. 처방을 취소하시겠습니까? '
    - 권한이 부여되지 않은 경우 : '실시부서에서 완료한 처방입니다. 오더를 취소할 수 없습니다.'
</th>
    </tr>
</table>

<span class="box diag">진단서</span> - 갑상선 초음파 판독 소견서 서식 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 소견서.[갑상선 초음파 판독 소견서] 화면 참조

<a href="/images{{page.url}}/7.png" target="_blank"><img src="/images{{page.url}}/7.png" alt="" /></a>[ 갑상선 초음파 판독 소견서 화면 ]
</th>
    </tr>
</table>
<span class="box diag">진단서</span> - 근로능력 평가용 진단서 개정 서식 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진단서.[근로능력평가용진단서(개정:2019.10.23)] 화면 참조

<a href="/images{{page.url}}/8.png" target="_blank"><img src="/images{{page.url}}/8.png" alt="" /></a>[ 근로능력평가용진단서(개정:2019.10.23)] 화면 ]
</th>
    </tr>
</table>
<span class="box diag">진단서</span> - 코로나19 검사의뢰서 의뢰기관 정보 자동 수록
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 의뢰서.[코로나19 검사의뢰서] 화면 참조
2) 환자 조회 시 발행의사 기준 의뢰기관 정보 자동 수록 기능 지원
</th>
    </tr>
</table>
<span class="box diag">진단서</span> - 경부 초음파 판독 소견서 서식 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 소견서.[경부 초음파 판독 소견서] 화면 참조

<a href="/images{{page.url}}/9.png" target="_blank"><img src="/images{{page.url}}/9.png" alt="" /></a>[ 경부 초음파 판독 소견서 화면 ]
</th>
    </tr>
</table>

<span class="box inspect">심사</span> - 대기자 자리비움 변경기록 로그 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.[진료대기] 또는 외래진료.[대기] 탭 참조
2) 대기자 목록 Right Click 후 [자리 비움] 메뉴 Click
3) 관리자.[변경기록] 화면에서 [자리 비움] 상태 변경 이력 확인
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 특정기호 환자조회 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 우측 상단 [내역조회] 메뉴 Click 후 [특정기호 환자 조회] 메뉴 Click
2) 외래진료.[진료차트] 탭의 상병.[특정기호] 기준으로 환자 목록 조회
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 특이증상 환자조회 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 우측 상단 [내역조회] 메뉴 Click 후 [특이증상 환자 조회] 메뉴 Click
2) 외래진료.[진료신상] 탭의 [특이증상] 기준으로 환자 목록 조회
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 특정증상 환자조회 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 우측 상단 [내역조회] 메뉴 Click 후 [특정증상 환자 조회] 메뉴 Click
2) 외래진료.[진료신상] 탭의 [증상] 기준으로 환자 목록 조회
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 특례환자 협진시 청구 오류
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료구분.[특례] 차트 당일 여러 건 존재 시 청구 오류 패치
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 청구 데이터 가져오기, 진료의뢰서 데이터 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 보험청구 화면 참조
2) 상단 [청구자료 가져오기] 메뉴 Click
3) 청구 대상 설정 후 [가져오기] 버튼 Click 시 진료의뢰서 자료가 포함되도록 기능 변경
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 환경설정 통합검색 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 상단 [환경설정] 버튼 Click - [환경설정 통합검색] 메뉴 Click
2) 기준정보, 환경설정, 사용자설정, 로컬설정, 원외처방전설정 기준 조회 및 검색
3) 검색 결과를 Click 하여 대상 설정 화면으로 이동
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 환경설정 클래식 메뉴 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 상단 [환경설정] 버튼 Click - [환경설정 클래식] 메뉴 Click
2) 기준정보, 환경설정, 사용자설정, 로컬설정 기준 조회 및 검색
3) [2.0 설정값] 및 [5.0 설정값] 확인
4) [5.0 설정값] 우측 [...] 버튼 Click 시 기능 지원 여부에 따라 창 분류 팝업
    - 5.0 지원 : 대상 설정 창 (기준정보, 환경설정, 사용자설정, 로컬설정)
    - 5.0 미지원 : 통합검색 창
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 자격조회정보와 보험정보 다를 경우 심사 점검 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 심사 화면 참조
2) [심사] 버튼 Click 하여 진료 심사 내역 불러오기
3) 심사 내역 중 '1042 - 건강보험 자격정보 기록이 없습니다.' 확인
4) 외래접수 화면에서 대상 환자를 불러와 자격조회 수행 후 [저장] 버튼 Click
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 산재 청구 오류
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 보험구분.[산재] 차트 청구 시 서식번호 기재 착오 오류 패치
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 수술 30% 자동가산 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수술 가산수가 사용 (예시 수술코드 : Q7703)
2) 가산적용 (30% 가산 및 산정코드 '080' 적용)
    - 평일 오후 6시 이후
    - 토요일, 공휴일
3) 30% 가산 적용 가능 수가를 자동 관리
4) 수술 항목만 적용
5) 검진 당일 수가는 적용 제외
6) 속성 창에서 야간 등 설정한 경우, 사용자 설정 값 우선 적용
</th>
    </tr>
</table>
<span class="box other">통계</span> - 수입통계.외래진료현황 항목 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수입통계.[외래진료현황] 탭 참조
2) 추가 항목 : [초재진구분], [최초내원일], [전화번호], [우편번호], [주소]
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 검사결과 판정 참고내용 툴팁 표시 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기본자료.[수가정보] 화면 참조
2) [검사정보] 탭 Click 후 [검사결과 참고내용] 항목 입력
3) 검사결과 화면에서 대상 수가 Mouse Over 하여 참고내용 확인
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 검사결과 오전/오후별 판정 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기본자료.[수가정보] 화면 참조
2) [검사정보] 탭 Click 후 [정상치] 항목 우측 [...] 버튼 Click
3) 참고치 정보 창에서 적용기준.[남여/오전오후] 을 설정하여 정상치 기준 관리
</th>
    </tr>
</table>
<span class="box other">[KIOSK 5.0]</span> 당일 수납 완료 시 증명서 출력 허용 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.[기본] 화면 참조
2) [당일 수납 완료 시 증명서 출력 허용] 항목 선택 후 [증명서] 메뉴 Click
3) 일자 기준 완료하지 않은 수납 건이 존재하는 경우 [증명서 출력] 불가
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> 코로나19·독감 동시 PCR 검사 관련 청구방법
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 9월 16일 이후 코로나19·독감 동시 PCR 검사 수가 (D680113*) 사용
2) 환자 본인부담
    - D6801136(급여) : 환자 본인부담금 면제 (전액 공단 부담)
    - D6801136(전액본인부담) : 환자 전액 본인부담
3) 해당 검사 수가 사용시 자동 분리 청구
</th>
    </tr>
</table>


<bold># 9/15 배포</bold>
=====================
<span class="box jemu">원무</span> - 환자명 공백 존재시 외래진료비 영수증 출력 bug 패치
<span class="box chart">진료</span> - 특정내역 리피트 bug 패치
<span class="box chart">진료</span> - 비급여 수가 처방창에서 단가 표시 bug 패치
<span class="box chart">진료</span> - 비백신설정 동작 bug 패치
<span class="box inspect">심사</span> - 입원환자 산정특례 대상자 등록번호 누락 bug 패치
<span class="box inspect">심사</span> - 진찰료없음일 경우 주간산정 알림 bug 패치
<span class="box inspect">심사</span> - 원내 퇴장방지의약품 JS002 특정내역 수록 bug 패치
<span class="box other">[Interface]</span> Medical Standard PACS
<span class="box other">[Scan]</span> PDF 파일 등록  기능 추가
<span class="box other">[LabViewer]</span> 새로고침 동작 변경


<bold># 9/6 배포</bold>
=====================
<span class="box inspect">심사</span> - 시설공동사용 수가 추가청구 bug 패치


<bold># 9/2 배포</bold>
=====================
<span class="box inspect">심사</span> - 대면진료 MT043 특정내역 발생 오류 수정
<span class="box notice">[고시]</span> 타이레놀 2건 심평원 약가 정정고시 적용(646900565, 646900690)


</pre>
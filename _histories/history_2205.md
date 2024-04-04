---
title: 2022년 5월 업데이트 히스토리
menuTitle: 2022년 5월
historyHome: 0
yearMonth: 2205
---

<pre>

<bold># 5/31 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 6월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 6월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 6월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 5/30 배포</bold>
===================== 
<span class="box jemu">원무</span> - 파일백업시 백업 사본경로 동작  bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.백업설정.파일백업.백업사본경로 항목을 설정합니다.
2) 파일백업시 서버의 C 드라이브에 기본백업이 수행됩니다.
3) 백업사본경로에 백업파일이 복사됩니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 전처방  진료메모 표시 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.전처방.진료메모표시 항목을 설정합니다.
2) 전처방의 해당일자에 '진료 메모' 문구가 표시됩니다.
3) '진료 메모' 에 마우스를 올리면 메모 내용이 툴팁으로 표시됩니다.
4) '진료 메모' 를 클릭하면 진료메모탭으로 이동되며 해당 메모를 편집할 수 있습니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 외래진료 수납창 진료의사 항목 추가  (수납금액 우측 진료의사 항목 참조)

<span class="box chart">진료</span> - PACS 'US, ES 명칭 형식' 옵션 기능 추가  (환경설정.연동관리.PACS 'US ES 명칭 형식' 항목 참조)

<span class="box lab">검사실</span> - 검사실 결과 항목 우클릭 메뉴 기능 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 결과 항목에 우클릭하여 메뉴를 표시합니다.
2) 메뉴를 클릭합니다.
3) 선택한 메뉴의 텍스트가 결과항목에 수록됩니다.
</th>
    </tr>
</table>

<bold># 5/26 배포</bold>
=====================
<span class="box chart">진료</span> - 계산창 원외처방 내역중 비급여 표시 기능 추가  (옵션 없음)
<span class="box chart">진료</span> - 약국이없는지역에서 처방일수 일괄 변경 기능 적용
<span class="box chart">진료</span> - 예약탭 정렬순서 변경 (예약일자 및 시간순 정렬)

<span class="box inspect">심사</span> - 법정감염병 신고 알림' 심사에러코드 추가 
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.청구심사탭.[...].심사대상 메뉴 참조
2) 법정감염병 신고 알림으로 점검된 내용을 심사결과목록에서 제외할 수 있습니다.
</th>
    </tr>
</table>
<span class="box other">통계</span> - 기간별처방통계 원외처방 총액 산정 방식 변경  (원외처방의 경우도 금액을 산정합니다)     

<bold># 5/24 배포</bold>
=====================
<span class="box chart">진료</span> - 묶음처방 클래식 모드에서 더블클릭 동작 bug  
<span class="box chart">진료</span> - 진료메모 한글모드 동작 변경  (한영모드 변경되지 않게)

<span class="box other">[고시]</span> 2022년 5월 약가 2차 등록 (자동 실행)

<bold># 5/23 배포</bold>
=====================
<span class="box chart">진료</span> - 웹백신창에서 백신코드 Relay 동작   bug


<bold># 5/19 배포</bold>
=====================
<span class="box jemu">원무</span> - 외래접수 검안오더시 병명 기본 리피트 기능 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.실시부서.검안오더옵션.병명기본리피트 항목을 설정합니다.
2) 외래접수에서 검안오더를 내립니다.
3) 병명이 기본리피트 되어 차트에 수록됩니다.
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 상단 환경설정 버튼 접근권한 동작  bug  (기준정보.역할및권한 접근권한 설정 적용)
<span class="box jemu">원무</span> - 의료급여 입원 수납금액이 0원일때 수납 진행불가  bug  (입원수납창 참조)
<span class="box jemu">원무</span> - 영수증 환불건 저장시 납부하지않은금액 발생 bug  (외래진료비 계산서.영수증 참조)
<span class="box jemu">원무</span> - 자격조회 결과중 '요양병원 입원중' 일때 알림 기능 추가  (접수확인창에서 '요양병원 입원중 환자입니다.' 메시지 팝업)
<span class="box jemu">원무</span> - 월간 예약 건수 표시 기준 변경  (예약 취소 건 제외후 건수 표시)

<span class="box chart">진료</span> - 대기자 접수메모 키워드 알림 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.대기자.접수메모키워드알림 항목을 설정합니다.
2) 키워드를 '확진,신속항원,비대명' 과 같이 콤마로 구분하여 등록합니다.
3) 진료대기창에서 접수메모를 확인합니다.
4) 접수메모중 키워드에 해당할경우 강조되어 표시됩니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 접수의사 고정 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.진료.대기자.접수의사고정 항목을 설정합니다.
2) 진료대기창에서 타의사 진료대기환자를 FU 합니다.
3) 접수의사고정으로 설정된 경우, 접수시의 의사가 변경되지 않습니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 오더창 Head 표시 설정 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.오더 버튼을 클릭합니다.
2) Heads탭.[...]에서 'Head 표시 설정' 메뉴을 선택합니다.
3) Head 목록에 표시 항목이 표시됩니다.
4) Head를 표시하지 않을 표시 항목을 일괄 Uncheck 합니다.
5) [...]에서 'Head 표시 저장' 메뉴를 선택합니다.
6) 설정값이 일괄 저장되고, 표시항목에 설정된 헤더만 표시됩니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 검사결과탭.엑셀결과보기탭 선택 동작 속도 개선
<span class="box chart">진료</span> - 의약품정보 검색창에서 ESC 키 입력시 간헐적으로 종료될 수 있는 증상  bug  
<span class="box chart">진료</span> - 증상 빨리 입력시 한글깨짐 bug
<span class="box chart">진료</span> - 검안 추가오더시 진료대기창 상태 표시 bug  (미완료 검안오더 존재시 'E>' 표시)

<span class="box diag">진단서</span> - 건강진단결과서 (구 보건증) 서식 추가  (진단서탭 참조)

<span class="box other">마약류</span> - 구입업체전송기록 가져오기 점검 기능 추가  (판매일자 2개 이상일때 확인 메시지 추가)

<span class="box other">통계</span> - 출력권한 설정 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.역할및권한에서 접근권한 및 출력권한을 설정합니다.
2) 출력권한 부재시 인쇄 및 엑셀내보내기 기능을 수행할 수 없습니다.
3) 고객관리 메뉴 적용 : CRM, 주소록, 보상관리, 예약현황
4) 통계 메뉴 적용 : 인원통계, 진료통계, 수입통계, 청구통계, 진료비통계, 매출보고서, 진료현황
</th>
    </tr>
</table>
<span class="box lab">검사실</span> - 검사실 완료일시 표시 기능 추가  (환경설정.실시부서.검사항목보기옵션.전체보기 경우만 해당)


<bold># 5/4 배포</bold>
=====================
<span class="box jemu">원무</span> - 외래영수증에 입원진료건  포함되는 bug  (영수증.외래수납현황 목록에서 입원 수납내역 제외)

<span class="box jemu">원무</span> - 전달메모 기록 존재 알림 컬러 변경  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 전달메모 존재시 : 하늘색
2) 오늘일자 전달메모 존재시 : 오렌지색
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - DRG 비급여 입원처방 발생시 영수증 비급여 수록 bug  (비급여 항목별로 영수증에 수록되게)

<span class="box chart">진료</span> - [PicShow] 영상비교창 비교모드에서 펜툴 기능 변경  (비교모드에서 펜툴 기능 지원)
<span class="box chart">진료</span> - 검사결과 항목별 결과 미표시  bug  (외래진료.검사결과탭.항목별탭 참조)
<span class="box chart">진료</span> - DrugInfo 의약품정보 검색시 발생할 수 있는 응답없음 증상   bug

<span class="box inspect">심사</span> - 중복상병 청구 제외 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.청구.청구옵션.중복상병청구제외 항목 참조
2) 중복상병 청구제외시 병명 청구코드를 기준으로 중복수록되지 않습니다.
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 청구확인 불러오기 속도 개선

<span class="box lab">검안실</span> - 대기목록 삭제 메뉴 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 검안오더후 진료실에서 검안오더 코드를 모두 취소한 경우 검안대기 목록에 표시될 수 있습니다.
2) 검안대기목록에서 우클릭합니다.
3) 삭제 메뉴를 누르면 삭제확인후 삭제를 진행합니다.
4) 차트에 검안오더가 존재할 경우 삭제할 수 없습니다.
</th>
    </tr>
</table>

<span class="box other">[KIOSK 5.0]</span> 실행시 백업 파일 삭제  (업그레이드 백업파일중 불필요 파일 삭제)
<span class="box other">[KIOSK 5.0]</span> 진료의 표시 순서 bug  (기준정보.직원정보 순서변경 기능 참조)


<bold># 5/2 배포</bold>
=====================
<span class="box notice">[고시]</span> 2022년 5월 수가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 5월 3일 재택치료 관련 고시 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 병원급 재택치료 전화상담·처방형 전화상담 관리료 추가 :  AH270, AH272
2) 의원급 재택치료 전화상담·처방형 전화상담 관리료 추가 :  AH271, AH273
3) 병원급 재택치료 의료상담센터형 전화상담 관리료 추가 :  AH274, AH276
4) 의원급 재택치료 의료상담센터형 전화상담 관리료 추가 :  AH275, AH277
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> 5월 3일 이후 삭제코드 사용시 알림 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 알림 대상 삭제코드 : AH233, AH234, AH237, AH238  
2) 알림 문구 : '5월 3일부로 지원이 종료되었습니다.'
</th>
    </tr>
</table>

</pre>
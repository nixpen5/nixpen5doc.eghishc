---
title: 2022년 4월 업데이트 히스토리
menuTitle: 2022년 4월
historyHome: 0
yearMonth: 2204
---

<pre>


<bold># 4/29 배포</bold>
=====================
<span class="box jemu">원무</span> - 환불건 포함된 영수증 합산출력시 환자구분 항목 수록룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 일반 수납건과 환불 수납건을 '영수증 합산' 하는 경우 환자구분을 변경된 보험유형으로 출력합니다.
2) 진료환불인 경우 차트의 보험유형을 변경후 영수증을 확인 하시기 바랍니다.
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 전처방 판독소견서 보기 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.전처방.판독소견서표시 항목에 체크합니다.
2) 전처방 EMR 필터를 선택합니다.
3) 판독소견서가 작성된 환자를 FU 합니다.
4) 전처방창에서 판독소견서가 작성된 일자 아래에 '판독소견서' 문구가 표시됩니다.
5) '판독소견서' 문구에 마우스를 올리면 판독소견서 내용이 툴팁으로 표시됩니다.
6) '판독소견서' 문구를 클릭하면 판독소견서창이 실행됩니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 진료메모탭에서 판독소견서 참조 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료.진료메모탭을 선택합니다.
2) 우측 상단의 '판독소견서' 버튼을 누릅니다.
3) 해당 환자의 판독소견서 기록이 표시됩니다.
4) 판독소견서 기록을 더블클릭하면 진료메모창에 판독소견 내용이 복사됩니다. 
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 판독소견서 출력물 변경  (성별 추가, 검사일시 항목을 의뢰일자로 변경)

<span class="box lab">방사선실</span> 판독소견서 버튼 기능 추가   (상단 판독소견서 버튼 참조)
<span class="box lab">방사선실</span> 소견리스트탭 기능 삭제  (판독소견서 기능으로 대체)

<span class="box notice">[고시]</span> 2022년 5월 약가 등록 (자동 실행)
<span class="box notice">[고시]</span> 2022년 5월 치료재료툴 (바로가기.공지사항.미설치툴 참조)


<bold># 4/28 배포</bold>
=====================
<span class="box jemu">원무</span> - 추가수납 삭제 기능 추가  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납대기창에서 추가수납건을 선택합니다.
2) 우클릭하여 '추가수납 삭제' 메뉴를 선택합니다.
3) 추가수납건이 아닐경우 메뉴가 표시되지 않습니다.
4) 권한확인창이 뜨면 아이디 패스워드를 입력합니다.
5) 수납관리자 권한이 없으면 진행되지 않습니다.
6) 추가수납건 삭제가 수행됩니다.
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 입원환자 컨텐츠 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.화면설정.화면디자인 참조
2) 입원환자 컨텐츠를 선택합니다.
3) 배치할 위치를 지정합니다.
4) 화면을 저장합니다.
</th>
    </tr>
</table>

<span class="box chart">진료</span> - 진료요약창에 일반구분 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료요약창에서 일반 진료건일 경우 일자항목에 Red막대가 표시됩니다.
2) 사용자설정.진료업무.전처방 메뉴에서 진료요약창 옵션을 변경할 수 있습니다.
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 진료의 변경후 진행중 상태 표시룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료의 변경후 해당 진료건이 '진료중' 으로 표시되지 않도록 변경
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 대기탭 접수메모 중복 표시 증상   bug  
<span class="box chart">진료</span> - 특이증상 빈줄 표시 증상  bug
<span class="box chart">진료</span> - 외래진료 계산창에서 진료완료시 입원 수납 데이터 발생 bug
<span class="box chart">진료</span> - 저장시 간헐적으로 발생하는 응답없음 증상   bug


<span class="box inspect">심사</span> - 급여제한자 설정 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료에서 속성 버튼을 누릅니다.
2) 속성창에서 '급여제한자' 를 체크합니다.
3) 차트를 저장하고 계산 결과를 확인합니다.
4) 자격조회결과를 기준으로 기본 설정됩니다.
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 파일백업 보관일수 동작 bug
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 파일백업 보관일수 설정값에 따라 보관일수가 경과된 사본파일 삭제 수행
2) 환경설정.백업설정 메뉴 참조
</th>
    </tr>
</table>

<span class="box notice">[고시]</span> U071 법정감염병구분 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 법정감염병 제2급으로 변경
2) 대상병명 : U07.1, U07.2
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> 건강여성첫걸음 대상자 조건 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 변경전 : 만12세 여성 청소년
2) 변경후 : 만13 ~ 17세 여성 청소년
3) 차트저장시 나이에 따른 점검룰 변경
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> 대면진료 시 외래진료센터 미해당 기관에서 'H/재택치료' 기재
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래진료센터 기관인 경우 병원정보.상세정보.외래진료센터 항목체 체크합니다.
2) 외래진료센터 인 경우 조제시참고사항에 'T/외래진료센터' 수록
3) 외래진료센터 아닌 경우 조제시참고사항에 'H/재택치료' 수록
</th>
    </tr>
</table>

<span class="box other">[LabViewer]</span> ImageView - 선택영상 내보내기 메뉴 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 좌측 영상 썸네일목록에서 내보내기할 영상 선택
2) [...]버튼.선택영상 내보내기 메뉴 선택
3) 내보내기할 폴더 지정
</th>
    </tr>
</table>

<span class="box other">[SCAN]</span> 동일 파일명인 파일을 업로드 할수 없음    bug


<bold># 4/21 배포</bold>
=====================
<span class="box jemu">원무</span> - 접수아이디로 진료확인서2 서식 작성 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 접수아이디로 로그인된 상태에서 진료확인서2 발행가능
2) 진료확인서2 서식만 해당됩니다.
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 의료급여진료건의 카드수납시 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수납대기목록에서 카드수납을 누릅니다.
2) 해당 수납건이 의료급여건일 경우 상세수납창이 실행됩니다.
3) 진료확인번호 승인 진행 여부 메시지가 표시됩니다.
</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 일간 예약장부 동일시간대 예약 다수건 출력 지원  (예약.일간탭.출력버튼.일간출력 메뉴 참조)
<span class="box jemu">원무</span> - 자격조회 조회된 수진자명이 일치하지 않습니다 메시지 동작 변경  (외국인일 경우 메시지 표시 안함)

<span class="box chart">진료</span> - 전달메모 보기옵션 기능 추가  (전달메모창.[...]버튼.보기모드 참조)
<span class="box chart">진료</span> - 외래진료 다른 탭 클릭시 편집중인 증상 초기화 bug  (증상창 편집후 다른탭 누를경우에도 편집중인 증상 유지)

<span class="box chart">진료</span> - 영상비교창 창이동 기능 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 영상비교창 타이틀을 Drag 하여 즉시 이동 가능
2) 영상비교창 모니터 위치 기억
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 좌우검사 큰화면보기창 크기변경 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 상단바를 Drag하여 표시되는 창크기 변경
2) 창크기 기억
</th>
    </tr>
</table>
<span class="box chart">진료</span> - 진료중 동작룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 진료스텝일 경우 진료중 변경 안함
2) 로컬설정.기본.사용구분설정 참조
</th>
    </tr>
</table>
<span class="box diag">진단서</span> - 당뇨병환자 소모성 재료처방전(연속혈당측정용 전극용) (개정:2021.12.29) 서식 개정  (진단서.신청서탭 참조)
<span class="box diag">진단서</span> - 영문코로나검사확인서 서식 추가  (진단서.확인서탭 참조)

<span class="box inspect">심사</span> - 수가정보 수가목록 코드구분별 엘셀내보내기 기능 추가  (수가정보창.[...]버튼.수가목록 엑셀내보내기 메뉴 참조)

<span class="box inspect">심사</span> - 급여제한자 청구 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 접수시 '자격조회 결과 보험료체납급여제한자 입니다' 알림 표시
2) 처방창에 보험코드로 처방 (주의 - 전액부담코드로 처방하지 않습니다.)
3) 차트 저장시 '자격조회 결과 보험료체납급여제한자 입니다. 전액본인부담 후 청구대상' 알림 표시
4) 수납대상액은 총진료비와 비보험총액의 합산액으로 발생
5) 청구시 본인부담금은 요양급여총액으로 발생, 청구액은 0원
</th>
    </tr>
</table>
<span class="box inspect">심사</span> - 본인부담구분.서비스 일 경우 단가 0원 알림 제외
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 수가정보에서 본인부담구분.서비스일 경우 단가 0원 알림 제외
2) 처방창에서 본인부담구분.서비스일 경우 단가 0원 알림 제외
</th>
    </tr>
</table>

<span class="box lab">검안실</span> - 지원부서탭 메뉴 버튼 표시룰 적용
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 기준정보.실시부서창에서 사용하지 않는 실시부서를 사용여부.N 으로 설정
2) 지원부서탭 메뉴에서 미사용 실시부서가 표시되지 않습니다.
</th>
    </tr>
</table>
<span class="box lab">검안실</span> - FU 이후 검안항목 포커싱 동작   bug  (차트번호 항목을 빠르게 클릭시 환자 클리어 되는 증상)
<span class="box lab">검안실</span> - 검안오더 대기목록 불러오기 동작   bug  (검안실.대기차에서 FU시 오더가 표시되지 않을 수 있는 증상)


<span class="box notice">[고시]</span> 코로나 단독검사 무료
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 대상 검사코드 : D658404*, D658497*, D680001*, D658305*, D658397*, D680113*
2) 검사코드를 포함하여 처방
3) 검사코드 비용은 수납금액이 발생되지 않습니다.
4) 계산창에 '코로나19 확진용 단독검사료 본인부담금 면제 대상자' 표시
5) 청구시 자동 분리
6) 청구시 코로나단독검사무료명세서에 'MT043' 자동 수록
</th>
    </tr>
</table>

<bold># 4/20 배포</bold>
=====================
<span class="box jemu">원무</span> - 외래수납.수납대기 안보이는 증상   bug  (네트웍이 느린 경우)
<span class="box notice">[고시]</span> 코로나19 진단검사 급여기준 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 변경전청구코드 : D658404*  변경후청구코드 : D658305*
2) 변경전청구코드 : D658497*  변경후청구코드 : D658397*
3) 변경전청구코드 : D680001*  변경후청구코드 : D680113*
4) 처방창에서 4/20일 이후에 변경전청구코드 사용시 급여중지 알림창 표시
</th>
    </tr>
</table>
<span class="box notice">[고시]</span> 2022년 4월 20일 적용 수가 등록 (자동 실행)
<span class="box other">[SCAN]</span> FileViewData 파일명 규칙룰 변경 


<bold># 4/18 배포</bold>
=====================
<span class="box jemu">원무</span> - 백신지원금 포함시 수납대상액 10원 차이 bug


<bold># 4/14 배포</bold>
=====================
<span class="box jemu">원무</span> - 입원영수증 비급여 항목 편집 기능 추가  
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
        <th style="font-weight:normal;">1) 입원수납.영수증 버튼 참조</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 차트기록창에서 단축키로 닫기 동작 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style="font-weight:normal;">1) 외래접수에서 차트보기 단축키가 F6으로 설정된경우, 단축키로 차트기록창이 열립니다.
2) 차트기록창에서 동일한 단축키를 누르면, 차트기록창이 닫힙니다.</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 와콤 개인정보활용동의 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 동의서창의 [...] 버튼을 클릭합니다.
2) 개인정보활용동의설정에서 동의서서명방법을 와콤으로 변경합니다.
3) 동의서 화면에서 [개인정보활용동의] 버튼을 누릅니다.
</th>
    </tr>
</table>
<span class="box jemu">원무</span>  - 접수메모 상용구 기능 추가  (사용자설정.접수업무.접수메모옵션 참조)
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 외래접수.접수메모창에서 '접수메모' 타이틀을 클릭후 상용구를 픽업할 수 있습니다.
2) 외래접수.특이사항창에서 '특이사항' 타이틀을 클릭후 사용구를 픽업할 수 있습니다.
3) 주의 - 옵션을 설정한다음 프로그램을 재시작후 동작합니다.
4) 접수메모 편집창에서 상용구 단축키를 사용할 수 있습니다.</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 외래접수 차트기록창 클래식에 특이증상 보기 옵션 기능 추가   
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.진료업무.차트보기 메뉴에서 특이증상 표시 항목에 체크합니다.
2) 외래접수.차트기록창에 특이증상이 표시됩니다.
3) 특이증상 영역의 위 아래부분을 조절하여 특이증상 영역의 크기를 변경할 수 있습니다.</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 예진실 접수 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용을 위한 기본 설정
1-1) 기준정보.진료관리.예진실 메뉴에서 예진실을 등록합니다.
1-2) 환경설정.기준관리.실시부서 메뉴에서 예진실옵션을 설정합니다.
2) 기준정보.역할및권한창에서 권한 설정
2-1) 의사 역할을 예진으로 복사합니다.
2-2) 예진 역할을 선택후 타의사차트편집 권한을 허용으로 설정합니다.
2-3) 예진 역할에 예진담당자를 등록합니다. (사용자추가)
3) 예진환자 접수
3-1) 접수확인창에서 예진실 선택후 접수시 해당 예진실로 보류 처리됩니다.
4) 예진환자 진료
4-1) 외래진료.화면설정.차트버튼설정 메뉴에서 예진완료 버튼을 등록합니다.
4-2) 외래진료.보류탭에서 예진할 환자를 선택합니다.
4-3) 권한을 가진 예진담당자는 의사의 기록을 변경할 수 있습니다.
4-4) 예진실을 선택후 예진처방을 입력합니다.
4-5) 예진완료 버튼을 누르면 진료대기 상태로 변경됩니다.</th>
    </tr>
</table>
<span class="box jemu">원무</span> - 수가명이 길경우 진료비세부산정내역서 출력  bug  
<span class="box jemu">원무</span> - 일반환자 10원차이 bug  (수납대상액절사조건.100원단위반올림 옵션사용시 bug)

<span class="box jemu">원무</span> - '영수증 실행파일 사용' 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 사용자설정.기본.실험실옵션 '영수증 실행파일 사용' 항목을 설정합니다.
2) 카드수납화면에서 영수증/진료비세부내역서/원외처방전 출력속도가 단축됩니다. 
3) 수납상세화면에서 영수증/진료비세부내역서/원외처방전 출력속도가 단축됩니다.
4) 외래진료비계산서영수증화면에서 영수증 출력속도가 단축됩니다.</th>
    </tr>
</table>
<span class="box chart">진료</span> - 영상비교창 이동 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 영상비교창에서 타이틀을 더블클릭합니다.
2) 영상비교창을 타이틀을 잡고 이동할 모니터로 Drag합니다.</th>
    </tr>
</table>
<span class="box chart">진료</span> - 리피트시 본인부담구분.서비스 적용룰 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 리피트할 코드의 본인부담구분이 서비스인경우 서비스로 리피트됩니다.
2) 묶음처방에 등록된 본인부담구분이 서비스인경우 서비스로 처방됩니다.</th>
    </tr>
</table>
<span class="box chart">진료</span> - 영상소견서 서식 개선  (폰트 등 일부 개선)

<span class="box lab">[LabViewer]</span> 실행 버튼 동작 변경
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 해당 프로그램이 실행중인 상태이면 프로그램을 전면에 표시합니다.</th>
    </tr>
</table>
<span class="box lab">[LabViewer]</span> 새로고침 단축키 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) F5 키를 누르면 표시중인 기록을 새로고침합니다.
2) PosVision 단축키는 F6으로 변경됩니다.</th>
    </tr>
</table>
<span class="box lab">[LabViewer] EyeView</span> - 검안결과 복사 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 복사할 결과에서 마우스 우클릭후 '복사'를 선택합니다.
2) 검사결과 등록창이 뜨고 검사결과가 복사되면, 확인후 저장합니다.</th>
    </tr>
</table>
<span class="box lab">[LabViewer] EyeView</span> - 좌우검사 입력방식 옵션 기능 추가
<table style="width:100%; margin-bottom: 0; margin-top: 10px;">
    <tr>
<th style=" border-spacing: 5px; font-weight: normal">1) 환경설정.접수.좌우검사입력방식을 설정합니다.
2) 결과입력화면의 항목을 좌우로 또는 상하 방향으로 표시후 입력할 수 있습니다.</th>
    </tr>
</table>

<bold># 4/11 배포</bold>
=====================
<span class="box jemu">원무</span> - 카드단말기.싸인패드 이용한 개인정보활용동의  (기준정보.개인정보활용동의설정.동의서서명방법.싸인패드 참조)
<span class="box jemu">원무</span> - 싸인패드 개인정보활용동의 서명 동작 변경  (동의서창.개인정보활용동의 버튼 클릭시 싸인패드 동작)
<span class="box jemu">원무</span> - 개인정보활용동의 삭제 기능 추가 (외래접수.개인정보정보동의 창에서 동의내역을 우클릭하여 삭제)
<span class="box jemu">원무</span> - 개인정보활용동의서 기록 방식 변경  (저장 또는 거부중 최종 1건만 보관)
<span class="box jemu">원무</span> - 외래접수.검안오더 연결병명 누락 증상 bug
<span class="box jemu">원무</span> - 입원등록창에 퇴원 동시 등록 기능 추가 (입원정보탭.입원등록창.퇴원 항목 선택 후 저장 시 입퇴원 동시 처리)
<span class="box jemu">원무</span> - 입원진료.계산창에서 진료완료 버튼 동작   bug  (입원진료.계산창에서 진료완료시 수납데이터 발생하지 않게)
<span class="box chart">진료</span> - 정신과 차트 보기 옵션 기능 추가  (외래진료.화면설정.화면디자인에서 환자메모 컨텐츠 추가하여 사용)
<span class="box chart">진료</span> - 특정동작에서 증상 표시 안되는 증상   bug  (2건 이상 기록된 일자의 차트를 반복 호출 시 증상이 표시되지 않는 bug)
<span class="box chart">진료</span> - 처방창에서 묶음처방코드 변경 동작 bug  (묶음코드에 속한 수가코드를 재입력(코드 Enter) 시 발생 bug)
<span class="box chart">진료</span> - 증상정렬 옵션일때 묶음증상 정렬 적용 (증상정렬 옵션 사용 시 처방창.증상의 묶음 상태를 해제 및 정렬하여 차트 저장)
<span class="box chart">진료</span> - 증상 모음장 그룹 더블클릭시 일괄추가 옵션 기능 추가 (사용자설정.진료업무.증상편집옵션.증상 모음장 그룹 더블클릭 시 일괄 추가 옵션 참조)
<span class="box chart">진료</span> - 진료대기목록 보류 컬러를 검사상태별로 표시 ('E>' : Green, 'E<' : Orange)
<span class="box chart">진료</span> - 좌우검사 큰화면보기 단축키 추가 (외래진료.화면설정.단축키설정.큰화면보기 참조)
<span class="box inspect">심사</span> - 환경설정 등록되지 않은 수가 입력시 라이브러리 기준 추가 옵션 기능 추가 (환경설정.계산및산정.처방옵션.등록되지 않은 수가 입력 시 라이브러리 기준추가 옵션 참조)
<span class="box inspect">심사</span> - 작은청구조회시 실행제한시간 변경 (프로그램 시작후 동작시 간헐적 오류발생 증상)
<span class="box inspect">심사</span> - 심사창에서 전달메모 반복 표시   bug  ([접수보기] 버튼 클릭시 전달메모창이 반복 팝업되는 증상)
<span class="box lab">검안실</span> - 차트삭제후 검안실 대기목록 남아있는 증상 bug  (차트 삭제시 검안실 대기목록 남지 않도록)
<span class="box lab">검안실</span> - 오더 삭제 동작 bug (오더 모두 삭제 후 검안실 대기목록 남지 않도록)
<span class="box other">통계</span> - 기간별처방통계 결과에 증상 포함   bug  
<span class="box other">공통</span> - 내메뉴관리 검안실 추가 (사용자.내메뉴관리.지원부서탭 참조)
<span class="box other">공통</span> - 화면전환시 전달메모 표시 동작  변경 (외래진료에서 전달메모 창 팝업 확인 후 외래접수로 이동 시 전달메모 창 팝업되지 않도록)
<span class="box other">[LabViewer]</span> 영상비교창 Drag 기능 추가 (영상 확대 후 마우스 Drag 시 대상 방향으로 화면 이동)
<span class="box other">[LabViewer]</span> ImageView - 검사결과 보기 기능 추가 ([...]버튼에서 좌우검사 결과보기 클릭하여 표시할 1건의 검사 장비 선택)
<span class="box other">[LabViewer]</span> EyeView - 오늘 날짜의 검안결과 컬러 표시  기능 추가  (오늘날짜의 결과를 구분하여 표시)
<span class="box other">[LabViewer]</span> EyeView검사결과 - 전일자결과 수정 동작 변경  ('일자(차수)' 헤더 더블클릭 시 수정 모드 변경)
<span class="box other">[LabViewer]</span> 검사장비실행 버튼 동작 변경  (검사장비실행 버튼 클릭시 화면정리)
<span class="box other">[LabViewer]</span> 좌우검사 결과지 출력 기능 추가 (좌우검사 데이터 우클릭.좌우검사 결과지 출력 (A4) 메뉴 참조)
<span class="box other">[LabViewer]</span> 모니터 LastValue 기능 추가 (마지막으로 프로그램이 종료된 모니터 위치를 저장하여 재실행 시 적용)
<span class="box other">[LabViewer]</span> 선택탭 LastValue 기능 추가 (마지막 선택 탭 저장하여 프로그램 재실행 시 적용)
<span class="box other">[LabViewer]</span> 펜차트 - 중분류 서식그룹 기능 추가 (기준정보.펜차트 메뉴 참조)   
<span class="box other">[LabViewer]</span> 펜차트 - 서식그룹 선택하여 새차트 작성 기능 추가 (펜차트 상단에서 대분류 선택 후 중분류 더블클릭하여 새 차트 작성)


<bold># 4/6 배포</bold>
=====================
<span class="box diag">진단서</span> - 진료확인서1 진료일자가져오기창  팝업룰 변경  (필요시만 팝업)
<span class="box inspect">심사</span> - 신속항원검사 청구시 MX999 자동 수록 (MX999 - '"H/재택치료')
<span class="box other">[SmartCheck]</span> 실시간 사전점검중 멈춤 현상 bug  (건강보험/의료급여 외래만 점검)


<bold># 4/5 배포</bold>
=====================
<span class="box inspect">심사</span> - 외국인 성명길경우 청구조회 동작 bug    
<span class="box notice">[고시]</span> 코로나 대면진료 분리청구    
<span class="box notice">[고시]</span> 신속항원검사 의사별 100회 초과시 알림 기능 추가
<span class="box notice">[고시]</span> 코로나19 외래진료센터


<bold># 4/4 배포</bold>
=====================
<span class="box jemu">원무</span> - 검안오더시 연결수가 수록 동작 bug  (외래접수.검안오더창에서 지시할경우 연결수가 적용되게)
<span class="box jemu">원무</span> - DRG 소절개 본인부담금  (별도보상항목 종별가산 적용)
<span class="box jemu">원무</span> - 진료대기설정값 풀림 증상 bug  
<span class="box chart">진료</span> - 입원진료.계산창에서 진료완료 버튼 동작 bug  (진료완료시 수납오더 발생하지 않게)
<span class="box chart">진료</span> - 처방점검창 표시 이후 계산창에서 InsertKey 동작 bug  (변경후 출력버튼 동작하고 계산창 닫힘)
<span class="box chart">진료</span> - 검안실오더 추가 발생시 실시부서진행상태 적용룰 변경  
<span class="box notice">[고시]</span> 신속항원검사 양성 확인 조건 변경  (변경후 신속항원검사 'D662097*' 처방 여부 기준)
<span class="box notice">[고시]</span> 코로나19 대면진료관리료  (코드 : AH240, AH241  주의 : 타질환 진료시 차트 추가)
<span class="box notice">[고시]</span> 코로나19 감염예방관리료 한시적 지원 종료  (4/4일 부터 사용불가 : AH321, AH322, AH323, AH324)

</pre>
---
title: 2018년 6월 감염병 자동신고시스템 연계
mainCategory: 주요 고시
subCategory: 2018년 고시
pageOrder: 5
---

<style>
    pre { margin-top:0px; margin-bottom:0px; margin-left:25px; margin-right:25px; }
    .s1 { margin-top:0px; margin-bottom:-22px; margin-left:40px; margin-right:0px; text-indent:-22px; }
    .s2 { margin-top:10px; margin-left:43px}
    .s3 { margin-top:0px; margin-left:43px}
</style>

<t2><bold>❍ 개요</bold></t2>
<pre>
✔ 사업 추친 배경 및 목적
<div class="s1">✎ 감염병 신고는 의무 신고하도록 되어있습니다.<br/>신고지연이나 누락을 방지하고 조기 발생 인지를 위한 시스템 구축을 목적으로 합니다.</div>
✔ 사용 전 준비
<div class="s1">✎ 질병관리본부 질병보건통합관리시스템 (<a href="http://is.cdc.go.kr" target="_blank">http://is.cdc.go.kr</a>) 에서<br/>사용자 가입 및 인증서 등록</div>
✔ 감염병의 종류
</pre>
<table style="margin-left:25px">
        <tbody style="font-size:15px">
        <tr>
            <td style="width:65px;text-align:center">제 1군</td>
            <td>
                먹는 물에 의해 전염되며 전염속도가 빠르고 사회적 파급 효과가 매우 큰 병<br/>
                1. 콜레라 2. 페스트 3. 장티푸스 4. 파라티푸스 5. 세균성이질 6. 장출혈성 대장균감염증
            </td>
        </tr>
        <tr>
            <td style="width:65px;text-align:center">제 2군</td>
            <td>
                감염병은 전염 속도가 빠른 감염병들이지만 예방접종을 통해 예방할 수 있는 감염병들이며 국가 예방접종사업의 대상<br/>
                01. 디프테리아 2. 백일해 3. 파상풍 4. 홍역 5. 유행성 이하선염 6. 풍진 7. 폴리오 8. B형 간염 9. 일본뇌염 10. 수두
            </td>
        </tr>
        <tr>
            <td style="width:65px;text-align:center">제 3군</td>
            <td>
                1군 전염병만큼 빠르게 전파되고 파급효과가 크지는 않지만, 반복하여 유행할 가능성이 있어서 지속적으로 감시를 하고 유행할 경우에 방역을 위한 대책을 세워야 하는 감염병<br/>
                1. 말라리아 2. 결핵 3. 한센병 4. 성병 · 성전파질환 5. 성홍열 6. 수막구균성 수막염 7. 레지오넬라증 8. 비브리오 패혈증 9. 발진티푸스 10. 발진열 11. 쯔쯔가무시병 12. 렙토스피라증 13. 브루셀라증 14. 탄저병 15. 공수병 16. 신증후군출혈열 17. 인플루엔자 18. 후천성 면역결핍증(AIDS)
            </td>
        </tr>
        <tr>
            <td style="width:65px;text-align:center">제 4군</td>
            <td>
                국내에서 새롭게 발생하거나 국내로 유입될 것이 우려되는 해외의 감염병<br/>
                1. 황열 2. 뎅기열 3. 마르부르그열 4. 에볼라열 5. 라사열 6. 리슈마니아증 7. 바베시아증 8.아프리카 수면병 9. 크립토스포리디움증 10. 주혈흡충증 11. 딸기종 12. 열대백반피부염 13. 두창 14. 보툴리누스중독증 15. 중증급성 호흡기 증후군(SARS) 16. 조류인플루엔자인체감염증 17. 야토병 18. 큐열 19. 신종전염병증후군
            </td>
        </tr>
        <tr>
            <td style="width:65px;text-align:center">지정</td>
            <td>
                1. A형 간염 2. C형 간염 3. 반코마이신내성 황색포도상구균(VRSA)감염증 4. 샤가스병 5. 광동
                주혈선충증 6. 유극악구충증 7. 사상충증 8. 포충증 9. 크로이츠펠트-야콥병(CJD) 및 변종 크로
                이츠펠트-야콥병(vCJD) 10. 살모넬라균감염증 11. 장염비브리오균감염증 12. 장독소성 대장균감
                염증 13. 장침습성 대장균감염증 14. 장병원성 대장균감염증 15. 캄필로박터균감염증 16. 클로
                스트리듐퍼프린젠스감염증 17. 황색포도상구균감염증 18. 바실루스셀레우스균감염증 19. 예르시
                니아엔테로콜리티카감염증 20. 리스테리아모노사이토제네스감염증 21. 그룹 A형 로타바이러스감
                염증 22. 아스트로바이러스감염증 23. 장내아데노바이러스감염증 24. 노로바이러스감염증 25.
                이질아메바감염증 26. 람블편모충감염증
            </td>
        </tr>
    </tbody>
</table>

<t2><bold>❍ 법정감염병 기능 메뉴</bold></t2>
<pre>
✔ 법정감염병 기능 및 자동신고서 메뉴 추가
</pre>
[![](/images/{{page.url}}_1.png)](/images/{{page.url}}_1.png){: target="_blank" .s2 }
<a class="s3">[ 상단메뉴 - 바로가기 화면 ]</a>

<t2><bold>❍ 법정감염병 인증서 정보 등록</bold></t2>
<pre>
✔ 법정감염병 인증서 정보 등록
<div class="s1">✎ 질병관리본부 질병보건통합관리시스템에서 사용할 인증서(청구시 사용하는 인증서)를<br/> 선택 후‘선택’버튼을 눌러 해당 인증서를 등록합니다.</div>
<div class="s1">✎ 해당 작업은 모든 PC에 적용 됩니다.</div>
<div class="s1"><red>✎ 인증서 등록이 완료되지 않으면 신고서를 작성할 수 없습니다.</red></div>
</pre>
[![](/images/{{page.url}}_2.png)](/images/{{page.url}}_2.png){: target="_blank" .s2}  
<a class="s3">[ 인증서 등록 화면 ]</a>

<t2><bold>❍ 법정감염병 진단기준 웹페이지 보기</bold></t2>
<pre>
✔ 법정감염병 진단기준 웹페이지 보기
<div class="s1">✎ 법정감염병코드를 기준으로 진단신고기준, 환자관리 정보등을 확인할 수 있습니다.</div>
</pre>
[![](/images/{{page.url}}_3.png)](/images/{{page.url}}_3.png){: target="_blank" .s2}  
<a class="s3">[ 진단기준 웹페이지 보기 화면 ]</a>

<pre>
<div class="s1">✎ 차트에서 법정감염병코드 사용 시 경고팝업에서 ‘진단기준 웹페이지 보기’로 확인 가능</div>
</pre>
[![](/images/{{page.url}}_4.png)](/images/{{page.url}}_4.png){: target="_blank" .s2}  
<a class="s3">[ 차트 병명 입력 화면 ]</a>

<!--
<t2><bold>❍ 법정감염병 자동신고서 작성</bold></t2>
<pre>
✔ 법정감염병 자동신고서 작성
<div class="s1">✎ 신고 및 내역조회 가능</div>
<div class="s1">✎ 입력항목 중 <red>‘*’</red> 표시된 항목은 필수 항목 입니다.</div>
<div class="s1">✎ 감염병발생신고 / 병원체검사결과신고 / 검체의뢰신고 서식의 경우<br/>차트저장 후 작성이 가능합니다. </div>
<div class="s1">✎ 감염병발생신고 <blue>(차트저장 후 작성 가능)</blue></div>
</pre>


[![](/images/{{page.url}}_5.png)](/images/{{page.url}}_5.png){: target="_blank" .s2}
<a class="s3">[ 감염병발생신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 감염병발생내역조회</div>
</pre>

[![](/images/{{page.url}}_6.png)](/images/{{page.url}}_6.png){: target="_blank" .s2}
<a class="s3">[ 감염병발생내역조회 웹 화면 ]</a>

<pre>
<div class="s1">✎ 병원체검사결과신고 <blue>(차트저장 후 작성 가능)</blue></div>
</pre>

[![](/images/{{page.url}}_7.png)](/images/{{page.url}}_7.png){: target="_blank" .s2}
<a class="s3">[ 병원체검사결과신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 병원체검사결과내역조회</div>
</pre>

[![](/images/{{page.url}}_8.png)](/images/{{page.url}}_8.png){: target="_blank" .s2}
<a class="s3">[ 병원체검사결과내역조회 웹 화면 ]</a>

<pre>
<div class="s1">✎ 검체의뢰신고 <blue>(차트저장 후 작성 가능)</blue></div>
</pre>

[![](/images/{{page.url}}_9.png)](/images/{{page.url}}_9.png){: target="_blank" .s2}
<a class="s3">[ 검체의뢰신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 검체의뢰내역조회</div>
</pre>

[![](/images/{{page.url}}_10.png)](/images/{{page.url}}_10.png){: target="_blank" .s2}
<a class="s3">[ 검체의뢰내역조회 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시 인플루엔자 신고 <blue>(의원급중 해당 기관)</blue></div>
</pre>

[![](/images/{{page.url}}_11.png)](/images/{{page.url}}_11.png){: target="_blank" .s2}
<a class="s3">[ 표본감시 인플루엔자 신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시 수족구병 신고 <blue>(의원급중 해당 기관)</blue></div>
</pre>

[![](/images/{{page.url}}_12.png)](/images/{{page.url}}_12.png){: target="_blank" .s2}
<a class="s3">[ 표본감시 수족구병 신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시 안과감염병 신고 <blue>(의원급중 해당 기관)</blue></div>
</pre>

[![](/images/{{page.url}}_13.png)](/images/{{page.url}}_13.png){: target="_blank" .s2}
<a class="s3">[ 표본감시 안과감염병 신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시 안과감염병 신고 <red>(병원급 중 해당 기관)</red></div>
</pre>

[![](/images/{{page.url}}_14.png)](/images/{{page.url}}_14.png){: target="_blank" .s2}
<a class="s3">[ 표본감시신고 장관감염증 신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시신고 장관감염증 내역조회</div>
</pre>

[![](/images/{{page.url}}_15.png)](/images/{{page.url}}_15.png){: target="_blank" .s2}
<a class="s3">[ 표본감시신고 장관감염증 내역조회 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시신고 급성호흡기감염증 신고 <red>(병원급 중 해당 기관)</red></div>
</pre>

[![](/images/{{page.url}}_16.png)](/images/{{page.url}}_16.png){: target="_blank" .s2}
<a class="s3">[ 표본감시신고 급성호흡기감염증 신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시신고 급성호흡기감염증 내역조회</div>
</pre>

[![](/images/{{page.url}}_17.png)](/images/{{page.url}}_17.png){: target="_blank" .s2}
<a class="s3">[ 표본감시신고 급성호흡기감염증 내역조회 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시신고 엔테로바이러스감염증 신고 <red>(병원급 중 해당 기관)</red></div>
</pre>

[![](/images/{{page.url}}_18.png)](/images/{{page.url}}_18.png){: target="_blank" .s2}
<a class="s3">[ 표본감시신고 엔테로바이러스감염증 신고 웹 화면 ]</a>

<pre>
<div class="s1">✎ 표본감시신고 엔테로바이러스감염증 내역조회</div>
</pre>

[![](/images/{{page.url}}_19.png)](/images/{{page.url}}_19.png){: target="_blank" .s2}
<a class="s3">[ 표본감시신고 엔테로바이러스감염증 내역조회 웹 화면 ]</a>
-->
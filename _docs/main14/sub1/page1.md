---
title: 상병/처방 드래그 기능 추가
mainCategory: 업데이트 완료
subCategory: 주요 기능
pageOrder: 1
---

<br>

## 개요

- 병명, 수가명 드래그하여 순서 이동 
- 코드 드래그하여 선택한 후 일괄 삭제
- 수량/횟수/일수/용법코드/본인부담 드래그하여 선택한 후 일괄 적용
<br><span style="color:#696868; padding-left: 0px;">        ※ 드래그 중 Escape Key 로 동작을 취소할 수 있습니다.</span>

<br>

## 기능 상세

- 병명, 수가명 드래그하여 순서 이동 
    - 병명 및 처방 사용자 설정에서 **순서 이동 (병명, 수가, 슬립증상)** 옵션을 설정합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_1.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_1.png">
        </a>
    </td>
</table>
<span style="padding-left: 30px;">    ① 상병 창에서 **상병명** 을 선택한 후 마우스를 끌어 다른 줄로 위치를 변경합니다.</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_2.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_2.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 네 번째 줄 U07.1 상병 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_3.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_3.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 첫 번째 줄 I10.9 주상병으로 위치 이동</span>
<br>

<span style="padding-left: 30px;">    ② 처방 창에서 **수가명** 을 선택한 후 마우스를 끌어 다른 줄로 위치를 변경합니다. </span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_4.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_4.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 첫 번째 줄 G2501 검사 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_5.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_5.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 네 번째 줄 G1101 검사로 위치 이동</span>
<br>

<span style="padding-left: 30px;">    ③ 처방 창에서 **증상** 을 선택한 후 마우스를 끌어 다른 줄로 위치를 변경합니다. </span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_6.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_6.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 두 번째 줄 증상 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_7.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_7.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 여덟 번째 줄 증상으로 위치 이동</span>
<br>
<br>

- 코드 드래그하여 선택한 후 일괄 삭제
    - 병명 및 처방 사용자 설정에서 **드래그 선택 기능 사용** 옵션을 설정합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_8.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_8.png">
        </a>
    </td>
</table>
<span style="padding-left: 30px;">    ① 상병 창 **코드** 에서 마우스를 끌어 여러 건을 선택한 후 Delete Key 로 일괄 삭제합니다.</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_9.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_9.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 첫 번째 줄 J01.00 부터 세 번째 줄 J20.9 상병 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_10.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_10.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ Delete Key 로 선택 상병 삭제</span>
<br>

<span style="padding-left: 30px;">    ② 처방 창 **코드** 에서 마우스를 끌어 여러 건을 선택한 후 Delete Key 로 일괄 삭제합니다.</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_11.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_11.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 네 번째 줄 G1101 부터 다섯 번째 줄 F6300 검사 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_12.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_12.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ Delete Key 로 선택 검사 삭제</span>
<br>
<br>

- 수량/횟수/일수/용법코드/본인부담 드래그하여 선택한 후 일괄 적용
    - 병명 및 처방 사용자 설정에서 **드래그 선택 기능 사용** 옵션을 설정합니다.
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_8.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_8.png">
        </a>
    </td>
</table>
<span style="padding-left: 30px;">    ① 처방 창 **수량/횟수/일수** 에서 마우스를 끌어 여러 건을 선택하면 일괄 변경 창이 팝업됩니다.</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_13.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_13.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 두 번째 줄 640000480 내복약부터 여덟 번째 줄 MM010 수가 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_14.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_14.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 팝업된 창에서 변경 후 수량/횟수/일수 입력</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_15.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_15.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ Enter Key 로 선택 내복약 수량/횟수/일수 적용</span>
<br>
<span style="color:red; padding-left: 30px;">        ※ 우선순위에 따라 일괄 변경 동작 (오편집 방지)</span>
<br>
<span style="color:red; padding-left: 50px;">        - 내복, 외용 약가 우선 적용</span>
<br>
<span style="color:red; padding-left: 50px;">        - 내복, 외용 약가가 없을 경우 주사제 우선 적용</span>
<br>
<span style="color:red; padding-left: 50px;">        - 내복, 외용, 주사제가 없을 경우 동일한 분류(항목번호)를 선택했을 때에만 일괄 변경 창 팝업</span>
<br>

<span style="padding-left: 30px;">    ② 처방 창 **용법** 에서 마우스를 끌어 여러 건을 선택하면 일괄 변경 창이 팝업됩니다.</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_16.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_16.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 네 번째 줄 645304790 부터 일곱 번째 줄 642000250 외용약 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_17.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_17.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 팝업된 창에서 변경 후 용법코드 입력</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_18.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_18.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ Enter Key 로 선택 외용약 용법코드 적용</span>
<br>
<span style="color:red; padding-left: 30px;">        ※ 우선순위에 따라 일괄 변경 동작 (오편집 방지)</span>
<br>
<span style="color:red; padding-left: 50px;">        - 내복, 외용 약가 우선 적용</span>
<br>
<span style="color:red; padding-left: 50px;">        - 내복, 외용 약가가 없을 경우 주사제 우선 적용</span>
<br>
<span style="color:red; padding-left: 50px;">        - 내복, 외용, 주사제가 없을 경우 동일한 실시부서를 선택했을 때에만 부위 일괄 변경 창 팝업</span>
<br>

<span style="padding-left: 30px;">    ③ 처방 창 **본인부담** 에서 마우스를 끌어 여러 건을 선택하면 일괄 변경 창이 팝업됩니다.</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_19.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_19.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 첫 번째 줄 G2501 검사부터 열 번째 줄 641600030 내복약 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_20.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_20.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ 팝업된 창에서 변경 후 본인부담 선택</span>
<table class="imgBox">
    <td class="imgBox">
        <a href="/images/{{page.url}}_21.png" target="_blank">
            <img class="minCenter" src="/images/{{page.url}}_21.png">
        </a>
    </td>
</table>
<span style="color:#696868; padding-left: 30px;">▲ Enter Key 로 선택 처방 본인부담 적용</span>
<br>
<span style="color:red; padding-left: 30px;">        ※ 우선순위 없이 선택된 모든 처방을 대상으로 일괄 변경 창 팝업 및 적용</span>
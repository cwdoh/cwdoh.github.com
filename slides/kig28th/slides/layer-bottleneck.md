## GPU와 연계시켜 보면

<br/>

* ### 각 레이어는 크기만큼의 메모리를 할당
<ul>
<li class="fragment roll-in">레이어가 많아지면? <span class="fragment">레이어의 메모리 점유율 상승</span></li>
<li class="fragment roll-in">메모리가 부족하면? <span class="fragment">버퍼 사용을 위해 기존 레이어 제거</span></li>
<li class="fragment roll-in">레이어가 제거되면? <span class="fragment">렌더링이 필요할 때 레이어를 재전송</span></li>
<li class="fragment roll-in">전송이 반복되면? <span class="fragment">렌더링의 총 시간이 증가</span></li>
</ul>
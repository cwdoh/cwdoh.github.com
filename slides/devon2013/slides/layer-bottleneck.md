## GPU 동작

<br/>

* ### 각 레이어는 크기만큼의 메모리를 할당
* #### 레이어가 많아지면? <span class="fragment">레이어의 메모리 점유율 상승</span>
* #### 메모리가 부족하면? <span class="fragment">버퍼 사용을 위해 기존 레이어 제거</span>
* #### 레이어가 제거되면? <span class="fragment">렌더링이 필요할 때 레이어를 재전송</span>
* #### 전송이 반복되면? <span class="fragment">렌더링의 총 시간이 증가</span>

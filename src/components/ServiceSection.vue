<template>
     <section class="text_wrap">

            <div class="text_container">
                <div class="text01">
                    <span>Sign Up</span>
                    <h2>WHY Artek</h2>
                    <p>100년 역사의 아르텍의 특별한 <br>서비스를 제공드립니다.</p>
                </div>
                <div class="text_box1">
                    <div class="text">
                        <h2>정밀검사</h2>
                        <p>고객님들께 최상의 제품을 전달드리기위해<br>꼼꼼히 검수하여 배송 드립니다.
                            <br>정밀검사를 마친 제품은 실시간 확인 가능합니다.
                        </p>
                    </div>
                    <div class="text">
                        <h2>전문 AS 지원</h2>
                        <p>수령 시 제품 문제 AS는 제품 리콜 후<br> 수리,새 제품 발송,부품 발송 등의 방식이
                            사용됩니다.<br>1개월 이상 소요 시 100% 환불됩니다.
                        </p>
                    </div>
                </div>
                <div class="text_box2">
                    <div class="text">
                        <h2>정품 보장</h2>
                        <p>저희 Aretek은 현재까지 판매한 상품 중<br>
                            단 하나의 가품도 없었습니다.<br>브랜드 공식 딜러십을 가진 업체만 거래합니다.</p>
                    </div>
                    <div class="text">
                        <h2>가장 빠른 배송</h2>
                        <p>미리 제작되어 있는 따끈따끈한<br>
                            상품을 구매하면 2~3달이 걸리는 긴 제작과정 없이<br>
                            가장 빠르게 받아보실 수 있습니다.</p>
                    </div>
                </div>
            </div>
        </section>
</template>
<style scoped>
.text_wrap{
    height: 400px;

}


.text_container{
    display:flex;
    justify-content: space-between;
    position: relative;
}

.text_container .text01{
    margin: 60px;
    padding: 60px;
    text-align: center;
}

.text_container .text01 span{
    text-align: center;
    background: #eee;
    border-radius: 30px;
    width: 100px; height: 30px;
    display: inline-block;
    line-height: 30px;
}

.text_container .text01 h2{
    margin: 10px;
}

 .text_box1{
  position: absolute;left:40%;top: 30px;

;}
 
    .text_box1>.text:nth-child(1){
       margin-top: 50px;
    }

    .text_box1>.text:nth-child(2){
        margin-top: 50px;
    }

    .text_box2{
       
        position: absolute;
        right:10%;top: 30px;
    }

    .text_box2>.text:nth-child(1){
        margin-top: 50px;
     }
 
     .text_box2>.text:nth-child(2){
         margin-top: 50px;
     }
</style>
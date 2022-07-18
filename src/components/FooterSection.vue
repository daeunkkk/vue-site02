<template>
        <footer id="footerType" class="footer__wrap section nexon gray">
        <h2 class="ir_so">푸터 영역</h2>
        <div class="footer__inner container">
            <div class="footer__menu">
                <div>
                    <h3>Artek</h3>
                    <ul>
                        <li><a href="/">Nils-Gustav Hahl</a></li>
                        <li><a href="/"></a></li>
                    </ul>
                </div>
                <div>
                    <h3>고객센터</h3>
                    <ul>
                        <li><a href="/">1688-1547</a></li>
                        <li><a href="/">채팅상담 09:00~18:00</a></li>
                        <li><a href="/">문의메일 artek@naver.com</a></li>
                    </ul>
                </div>
                <div>
                    <h3>개인정보방침</h3>
                    <ul>
                        <li><a href="/">개인정보동의</a></li>
                        <li><a href="/">개인정보동의</a></li>
                        <li><a href="/">개인정보동의</a></li>
                    </ul>
                </div>
        
                <div>
                    <h3>공지사항</h3>
                    <ul>
                        <li><a href="/">배송공지</a></li>
                        <li><a href="/">이벤트공지</a></li>
                    </ul>
                </div>
                <div>
                    <h3>Q&A</h3>
                    <ul>
                        <li><a href="/">많이하는질문</a></li>
                        <li><a href="/">1:1상담신청</a></li>
                        <li><a href="/">신고하기</a></li>
                    </ul>
                </div>
            </div>
            <address class="footer__right">
                ©2022 artek. All rights reserved.
            </address>
        </div>
    </footer>
</template>

<style scoped>
footer {
    background: #eceff1;
    height: 150px;
}
.footer__menu {
    display: flex;
    justify-content: space-between;
    padding: 20px;

}

.footer__menu > div:nth-child(1){
    margin-left: 100px;
}
.footer__menu > div {
    width: 16%;
    text-align: left;
}
.footer__menu > div h3 {
    font-size: 20px;
    font-weight: 500;
    margin-bottom: 20px;
}
.footer__menu > div li a {
    font-size: 16px;
    line-height: 1.6;
    color: #777;
    font-weight: 300;
}
.footer__right {

    margin-top:20px;
    padding-top: 30px;
    height: 30px;
    text-align: center;

}
</style>
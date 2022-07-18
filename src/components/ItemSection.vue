<template>
        <section id="cont_4">
            <div class="best_item">
                <div class="item_intro">
                    <h2>Artek Best Item</h2>
                    <p>가장 인기있는 Hot한 제품만 모아놨습니다.</p>
                </div>
                <div class="item_wrrap">
                    <div class="item_img">
                
                        <div><a href="/"><img src="../assets/img/7_135439.jpg" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                   
                        <div><a href="/"><img src="../assets/img/1000083546_main_066.png" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                    </div>
                    <div class="item_img">
                        <div><a href="/"><img src="../assets/img/1000083469_main_077.jpg" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                        <div><a href="/"><img src="../assets/img/1000065031_main_05.jpg" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                    </div>
                    <div class="item_img">
                        <div><a href="/"><img src="../assets/img/1000123616_main_035.jpg" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                        <div><a href="/"><img src="../assets/img/1000083546_main_066.png" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                    </div>
                    <div class="item_img">
                        <div><a href="/"><img src="../assets/img/5744610816_main_220619.png" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                        <div><a href="/"><img src="../assets/img/5741104558_main_220619.png" alt=""/></a>
                            <h2>Fritz Hansen</h2>
                            <p>에그 라운지체어</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
</template>
<style scoped>

.best_item{text-align: center;margin-top: 20px;
margin-bottom: 50px;}

.item_intro h2{
    background: #000;
    display: inline;
    color: #fff;
}
.item_intro p{
    padding-top: 10px;
    margin-bottom: 20px;
}
.item_wrrap{
display: flex;
justify-content: space-around;
text-align: center;
}

.item_img>div a {
    padding: 10px;
}
.item_img>div a img{
 width: 150px;height: 150px;
 padding-bottom: 20px;
}
.item_img>div a img:hover {transform: rotateZ(100);}
</style>
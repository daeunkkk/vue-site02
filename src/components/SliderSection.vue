<template>
     <section class="Slider">
            <div class="slider_wrap">
                <h2 class="ir_so">슬라이드 배너</h2>
                <div class="slider_inner">
                    <div class="slider_img">
                        <img src="../assets/img/463d163fac17aa28e4b0ad080a2e4b6f_82616.jpg" alt="">
                    </div>
                    <i class="fas fa-chevron-left fa-2x prev"></i>
                    <i class="fas fa-chevron-right fa-2x next"></i>
                    <div></div>
                    <div class="slider_dot">
                        <ul class="dot">
                            <li><a href="/"><span class="ir_so">1</span></a></li>
                            <li><a href="/"><span class="ir_so">2</span></a></li>
                            <li><a href="/"><span class="ir_so">3</span></a></li>
                            <li><a href="/"><span class="ir_so">4</span></a></li>
                            <li><a href="/"><span class="ir_so">5</span></a></li>
                        </ul>
                    </div>
                </div>
            </div>


        </section>
</template>
<style scoped>
.slider_inner{position: relative;}

.prev {
  position: absolute;
  top: 40%;
  left: 10px;
  width: 40px;height: 40px;
  color: #fff;
}
.next{
  position: absolute;
  top: 40%;
  right: 10px;
  color: #fff;
}

.slider_dot{
  display: flex;
  flex-wrap: wrap;
  flex-direction:row; /*수평 정렬*/
  align-items: center;
  justify-content: center;}
.slider_dot ul{position: absolute;bottom: 0;}
.slider_dot ul li{display: inline-block;}
.slider_dot ul li a{
  display: block;
  width: 50px;
  height: 3px;
  background: rgba(255, 255, 255, 0.796);
  border: none;
margin-bottom: 10px;}


</style>
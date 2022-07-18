<template>
       <header id="header">
        <div class="header_nav">
            <h2>Artek</h2>
            <ul>
                <li><a href="/">가구</a></li>
                <li><a href="/">조명</a></li>
                <li><a href="/">홈데코</a></li>
                <li><a href="/">키친</a></li>
                <li><a href="/">빠른배송</a></li>
            </ul>
        </div>
        <div class="header_search">
            <input type="text" id="search">
        </div>
        <a href="/"><i class="fas fa-search"></i></a>
    </header>
</template>
<style scoped>
#header{text-align: center;}
#header h2{font-size: 5em;   margin: 5px;}
#header ul { margin-top: 20px;}
#header ul li {display: inline-block; padding:0 40px; margin: 20px;} 
#header ul li a { font-size: 15px;}
#header ul li a :hover {color:#fff}
.header_search {position: absolute;top: 0; right: 40px;margin-top: 30px;}
.header_search input {width: 150px; height: 30px;border-radius: 30px; border: 1px solid;
}
#header a i{position: absolute; right: 50px;top: 38px;}


</style>
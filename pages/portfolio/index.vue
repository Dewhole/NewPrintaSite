<template>
  <div class="main">
    <pageHeader/>
        <div class="portfolio">
            <div class="title">ПОРТФОЛИО</div>
            <div class="main-section">
                <div class="main-header">
                    <button class="all category">ALL</button>
                    <button class="internet category">ИНТЕРНЕТ МАГАЗИН</button>
                    <button class="corp category">КОРПОРАТИВНЫЙ САЙТ</button>
                    <button class="landing category">LANDING PAGE</button>
                    <button class="card category">САЙТ ВИЗИТКА</button>
                    <button class="prototype category">ПРОТОТИП</button>
                    <button class="design category">ДИЗАЙН</button>
                </div>
            </div>
                <div class="block1"></div>
            </div>
            <div class="prefooter">
                <h2 class="text">ПОНРАВИЛИСЬ НАШИ РАБОТЫ?</h2>
                <button class="pink-button">Связаться с менеджером</button>
            </div>
   <pageFooter/>
  </div>

</template>

<script>

import pageHeader from '~/components/pageHeader.vue'
import pageFooter from '~/components/pageFooter.vue'
export default {
  components: {
    pageHeader,
    pageFooter,
  }
}
</script>

<style>
.text{
    margin-top: 15px;
    font-size: 24px;
    letter-spacing: 0.05em;
    font-family: "Roboto slab", sans-serif;
    margin-right: 40px;
}
.pink-button{
    padding: 13px 34px;
    border: 3px solid #fff;
    margin-left: 40px;

}
.prefooter{
    color: #fff;
    font-size: 18px;
    font-weight: 700;
    display: flex;
    padding: 50px 0px 50px 0px;
    background-color: #ec008c;
    justify-content: center;

}
.flexbox{
    display: flex;
}
.block1{   
    background: url(/akva1.jpg);
}
.block2{   
    background: url(/millory1.jpg);
}
.block3{   
    background: url(/missis1.jpg);
}
.block4{   
    background: url(/uctez1.jpg);
}
.block5{   
    background: url(/vt1.jpg);
}
.block6{   
    background: url(/apokr1.jpg);
}
.block{
    height: 555px;
    max-width: 555px;
    background-repeat: no-repeat;
}
.category.active, .category:hover {
    border-color: #ec008c;
}
.category{
    border: 3px solid #dedede;
    margin: 0 5px 5px 0;
    padding: 7px 15px;
    color: #ababab;
}
.main-header{

    list-style: none;
    margin-bottom: 40px;
    margin-top: 40px;
    cursor: default;
    font-size: 16px;
    text-align: center;
}
.title{
    font-size: 36px;
    color: white;
    padding: 80px;
    padding-bottom: 80px;
    background-color: #d0d0d0;
    text-align: center;
}
</style>
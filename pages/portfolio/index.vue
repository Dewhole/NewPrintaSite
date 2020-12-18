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
                <div class="flex-blocks">
                    <div class="block block1">
                        <div class="block-text">
                            <div class="text-margin">
                                <a href=""><h3>ИНТЕРНЕТ-МАГАЗИН АКВАЛИНИЯ</h3><span>ИНТЕРНЕТ-МАГАЗИН</span></a><br>
                                <div class="black-button"><a href="" class="block-button">Подробнее</a></div>
                            </div>
                        </div>
                    </div>
                    <div class="block block2">
                        <div class="block-text">
                            <div class="text-margin">
                                <a href=""><h3>ЛЕНДИНГ MILLORY</h3><span>ЛЕНДИНГ</span></a><br>
                                <div class="black-button"><a href="" class="block-button">Подробнее</a></div>
                            </div>
                        </div>
                    </div>                    
                </div>
                    <div class="flex-blocks">
                        <div class="block block3">
                            <div class="block-text">
                                <div class="text-margin">
                                    <a href=""><h3>САЙТ МИССИС НОВОСИБИРСК INT</h3><span>САЙТ ВИЗИТКА</span></a><br>
                                    <div class="black-button"><a href="" class="block-button">Подробнее</a></div>
                                </div>
                            </div>
                        </div>
                        <div class="block block4">
                            <div class="block-text">
                                <div class="text-margin">
                                    <a href=""><h3>КОРПОРАТИВНЫЙ САЙТ УЦ</h3><span>КОРПОРАТИВНЫЙ САЙТ</span></a><br>
                                    <div class="black-button"><a href="" class="block-button">Подробнее</a></div>
                                </div>
                            </div>
                        </div>
                    </div>
                <div class="flex-blocks">
                    <div class="block block5">
                        <div class="block-text">
                            <div class="text-margin">
                                <a href=""><h3>ПРОТОТИП САЙТА ВОСТОЧНАЯ ТЕХНИКА</h3><span>ПРОТОТИП САЙТА</span></a><br>
                                <div class="black-button"><a href="" class="block-button">Подробнее</a></div>
                            </div>
                        </div>
                    </div>
                    <div class="block block6">
                        <div class="block-text">
                            <div class="text-margin">
                                <a href=""><h3>САЙТ АССОЦИАЦИИ ПОДРЯДНЫХ ОРГАНИЗАЦИЙ КАПИТАЛЬНОГО РЕМОНТА</h3><span>САЙТ ВИЗИТКА</span></a><br>
                                <div class="black-button"><a href="" class="block-button">Подробнее</a></div>
                            </div>
                        </div>
                    </div>
                </div>
                
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


.h3{
    font-family: "Roboto slab", sans-serif;
    margin-top: 0;
    text-transform: uppercase;
    color: #646464;
    letter-spacing: 0.05em;
    font-weight: 700;
}
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
    margin-top: 40px;

}
.flexbox{
    display: flex;
}
.text-margin{
    margin-top: 45%;
    
}


/* 123123123123 */
.block-text{
    text-align: center;
    display: flex;
    flex-direction: column;
    margin: auto;
    height: 100%;
    width: 555px;
    font-size: 20px;
    opacity: 0
}
.block-button{
    font-size: 20px;
    padding: 18px 35px;
    background: transparent;
    border: 3px solid #fff;
    position: relative;
    top: 40px;
    
}
.block a{
    text-decoration: none;
    color: white;
}
.black-button a:hover{
    font-size: 20px;
    padding: 18px 35px;
    background: transparent;
    background-color: black;
    position: relative;
    top: 40px;
    transition: 1s;
        
}     
.block :hover{   
    background-color: rgba(236, 0, 140, 0.6);
    border: 5px solid rgba(255, 255, 255, 0.2);
    background-size: 100%;

    transition: 0.5s;
    opacity: 1
}
.block-text :hover{
    background: transparent;
    border: none;
    opacity: 1
}

.block1{   
    background: url(/akva1.jpg);
    background-position-x: -60px;
}
.block2{   
    background: url(/millory1.jpg);
    background-position-x: -110px;
}
.block3{   
    background: url(/missis1.jpg);
    background-position-x: -110px;
}
.block4{   
    background: url(/uctez1.jpg);
    background-position-x: -110px;
}
.block5{   
    background: url(/vt1.jpg);
    background-position-x: -110px;
}
.block6{   
    background: url(/apokr1.jpg);
    background-position-x: -130px;
}
.block{
    height: 555px;
    max-width: 555px;
    background-repeat: no-repeat;
    margin: auto;
    
}
.flex-blocks{
    display: flex;
    max-width: 1160px;
    margin: auto;   
    margin-bottom: 20px;
}
/* 123123123123 */


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
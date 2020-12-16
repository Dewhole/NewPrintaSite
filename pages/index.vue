<template id="app">
<div class="main" id="app">
      <span
         class="menu-point"
         v-bind:class="{active: activeSection == index}"
         v-on:click="scrollToSection(index)"
         v-for="(offset, index) in offsets"
         v-bind:key="index">
      </span>

  <div class="section section1-bg-image">
    <div class="pageHeader"><pageHeader/></div>

      <div class="section1">
        <div class="block-for-pink">
          <div class="pink-block">
            <div class="section1-text">ИНТЕРНЕТ РЕШЕНИЯ <br> ДЛЯ ВАШИХ ЗАДАЧ</div>
          </div>
        </div>
      </div>
    </div>



    <div class="section section2-bg-image">
      <div class="block-for-pink2-5">
        <div class="pink-block2">
          <div class="section2-5-content">
            <div class="section2-5-title"><h2>ЗАКАЗАТЬ ИНТЕРНЕТ-МАГАЗИН:</h2>
            <p class="section2-5-subtitle">Начни продавать онлайн</p>
            </div>
            <div class="section2-5-padding"></div>
            <div class="section2-5-rows section2-row1">
              <div class="section2-5-icon section2-row1-icon1"><img src="/time-icon.png" alt=""></div>
              <div class="section2-5-text section2-row1-text1">Продажи круглосуточно 7 дней в неделю без дополнительных затрат</div>
            </div>
            <div class="section2-5-rows section2-row2">
              <div class="section2-5-icon section2-row2-icon2"><img src="/sale-icon.png" alt=""></div>
              <div class="section2-5-text section2-row2-text2">Увеличение длины чека и частоты покупок более чем на 20%</div>
            </div>
            <div class="section2-5-rows section2-row3">
              <div class="section2-5-icon section2-row3-icon3"><img src="/many-icon.png" alt=""></div>
              <div class="section2-5-text section2-row3-text3">Полный контроль расходов, отсутствие финансовых потерь</div>
            </div>
            <div class="section2-5-button"><a href="" class="section2-5-button-href">Заказать от 50.000₽</a></div>
          
          </div>
        </div>
      </div>
    </div>



    <div class="section section3-bg-image">
      <div class="block-for-pink2-5">
        <div class="pink-block3">
          <div class="section2-5-content">
            <div class="section2-5-title"><h2>ЗАКАЗАТЬ КОРПОРАТИВНЫЙ САЙТ:</h2>
            <p class="section2-5-subtitle">Ваш новый офис в сети</p>
            </div>
            <div class="section2-5-padding"></div>
            <div class="section2-5-rows section2-row1">
              <div class="section2-5-icon section2-row1-icon1"><img src="/oper-icon.png" alt=""></div>
              <div class="section2-5-text section2-row1-text1">Больше клиентов - проще коммуникации</div>
            </div>
            <div class="section2-5-rows section2-row2">
              <div class="section2-5-icon section2-row2-icon2"><img src="/bril-icon.png" alt=""></div>
              <div class="section2-5-text section2-row2-text2">Лучше имидж - крупнее контракты</div>
            </div>
            <div class="section2-5-rows section2-row3">
              <div class="section2-5-icon section2-row3-icon3"><img src="/grom-icon.png" alt=""></div>
              <div class="section2-5-text section2-row3-text3">Шире охват - больше клиентов</div>
            </div>
            <div class="section2-5-button"><a href="" class="section2-5-button-href">Заказать от 40.000₽</a></div>
          
          </div>
        </div>
      </div>
    </div>



    <div class="section section4-bg-image">
      <div class="block-for-pink2-5">
        <div class="pink-block4">
          <div class="section2-5-content">
            <div class="section2-5-title"><h2>ЗАКАЗАТЬ LANDING PAGE</h2>
            <p class="section2-5-subtitle">Быстрые продажи в интернет</p>
            </div>
            <div class="section2-5-padding"></div>
            <div class="section2-5-rows section2-row1">
              <div class="section2-5-icon section2-row1-icon1"><img src="/tet-icon.png" alt=""></div>
              <div class="section2-5-text section2-row1-text1">Все предложения на одной странице, компактно и эффективно</div>
            </div>
            <div class="section2-5-rows section2-row2">
              <div class="section2-5-icon section2-row2-icon2"><img src="/mon-icon.png" alt=""></div>
              <div class="section2-5-text section2-row2-text2">Быстрое продвижение, результаты уже через месяц</div>
            </div>
            <div class="section2-5-rows section2-row3">
              <div class="section2-5-icon section2-row3-icon3"><img src="/dollar-icon.png" alt=""></div>
              <div class="section2-5-text section2-row3-text3">Реальная экономия на сроках и деньгах</div>
            </div>
            <div class="section2-5-button"><a href="" class="section2-5-button-href">Заказать от 17.000₽</a></div>
          
          </div>
        </div>
      </div>
    </div>



    <div class="section section5-bg-image">
      <div class="block-for-pink2-5">
        <div class="pink-block5">
          <div class="section2-5-content">
            <div class="section2-5-title"><h2>ЗАКАЗАТЬ САЙТ ВИЗИТКУ:</h2>
            <p class="section2-5-subtitle">Расскажите о своих<br> преимуществах клиентам</p>
            </div>
            <div class="section2-5-padding"></div>
            <div class="section2-5-rows section2-row1">
              <div class="section2-5-icon section2-row1-icon1"><img src="/brow-icon.png" alt=""></div>
              <div class="section2-5-text section2-row1-text1">Всё о Вашей компании лаконично, удобно, компактно</div>
            </div>
            <div class="section2-5-rows section2-row2">
              <div class="section2-5-icon section2-row2-icon2"><img src="/grom-icon.png" alt=""></div>
              <div class="section2-5-text section2-row2-text2">Увеличение охвата и привлечение новых клиентов</div>
            </div>
            <div class="section2-5-rows section2-row3">
              <div class="section2-5-icon section2-row3-icon3"><img src="/good-icon.png" alt=""></div>
              <div class="section2-5-text section2-row3-text3">Идеальное решение для малого бизнеса</div>
            </div>
            <div class="section2-5-button"><a href="" class="section2-5-button-href">Заказать от 25.000₽</a></div>
          
          </div>
        </div>
      </div>
    </div>



  <div class="section section6">
    <div class="section6-bg-image">
      <div class="section6-icon"><img src="/logo-w.png" alt=""></div>
      <div class="section6-text">Мы убеждены, что при создании сайта нужно учитывать все факторы интересные для клиента, разработанный сайт должен быть удобным, понятным и функциональным для клиента. А система управления сайтом(CMS) должна максимально подходить для ваших задач и помогать в эффективном управлении сайта, а не создавать дополнительные трудности.</div>
      <div class="section6-subtext">УДОБСТВО. ФУНКЦИОНАЛЬНОСТЬ. КОНВЕРСИЯ</div>
    </div>
    <div class="section6-footer">
      <div class="aaa">
      <div class="section6-pink-block">
        <div class="section6-pink-block-icon"><img src="iconshome-12.png" alt=""></div>
        <div class="section6-pink-text-block">
          <div class="section6-pink-block-text1">7</div>          
          <div class="section6-pink-block-text2">Лет работы</div>  
        </div>   
      </div>
      <div class="section6-pink-block">
        <div class="section6-pink-block-icon"><img src="iconshome-13.png" alt=""></div>
        <div class="section6-pink-text-block">
          <div class="section6-pink-block-text1">15</div>          
          <div class="section6-pink-block-text2">Специалистов</div>  
        </div>         
      </div>
      <div class="section6-pink-block">
        <div class="section6-pink-block-icon"><img src="iconshome-14.png" alt=""></div> 
        <div class="section6-pink-text-block">
          <div class="section6-pink-block-text1">124</div>          
          <div class="section6-pink-block-text2">Довольных клиента</div>  
        </div>        
      </div>
      </div>
    </div>
  </div> 



  <div class="section section7">
    <div class="section7-bg-image">
      <div class="section7-hight">
      <div class="section7-title">ПРОДВИНУТЫЙ СЕРВИС</div>
      <div class="section7-hr"></div>
      <div class="section7-text">Это создание сайтов под ключ, эффективно и качественно</div>
    </div>
    </div>
      <div class="section7-blocks1 ">
      <div class="section7-white-block">
        <div class="section7-white-block-icon"><img src="iconshome-12.png" alt=""></div>
        <div class="section7-white-title-block">АНАЛИЗ</div> 
        <div class="section7-white-text-block">Бизнес без анализа - это игра в слепую. Мы анализируем конкурентную среду и результаты РК</div>   
      </div>
      <div class="section7-white-block">
        <div class="section7-white-block-icon"><img src="iconshome-13.png" alt=""></div>
      <div class="section7-white-title-block">ВЕБ-ДИЗАЙН</div> 
        <div class="section7-white-text-block">Для создания уникального и продвинутого сайта мы предлагаем разработку дизайна</div>       
      </div>
      <div class="section7-white-block">
        <div class="section7-white-block-icon"><img src="iconshome-14.png" alt=""></div> 
        <div class="section7-white-title-block">МАРКЕТИНГ</div> 
        <div class="section7-white-text-block">Для успешного продвижения своих услуг, требуется грамотное позиционирование</div>       
      </div>
    </div>

      <div class="section7-blocks2 ">
      <div class="section7-white-block">
        <div class="section7-white-block-icon"><img src="iconshome-12.png" alt=""></div>
        <div class="section7-white-title-block">ПОДДЕРЖКА</div> 
        <div class="section7-white-text-block">Поддержка, наполнение и ведение сайта необходимы для его нормального функционирования</div>   
      </div>
      <div class="section7-white-block">
        <div class="section7-white-block-icon"><img src="iconshome-13.png" alt=""></div>
      <div class="section7-white-title-block">ПРОДВИЖЕНИЕ</div> 
        <div class="section7-white-text-block">Без продвижения сайт не эффективен. Инструменты Яндекс и Google сделают сайт посещаемым</div>       
      </div>
      <div class="section7-white-block">
        <div class="section7-white-block-icon"><img src="iconshome-14.png" alt=""></div> 
        <div class="section7-white-title-block">ИЗОБРАЖЕНИЯ</div> 
        <div class="section7-white-text-block">Качественные изображения делают сайт привлекательнее и увеличивают конверсию</div>       
      </div>
    </div>
  </div> 

</div>
</template>

<script>

import pageHeader from '~/components/pageHeader.vue'
export default {
  components: {
    pageHeader,

  }
}




</script>

<style>
.pageHeader{
  position: sticky;
  top: 0;
}
.section{
  width: 100%;
  height: 100%;
}
.main{
margin: 0;
    padding: 0;
    font-family: "Roboto slab", sans-serif;
    color: #646464;
    font-size: 16px;
    line-height: 1.5;

    -webkit-font-smoothing: antialiased;
    background: #f5f0f0;
    outline: 0;
    overflow-x: hidden;
    overflow-y: auto;
}
.header a{
  text-decoration: none;
  color: #fff;
  outline: none;
  -webkit-transition: color 0.2s ease-in-out;
  -moz-transition: color 0.2s ease-in-out;
  -ms-transition: color 0.2s ease-in-out;
  -o-transition: color 0.2s ease-in-out;
  transition: color 0.2s ease-in-out;
}

/* section 7 */
.section7-hight{
  text-align: center;
  margin: auto;
}
.section7-hr{
  width: 170px;
  border-top: 3px solid #959595;

  text-align: center;
  margin: auto;
  margin-top: 20px;
  margin-bottom: 20px;
}
.section7-title{
  font-family: "Roboto slab", sans-serif;
  font-size: 28px;
  font-weight: 700;
  margin-top: 130px;
}
.section7-blocks1{
  max-width: 1220px;
  height: 415px;
  display: flex;
  text-align: center;
  margin: auto;
}
.section7-blocks2{
  max-width: 1220px;
  height: 415px;
  display: flex;
  text-align: center;
  margin: auto;
  margin-top: -50px;
}
.section7-white-block-icon{
  margin: auto;
  margin-top: 40px;
}
.section7-white-title-block{
  font-weight: 700;
  font-size: 21px;
  margin-bottom: 21px;
  font-family: "Roboto", sans-serif;
  letter-spacing: 0.05em;
}
.section7-white-text-block{
    font-size: 16px;
    color: #969696;
    font-weight: normal;
    line-height: 25px;
    font-family: "Roboto light", sans-serif;
    max-width: 300px;
    margin: auto;
}
.section7-white-block{
  background-color: #fff; 
  width: 100%;
  margin-left: 15px;
  margin-right: 15px;
  margin-top: 40px;
  margin-bottom: 40px;
}

/* section 6 */
.section6{
  max-height: 1000px;
}
.section6-pink-block-icon{
  margin: auto;
  margin-right: 10px;
}
.section6-pink-block-icon img{
  width: 110%;
  height: 110%;
}
.section6-pink-text-block{
  margin:auto;
  margin-left: 10px;
}
.section6-pink-block-text1{
  font-size: 60px;
  font-weight: 700;
  color: #fff;
  display: block;
  line-height: 1;
  text-align: left;
}
.section6-pink-block-text2{
  font-size: 16px;
  margin-bottom: 0;
  font-weight: 300;
  color: #fff;
}
.aaa{
  max-width: 1220px;
  height: 415px;
  display: flex;
  text-align: center;
  margin: auto;
  
}
.section6-pink-block{
  background-color: rgba(236, 0, 140, 0.7); 
  width: 100%;
  margin-left: 15px;
  margin-right: 15px;
  margin-top: 40px;
  margin-bottom: 40px;
  display: flex;

}
.section6-bg-image{
  background: #f5f0f0;
  vertical-align: middle;
  
}
.section6-icon{
  opacity: 0.53;
  opacity: 0.53;
  width:80%;
  text-align: center;

  margin: auto;
  margin-top: 130px;
  top: 120px;
}

.section6-text{
  opacity: 0.53;
  max-width: 700px;
  text-align: center;
  margin: auto;
  margin-top: 50px;
  line-height: 33.5px;
}
.section6-subtext{
  font-weight: 700;
  font-size: 28px;
  margin-bottom: 20px;
  width:100%;
  text-align: center;
  padding: 60px 0 60px 0px;
}
.section6-footer{
  background: url(/process.jpg) 1% 10% no-repeat; top: 0%; left: 0px;
  height: 415px;


}


/* section 5 */
.section5-bg-image{
  height: 1000px;
  background: url(/block-5.jpg) 10% 10% no-repeat; top: 0%; left: 0px;
  position: relative; transform: translate3d(0px, 0%, 0px); transition: all 1000ms ease 0s;
}
.pink-block5{
  padding: 50px;
  background-color: rgba(99, 48, 133, 0.70);
  max-width: 1020px;
  height: 712px;
  position: relative;
  top: 120px;
  width: 70%;
}

/* section 4 */
.section4-bg-image{
  height: 1000px;
  background: url(/block-4.jpg) 100% 100% no-repeat; top: 0%; left: 0px;
  position: relative; transform: translate3d(0px, 0%, 0px); transition: all 1000ms ease 0s;
}
.pink-block4{
  padding: 50px;
  background-color: rgba(0, 114, 188, 0.70);
  max-width: 1020px;
  height: 712px;
  position: relative;
  top: 120px;
  width: 70%;
}


/* section 3 */
.pink-block3{
  padding: 50px;
  background-color: rgba(160, 65, 13, 0.70);
  max-width: 1020px;
  height: 712px;
  position: relative;
  top: 120px;
  width: 70%;
}
.section3-bg-image{
  height: 1000px;
  background: url(/block-3.jpg) 10% 10% no-repeat; top: 0%; left: 0px;
  position: relative; transform: translate3d(0px, 0%, 0px); transition: all 1000ms ease 0s;

}


/* section 2 */
.section2-5-button-href{
  display: inline-block;
  text-align: center;
  width: 482px;
  font-size: 28px;
  text-decoration: none;
  color: #fff;
  font-weight: 700;
}
.section2-5-button :hover{
  background-color: rgba(236, 0, 140, 0.7);
}
.section2-5-button{
  padding: 12px 0;
  width: 100%;
  background-color: transparent;
  border: 3px solid #fff;
  cursor: pointer;
  max-width: 482px;
  margin-top: 40px;
  min-height: 1px;

}
.section2-5-padding{
  margin-top: 40px;
}
.section2-5-text{
  margin-left: 10px;
}
.section2-5-rows{
  display: flex;
  font-size: 24px;
  color: #fff;
  font-family: "Roboto light", sans-serif;
  font-weight: 300;
  margin-top: 25px;
  max-width: 500px;

}
.section2-5-content{
  width: 70.33333333%;
  min-height: 1px;
  margin-left: auto;
  margin-right: auto;

}
.section2-5-subtitle{
  font-size: 28px;
  font-family: "Roboto slab", sans-serif;
  margin-top: 0;
  color: #fff;
  font-weight: 700;
  letter-spacing: 0.05em;
  text-transform: initial;
  line-height: 35px;
}
.section2-5-title{
  font-size: 27px;
  font-family: "Roboto slab", sans-serif;
  margin-top: 0;
  color: #fff;
  font-weight: 700;
  letter-spacing: 0.075em;
  text-transform: initial;
  line-height: 60px;
}
.block-for-pink2{
  vertical-align: middle;
    
}
.pink-block2{
  padding: 50px;
  background-color: rgba(122, 0, 38, 0.70);
  max-width: 1020px;
  height: 712px;
  position: relative;
  top: 120px;
  width: 75%;
}
.section2-bg-image{
  height: 1000px;
  background: url(/block-2.jpg) 100% 100% no-repeat; top: 0%; left: 0px;
  position: relative; transform: translate3d(0px, 0%, 0px); transition: all 1000ms ease 0s;

}


/* section1 */

.block-for-pink{

    vertical-align: middle;
}
.pink-block{
  padding: 65px;
  background-color: rgba(236, 0, 140, 0.7);
  max-width: 1170px;
  margin: auto;
  position: relative;
  top: 320px;
}
.section1{

}
.section1-text{
  font-size: 56px;
  text-align: center;
  color: white;
  font-family: "Roboto slab";
  font-weight: 700;
  letter-spacing: 0.05em;
  
}
.section1-bg-image{
  height: 1000px;
  background: url(/block-1.jpg) 100% 100% no-repeat; position: absolute; top: 0%; left: 0px;
  position: relative; transform: translate3d(0px, 0%, 0px); transition: all 1000ms ease 0s;
}
</style>
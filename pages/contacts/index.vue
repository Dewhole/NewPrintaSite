<template>
  <div class="main">
    <pageHeader/>
        <div class="contacts">
            <div class="left-block">
                <div class="footer-title">КОНТАКТЫ</div>
                <div class="footer-subtitle">ВРЕМЯ РАБОТЫ</div>
                <div class="footer-time">Пн-Пт: 9:00 – 18:00</div>

                <div class="adress phone">
                    <div class="adress-icon"><img src="iconshome-12.png" alt=""></div>
                    <div class="adress-text">
                        <div class="adress-title">АДРЕС</div>
                        <div class="adress-tex footer-time">Новосибирск,<br> г. Новосибирск, проспект Димитрова, 18</div>
                    </div>
                </div>

                <div class="phone adress">
                    <div class="phone-icon"><img src="iconshome-12.png" alt=""></div>
                    <div class="phone-text adress-text">
                        <div class="phone-title adress-title">НАШ НОМЕР</div>
                        <div class="phone-text ">8 800 555 61 53<br> +7 495 137 77 37<br> +7 383 207 93 93</div>
                    </div>
                </div>
            </div>


            <div class="right-block">
                <form action="">
                    <div class="input-flex">
                        <input class="name input-form" placeholder="Имя*" type="text">
                        <input class="mail input-form" placeholder="E-mail*" type="text">                   
                    </div>
                    <div class="form-vertical">
                      <input class="phone-number input-form" placeholder="Телефон*" type="text"><br>
                      <input class="head-message input-form" placeholder="Тема" type="text"><br>
                      <div class="message"><textarea class="message input-form" placeholder="Сообщение*" type="text"></textarea></div>
                      <button class="send-form">Отправить сообщение</button>    
                    </div>
            </form>
            </div>
        </div> 
        <div class="bg-map">
          <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1143.2077882020897!2d82.91331605711764!3d55.03593398355779!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xbb7890e9b7b12e41!2z0J_RgNC40L3RgtCwLCDRgtC40L_QvtCz0YDQsNGE0LjRjw!5e0!3m2!1sru!2sru!4v1607939296544!5m2!1sru!2sru" width="100%" height="450px" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>   
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
/* right block */
.input.active, .input:hover{
  
}
.message{
  min-height: 100px;
}
.bg-map{
  background-color: #303030;
}

.send-form{
  font-size: 18px;
  padding: 13px 34px;
  background-color: #ec008c;
  color: #fff;
  font-weight: 700;
}
.right-block{
  margin-left: 30px;
  margin-top: 80px;
  width: 1000px;
}
.input-flex{
  display: flex;
}
.input-form{
  height: 47px;
  line-height: 47px;
  border: 2px solid #e3e3e3;
  padding: 0 16px;
  margin-bottom: 16px;
  width: 100%;
}
.input-form.text:active{
  border: 2px solid #ec008c;
}
.mail{
  margin-left: 15px;
}
/* left block */

.left-block{
  margin-left: 20px;
}
.contacts{
  display: flex;
  max-width: 1200px;
  margin: auto;
  margin-top: 60px;
  margin-bottom: 30px;
}
.footer-title{
  font-size: 28px;
  font-weight: 700;
}
.footer-subtitle{
  font-size: 18px;
  font-weight: 700;
  margin-top: 35px;
}
.footer-time{
  font-size: 16px;
  color: #969696;
  margin-top: 6px;
}
.adress{
  margin-top: 35px;
  display: flex;
}
.adress-text{
  margin-left: 15px;
  max-width: 280px;
}
.adress-title{
    font-size: 12px;
    margin-top: 5px;
    margin-bottom: 7px;
    font-weight: 700;
}  
.phone-text{
  font-size: 16px;


}


</style>
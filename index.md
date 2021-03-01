# ЕДЗ
#### Только проверенная домашняя работа
#### Проверено проффесионалами в домашней работе

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
 #typing-text {
     color: #246904;
     border: solid 1px transparent;
     font-weight: bold;
     text-align: left;
     font-family: Arial, Helvetica, sans-serif;
     overflow: auto;
     background-color: transparent;
     font-size: 15px;
     padding: 5px;
     height: 30px;
     width: 300px;
     outline: none;
     resize: none;
     box-sizing: border-box;
}
  .Marquee-box {
     position: relative;
     display: inline-block;
     width: 500px;
     height: 80px;
  }
  .MyMarquee {
     text-align: center;
     font-weight: bold;
     max-width: 100%;
     height: 100%;
     font-size: 25px;
     border: 1px solid transparent;
     color: #0e6b00;
     font-family: Arial, Helvetica, sans-serif;
     vertical-align: middle;
     -webkit-box-sizing: border-box;
        -moz-box-sizing: border-box;
             box-sizing: border-box;
     background-color: transparent;

     text-shadow: 2px 2px 2px #A3A3A3;
  }
  .MyMarquee div {
     display: inline-block;
     vertical-align: middle;
  }
  .MyMarquee a, .MyMarquee img {
     display: inline-block;
     text-decoration: underline;
     color: #0e6b00;
     vertical-align: middle;
  }


</style>
<br>

___

<textarea id="typing-text" readonly></textarea>
<br>

<table class="tg">
<thead>
  <tr>
    <th class="tg-baqh">Предмет</th>
    <th class="tg-baqh">Цена/Рубль</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">История</td>
    <td class="tg-baqh">5</td>
  </tr>
  <tr>
    <td class="tg-0lax">Обществознание</td>
    <td class="tg-baqh">5</td>
  </tr>
  <tr>
    <td class="tg-0lax">Русский</td>
    <td class="tg-baqh">4</td>
  </tr>
  <tr>
    <td class="tg-0lax">География</td>
    <td class="tg-baqh">4</td>
  </tr>
  <tr>
    <td class="tg-0lax">Английский</td>
    <td class="tg-baqh">4</td>
  </tr>
  <tr>
    <td class="tg-0lax">Математика</td>
    <td class="tg-baqh">3</td>
  </tr>
  <tr>
    <td class="tg-0lax">ОДНК</td>
    <td class="tg-baqh">3</td>
  </tr>
</tbody>
</table>
<script>
(function () {
   var CharacterPos = 0;
   var MsgBuffer = "";
   var TypeDelay = 100; 
   var NxtMsgDelay = 1000;
   var MsgIndex = 0;
   var delay;
   var MsgArray = ["Мы работаем для:","202 кабинета!","Наша команда состоит из:","Григория","И","Руслана"];

   function StartTyping() {
      var id = document.getElementById("typing-text");
      if (CharacterPos != MsgArray[MsgIndex].length) {
         MsgBuffer  = MsgBuffer + MsgArray[MsgIndex].charAt(CharacterPos);
         id.value = MsgBuffer+"_";
         delay = TypeDelay;
         id.scrollTop = id.scrollHeight; 
      } else {
         delay = NxtMsgDelay;
         MsgBuffer   = "";
         CharacterPos = -1;
         if (MsgIndex!=MsgArray.length-1){
           MsgIndex++;
         }else {
           MsgIndex = 0;
         }
       }
       CharacterPos++;
       setTimeout(StartTyping,delay);
   }
StartTyping();
})();
</script>
<br>

___

<br>
## Скидки*
### слии вы впервые у нас, скидка - 10%
 <div class="Marquee-box">
   <marquee class="MyMarquee" id="my_marquee" direction="left" behavior="1" scrollamount="3" onmouseover="this.stop()" onmouseout="this.start()">
     <div>Приведи друга, и получи скидку 15%</div>
   </marquee>
 </div>


###### *Скидки действуют на одну транзакцию
<script>
  var message="Запрещаю Сохранять что-либо!!!";
  function clickIE4(){
     if (event.button==2){
           alert(message);
           return false;
        }
  }

   function clickNS4(e){
     if (document.layers||document.getElementById&&!document.all){
         if (e.which==2||e.which==3){
           alert(message);
           return false;
          }
      }
    }

   if (document.layers){
       document.captureEvents(Event.MOUSEDOWN);
       document.onmousedown=clickNS4;
   } else if (document.all&&!document.getElementById){
       document.onmousedown=clickIE4;
   }

   document.oncontextmenu=new Function("alert(message);return false")
 </script> 

___

<div class="copyright" align="center">
  <script>
    document.write('&copy;' );
    document.write(' 2021 - ');
    document.write(new Date().getFullYear());
    document.write(' edz - All Rights Reserved.');
    document.write('<br/>Last Updated : ');
    document.write(document.lastModified);
  </script>
</div>

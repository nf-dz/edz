# ЕДЗ
###### Только проверенная домашняя работа
###### Проверено проффесионалами в домашней работе

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
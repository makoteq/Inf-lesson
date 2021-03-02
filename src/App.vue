<template>
  <div class="wrapper  d-flex ">
    <div class="inner_wrapper container ">

  <div class="row " >
    <div class="col-sm text">
      <span class="header">Sposoby Komunikacji</span>
      <span class="section_header">E-mail </span><br>
      <p>E-mail - usługa internetowa służąca do przesyłania listów elektronicznych, do których można dołączyć załączniki. Wymaga posiadania konta pocztowego.</p>
      <span class="section_header">Czat</span><br>
        <p>Czat - rodzaj rozmowy między dwoma lub wieloma użytkownikami komputerów za pośrednictwem Internetu lub innej sieci komputerowej, polegającej na naprzemiennym przesyłaniu wiadomości tekstowych.  </p>
      <span class="section_header">Komunikator</span> 
        <p>Komunikator - program komputerowy umożliwiający natychmiastowe przesyłanie komunikatów tekstowych, głosowych i obrazu.</p>
      <span class="section_header">Grupa dyskusyjna </span> 
        <p>Grupa dyskusyjna - w internecie to ogólna nazwa wszelkich form dyskusji internetowej przypominających wymianę korespondencji, a nie rozmowy w czasie rzeczywistym.</p>
      <span class="section_header">Forum dyskusyjne </span> 
        <p>Forum dyskusyjne - przeniesiona do struktury stron WWW forma grup dyskusyjnych, która służy do wymiany informacji i poglądów między osobami o podobnych zainteresowaniach przy użyciu przeglądarki internetowej.</p>
      <span class="section_header">Web 2.0</span> 
        <p>Web 2.0 - serwis internetowy, który umożliwia interakcję użytkowników polegającą na współtworzeniu zasobów serwisu. Potoczne określenie serwisów internetowych powstałych po 2001 roku, w których działaniu podstawową rolę odgrywa treść generowana przez użytkowników danego serwisu</p>
      <span class="section_header">Blog</span> 
        <p>Blog - rodzaj strony internetowej zawierającej odrębne, uporządkowane chronologicznie wpisy, których autorem jest właściciel bloga. Blogi umożliwiają zazwyczaj archiwizację oraz kategoryzacje i tagowanie wpisów, a także komentowanie notatek przez czytelników danego dziennika sieciowego</p>
      <span class="section_header">FTP</span> 
        <p>FTP - protokół transferu plików. Usługa umożliwiająca pobieranie plików (ang. download) ze specjalnych komputerów, zwanych serwerami FTP, a także umieszczanie naszych plików (ang. upload) na takich serwerach, do których mamy prawo dostępu</p>
      <span class="section_header">Chmura</span> 
        <p>Chmura - znana w języku angielskim jako cloud computing ,to bez wątpienia jeden z najważniejszych trendów wyznaczonych obecnie przez branżę IT. W tym modelu przechowywanie aplikacji informacji odbywa się na serwerach umieszczonych poza lokalną siecią, a nie na komputerze użytkownika.</p>
    </div>
    <div class="col-sm d-none d-lg-block ">
      <img class="big_img" src="./assets/img.png" alt="">
    </div>
  </div>



    </div>
    
  <div class="background_element1"></div>
    <div class="background_element2"></div>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;700;900&display=swap");
#app {
  font-family: "Poppins", sans-serif;
  text-align: center;
  color: #2c3e50;
}
.icon{
  margin: 5px;
  height: 30px;
}
.header{
  margin:0 auto;
  margin-bottom: 40px;
  margin-top: 40px;
  display: block;
  font-weight: 900;
  font-size: 2em;
}
p{
  color: rgba(0, 0, 0, 0.6);
    font-size: 0.9em;
    width: 80%;
    margin:0 auto;
}
.section_header{
  font-weight: 700;
  font-size: 1.1em;
  color: rgba(0, 0, 0, 0.8);
}
.wrapper {
  min-width: 100vw;
  min-height: 100vh;
  background-color: #EDF4F4;
}
.inner_wrapper {
  padding-top:5vh ;
  z-index:2;
  max-width: 90vw;
  min-height: 90vh;
  margin-top: 5vh;
  border-radius: 25px;
  background-color: rgb(255, 255, 255);
}
.background_element1{
  position:absolute;
  width: 50vw;
height: 40vh;
right: 0;
bottom: 0;
background: rgba(212, 104, 150);
filter: blur(40px);
 z-index:1;
   border-radius:  80% 0% 00% 10%;
}
.background_element2{
  position:absolute;
  width: 20vw;
height: 70vh;
left: 0;
top: 0;
filter: blur(40px);
  border-radius:  0%  10% 80% 0%;
background: rgba(255, 220, 96);

 z-index:1;
}
.big_img{
  margin-top: 6vh;
}
</style>

<template>
  <div class="wrapper  d-flex ">
    <div class="inner_wrapper container ">

  <div class="row " >
    <div class="col-sm text">
      <span class="header">Sposoby Komunikacji</span>
      <span class="section_header">chat</span><img class="icon" src="./assets/chat.png" alt=""><br>
      <p>Blog (ang. web log – dziennik sieciowy) – rodzaj strony internetowej zawierającej odrębne, zazwyczaj uporządkowane chronologicznie wpisy. Blogi umożliwiają zazwyczaj archiwizację oraz kategoryzację i tagowanie wpisów, a także komentowanie notatek przez czytelników danego dziennika sieciowego. Ogół blogów traktowany jako medium komunikacyjne nosi nazwę blogosfery. W blogach najważniejszą funkcję komunikacyjną pełni tekst językowy, choć pojawiają się także materiały graficzne czy nagrania video[1].</p>
      <span class="section_header">Blog</span><img class="icon" src="./assets/blog.png" alt=""><br>
        <p>Blog (ang. web log – dziennik sieciowy) – rodzaj strony internetowej zawierającej odrębne, zazwyczaj uporządkowane chronologicznie wpisy. Blogi umożliwiają zazwyczaj archiwizację oraz kategoryzację i tagowanie wpisów, a także komentowanie notatek przez czytelników danego dziennika sieciowego. Ogół blogów traktowany jako medium komunikacyjne nosi nazwę blogosfery. W blogach najważniejszą funkcję komunikacyjną pełni tekst językowy, choć pojawiają się także materiały graficzne czy nagrania video[1].</p>
      <span class="section_header">poczta elektroniczna</span><img class="icon" src="./assets/mess.png" alt="">
        <p>Blog (ang. web log – dziennik sieciowy) – rodzaj strony internetowej zawierającej odrębne, zazwyczaj uporządkowane chronologicznie wpisy. Blogi umożliwiają zazwyczaj archiwizację oraz kategoryzację i tagowanie wpisów, a także komentowanie notatek przez czytelników danego dziennika sieciowego. Ogół blogów traktowany jako medium komunikacyjne nosi nazwę blogosfery. W blogach najważniejszą funkcję komunikacyjną pełni tekst językowy, choć pojawiają się także materiały graficzne czy nagrania video[1].</p>
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

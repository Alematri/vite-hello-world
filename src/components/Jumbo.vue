<script>
  export default{
  name: 'Jumbo'
}
</script>

<template>
      <div id="jumbotron">
        <div class="content">
          <h1>Il tuo posto per parlare</h1>
          <p> Che tu faccia parte di un club scolastico, gruppo di gamer, comunità artistica mondiale, o semplicemente di un piccolo gruppo di amici che vuole passare il tempo assieme, Discord rende più facile chiacchierare ogni giorno e ritrovarsi più spesso. </p>
          <a id="btn-download" class="btn btn-big btn-white" href="#"><i class="fa-solid fa-down-long"></i> Scarica per Mac</a>
          <a id="btn-opendiscord" class="btn btn-big btn-dark" href="#">Apri Discord nel tuo browser</a>
        </div>
      </div>
</template>

<style>
  #jumbotron{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 500px;
  background-color: #255EE9;
  background-size: cover;
  background-position: center;
  background-image: url(../assets/jumbo.png);
  }

  #jumbotron .content{
    text-align: center;
    width: 50%;
  }

  #jumbotron h1{
    font-size: 48px;
    margin-bottom: 30px;
  }

  #jumbotron h1{
    font-size: 48px;
    margin-bottom: 30px;
  }

  #jumbotron p{
    font-size: 20px;
    line-height: 32px;
    margin-bottom: 30px;
  }

  #btn-download{
    margin: 0 10px 0 0;
  }

  #btn-opendiscord{
    margin: 0 0 0 10px;
  }
</style>
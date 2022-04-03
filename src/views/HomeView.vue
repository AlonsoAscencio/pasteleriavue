<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/img/logo.png">
    <div class="table" id="PanBase">
      <div>
      <h1>Bienvenido a Pastel Soul</h1>
      <h2>El pastel que alimenta tu alma</h2>

      <p>
      Nos encontramos en av. del centro no. 59 <br>
      con un horario de atencion desde las 10:00 a.m. - 9:00 p.m. 
      </p>
    </div>
    
        <div class="article">

            <h3>Tipos de harina</h3>
            <table>
                <tr>
                    <th>Pan</th>
                    <th>Precio</th>
                </tr>
                <tr>
                    <td>Harina de trigo</td>
                    <td>$50</td>
                </tr>
                <tr>
                    <td>Harina de arroz</td>
                    <td>$80</td>
                </tr>
                <tr>
                    <td>Harina de maiz</td>
                    <td>$80</td>
                </tr>
                <tr>
                    <td>Harina de avena</td>
                    <td>$100</td>
                </tr>
                <tr>
                    <td>Harina de frutos secos</td>
                    <td>$120</td>
                </tr>
              </table>
              <div class="figure">
                <img id="pastel" src="../assets/img/harina.jpg" alt="">
              </div>
        </div>
    
  
    </div>    

  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'HomeView',
 
}
</script>
<style scoped>
.home{
  display: flex;
  flex-direction: column;
  align-items: center;
}

h3{
    color: #ffffff;
    font-size: 3rem;
    text-align: center;
}
table{
    justify-content: center;
    text-align:left;
    padding-top: 5%;
    padding-bottom: 3%;
    border-collapse:separate ;
    border-spacing: 15px 15px;

        
}
h1,h2,p{
    
    height: 60px;
    color: #383838;
    padding-bottom: 40px;
    font-size: 40px;
    text-align: center;

}

.article{
  
  color: #ffffff;
  font-size: larger ;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  background: #38383880;
 
  border-radius: 20px; 
}
.figure img{
  border-radius: 15px;
}

</style>
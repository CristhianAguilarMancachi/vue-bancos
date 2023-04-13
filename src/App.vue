<template>
  <section class="portafolio">
            <div class="contenedor">
                <h2 class="titulo">INSTITUCIONES </h2>
                <div class="galeria-port">
                    <div class="imagen-port">
                        <img src="https://www.bcp.com.bo/BilleteraMovil/Images/LogoBCP4.png" alt="">
                        <div class="hover-galeria-red">
                            <img src="img/icono1.png" alt="">
                            <a href="l_red.html">BCP</a>
                        </div>
                    </div>
                    <div class="imagen-port">
                        <img src="https://www.la-razon.com/wp-content/uploads/2022/10/01/18/BANCO-SOL.png" alt="">
                        <div class="hover-galeria-yellow">
                            <img src="img/icono1.png" alt="">
                            <a href="l_yellow.html">BANCO SOL</a>
                        </div>
                    </div>
                    <div class="imagen-port">
                        <img src="https://brandemia.org/sites/default/files/inline/images/bnb_logo_portada.jpg" alt="">
                        <div class="hover-galeria-green">
                            <img src="img/icono1.png" alt="">
                            <a href="l_green.html">BNB</a>
                        </div>
                    </div>
        
                </div>
            </div>
    </section>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

/* Galeria */


.portafolio{
    background: #f2f2f2;
}

.galeria-port{
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
}

.imagen-port{
    width: 24%;
    margin-bottom: 10px;
    overflow: hidden;
    position: relative;
    cursor: pointer;
    box-shadow: 0 0 6px 0 rgba(0, 0, 0, .5);
}

.imagen-port > img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
}

.hover-galeria{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    transform: scale(0);
    background: hsla(216, 56%, 37%, 0.664);
    transition: transform .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hover-galeria-red{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    transform: scale(0);
    background: hsla(0, 56%, 37%, 0.664);
    transition: transform .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}


.hover-yellow{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    transform: scale(0);
    background: hsla(43, 56%, 37%, 0.664);
    transition: transform .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hover-galeria-yellow{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    transform: scale(0);
    background: hsla(43, 56%, 37%, 0.664);
    transition: transform .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hover-galeria-green{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    transform: scale(0);
    background: hsla(113, 56%, 37%, 0.664);
    transition: transform .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hover-galeria-purple{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    transform: scale(0);
    background: hsla(286, 62%, 29%, 0.664);
    transition: transform .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hover-galeria img{
    width: 50px;
}

.hover-galeria p{
    color: #fff;
}

.hover-galeria-red a{
    color:#fff;
    font-weight: 800;
    text-decoration: none;
    margin-right: 10px;

}

.hover-galeria-yellow a{
    color:#fff;
    font-weight: 800;
    text-decoration: none;
    margin-right: 10px;
}

.hover-galeria-green a{
    color:#fff;
    font-weight: 800;
    text-decoration: none;
    margin-right: 10px;
}

.hover-galeria-purple a{
    color:#fff;
    font-weight: 800;
    text-decoration: none;
    margin-right: 10px;
}

.imagen-port:hover .hover-galeria{
    transform: scale(1);
}

.imagen-port:hover .hover-galeria-green{
    transform: scale(1);
}

.imagen-port:hover .hover-galeria-red{
    transform: scale(1);
}

.imagen-port:hover .hover-galeria-yellow{
    transform: scale(1);
}

.imagen-port:hover .hover-galeria-purple{
    transform: scale(1);
}

</style>

<template>
    <div>
        <div class="header">
                <div class="dentro-header">
                    <div class="immagine">
                        <img src="img/dc-logo.png" alt="">
                    </div>
                    <div class="indice">
                        <ul>
                            <li>CHARACTER</li>
                            <li>COMICS</li>
                            <li>MOVIES</li>
                            <li>TV</li>
                            <li>GAMES</li>
                            <li>COLLECTIBES</li>
                            <li>VIDEOS</li>
                            <li>FANS</li>
                            <li>NEWS</li>
                            <li>SHOP</li>
                        </ul>
                    </div>
                </div>
           </div>
           <div class="bg-img">
               <img src="../assets/jumbotron.jpg" alt="">

               

           </div>
    </div>
        
</template>

<script>

export default {
    name: 'MyHeader',
    data() {
        return {
            title: "ciao"
        }
    }
}
</script>

<style  scoped lang="scss">
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.header{
    width: 100%;
    height: 12vh;
    display: flex;
    align-items: center;
}
.dentro-header{
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 50px;
}
.indice  > ul{
    display: flex;
    gap: 25px;
}
.indice > ul li{
    font-size: 13px;
    list-style: none;
}
.immagine{
    width: 8%;
    height: 70%;
}
.immagine > img{
    width: 100%;
}
.bg-img{
    width: 100%;
    max-height: 50vh;
    overflow: hidden;
}
.bg-img > img{
    width: 100%;
    height: 100%;
}


</style>


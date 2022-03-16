<template>
    <div>
        <div class="secmain">
            <div class="dentrosecmain">
                <div class="carte">
                    <div >
                        <div class="imgmain">
                            <img src="img/buy-comics-digital-comics.png" alt="">
                        </div>
                        <span>DIGITAL COMICS</span>
                    </div>

                    <div >
                        <div class="imgmain">
                            <img src="img/buy-comics-merchandise.png" alt="">
                        </div>
                        <span>DC MERCHANDISE</span>
                    </div>

                    <div >
                        <div class="imgmain">
                            <img src="img/buy-comics-subscriptions.png" alt="">
                        </div>
                        <span>SUBSCRIPTION</span>
                    </div>

                    <div >
                        <div class="imgmain">
                            <img src="img/buy-comics-shop-locator.png" alt="">
                        </div>
                        <span>COMIC SHOP LOCATOR</span>
                    </div>

                    <div >
                        <div class="imgmain">
                            <img src="img/buy-dc-power-visa.svg" alt="">
                        </div>
                        <span>DC POWER VISA</span>
                    </div>
                    
                </div>
                
            </div>
         </div>

         <!-- main tre -->
         
         <div class="maintre">
             <div class="maintrecentr">
                 <div class="liste">
                     <div class="par">
                         <h3>DC COMICS</h3>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <h3>SHOP</h3>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                     </div>
                     <div class="par">
                         <h3>DC</h3>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                        
                     </div>
                     <div class="par">
                         <h3>SITES</h3>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                         <p>lorem</p>
                     </div>
                 </div>
                 <div class="bglogo">
                    <!-- <img src="img/dc-logo-bg.png" alt=""> -->
                 </div>
             </div>

         </div>

    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.liste{
    display: flex;
    
}
.par{
    color: rgba(255, 255, 255, 0.363);
    font-size: 14px;
    padding-right: 30px;
}
.par > h3{
    color: white;
}
.par >  p{
    margin: 0;
    padding-bottom: 5px;
}
.secmain{
    width: 100%;
    height: 20vh;
    background-color: rgba(5, 83, 185, 0.918);
}
.dentrosecmain{
    width: 80%;
    height: 100%;
    margin: 0 auto;
}
.carte{
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    
}
.carte > div img{
    width: 40px;
    
}
.carte > div span{
    font-size: 13px;
    color: white;
    padding-left: 10px;
}
.carte > div {
    display: flex;
    align-items: center;
    justify-content: center;
}
.imgmain{
    width: 60px;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.imgmain > img{
    min-width: 90%;
    max-height: 100%;
}


/* main ter */
.maintre{
    width: 100%;
    height: 60vh;
    background-image: url(../assets/footer-bg.jpg);
}
.maintrecentr{
    width: 80%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.bglogo{
    width: 52.5%;
    background-position: center;
    height: 100%;
    background-image: url(../assets/dc-logo-bg.png);
    background-repeat: no-repeat;
    
}
.bglogo > img{
    padding-bottom: 50px;

}

</style>
<template>
    <div>
        <div class="footer">
            <div class="footercentro">
                <div class="signup">
                    SIGN-UP NOW!
                </div>
                <div class="follow">
                    FOLLOW US
                    <div class="icona">
                        <img src="img/footer-facebook.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="img/footer-twitter.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="img/footer-youtube.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="img/footer-pinterest.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="img/footer-periscope.png" alt="">
                    </div>
                    
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
.footer{
    width: 100%;
    height: 15vh;
    background-color: rgba(0, 0, 0, 0.904);
}
.footercentro{
    width: 80%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.signup{
    color: white;
    border: 2px solid rgba(5, 83, 185, 0.918);
    width: max-content;
    height: max-content;
    padding: 10px;
}
.follow{
    color: rgba(5, 83, 185, 0.918);
    display: flex;
    align-items: center;
    gap: 15px;
}
.icona{
    width: 40px;
    height: 40px;
}


</style>
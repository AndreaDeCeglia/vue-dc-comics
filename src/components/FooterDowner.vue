<template>
  <div id="footer-downer">
    <div id="footer-container">
        
        <button>
            SIGN-UP NOW
        </button>

        <div id="socials">
            <div>
                <h4>
                    FOLLOW US
                </h4>
            </div>
            <div>
                <img src="./../assets/img/footer-facebook.png" alt="">
            </div>
            <div>
                <img src="./../assets/img/footer-twitter.png" alt="">
            </div>
            <div>
                <img src="./../assets/img/footer-youtube.png" alt="">
            </div>
            <div>
                <img src="./../assets/img/footer-periscope.png" alt="">
            </div>
            <div>
                <img src="./../assets/img/footer-pinterest.png" alt="">
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterDowner',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#footer-downer{
    background-color: #303030;
    padding: 1% 0;

    #footer-container{
        width: 80%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

            button{
                padding: 1%;
                background-color: #303030;
                border: 1px solid #0282F9;
                color: white;
            };

            #socials{
                width: 35%;
                display: flex;
                justify-content: space-between;
                align-items: center;

                    h4{
                        color: #0282F9;
                    }
                    img{
                        width: 70%;
                    }
            }
    }
}

</style>
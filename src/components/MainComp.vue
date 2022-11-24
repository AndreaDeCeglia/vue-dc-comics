<template>
  <div id="main-container">
    <ul>
        <li>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <a href="#">DIGITAL COMICS</a>
        </li>
        <li>
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <a href="#">DC MERCHANDISE</a>
        </li>
        <li>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <a href="#">SUBSCRIPTION</a>
        </li>
        <li>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <a href="#">COMIC SHOP LOCATOR</a>
        </li>
        <li>
            <img id="svg" src="../assets/img/buy-dc-power-visa.svg" alt="">
            <a href="#">DC POWER VISA</a>
        </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'MainComp',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#main-container{
    background-color: #0282F9;
    height: 15vh;
    padding: 1% 0;
    display: flex;
    align-items: center;

        ul{
            width: 78%;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            list-style: none;
            font-size: .5rem;
                li{
                    width: 20%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    img{
                        width: 20%;
                    };
                    a{
                        text-decoration: none;
                        color: white;
                        margin-left: 3%;
                    }
                    
                }
                

        }
}

</style>
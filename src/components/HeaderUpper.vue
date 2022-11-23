<template>
  
    <div id="container-upper">
        <!-- logo container -->
        <div id="logo-container">
            <img src="./../assets/img/dc-logo.png" alt="">
        </div>
        <!-- navbar container -->
        <nav>
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>    
                </li>
                <li>
                    <a href="#">COMICS</a>    
                </li>
                <li>
                    <a href="#">MOVIES</a>    
                </li>
                <li>
                    <a href="#">TV</a>    
                </li>
                <li>
                    <a href="#">GAMES</a>    
                </li>
                <li>
                    <a href="#">COLLECTIBLES</a>    
                </li>
                <li>
                    <a href="#">VIDEOS</a>    
                </li>
                <li>
                    <a href="#">FANS</a>    
                </li>
                <li>
                    <a href="#">NEWS</a>    
                </li>
                <li>
                    <a href="#">SHOP</a>    
                </li>
            </ul>
        </nav>
    </div>
  
</template>

<script>
export default {
  name: 'HeaderUpper',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#container-upper{
    height: 50%;
    font-size: .7rem;
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

#logo-container{
    max-height: 100%;
}

img{
    width: 50%;
}

nav{
    width: 60%;
    height: 100%;
}

ul{
    display: flex;
    justify-content: space-between;
    align-items: center;
    list-style: none;
    height: 100%;
        li{
            height: 100%;
            // vertical-align: middle;
            display: flex;
            justify-content: center;
            align-items: center;
                a{
                    text-decoration: none;
                    color: black;
                };
        };
        li:hover{
            cursor: pointer;
            color: #0C7CEC;
            border-bottom: 2px solid #0C7CEC;
        };
}

</style>
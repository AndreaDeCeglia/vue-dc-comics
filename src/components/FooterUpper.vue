<template>
  <div id="footer-upper">
    <div id="footer-container">
      <div id="footer-listes">
      <div>
        <ul>
          <li>
            <h4>
              DC COMICS
            </h4>
          </li>
          <li>
            <a href="#">
              Character
            </a>
          </li>
          <li>
            <a href="#">
              Comics
            </a>
          </li>
          <li>
            <a href="#">
              Movies
            </a>
          </li>
          <li>
            <a href="#">
              TV
            </a>
          </li>
          <li>
            <a href="#">
              Games
            </a>
          </li>
          <li>
            <a href="#">
              Videos
            </a>
          </li>
          <li>
            <a href="#">
              News
            </a>
          </li>
        </ul>
        <ul>
          <li>
            <h4>
              SHOP
            </h4>
          </li>
          <li>
            <a href="#">
              Shop DC
            </a>
          </li>
          <li>
            <a href="#">
              Shop CD Collectibles
            </a>
          </li>
        </ul>
      </div>
      <div>
        <ul>
          <li>
            <h4>
              DC
            </h4>
          </li>
          <li>
            <a href="#">
              Terms Of Use
            </a>
          </li>
          <li>
            <a href="#">
              Privacy policy(New)
            </a>
          </li>
          <li>
            <a href="#">
              Ad Choise
            </a>
          </li>
          <li>
            <a href="#">
              Advertising
            </a>
          </li>
          <li>
            <a href="#">
              Jobs
            </a>
          </li>
          <li>
            <a href="#">
              Subscriptions
            </a>
          </li>
          <li>
            <a href="#">
              Talent Workshop
            </a>
          </li>
          <li>
            <a href="#">
              CPSC Certificates
            </a>
          </li>
          <li>
            <a href="#">
              Rantings
            </a>
          </li>
          <li>
            <a href="#">
              Shop Help
            </a>
          </li>
          <li>
            <a href="#">
              Contact Us
            </a>
          </li>
        </ul>
      </div>
      <div>
        <ul>
          <li>
            <h4>
              SITES
            </h4>
          </li>
          <li>
            <a href="#">
              DC
            </a>
          </li>
          <li>
            <a href="#">
              MAD Magazine
            </a>
          </li>
          <li>
            <a href="#">
              DC Kids
            </a>
          </li>
          <li>
            <a href="#">
              DC Universe
            </a>
          </li>
          <li>
            <a href="#">
              DC Power Visa
            </a>
          </li>
        </ul>
      </div>
    </div>
    <div id="footer-logo">
      <!-- <img src="./../assets/img/dc-logo-bg.png" alt=""> -->
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterUpper',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#footer-upper{
  // height: 100px;
  background-image: url('./../assets/img/footer-bg.jpg');
  object-fit: cover;
  padding: 1% 0;

  #footer-container{
    height: 100%;
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    
      #footer-listes{
        padding: 1%;
        display: flex;
        justify-content: space-between;
      };

      #footer-logo{
        
        img{
          width: 80%;
        }
      }
  }
}

ul{
  list-style: none;

    li{

      h4{
        color: white;
        padding: 10% 0 5% 0;
      };
      a{
        text-decoration: none;
        color: grey;
        font-size: .7rem;
      }
    }
}

</style>
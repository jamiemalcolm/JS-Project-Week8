<template>
    <div>
      <div class="footer">
        <h3>Coded by <br>Evelyn, Jamie and Mila </h3>
        <ul class="social">
              <li><a class="icoLinkedin" href="https://www.linkedin.com/company/nasa/" title="Linkedin"><i class="fa fa-linkedin"></i></a></li>
              <li><a class="icoTwitter" href="https://twitter.com/NASA" title="Twitter"><i class="fa fa-twitter"></i></a></li>
              <li><a class="icoFacebook" href="https://www.facebook.com/NASA/" title="Facebook"><i class="fa fa-facebook"></i></a></li>
              <li><a class="icoInstagram" href="https://www.instagram.com/nasa/" title="Instagram"><i class="fa fa-instagram"></i></a></li>
        </ul>
    </div>
  </div>
</template>
<style scoped>
.footer {
  background-color: rgba(255, 255, 255, 0.308);
  padding: 40px 0;
  text-align: center;
}

ul.social {
  list-style: none;
  display: inline;
  margin: auto;
}
ul.social li {
  display: inline;
  margin: 0 10px;
}

.social a.icoFacebook:hover {
  background-color: #3B5998;
}
.social a.icoTwitter:hover {
  background-color: #33ccff;
}
.social a.icoLinkedin:hover {
  background-color: #007bb7;
}
.social a.icoInstagram:hover {
  background: #f09433;
  background: -moz-linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
  background: -webkit-linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
  background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
  
}

.social a.icoRss:hover i, .social a.icoFacebook:hover i, .social a.icoTwitter:hover i, .social               a.icoLinkedin:hover i {
  color: #fff;
}

.social li a {
  display: inline-block;
  position: relative;
  margin: 0 auto 0 auto;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  text-align: center;
  width: 60px;
  height: 60px;
  font-size: 22px;
}

.social li i {
  margin: 0;
  line-height: 60px;
  text-align: center;
}

.social li a:hover i, .triggeredHover {
  -moz-transform: rotate(360deg);
  -webkit-transform: rotate(360deg);
  -ms--transform: rotate(360deg);
  transform: rotate(360deg);
  -webkit-transition: all 0.3s;
  -moz-transition: all 0.3s;
  -o-transition: all 0.3s;
  -ms-transition: all 0.3s;
  transition: all 0.3s;
}

.social i {
  color: #fff;
  -webkit-transition: all 0.8s;
  -moz-transition: all 0.8s;
  -o-transition: all 0.8s;
  -ms-transition: all 0.8s;
  transition: all 0.8s;
}

.social a {
  background-color: #CCD8EA;
}

  .social li a {
    display: inline-block;
    position: relative;
    margin: 0 auto 0 auto;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    text-align: center;
    width: 40px;
    height: 40px;
    font-size: 16px;
  }

  .social li i {
    margin: 0;
    line-height: 40px;
    text-align: center;
  }


  .social li a {
    display: inline-block;
    position: relative;
    margin: 0 auto 0 auto;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    text-align: center;
    width: 40px;
    height: 40px;
    font-size: 16px;
  }

  .social li i {
    margin: 0;
    line-height: 40px;
    text-align: center;
  }
  h3 { text-align: center;
}


</style>
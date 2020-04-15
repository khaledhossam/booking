<template>

    <div class="nav">

    <b-navbar toggleable="md" id="bg" fixed="top">

        <!-- LOGO -->

     <img src="@/assets/logo.png" />

        
        <b-navbar-nav > 
        <b-nav-item to="/" id="home">Home</b-nav-item>

        <b-nav-item  id="hotels"> Hotels </b-nav-item>

        <!-- Navbar dropdowns -->

        <b-nav-item-dropdown id="promotions" text="Promotions" right></b-nav-item-dropdown>
        
        <b-nav-item-dropdown id="promotions" text="Destinations" right>
            <b-dropdown-item href="#">EN</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item to="/About" > About Us </b-nav-item>
        <b-nav-item> Voucher </b-nav-item>
        <b-nav-item to="/Account"> Sign Up </b-nav-item>
        <b-nav-item to="/Account"> Sign In </b-nav-item>
        </b-navbar-nav>
    </b-navbar>
    </div>
    
</template>

<script>
</script>

<style>
.navbar-light .navbar-nav .nav-link {
  color: #9F9F9F;
  font-family: "Playfair Display";
  line-height: 21px;
  margin-right: 50px;

}

#bg {
  background-color: #2D2D2D;
}

#home {
  height: 21px;
  width: 43px;
  color: #E0AD1E;
  font-family: "Playfair Display";
  font-size: 16px;
  line-height: 21px;
  margin-right: 140px;
  margin-left: 100px;
}
#hotels {
  height: 21px;
  width: 47px;
  color: #9F9F9F;
  font-family: "Playfair Display";
  font-size: 16px;
  line-height: 21px;
  margin-right: 50px;
}

#promotions {
  height: 21px;
  width: 84px;
  color: #9F9F9F;
  font-family: "Playfair Display";
  font-size: 16px;
  line-height: 21px;
  margin-right: 50px;
}
.nav{
    padding: 25px;
}
</style>
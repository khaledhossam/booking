<template>
  <div id="cards" >

    <h1>Best Promotions</h1>
    <b-container align="center">
    <b-button>Combo</b-button>
     <b-button>Hotels</b-button>
    </b-container>
  <b-card-group>
    <b-card title="Title" img-src="@/assets/img2.jpg" img-alt="Image" img-top>
      <b-card-text>
        Family Safari Vacation To The Home Of The Gods.
      </b-card-text>
      <template v-slot:footer>
        <small class="text-muted">JW Mariot</small>
      </template>
    </b-card>

    <b-card title="Title" img-src="@/assets/img2.jpg" img-alt="Image" img-top>
      <b-card-text>
        Cdc Issues Health Alert Notice For Travelers To Usa From Hon
      </b-card-text>
      <template v-slot:footer>
        <small class="text-muted">JW Mariot</small>
      </template>
    </b-card>

    <b-card title="Title" img-src="@/assets/img2.jpg" img-alt="Image" img-top>
      <b-card-text>
        Airport Hotels The Right Way To Start A Short Break Holiday
      </b-card-text>
      <template v-slot:footer>
        <small class="text-muted">JW Mariot</small>
      </template>
    </b-card>
  </b-card-group>
</div>

</template>

<script>

</script>

<style scoped>


.card{

font-family: "Playfair Display";
font-size: 16px;
font-weight: bold;
line-height: 24px;

}


#cards{
  padding: 50px;
}

.btn{
  margin-left: 0%;
  margin-right: auto;
  margin-bottom: 10px;
  color: #000000;
  font-family: "Playfair Display";
  font-weight: bolder;
}

</style>

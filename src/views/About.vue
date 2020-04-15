<template>
  <div> 
    <nav-bar ></nav-bar>
    

<b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption="First slide"
      img-src="https://picsum.photos/1024/480/?image=10"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Second Slide"
      img-src="https://picsum.photos/1024/480/?image=12"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="https://picsum.photos/1024/480/?image=22"
    ></b-carousel-slide>
  </b-carousel>





    <b-container >
       <b-row>
         <b-col>
           <h3>GUESTS SERVICES OF SUN TRAVEL</h3>

              Reservation and ticketing by phone, email from 8:00 to 18:30 on weekdays(including Holidays and New Year).
              Free ticket delivery in the city.
              Free advice on the best flight routes with the most suitable price.
              Advice on participation and benefit from frequent flyer programs of airlines such as: Golden Lotus Plus, Asia Miles, Royal Orchid Plus ...
              Support changing date, time of flight, refund tickets quickly and conveniently.

              <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption="First slide"
      img-src="https://picsum.photos/1024/480/?image=10"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Second Slide"
      img-src="https://picsum.photos/1024/480/?image=12"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="https://picsum.photos/1024/480/?image=22"
    ></b-carousel-slide>
  </b-carousel>

<h3>GUESTS SERVICES OF SUN TRAVEL</h3>

Reservation and ticketing by phone, email from 8:00 to 18:30 on weekdays(including Holidays and New Year).
              Free ticket delivery in the city.
              Free advice on the best flight routes with the most suitable price.
              Advice on participation and benefit from frequent flyer programs of airlines such as: Golden Lotus Plus, Asia Miles, Royal Orchid Plus ...
              Support changing date, time of flight, refund tickets quickly and conveniently.


        </b-col>


        
        <b-col>BOOKING ROOM FORM</b-col>
      </b-row>
    </b-container>

   <h2>Similar Hotels</h2>
 <b-card-group deck>

    <b-card title="Title" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
      <template v-slot:footer>
        <small class="text-muted">Last updated 3 mins ago</small>
      </template>
    </b-card>

    <b-card title="Title" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
      <template v-slot:footer>
        <small class="text-muted">Last updated 3 mins ago</small>
      </template>
    </b-card>

    <b-card title="Title" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" img-top>
      <b-card-text>
        This card has supporting text below as a natural lead-in to additional content.
      </b-card-text>
      <template v-slot:footer>
        <small class="text-muted">Last updated 3 mins ago</small>
      </template>
    </b-card>

    <b-card title="Title" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This card has even longer content than the first to show that equal height action.
      </b-card-text>
      <template v-slot:footer>
        <small class="text-muted">Last updated 3 mins ago</small>
      </template>
    </b-card>
  </b-card-group>

  </div>
</template>


<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'Home',
  components: {
    "nav-bar":NavBar,
  }
}


</script>


<style>
.col{
  padding-top: 100px;
  padding-bottom: 100px;
  font-family: Playfair Display Regular;
}

.card-deck{
  font-family: Playfair Display Regular;
}
</style>
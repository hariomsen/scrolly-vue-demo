<template>
  <div class="item-container">
    <scrolly parentScroll=false passiveScroll=true style="width:300px;height:600px;" class="vertical-scrollbar-demo" >
      <scrolly-viewport>
        <ul>
          <li class="active router-link-active">
            <a href="/online-deal">
              <img
                width="300px"
                height="290px"
                src="https://dev.w3.org/SVG/tools/svgweb/samples/svg-files/AJ_Digital_Camera.svg"
              >All
            </a>
          </li>
          <li class>
            <a href="/online-deal/baby-kids">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Baby &amp; Kids
            </a>
          </li>
          <li class>
            <a href="/online-deal/beauty-personal-health-care">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Beauty, Personal &amp; Health Care
            </a>
          </li>
          <li class>
            <a href="/online-deal/credit-card-offers">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Credit Card Offers
            </a>
          </li>
          <li class>
            <a href="/online-deal/e-commerce-sale">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >E-Commerce Sale
            </a>
          </li>
          <li class>
            <a href="/online-deal/electronics">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Electronics
            </a>
          </li>
          <li class>
            <a href="/online-deal/fashion">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Fashion
            </a>
          </li>
          <li class>
            <a href="/online-deal/festival-offers">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Festival Offers
            </a>
          </li>
          <li class>
            <a href="/online-deal/food-grocery">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Food &amp; Grocery
            </a>
          </li>
          <li class>
            <a href="/online-deal/home-kitchen">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Home &amp; Kitchen
            </a>
          </li>
          <li class>
            <a href="/online-deal/laptops-computers">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Laptops &amp; Computers
            </a>
          </li>
          <li class>
            <a href="/online-deal/mobile-tablets">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Mobile &amp; Tablets
            </a>
          </li>
          <li class>
            <a href="/online-deal/others">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Others
            </a>
          </li>
          <li class>
            <a href="/online-deal/recharge">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Recharge
            </a>
          </li>
          <li class>
            <a href="/online-deal/travel">
              <img
                width="300px"
                height="300px"
                src="https://res.cloudinary.com/paisawapas/image/upload/v1493278147/category_jii17o.png"
              >Travel
            </a>
          </li>
        </ul>
      </scrolly-viewport>
      <scrolly-bar axis="y"></scrolly-bar>
      <!-- enable if you want x scroll -->
      <!-- <scrolly-bar axis="x"></scrolly-bar> -->
    </scrolly>
  </div>
</template>

<script>
import { Scrolly, ScrollyViewport, ScrollyBar } from "vue-scrolly";
export default {
  name: "Demo",
  props: {
    msg: String
  },
  components: {
    Scrolly,
    ScrollyViewport,
    ScrollyBar
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
} */
.item-container{
  margin:0px auto;
  width:300px;
}
ul {
  list-style:none;
}
</style>

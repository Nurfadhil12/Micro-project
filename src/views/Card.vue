<template>
  <div>
    <Navbar />
    <div class="container">
    <div class="row mb-4">
        <div class="col-12">
          <b-card
            title="Pohon Sakura"
            img-src="https://picsum.photos/600/300/?image=25"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 100%; border:none"
            class="mb-2"
          >
            <b-card-text style="display:flex">
                    <a href="https://www.facebook.com/sharer.php?u=https://micro-project.vercel.app/card" style="margin:0px 20px">
                        <p>
                        facebook
                        </p>
                    </a>
                    <a href="https://twitter.com/share?url=https://micro-project.vercel.app/card" style="margin:0px 20px">
                        <p>
                        twitter
                        </p>
                    </a>
                    <a href="https://api.whatsapp.com/send?https://micro-project.vercel.app/card" style="margin:0px 20px">
                        <p>
                        whatsapp
                        </p>
                    </a>
                    <a href="https://www.linkedin.com/shareArticle?url=https://micro-project.vercel.app/card" style="margin:0px 20px">
                        <p>
                        linkedin
                        </p>
                    </a>
            </b-card-text>
            <b-card-text>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur nisl ante, mollis eget porta quis, consequat et lacus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non purus quam. Nullam ut condimentum nisl, eget blandit est. In hac habitasse platea dictumst. Donec leo elit, vulputate eu imperdiet vitae, feugiat eu odio. Vestibulum vehicula gravida dui, vel cursus dolor tincidunt in. Pellentesque sodales congue sem, sed suscipit erat dapibus quis. Nullam at quam fermentum, mattis mi quis, venenatis lorem. Pellentesque mollis massa rutrum lacinia hendrerit. In hac habitasse platea dictumst. Etiam nec tortor aliquam, sodales risus vel, dapibus nunc. Aenean massa orci, dignissim dignissim massa ac, vestibulum porta nisi. Maecenas porttitor ut quam vel bibendum.
              
            </b-card-text>

          </b-card>
        </div>
      </div>
  </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
// import CardProduct from "@/components/CardProduct.vue";
// import axios from "axios";

export default {
  name: "Card",
  components: {
    // CardProduct,
    Navbar,

  },
};
</script>
<style>
</style>
<template>
  <section class="hero is-fullheight" id="scroll-right">
    <div class="hero-body is-fullheight">
      <div class="container">
        <div class="columns is-centered is-vcentered">
          <div style="margin-right: 2em">
            <h1 class="title is-4 has-text-centered">
              <span itemprop="name">Scroller Right & Pane Left</span>
            </h1>
          </div>
          <ProductZoomer :base-images="images" :base-zoomer-options="zoomerOptions"/>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import ProductZoomer from "../ProductZoomer/ProductZoomer.vue";

export default {
  name: "app",
  data() {
    return {
      images: {
        thumbs: [
          {
            id: 1,
            url:
              "../images/thumbs/1.jpeg"
          },
          {
            id: 2,
            url:
              "../images/thumbs/2.jpeg"
          },
          {
            id: 3,
            url:
              "../images/thumbs/3.jpeg"
          },
          {
            id: 4,
            url:
              "../images/thumbs/4.jpeg"
          },
          {
            id: 5,
            url:
              "../images/thumbs/5.jpeg"
          },
          {
            id: 6,
            url:
              "../images/thumbs/6.jpeg"
          },
          {
            id: 7,
            url:
              "../images/thumbs/7.jpeg"
          },
          {
            id: 8,
            url:
              "../images/thumbs/8.jpeg"
          },
          {
            id: 9,
            url:
              "../images/thumbs/9.jpeg"
          }
        ],
        normal_size: [
          {
            id: 1,
            url:
              "../images/normal_size/1.jpeg"
          },
          {
            id: 2,
            url:
              "../images/normal_size/2.jpeg"
          },
          {
            id: 3,
            url:
              "../images/normal_size/3.jpeg"
          },
          {
            id: 4,
            url:
              "../images/normal_size/4.jpeg"
          },
          {
            id: 5,
            url:
              "../images/normal_size/5.jpeg"
          },
          {
            id: 6,
            url:
              "../images/normal_size/6.jpeg"
          },
          {
            id: 7,
            url:
              "../images/normal_size/7.jpeg"
          },
          {
            id: 8,
            url:
              "../images/normal_size/8.jpeg"
          },
          {
            id: 9,
            url:
              "../images/normal_size/9.jpeg"
          }
        ],
        large_size: [
          {
            id: 1,
            url:
              "../images/large_size/1.jpeg"
          },
          {
            id: 2,
            url:
              "../images/large_size/2.jpeg"
          },
          {
            id: 3,
            url:
              "../images/large_size/3.jpeg"
          },
          {
            id: 4,
            url:
              "../images/large_size/4.jpeg"
          },
          {
            id: 5,
            url:
              "../images/large_size/5.jpeg"
          },
          {
            id: 6,
            url:
              "../images/large_size/6.jpeg"
          },
          {
            id: 7,
            url:
              "../images/large_size/7.jpeg"
          },
          {
            id: 8,
            url:
              "../images/large_size/8.jpeg"
          },
          {
            id: 9,
            url:
              "../images/large_size/9.jpeg"
          }
        ]
      },
      zoomerOptions: {
        zoomFactor: 3,
        pane: "pane",
        hoverDelay: 300,
        namespace: "zoomer-right",
        move_by_click: false,
        scroll_items: 3,
        choosed_thumb_border_color: "#dd2c00",
        scroller_position: "left"
      }
    };
  },
  components: {
    ProductZoomer
  }
};
</script>


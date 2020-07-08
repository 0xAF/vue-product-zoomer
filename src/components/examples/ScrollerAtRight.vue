<template>
  <section class="hero is-fullheight" id="scroll-right">
    <div class="hero-body is-fullheight">
      <div class="container">
        <div class="columns is-centered is-vcentered">
          <div style="margin-right: 2em">
            <h1 class="title is-4 has-text-centered">
              <span itemprop="name">Scroller Right & Pane Left</span>
            </h1>
            <pre>
<code class="javascript">
  let zoomerOptions = {
      zoomFactor: 3,
      pane: "pane",
      hoverDelay: 300,
      namespace: "zoomer-right",
      move_by_click: false,
      scroll_items: 4,
      choosed_thumb_border_color: "#dd2c00",
      scroller_position: "right",
      zoomer_pane_position: "left"
  }
</code>
</pre>
          </div>
          <ProductZoomer :base-images="images" :base-zoomer-options="zoomerOptions"/>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import ProductZoomer from "../ProductZoomer";

export default {
  name: "app",
  data() {
    return {
      images: {
        thumbs: [
          {
            id: 1,
            url:
              "https://picsum.photos/id/1/60"
          },
          {
            id: 2,
            url:
              "https://picsum.photos/id/2/60"
          },
          {
            id: 3,
            url:
              "https://picsum.photos/id/3/60"
          },
          {
            id: 4,
            url:
              "https://picsum.photos/id/4/60"
          },
          {
            id: 5,
            url:
              "https://picsum.photos/id/5/60"
          },
          {
            id: 6,
            url:
              "https://picsum.photos/id/6/60"
          },
          {
            id: 7,
            url:
              "https://picsum.photos/id/7/60"
          },
          {
            id: 8,
            url:
              "https://picsum.photos/id/8/60"
          },
          {
            id: 9,
            url:
              "https://picsum.photos/id/9/60"
          }
        ],
        normal_size: [
          {
            id: 1,
            url:
              "https://picsum.photos/id/1/400"
          },
          {
            id: 2,
            url:
              "https://picsum.photos/id/2/400"
          },
          {
            id: 3,
            url:
              "https://picsum.photos/id/3/400"
          },
          {
            id: 4,
            url:
              "https://picsum.photos/id/4/400"
          },
          {
            id: 5,
            url:
              "https://picsum.photos/id/5/400"
          },
          {
            id: 6,
            url:
              "https://picsum.photos/id/6/400"
          },
          {
            id: 7,
            url:
              "https://picsum.photos/id/7/400"
          },
          {
            id: 8,
            url:
              "https://picsum.photos/id/8/400"
          },
          {
            id: 9,
            url:
              "https://picsum.photos/id/9/400"
          }
        ],
        large_size: [
          {
            id: 1,
            url:
              "https://picsum.photos/id/1/1024"
          },
          {
            id: 2,
            url:
              "https://picsum.photos/id/2/1024"
          },
          {
            id: 3,
            url:
              "https://picsum.photos/id/3/1024"
          },
          {
            id: 4,
            url:
              "https://picsum.photos/id/4/1024"
          },
          {
            id: 5,
            url:
              "https://picsum.photos/id/5/1024"
          },
          {
            id: 6,
            url:
              "https://picsum.photos/id/6/1024"
          },
          {
            id: 7,
            url:
              "https://picsum.photos/id/7/1024"
          },
          {
            id: 8,
            url:
              "https://picsum.photos/id/8/1024"
          },
          {
            id: 9,
            url:
              "https://picsum.photos/id/9/1024"
          }
        ]
      },

      zoomerOptions: {
        zoomFactor: 3,
        pane: "pane",
        hoverDelay: 300,
        namespace: "zoomer-right",
        move_by_click: false,
        scroll_items: 4,
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


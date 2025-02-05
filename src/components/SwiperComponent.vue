<template>
    <swiper-container
    :slides-per-view="7"
    :space-between="spaceBetween"
    :pagination="{
      hideOnClick: false,
    }"
    mousewheel-enabled="true"
    :breakpoints="{
      320: {
        slidesPerView: 1,
      },
      768: {
        slidesPerView: 2,
      },
      992: {
        slidesPerView: 3,
      },
      2048: {
        slidesPerView: 5,
      },
      4080: {
        slidesPerView: 7,
      },
    }"
  >
    <swiper-slide v-for="(item, index) in slides" :key="index">
        <slot :slide="item">
            <div class="title-container">
                <h2>{{ item.title }}</h2>
            </div>
            <div class="title-container">
                <h3>{{ item.description }}</h3>
            </div>
            <div class="text">
                <p>{{ item.details }}</p>
            </div>
        </slot>
    </swiper-slide>
</swiper-container>
</template>

<script>

import { register } from 'swiper/element/bundle';
import 'swiper/swiper-bundle.css';
register();

export default {
  name: "SwiperComponent",
  props: {
  slides: {
    type: Array,
    required: true,
    validator: (value) => value.every((slide) => 'title' in slide && 'description' in slide && 'details' in slide),
        },
    },
};
</script>

<style scoped lang="scss">

swiper-container::part(pagination) {
}

swiper-container::part(bullet-active) {
    background-color: #931116;
}

.text {
    display: flex;
    justify-content: center;
    align-items: center;

    p {
        text-align: justify;
    }
}

@media (min-width:320px) and (max-width: 991px) {
    .title-container {
    margin: 2vw 25px;
    }

    .text {
    margin: 25vw 25px;
        p {
            line-height: 25px;
        }
    }
}

@media (min-width:992px) and (max-width: 2048px) {
    .title-container {
    margin: 4vw 25px;
    }
    .text {
    margin: 12vw 25px;
        p {
            line-height: 25px;
        }
    }
}

@media (min-width:2049px) {
    .title-container {
    margin: 4vw 25px;
    }
    .text {
    margin: 5vw 25px;
        p {
            text-align: justify;
        }
    }
}



</style>
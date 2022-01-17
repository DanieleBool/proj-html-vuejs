<template>
    <main>
        <div>
            <options/>
            <hero-2/>
            <critics/>
            <div class="full-size"><img src="../../assets/img/page52x.jpg" alt="image_full_screen"></div>
            <news/>
            <takeout/>
            <Menu/>
            <Hero3/>
        </div>
    </main>
</template>

<script>
import options from '../sections/options.vue';
import hero2 from '../sections/hero2.vue';
import critics from '../sections/critics.vue';
import news from '../sections/news.vue';
import takeout from '../sections/takeout.vue';
import Menu from '../sections/Menu.vue';
import Hero3 from '../sections/Hero3.vue';

export default {
    name: 'Main',
    components: {
    options,
    hero2,
    critics,
    news,
    takeout,
    Menu,
    Hero3,
  }
}
</script>

<style lang="scss" scoped>
    .full-size{
        margin: 100px 0;
        img{
            width: 100%;
        }
    }
</style>
<template>
    <main>
        <div>
            <options/>
            <hero-2/>
            <critics/>
        </div>
    </main>
</template>

<script>
import options from '../sections/options.vue';
import hero2 from '../sections/hero2.vue';
import critics from '../sections/critics.vue';
export default {
    name: 'Main',
    components: {
    options,
    hero2,
    critics,
  }
}
</script>

<style scoped>

</style>
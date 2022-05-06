<template>
    <section :class="$css['one']">
        one
    </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
// import $style from '../assets/css.module.scss';

export default defineComponent({
    name: 'component1',
    // setup() {
    //     return {
    //         $style
    //     }
    // }
});
</script>

<style lang="scss" src="../assets/css.module.scss" module="$css"></style>

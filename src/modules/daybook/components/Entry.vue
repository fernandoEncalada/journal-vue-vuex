<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="entry-container mb-3 pointer p-2" @click="$router.push({ name: 'entry', params: { id: 10} })">
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">July</span>
        <span class="mx-2 fw-light">2021, Thursday</span>
    </div>

    <div class="entry-description">
        Aliquip do minim adipisicing aliquip occaecat officia esse et qui. Cupidatat proident sint reprehenderit veniam commodo duis consectetur do sit in. Aute culpa consectetur commodo sunt et. Lorem anim aute eiusmod id deserunt fugiat pariatur labore tempor aliqua eu officia. Mollit eu proident esse amet. Aliqua voluptate occaecat aute sint quis esse voluptate aliquip.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    
    .entry-description{
        font-size: 12px;
    }
}
</style>
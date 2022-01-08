<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push( {name: 'entry', params: {id:10}})"
  >
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">Julio</span>
        <span class="mx-2 fw-light">2021, jueves</span>
    </div>
    <div class="entry-description">
        Laboris mollit culpa fugiat elit officia tempor est. Dolore culpa consequat nulla incididunt tempor excepteur incididunt est mollit esse mollit ut reprehenderit. Ea exercitation enim anim anim ipsum qui culpa excepteur laborum laboris nostrud elit et labore. Aute consequat voluptate veniam ea incididunt minim minim aliquip id esse laboris quis. Pariatur deserunt pariatur magna ullamco irure ipsum proident consequat laborum do. Occaecat minim cillum mollit Lorem eiusmod sunt et amet do deserunt culpa nisi est pariatur. Pariatur dolor labore amet magna aliquip magna quis laborum.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color:grey , $amount:45);
        transition: 0.2s all ease-in;
    }

    .entry-description{
        font-size: 12px;
    }
}

</style>
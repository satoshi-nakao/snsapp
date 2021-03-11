<template lang="javascript">
<div class="container">
    <!-- <share-it /> -->
    <!-- <share-it dark />
    <share-it dense />
    <share-it outline /> -->
    <share-it :targets="['twitter', 'facebook']" />
    <share-it icons />
</div>
</template>
 
<script>
export default {
    components: {
 
    },
    data() {
        return {}
    }
}
</script>
 
<style>
.container {
    margin: 0 auto;
    min-height: 80vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    font-size: 20px;
}
</style>
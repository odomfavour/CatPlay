<template>
    <div class="row">
        <CatItem v-for="(cat, index) in 9" :key="index + '-cat-item'"/>
    </div>
</template>

<script>
    import CatItem from '~/components/cats/item';
export default {
    components: {
        CatItem
    }
}
</script>
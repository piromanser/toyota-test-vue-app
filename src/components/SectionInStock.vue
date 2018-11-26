<template>
    <div class="container">
        <div class="stock-block">
            <h4>Автомобили в наличии</h4>
            <ItemStock @requestPrice="$emit('requestPrice')" />
            <ItemStock @requestPrice="$emit('requestPrice')" />
            <ItemStock @requestPrice="$emit('requestPrice')" />
            <ItemStock @requestPrice="$emit('requestPrice')" />
            <ItemStock @requestPrice="$emit('requestPrice')" />
        </div>
    </div>
</template>

<script>
import ItemStock from '../components/ItemStock.vue'

export default {
    
    components: {
        ItemStock,
    }    
}
</script>

<style lang="scss" scoped>
.stock-block h4 {
    text-align: center;
}
</style>


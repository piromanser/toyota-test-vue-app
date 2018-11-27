<template>
    <div class="container">
        <div class="stock-block">
            <h4>Автомобили в наличии</h4>
            <img src="../assets/section-stock-line.png" alt="">
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
    font-size: 32px;
    font-weight: 700;
    line-height: 85.99px;
    letter-spacing: 0.16px;
    margin-bottom: 0;
}

.stock-block {
    display: flex;
    flex-direction: column;
    align-items: center; 
}

.stock-block img {
    margin-bottom: 70px;;
}
</style>


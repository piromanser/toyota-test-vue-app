<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <SectionHeader></SectionHeader>
    <SectionBanner/>
    <SectionModelSelect/>
    <SectionSelectedModel/>
    <SectionVariations/>
    <SectionInStock/> 
    <ItemStock/>
    <ItemStock/>
    <ItemStock/>
    <ItemStock/>
    <ItemStock/>
    <SectionBrief/>
    <SectionLikedAuto/>
    <SectionUnicOffer/>
    <SectionSpecialOffers/>
    <SectionTreidIn/>
    <SectionAdvantages/>
    <SectionTimer/>
    <SectionGetSpecialOffer/>
    <SectionContacts/>
    <SectionMap/>
    <SectionConditions/>
    <SectionFooter/>

    
  </div>
</template>

<script>
import SectionHeader from './components/SectionHeader.vue'
import SectionBanner from './components/SectionBanner.vue'
import SectionModelSelect from './components/SectionModelSelect.vue'
import SectionSelectedModel from './components/SectionSelectedModel.vue'
import SectionVariations from './components/SectionVariations.vue'
import SectionInStock from './components/SectionInStock.vue'
import ItemStock from './components/ItemStock.vue'
import SectionBrief from './components/SectionBrief.vue'
import SectionLikedAuto from './components/SectionLikedAuto.vue'
import SectionUnicOffer from './components/SectionUnicOffer.vue'
import SectionSpecialOffers from './components/SectionSpecialOffers.vue'
import SectionTreidIn from './components/SectionTreidIn.vue'
import SectionAdvantages from './components/SectionAdvantages.vue'
import SectionTimer from './components/SectionTimer.vue'
import SectionGetSpecialOffer from './components/SectionGetSpecialOffer.vue'
import SectionContacts from './components/SectionContacts.vue'
import SectionMap from './components/SectionMap.vue'
import SectionConditions from './components/SectionConditions.vue'
import SectionFooter from './components/SectionFooter.vue'

export default {
  name: 'app',
  components: {
    SectionHeader,
    SectionBanner,
    SectionModelSelect,
    SectionSelectedModel,
    SectionVariations,
    SectionInStock,
    ItemStock,
    SectionBrief,
    SectionLikedAuto,
    SectionUnicOffer,
    SectionSpecialOffers,
    SectionTreidIn,
    SectionAdvantages,
    SectionTimer,
    SectionGetSpecialOffer,
    SectionContacts,
    SectionMap,
    SectionConditions,
    SectionFooter,
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
}

section {
  border: 2px solid blue;
}

.container {
  border: 2px solid red;
  width: 960px;
  padding: 0 15px;
  margin: 0 auto;
}

</style>

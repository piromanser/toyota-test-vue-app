<template>
  <div id="app">
    <SectionHeader />
    <SectionBanner />
    <SectionModelSelect />
    <SectionSelectedModel />
    <SectionVariations />
    <SectionInStock @requestPrice="showModal = true" /> 
    <SectionBrief />
    <SectionLikedAuto />
    <SectionUnicOffer />
    <SectionSpecialOffers />
    <SectionTreidIn />
    <SectionAdvantages />
    <SectionTimer />
    <SectionGetSpecialOffer />
    <SectionContacts />
    <SectionMap />
    <SectionConditions />
    <SectionFooter />

    <transition name="fade">
      <ModalRequestPrice v-if="showModal" @closeModal="showModal = false" />
    </transition>
  </div>
</template>

<script>
import SectionHeader from './components/SectionHeader.vue'
import SectionBanner from './components/SectionBanner.vue'
import SectionModelSelect from './components/SectionModelSelect.vue'
import SectionSelectedModel from './components/SectionSelectedModel.vue'
import SectionVariations from './components/SectionVariations.vue'
import SectionInStock from './components/SectionInStock.vue'
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
import ModalRequestPrice from './components/ModalRequestPrice.vue'

export default {
  name: 'app',
  components: {
    SectionHeader,
    SectionBanner,
    SectionModelSelect,
    SectionSelectedModel,
    SectionVariations,
    SectionInStock,
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
    ModalRequestPrice,
  },
  data() {
    return {
      showModal: false
    }
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  color: #333333;
  position: relative;
  font-family: sans-serif;
}

section {
  // border: 2px solid blue;
}

.container {
  // border: 2px solid red;
  width: 960px;
  padding: 0 15px;
  margin: 0 auto;
}

.fade-enter-active, .fade-leave-active {
  transition: opacity .5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>

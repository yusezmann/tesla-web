<template>
  <div class="home">
    <Promo />
    <Specifications />
    <Interior />
    <CoreFeatures />
    <OrderNow />
  </div>
</template>

<script>
// @ is an alias to /src
import Promo from '../components/Promo.vue'
import Specifications from '../components/Specifications.vue'
import Interior from '../components/Interior.vue'
import CoreFeatures from '../components/CoreFeatures.vue'
import OrderNow from '../components/OrderNow.vue'
export default {
  name: 'Home',
  components: {
    Promo,
    Specifications,
    Interior,
    CoreFeatures,
    OrderNow
  }
}
</script>

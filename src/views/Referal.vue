<template>
  <Heading />
  <div class='bg-white'>
    <div class='my-14 max-w-3xl mx-auto grid grid-cols-1 gap-20 px-6 lg:max-w-7xl lg:grid-flow-col-dense lg:grid-cols-1'>
      <div class='sm:pt-6 space-y-6 lg:col-start-1 lg:col-span-1'>
        <Referral/>
      </div>
     
    </div>
  </div>
</template>

<script>


import Referral from '../components/referral/refferal.vue'

export default {
  components: {
    Referral
  },
}
</script>

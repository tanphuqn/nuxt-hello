<template>
  <div>

  <BindAtribute />
  <EventHandling />
  <TwoWayBindingVue />
  <ListRenderingVue />
  </div>
</template>
<script>
import BindAtribute from '../atoms/BindAttribute.vue'
import EventHandling from '../atoms/EventHandling.vue'
import ListRenderingVue from '../atoms/ListRendering.vue'
import TwoWayBindingVue from '../atoms/TwoWayBinding.vue'

export default {
  components:{
    BindAtribute,
    EventHandling,
    TwoWayBindingVue,
    ListRenderingVue
  }
}
</script>

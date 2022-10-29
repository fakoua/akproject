<template>
  <q-page padding class="row">
    <queue-component> </queue-component>
  </q-page>
</template>

<script lang="ts">
import QueueComponent from 'src/components/QueueComponent.vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'IndexPage',
  components: { QueueComponent },
});
</script>

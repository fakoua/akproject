<template>
  <div class="full-width row wrap justify-start items-start content-start">
    <div class="col-5">
      <q-form class="q-gutter-md">
        <q-select v-model="teamModel" :options="teams" label="Team" />
        <q-select v-model="testModel" :options="tests" label="Test" />

        <div>
          <q-btn label="Submit" type="submit" color="primary" />
          <q-btn
            label="Reset"
            type="reset"
            color="primary"
            flat
            class="q-ml-sm"
          />
        </div>
      </q-form>
    </div>
  </div>
</template>
<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'QueueComponent',
  setup() {
    return {
      teamModel: ref(null),
      testModel: ref(null),
      teams: ['First Team', 'Second Team', 'Third Team'],
      tests: ['Test 01', 'Test 02'],
    };
  },
});
</script>

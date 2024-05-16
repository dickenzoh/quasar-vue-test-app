<template>
  <q-item
    clickable
    tag="a"
    target="_blank"
    :href="props.link"
  >
  <q-item-section>
      <q-item-label>Assignment for cloit</q-item-label>
    </q-item-section>


  </q-item>
</template>

<script setup>
defineOptions({
  name: 'Header'
})

const props = defineProps({
  title: {
    type: String,
    required: true
  },

  caption: {
    type: String,
    default: ''
  },

  link: {
    type: String,
    default: '#'
  },

  icon: {
    type: String,
    default: ''
  }
})
</script>

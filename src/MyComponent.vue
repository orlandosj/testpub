<template>
  <b-input
    v-model="value"
    type="date"
    placeholder=""
    today-button
    :label-today-button="Hoje"
    close-button
    :label-close-button="Fechar"
    hide-header
    :locale="en"
  />
</template>

<script>
export default {
  name: 'MyComponent'
}
</script>
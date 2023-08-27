<template>
  <section>
    <ul class="list-group">
      <li
        class="list-group-item"
        v-for="index in items">
        Server #{{ index }}
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  props: ['items'],
}
</script>
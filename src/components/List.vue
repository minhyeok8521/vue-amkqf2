<template>
  <ul class="listType">
    <li>{{ msg }}</li>
  </ul>
</template>

<script>
export default {
  name: 'ListBox',
  props: ['msg'],
};
</script>

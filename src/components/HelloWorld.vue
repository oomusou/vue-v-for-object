<template>
  <div>
    <ul>
      <li v-for="(value, key) in data" :key="key">
        {{ value }}
      </li>
    </ul>
  </div>
</template>

<script>
const data = function() {
  return {
    data: {
      1: 'Sam',
      2: 'Kevin',
    },
  };
};

export default {
  name: 'HelloWorld',
  data,
};
</script>

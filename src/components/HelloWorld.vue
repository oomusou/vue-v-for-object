<template>
  <div>
    <ul>
      <li v-for="item in data" :key="item.id">
        {{ item.name }}
      </li>
    </ul>
  </div>
</template>

<script>
const data = function() {
  return {
    data: [
      { id: 1, name: 'Sam' },
      { id: 2, name: 'Kevin' },
    ],
  };
};

export default {
  name: 'HelloWorld',
  data,
};
</script>

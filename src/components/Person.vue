<template>
  <el-card :body-style="{ padding: '0px' }">
    <img :src="data.image" class="image"/>
    <div style="padding: 14px;">
      <h3>{{data.name}}</h3>
      <div>Location: {{data.location.name}}</div>
      <a :href="data.url">Details</a>
    </div>
  </el-card>
</template>

<script>
export default {
  name: 'person',
  props: ['data'],
};
</script>

<template>
  <div class="panel">    
    <p class="panel-heading">
      {{ name }}
    </p>
    <div class="panel-block">
      <p>URL: {{ url }}</p>
        
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    name: String,
    url: String
  }
}
</script>
<template>
<div>
  <ul class="nav nav-pills">
  <li class="nav-item">
    <RouterLink 
      class="nav-link" 
      active-class="active" 
      :to="{name: 'NestedOne', replace: true }"
    >
      Nested one
    </RouterLink>
  </li>
  <li class="nav-item">
    <RouterLink 
    class="nav-link" 
    active-class="active" 
    :to="{name: 'NestedTwo', replace: true}"
    >
      Nested two
    </RouterLink>
  </li>
</ul>
<hr class="my-4" />
<RouterView></RouterView>
</div>
</template>
<script setup>
</script>
<style>
</style>
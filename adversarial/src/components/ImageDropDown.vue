<template>
  <div class="dropdown">
      <button class="btn btn-info dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
      Select Image
      </button>
        <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
        <li><a class="dropdown-item" href="#">Potato</a></li>
        <li><a class="dropdown-item" href="#">Street Lamp</a></li>
        <li><a class="dropdown-item" href="#">Sushi</a></li>
        <li><a class="dropdown-item" href="#">Donkey </a></li>
        </ul>
      </div>
  </template>

<script>
export default {
  name: 'ModelDropDown',
  props: {
    description: String
  }
}
</script>

<style>

</style>
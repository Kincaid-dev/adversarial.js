<template>
  <div class="wrapper">
    <div class="options">
      <div class="label">Select a Model</div>
      <ModelDropDown/>
      <div class="label">Select an Attack</div>
      <AttackDropDown/>
      <div class="label">Turn This Image Into a/an:</div>
      <ImageDropDown/>
    </div>
    <div class="imageHolder">
      <ImageHolder />
      <img src="../../public/vuelogo.png">
    </div>
    <div class="generate">
      <Button value = "Generate"/>
    </div>
    <div class="upload">
      <Button value = "Upload Image"/>
    </div>
  </div>
</template>

<script>
import Button from './Button.vue'
import ModelDropDown from './ModelDropDown.vue'
import AttackDropDown from './AttackDropDown.vue'
import ImageDropDown from './ImageDropDown.vue'
import ImageHolder from './ImageHolder.vue'
export default {
  name: 'Container',
  components: {
    Button,
    ModelDropDown,
    AttackDropDown,
    ImageDropDown,
    ImageHolder
  }
}
</script>

<style>
.wrapper {
  background-color: #FFFFFF;
  width: 85%;
  height: fit-content;
  margin: auto;
  margin-top: 4em;
  padding: 1em;
  display: flex;
  flex-flow: row wrap;
  text-align: center;
}

.options {
  width: 45%;
  height: fit-content;
  padding: 1em;
}

.generate {
  width: 45%;
  height: fit-content;
  padding: 1em;
}

.imageHolder {
  width: 55%;
  background-color: black;
  height: fit-content;
}

.upload {
  width: 55%;
  height: fit-content;
  padding: 1em;
}

.label {
  text-align: left;
  font-weight: 600;
  font-family: "Raleway";
  padding-top: .8em;
  padding-bottom: .3em;
}
</style>


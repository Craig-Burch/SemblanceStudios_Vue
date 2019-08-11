<template>
  <div class="section section-basic" id="basic-elements">
    <div class="container">
      <h3 class="title">Basic Elements</h3>
      <h4>Buttons</h4>
      <p class="category">Pick your style</p>
      <div class="row">
        <div class="col-md-10">
         
          <n-button type="primary" size="lg" round>Round</n-button>
         
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import {
  Button,
  Checkbox,
  Radio,
  FormGroupInput,
  Slider,
  Switch
} from '@/components';

export default {
  components: {
    [Button.name]: Button,
    [Checkbox.name]: Checkbox,
    [Radio.name]: Radio,
    [FormGroupInput.name]: FormGroupInput,
    [Switch.name]: Switch,
    [Option.name]: Option,
    Slider
  },
  data() {
    return {
      radios: {
        radioOn: '2',
        radioOff: '2'
      },
      checkboxes: {
        unchecked: false,
        checked: true,
        disabledUnchecked: false,
        disabledChecked: true
      },
      switches: {
        defaultOn: true,
        defaultOff: false
      },
      sliders: {
        simple: 30,
        rangeSlider: [20, 60]
      }
    };
  }
};
</script>
<style></style>

<template>
  <div class="components">
    <color-picker-option></color-picker-option>
  </div>
</template>

<script>// @ is an alias to /src
import ColorPickerOption from '@/components/inputs/color-picker-option.vue';

export default {
  name: 'Components',
  components: {
    'color-picker-option' : ColorPickerOption,
  },
};</script>

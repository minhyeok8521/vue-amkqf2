<template>
  <div id="hello">
    <span>hi</span>
    <ButtonBox />
    <ListBox :msg="mm" />
  </div>
</template>

<script>
import ButtonBox from '../components/Button';
import ListBox from '../components/List';

export default {
  name: 'hello',
  data() {
    return {
      mm: 'ab',
    };
  },
  components: {
    ButtonBox,
    ListBox,
  },
};
</script>

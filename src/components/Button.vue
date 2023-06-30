<template>
  <div class="buttonBox">
    <button type="button">취소</button>
    <button type="button">확인</button>
  </div>
</template>
 
<script>
export default {
  name: 'ButtonBox',
  props: {
    msg: String,
  },
};
</script>

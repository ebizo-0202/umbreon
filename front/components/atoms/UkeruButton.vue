<template>
  <button :class="[$style.ukeruButton]">ウケるｗ</button>
</template>

<script>
export default {
  name: 'UkeruButton'
}
</script>

<style module>
.ukeruButton {
  appearance: none;
  border: 0;
  border-radius: 5px;
  background: #ffe100;
  font-weight: bold;
  color: #000;
  padding: 8px 16px;
  font-size: 16px;
  cursor: pointer;
  position: relative;
  height: 50px;
}

.ukeruButton:hover {
  background: #f5be14;
}

.ukeruButton:focus {
  outline: none;
}

.ukeruButton:active {
  top: 2px;
}

</style>
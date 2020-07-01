<template>
  <div :class="[$style.ipponPlate]">
    <div :class="[$style.ipponBox, $style.box10]"></div>
    <div :class="[$style.ipponBox, $style.box9]"></div>
    <div :class="[$style.ipponBox, $style.box8]"></div>
    <div :class="[$style.ipponBox, $style.box7]"></div>
    <div :class="[$style.ipponBox, $style.box6]"></div>
    <div :class="[$style.ipponBox, $style.box5]"></div>
    <div :class="[$style.ipponBox, $style.box4]"></div>
    <div :class="[$style.ipponBox, $style.box3]"></div>
    <div :class="[$style.ipponBox, $style.box2]"></div>
    <div :class="[$style.ipponBox, $style.box1]"></div>
  </div>
</template>

<script>
export default {
  name: 'IpponPlate'
}
</script>

<style module>
.ipponPlate {
  position: relative;
  height: 500px;
}
@media screen and (max-width: 480px) {
  .ipponPlate {
    height: 200px;
  }
}
.ipponBox {
  background: #d3d3d3;
  border: solid;
  position: absolute;
  box-shadow: 0 0 8px gray;
  box-shadow: 0 0 8px gray inset;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
}
.box10 {
  width: 85%;
  height: 95%;
  background: #ffe100;
}
.box9 {
  width: 80%;
  height: 85%;
  background: #ffe100;
}
.box8 {
  width: 75%;
  height: 75%;
}
.box7 {
  width: 70%;
  height: 65%;
}
.box6 {
  width: 65%;
  height: 55%;
}
.box5 {
  width: 60%;
  height: 45%;
}
.box4 {
  width: 55%;
  height: 35%;
}
.box3 {
  width: 50%;
  height: 25%;
}
.box2 {
  width: 45%;
  height: 15%;
}
.box1 {
  width: 40%;
  height: 5%;
}
</style>
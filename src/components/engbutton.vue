<template>
  <div type = "button" class = "buttoneng">
    <router-link :to="{name: 'Home'}" class = "cancerlink">
      <div class = "engtext">
          <p>English</p>
      </div>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "buttoneng",
  data() {
    return {
      msg: "placeholder"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.buttoneng {
  background-color: whitesmoke;
  border: 2px solid whitesmoke;
  color: white;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 12px;
  text-shadow: 2px 1px 2px rgba(0, 0, 0, 0.5);
  line-height: 0px;

  position: relative;
  margin: 35px 0px 0px -55px;
  width: 44px;
  height: 16px;
}

.buttoneng:hover {
  background-color: gainsboro;
  border-radius: 3px;
  border: 2px solid whitesmoke;
  color: white;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 12px;
  text-shadow: 2px 1px 2px rgba(0, 0, 0, 0.5);
  line-height: 0px;

  position: relative;
  margin: 35px 0px 0px -55px;
  width: 44px;
  height: 16px;
}

.engtext {
  margin: -4px 0px;
}

.cancerlink {
  text-decoration: none;
  color: white;
}
</style>

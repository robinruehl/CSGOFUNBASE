<template>
  <div type = "button" class = "debuttoncreator">
    <router-link :to="{name: 'DeCreator'}" class = "cancerlink">
      <div class = "creatortext">
        <p class = "text1">The</p>
        <p class = "text2">Creator</p>
      </div>
    </router-link>
  </div>
</template>

<script>
export default {
  name: "debuttoncreator",
  data() {
    return {
      msg: "placeholder"
    };
  }
};
</script>


<style scoped>
.debuttoncreator {
  background-color: lightgray;
  border: 2px solid whitesmoke;
  color: white;
  text-decoration: none;
  display: inline-block;
  font-size: 25px;
  text-shadow: 2px 1px 2px rgba(0, 0, 0, 0.5);
  line-height: 0px;
  width: 140px;
  height: 30px;
  margin: 15px 5px;
  position: relative;
}

.debuttoncreator:hover {
  background-color: gainsboro;
  border: 2px solid whitesmoke;
  font-size: 25px;
  line-height: 0px;
  width: 140px;
  height: 30px;
  margin: 15px 5px;
  position: relative;
}

.creatortext {
  text-align: left;
}

.text1 {
  margin: 15px 2px;
}

.text2 {
  margin: -15px 50px;
}

.cancerlink {
  text-decoration: none;
  color: white;
}
</style>

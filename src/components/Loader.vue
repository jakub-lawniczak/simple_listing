<template>
  <div id="loading"></div>
</template>
<script>
export default {
  name: "Loader",
};
</script>
<style lang="scss">
#loading {
  display: inline-block;
  width: 50px;
  height: 50px;
  border: 3px solid rgba(24, 155, 214, 0.3);
  border-radius: 50%;
  border-top-color: #fff;
  animation: spin 1s ease-in-out infinite;
  -webkit-animation: spin 1s ease-in-out infinite;
}

@keyframes spin {
  to {
    -webkit-transform: rotate(360deg);
  }
}
@-webkit-keyframes spin {
  to {
    -webkit-transform: rotate(360deg);
  }
}
</style>

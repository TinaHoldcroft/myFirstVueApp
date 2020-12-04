<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
(function () {
  localStorage.setItem('username', 'test');
  localStorage.setItem('password', '@1234');
})();
export default {
  name: 'app'
}
</script>
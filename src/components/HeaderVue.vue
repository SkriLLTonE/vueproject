<template>
  <header class="header">
    <div class="container">
      <div class="header__wrap">
        <router-link to="/" class="logo">logo</router-link>
        <ul class="menu">
          <li class="menu__list">
            <router-link to="/" class="menu__list-link">About</router-link>
          </li>
          <li class="menu__list">
            <router-link to="/" class="menu__list-link">Menu</router-link>
          </li>
          <li class="menu__list">
            <router-link to="/" class="menu__list-link">Active</router-link>
          </li>
          <li class="menu__list">
            <router-link to="/" class="menu__list-link">Contact</router-link>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>
  
 
<script>
export default {
  name: "HeaderVue",
  data() {
    return {};
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
 <!-- <style lang="scss" scoped>
.header {
  background: #3e62f2;
  color: white;
  padding: 20px 0;
}
.header__wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo {
  color: white;
  font-size: 25px;
}
.menu {
  display: flex;
  align-items: center;
  gap: 30px;
}
.menu__list-link {
  color: white;
  font-size: 20px;
}
@media screen and (max-width: 991px) {
  .header__wrap {
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 25px;
  }
}
</style> -->
<template>
  <div id="left_menu">
    <div class="menu_name">
      <h1>Code A Better Life</h1>
      <h5></h5>
    </div>
    <ul>
      <li class="nav">
        <span>github</span>
      </li>
      <li class="nav">
        <span>知乎</span>
      </li>
      <li class="nav">
        <span>简书</span>
      </li>

      <li class="nav">
        <span>掘金</span>
      </li>
      <li class="nav">
        <span>微信：gongshijier</span>
      </li>
    </ul>
    <div class="info">
      <img class="profile" src="../assets/profile.png" alt="head" />

      <div class="info_name">gongshijie</div>
      <h5></h5>
      <h5></h5>
      <h5></h5>
      <h5></h5>
      <h5></h5>
      <h5></h5>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SideBar'
}
</script>

<style>
@media (max-width: 767px) {
  #left_menu {
    display: none;
  }
}

#left_menu a:hover {
  color: #222;
  background: #f5f7f9;
}

.menu_name {
  background: rgb(38, 42, 48);
  color: white;
  padding: 10px 0;
}

nav {
  background: white;
  padding: 20px 0;
}

.nav {
  padding: 8px 20px;
  text-align: left;
}

.info {
  margin-top: 10px;
  padding: 20px;
  background: white;
}

.info_name {
  font-weight: 600;
  padding: 5px;
}

.profile {
  max-width: 100%;
  max-height: 100%;
}

.info img {
  width: 120px;
  height: 179px;
}

.archive {
  padding-top: 20px;
}

.archive .archive_count {
  display: block;
  color: #222;
  font-weight: 600;
  font-size: 16px;
}

.archive .archive_name {
  display: block;
  color: #999;
  font-size: 14px;
}

.communication {
  padding-top: 20px;
}

.communication_item {
  display: inline-block;
  width: 40%;
  font-size: 14px;
  font-weight: 600;
  padding: 5px;
}
</style>

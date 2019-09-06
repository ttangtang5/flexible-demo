<template>
  <div class="header">
    <div class="logo">
      <img src="../assets/icon/头部logo.png" alt />
    </div>
    <div class="nav">
      <div class="navItem" :class="{'selected': navNum == 1}" @click="navClick(1)">首页</div>
      <div class="navItem" :class="{'selected': navNum == 2}" @click="navClick(2)">教学研究</div>
      <div class="navItem" :class="{'selected': navNum == 3}" @click="navClick(3)">新闻中心</div>
      <div class="navItem" :class="{'selected': navNum == 4}" @click="navClick(4)">关于我们</div>
      <div class="navItem" :class="{'selected': navNum == 5}" @click="navClick(5)">关于我们</div>
    </div>
    <!-- <a-menu mode="horizontal" :style="{ lineHeight: '64px' }" @click="task" @select="test">
      <a-menu-item key="1">nav 1</a-menu-item>
      <a-menu-item key="2">nav 2</a-menu-item>
      <a-menu-item key="3">nav 3</a-menu-item>
      <a-sub-menu key="4">
        <span slot="title">
          <span>Navigation Three</span>
        </span>
        <a-menu-item key="5">Option 3</a-menu-item>
        <a-menu-item key="6">Option 4</a-menu-item>
        <a-sub-menu key="sub1-2" title="Submenu">
          <a-menu-item key="7">Option 5</a-menu-item>
          <a-menu-item key="8">Option 6</a-menu-item>
        </a-sub-menu>
      </a-sub-menu>
      <a-menu-item key="9">nav 5</a-menu-item>
    </a-menu>-->
  </div>
</template>

<script>
export default {
  data() {
    return {
      navNum: 1
    }
  },
  methods: {
    navClick: function(val) {
      this.navNum = val;
    }
  }
};
</script>

<style scoped>
img {
  width: 100%;
  height: auto;
  max-height: 100%;
}

.header {
  height: 132px;
  display: flex;
  align-items: center;
}

.logo {
  background: rgba(255, 255, 255, 0.2);
  float: left;
  width: 255px;
  height: 65px;
  position: relative;
  left: 360px;
}

.nav {
  display: flex;
  align-items: center;
  position: absolute;
  left: 993px;
}

.nav .navItem {
  height: 39px;
  width: 100px;
  background-color: #ffffff;
  line-height: 39px;
  text-align: center;
  color: #666666;
  font-size: 15px;
}

.nav .selected {
  border-radius: 20px;
  background-color: #192c5b;
  color: #ffffff;
}
</style>

<template>
  <div id="components-layout-demo-basic" class="layout">
     <Header></Header>
     <router-view></router-view>
    <!-- <a-layout>
      <a-layout-header>
          <Header></Header>
      </a-layout-header>
      <a-layout-content>
          <router-view></router-view>
      </a-layout-content>
      <a-layout-footer>
          <Footer></Footer>
      </a-layout-footer>
    </a-layout> -->
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./Header";
import Footer from "./Footer";

export default {
    components: {
        Header,
        Footer
    }
};
</script>

<style>
#components-layout-demo-basic {

}
#components-layout-demo-basic .ant-layout-header,
#components-layout-demo-basic .ant-layout-footer {
  background: #7dbcea;
  color: #fff;
}
#components-layout-demo-basic .ant-layout-footer {
  line-height: 1.5;
}
#components-layout-demo-basic .ant-layout-sider {
  background: #3ba0e9;
  color: #fff;
  line-height: 120px;
}
#components-layout-demo-basic .ant-layout-content {
  background: rgba(16, 142, 233, 1);
  color: #fff;
  min-height: 120px;
  line-height: 120px;
}
#components-layout-demo-basic > .ant-layout {
  margin-bottom: 48px;
}
#components-layout-demo-basic > .ant-layout:last-child {
  margin: 0;
}
</style>

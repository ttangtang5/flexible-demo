<template>
  <div class="footer">
    <div class="footerContent">
      <div class="logo">
        <img src="../assets/icon/底部logo.png" alt="">
      </div>
      <div class="msgList">
        <ul>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
          <li>新闻中心</li>
        </ul>
      </div>
      <div class="contact">
        <ul>
          <li>联系我们</li>
          <li>地址：深圳市南山区西丽街道TCL国际E城G栋707</li>
          <li>联系电话：400-004-8989</li>
        </ul>
      </div>
      <div class="qrcode"></div>
    </div>
    <div class="reference">Copyright©2019-2024大湾区教育联盟-版权所有&nbsp;&粤ICP备08001421号-5</div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
img {
  width: 100%;
  height: auto;
  max-height: 100%;
}

.footer {
  width: 100%;
  height: 458px;
  background-color: black;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footerContent {
  width: 100%;
  display: flex;
  justify-content: center;
  padding-top: 99px;
  font-size: 15px;
  color: #ffffff;
  line-height: 46px;
}

.footerContent .logo {
  width: 255px;
  height: 65px;
}

.footerContent .msgList {
  width: 470px;
  height: 205px;
}

.msgList ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
}

.msgList li {
  width: 130px;
}

.contact ul {
  list-style: none;
  display: flex;
  flex-direction: column;
}



.footerContent .qrcode {
  width: 107px;
  height: 107px;
  border: 1px solid red;
  position: relative;
  left: 74px;
}

.reference {
  font-size: 15px;
  line-height: 46px;
  color: #666666;
  position: relative;
  top: 80px;
}
</style>

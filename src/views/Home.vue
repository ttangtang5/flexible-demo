<template>
  <div class="container">
    <div class="banner">
      <img src="../assets/banner/banner.png" alt="banner" />
    </div>
    <div class="noticeContainer">
      <div class="notice">
        <img class="icon" src="../assets/icon/公告.png" alt />
        <div class="noticeMsg">大湾区教育联盟火热加盟中</div>
      </div>
      <div class="contact">
        <img class="icon" src="../assets/icon/电话.png" alt />
        <div class="phoneMsg">400-004-8989</div>
      </div>
    </div>
    <div class="introduceContainer">
      <div class="introduce">
        <div class="titleCN">联盟简介</div>
        <div class="titleEN">ABOUT US</div>
        <div class="content">
          数百位教育领域专家、教授、校长以及教育机构创始人合作发起
          以人为本，打造以学习者为中心的综合教育、教学平台
          民间发起形成的区域教育团体，为大湾区的发展提供人才支持
        </div>
        <div class="moreButton">查看更多 》</div>
      </div>
      <div class="introducePic">
        <img src="../assets/advantage/图.png" alt />
      </div>
    </div>
    <div class="advantage">
      <div class="titleCN">联盟优势</div>
      <div class="titleEN">SCHOOL ADVANTAGE</div>
      <div class="content">
        <div class="module" v-for="n in advantageArr" :key="n">
          <div class="pic">
            <img src="../assets/advantage/优秀企业.1.png" alt />
          </div>
          <div class="msg">占领大湾区人才高地</div>
        </div>
      </div>
    </div>
    <div class="newsContainer">
      <div class="policy">
        <div class="titleCN">政策动态</div>
        <div class="titleEN">POLICY DYNAMICS</div>
        <div class="content">
          <div class="module">
            <div class="pic">
              <img style="height:100%" src="../assets/advantage/年度报告.png" alt />
            </div>
            <div class="msg">
              <span>教育推广基金，助力学子梦想成真</span>
              <div>“青松”奖学金，奖励家境困难但品学兼优的学子参选条件该项奖励所有学生均可申请，每学年有且仅有一次申请机会。评选流程、标准与奖金方式每年5月提交申请，.....</div>
            </div>
            <div class="moreButton">
              <span>查看更多</span>
              <div class="icon">-></div>
            </div>
          </div>
          <div class="module">
            <div class="pic">
              <img style="height:100%" src="../assets/advantage/年度报告.png" alt />
            </div>
            <div class="msg">
              <span>教育推广基金，助力学子梦想成真</span>
              <div>“青松”奖学金，奖励家境困难但品学兼优的学子参选条件该项奖励所有学生均可申请，每学年有且仅有一次申请机会。评选流程、标准与奖金方式每年5月提交申请，.....</div>
            </div>
            <div class="moreButton">
              <span>查看更多</span>
              <div class="icon">-></div>
            </div>
          </div>
        </div>
      </div>
      <div class="news">
        <div class="titleCN">联盟新闻</div>
        <div class="titleEN">ALLIANCE NEWS</div>
        <div class="content">
          <div class="module">
            <div class="childTitle">“曙光”教育推广基金，助力学子梦想成真</div>
            <div
              class="childContent"
            >“青松”奖学金，奖励家境困难但品学兼优的学子参选条件该项奖励所有学生均可申请，每学年有且仅有一次申请机会。评选流程、标准与奖.....</div>
          </div>
          <div class="module">
            <div class="childTitle">“曙光”教育推广基金，助力学子梦想成真</div>
            <div
              class="childContent"
            >“青松”奖学金，奖励家境困难但品学兼优的学子参选条件该项奖励所有学生均可申请，每学年有且仅有一次申请机会。评选流程、标准与奖.....</div>
          </div>
          <div class="module">
            <div class="childTitle">“曙光”教育推广基金，助力学子梦想成真</div>
            <div
              class="childContent"
            >“青松”奖学金，奖励家境困难但品学兼优的学子参选条件该项奖励所有学生均可申请，每学年有且仅有一次申请机会。评选流程、标准与奖.....</div>
          </div>
          <div class="module">
            <div class="childTitle">“曙光”教育推广基金，助力学子梦想成真</div>
            <div
              class="childContent"
            >“青松”奖学金，奖励家境困难但品学兼优的学子参选条件该项奖励所有学生均可申请，每学年有且仅有一次申请机会。评选流程、标准与奖.....</div>
          </div>
        </div>
      </div>
    </div>
    <div class="formContainer">
      <div class="title">如果您也有推动新时期大湾区教育产业发展的共同愿望，欢迎加入我们！</div>
      <div class="form">
        <div class="formTitle">申请入会</div>
        <form action>
          <input type="text" value placeholder="您的姓名" />
          <input type="text" value placeholder="联系方式" />
          <input type="text" value placeholder="电子邮件" />
          <button type="submit">提交</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
  data() {
    return {
      advantageArr: [
        "../assets/advantage/优秀企业1.png",
        "../assets/advantage/学术性高端研讨会.png",
        "../assets/advantage/年度报告.png",
        "../assets/advantage/慈善同行.png",
        "../assets/advantage/表彰.png",
        "../assets/advantage/优秀企业2.png"
      ]
    };
  },
  methods: {}
};
</script>

<style scoped>
img {
  width: 100%;
  height: auto;
  max-height: 100%;
}

.banner {
  width: 100%;
}

.noticeContainer {
  width: 100%;
  height: 76px;
  background-color: #e4e3e3;
  line-height: 76px;
  text-align: center;
  display: flex;
  align-items: center;
}

.notice {
  width: 270px;
  display: flex;
  align-items: center;
  position: absolute;
  left: 366px;
}

.notice .icon {
  line-height: 76px;
  width: 32px;
  height: 26px;
}

.notice .noticeMsg {
  left: 21px;
  position: relative;
}

.contact {
  width: 345px;
  background-color: #2b478d;
  position: absolute;
  left: 1215px;
  display: flex;
}

.contact .icon {
  height: 35px;
  width: 40px;
  margin: auto 23px;
  margin-left: 51px;
}

.contact .phoneMsg {
  height: 76px;
  font-size: 30px;
  color: #ffffff;
}

.introduceContainer {
  display: flex;
  height: 509px;
  background-color: #f5f5f5;
}

.introduce {
  width: 504px;
  position: absolute;
  left: 358px;
  padding-top: 70px;
}

.introducePic {
  height: 355px;
  width: 551px;
  position: absolute;
  left: 1009px;
  padding-top: 69px;
}

.titleCN {
  font-size: 40px;
  font-weight: bold;
  color: #333333;
}

.titleEN {
  color: #999999;
  font-size: 24px;
}

.introduce .content {
  color: #333333;
  font-size: 18px;
  font-family: "MicrosoftYaHei";
  line-height: 36px;
  text-align: left;
  position: relative;
  top: 67px;
}

.introduce .moreButton {
  display: flex;
  width: 118px;
  height: 39px;
  background-color: #192c5b;
  font-size: 18px;
  color: #ffffff;
  line-height: 25px;
  align-items: center;
  justify-content: center;
  border-radius: 10px;
  position: relative;
  top: 149px;
}

.advantage {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 63px 361px 0;
}

.advantage .titleCN {
  font-size: 40px;
  color: #333333;
  font-weight: BOLD;
  line-height: 49px;
}

.advantage .titleEN {
  font-size: 24px;
  color: #999999;
  line-height: 33px;
}

.advantage .content {
  font-size: 18px;
  line-height: 37px;
  margin: auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-top: 59px;
}

.advantage .content .module {
  width: 379px;
  margin-bottom: 32px;
  box-shadow: 0 0 13px #989898;
}

.advantage .content .pic {
  height: 217px;
  width: 379px;
}

.advantage .content .msg {
  line-height: 96px;
  text-align: center;
}

.newsContainer {
  display: flex;
  padding: 62px 361px 95px;
}

.newsContainer .titleCN {
  font-size: 30px;
  color: #333333;
  font-weight: BOLD;
}

.newsContainer .titleEN {
  font-size: 18px;
  color: #999999;
  line-height: 33px;
}

.policy .content {
  display: flex;
  position: relative;
  top: 41px;
}

.policy .module {
  width: 340px;
  border: 1px solid #eeeeee;
  margin-right: 31px;
  display: flex;
  flex-direction: column;
}

.policy .module .pic {
  width: 340px;
  height: 223px;
}

.policy .module .msg {
  padding: 31px 25px 30px 25px;
  font-size: 12px;
  line-height: 21px;
  color: #666666;
  flex: 1;
}

.policy .module .msg span {
  font-size: 16px;
  color: #333333;
  margin-bottom: 16px;
}

.policy .module .msg div {
  padding-top: 16px;
}

.policy .module .moreButton {
  border-top: 1px solid #eeeeee;
  height: 54px;
  font-size: 15px;
  color: #333333;
}

.policy .module .moreButton span {
  margin-left: 24px;
  line-height: 54px;
  text-align: center;
}

.policy .module .moreButton .icon {
  margin-right: 10px;
  float: right;
  line-height: 54px;
}

.news {
  position: relative;
  left: 68px;
}

.news .content {
  font-size: 12px;
  color: #666666;
  /* height: 447px; */
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  position: relative;
  top: 41px;
}

.news .content .module {
  /* height: 118px; */
  width: 420px;
  line-height: 20px;
  border-bottom: 1px solid #dddddd;
  /* flex: 1; */
  padding-bottom: 24px;
}

.news .content .childTitle {
  font-size: 18px;
  color: #333333;
  line-height: 0;
  padding: 25px 0 19px 0;
}

.formContainer {
  height: 612px;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  background-image: url("../assets/advantage/底部图.png");
  background-repeat: no-repeat;
  background-size: cover;
}

.formContainer .title {
  margin-top: 94px;
  font-size: 24px;
  font-weight: BOLD;
  color: #ffffff;
  line-height: 46px;
  letter-spacing: 3px;
}

.formContainer .form {
  width: 509px;
  height: 310px;
  background-color: #ffffff;
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 64px;
}

.formContainer .form .formTitle {
  font-size: 24px;
  line-height: 46px;
  color: #333131;
  margin-top: 36px;
}

form {
  font-size: 13px;
  color: #999999;
  margin-top: 25px;
  display: flex;
  flex-direction: column;
}

form input {
  width: 250px;
  height: 33px;
  background-color: #f4f4f4;
  padding-left: 22px;
  border: 0;
  margin-bottom: 17px;
}

form button {
  width: 90px;
  height: 28px;
  background-color: #192c5b;
  color: #fffefe;
  border: 0;
  margin: auto;
}
</style>


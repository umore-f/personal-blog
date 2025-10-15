<template>
  <div class="clear-float header">
    <!-- 左博客名 -->
    <div class="PB left-float"><a href="">Raven</a></div>
    <!-- 右导航栏 -->
    <div>
      <ul class="right-float header-nav">
        <li><a href="">
            <House style="width: 1em; height: 1em; margin-right: 8px; color:azure;" />首页
          </a></li>
        <li><a href="">
            <Timer style="width: 1em; height: 1em; margin-right: 8px; color:azure;" />时间轴
          </a></li>
        <li><a href="">
            <Paperclip style="width: 1em; height: 1em; margin-right: 8px; color:azure;" />标签
          </a></li>
        <li><a href="">
            <Files style="width: 1em; height: 1em; margin-right: 8px; color:azure;" />分类
          </a></li>
        <li><a href="">
            <Document style="width: 1em; height: 1em; margin-right: 8px; color:azure;" />清单
          </a></li>
        <li><a href="">
            <Link style="width: 1em; height: 1em; margin-right: 8px; color:azure;" />友链
          </a></li>
        <li><a href="">
            <Pointer style="width: 1em; height: 1em; margin-right: 8px; color:azure;" />关于
          </a></li>
      </ul>
    </div>
    <!-- 主体部分 -->
    <div class="main-part">
      <div class="PBname">Raven</div>
      <div class="diary">每日语句</div>
    </div>
    <!-- 尾部 -->
    <div class="footer"><ArrowDown style="height: 40px;"/></div>
  </div>
</template>

<script setup>

</script>

<style scoped>
.header {
  position: relative;
  height: 770px;
  background-color:brown;
  background-image: url('');
  background-repeat: no-repeat;
  background-size: cover
}

.header-nav li {
  float: left;
  margin-top: 25px;
  padding-right: 20px;
}

.header-nav li a {
  width: 20px;
  height: 20px;
  font-size: 16px;
  text-align: center;
  color: azure;
}


.PB {
  width: 20px;
  height: 20px;
  font-size: 24px;
  padding: 25px 0px 0px 0px;
  margin-left: 20px;
}

.PB a {
  color: azure;
}

.main-part {
  height: 700px;
}

.main-part .PBname {
  width: 100px;
  height: 40px;
  text-align: center;
  position: absolute;
  top: 340px;
  left: 770px;
  font-size: 32px;
  color: azure;
}

.main-part .diary {
  width: 240px;
  height: 24px;
  font-size: 16px;
  position: absolute;
  top: 380px;
  left: 700px;
  /* text-align: center; */
}
.footer {
  text-align: center;
}
</style>

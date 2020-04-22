<template>
  <div class=".footer">
    <a href="https://github.com/zhangckcup/smarty.ink" class="github">
      <p>Fork me on github: zhangckcup/smarty.ink</p>
    </a>
    <a href="http://www.beian.miit.gov.cn/">
      <img src="@/assets/img/police-verified.png" ><p>京ICP备18048449号</p>
    </a>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less">
  .footer {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    border-top: 1px solid #eee;
    padding-top: 20px;
    a{
      display: flex;
      justify-content: center;
      text-decoration: none;
      color: #000;
      bottom: 0;
      &:link{
        opacity: 0.75;
      }
      &:hover{
        opacity: 1;
      }
      &>img{
        width: 20px;
        height: 20px;
      }
    }
  }
</style>
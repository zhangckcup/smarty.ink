<template>
  <b-container>
    <b-row>
      <b-col>
        <a href="http://www.beian.miit.gov.cn/" id="police">
          <img src="@/assets/img/police-verified.png" ><p>京ICP备18048449号</p>
        </a>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  
}
</script>

<style lang="less">
  #police{
    display: flex;
    justify-content: center;
    text-decoration: none;
    color: #000;
    position: fixed;
    bottom: 0;
  }
  #police>img{
    width: 20px;
    height: 20px;
  }
</style>
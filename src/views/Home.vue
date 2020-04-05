<template>
  <b-container id="home-container">
    <b-row>
      <b-col lg="9" md="12">
        <b-jumbotron header="Smarty.ink" lead="Use Bootstrap v4 Components for Vue.js 2 to Bulid.">
          <p>但由于本人毫无灵感，本网站除了首页，其他的不知道是什么。</p>
        </b-jumbotron>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
        <p>There is Home page.</p>
      </b-col>
      <b-col lg="3" class="d-none d-lg-block">
        <div class="palce-holder">

        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  methods: {
    onContext(ctx) {
      this.context = ctx
    }
  }
}
</script>

<style lang="less">
  #home-container {
    margin-top: 20px;
    padding-bottom: 120px;
  }
  .palce-holder{
    height: 100%;
    width: 100%;
    background-color: #eee;
    border-radius: 0.3rem;
  }
</style>
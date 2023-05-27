
<template>
  <div class="input-form">
    <form id="myform">
      <input type="text" class="input" placeholder="電子郵件（帳號）"/>
      <input type="password" class="input" placeholder="密碼"/>
      <div class="button-block">
        <div id="forget-password">合作學校帳密查詢</div>
        <div id="regist-account">忘記密碼</div>
      </div>
      <button type="submit" class="submit" onclick="">登入</button>
    </form>
  </div>
  <div class="link">
    不是校園版使用者嗎？<a target='blank'>前往企業版</a>
  </div>
</template>

<script>
export default {
  name: "inputform"
}
</script>

<style scoped>

</style>
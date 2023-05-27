<template>
    <div class="grid-container">
      <div>中文</div>
      <div>English</div>
      <div class="register">註冊新帳號</div>
    </div>
</template>

<script>
export default {
  name: "buttom_up"
}
</script>

<style scoped>
.grid-container{ /*使用grid*/
  padding: 24px 16px 24px 24px;
  display: grid;
  grid-template-columns: 60px  554px auto;
  float: left;
  margin: 8px auto 45px 12px;
  font-size: 14px;
  line-height: 24px;
  color: #505565;
  cursor: pointer
}
.register { /*按鈕*/
  float: right;
  margin-top: -8px;
  padding: 8px 12px;
  font-size: 14px;
  line-height: 24px;
  font-weight: 500;
  color: #ffffff;
  border-radius: 4px;
  background-color: #1762ad;
  cursor: pointer
}

</style>
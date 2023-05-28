
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
.input-form input {
  color: #929292;
  opacity: 0.5;
  border: none;
  cursor: text;
  display: block;
  padding: 8px 0px;
  border-bottom: solid 1px rgba(207,207,207,0.2);
  width: 300px;
  margin: 32px auto 12px auto;
  font-size: 14px;
  line-height: 24px;
  background-color: transparent
}

.input-form input:focus {
  outline: none /*消除選取時的外框*/
}

.input-form{
  font-size: 16px;
  line-height: 1.6;
  margin-bottom: 20px
}

.submit {
  display: block;
  width: 300px;
  height: 54px;
  margin: 16px auto -5px auto;
  font-size: 14px;
  line-height: 54px;
  color: #ffffff;
  text-align: center;
  cursor: pointer;
  border: none;
  background-size: 300px 54px;
  background-image: url(../assets/btnbg@2x.png)
}

.button-block{
  display: flex;
  cursor: pointer;
  font-size: 14px;
  margin: 75px auto 0px auto;
  width: 300px;
  color: #505565;
  line-height: 24px;
  text-decoration: underline;
  justify-content: space-between;
}
.button-block #regist-account:hover, #forget-password:hover  {
  color: #1e8cd6 /*滑鼠移到合作學校查詢、忘記密碼時改顏色*/
}

.link { /*前往企業版*/
  margin-top: 15px;
  height: 24px;
  line-height: 24px;
  font-size: 14px;
  text-align: center;
  color: #505565
}
.link a {
  font-weight: bold;
  color: #1762ad;
  cursor: pointer;
  text-decoration: underline;
}
</style>
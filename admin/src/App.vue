<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>
<style>
  html,body{
    margin: 0;
    padding: 0;
  }
  box{
    .payment-popup-content {
  margin: 20px 0;
}

.payment-details {
  margin: 20px 0 0 60px;
}

.payment-info {
  display: flex;
}
.info-label {
  color: #99a9bf;
}
.info-value {
  color: #606266;
  margin-left: 10px;
}
.dialog-footer {
  text-align: center;
  margin-top: 20px;
}
  }
</style>

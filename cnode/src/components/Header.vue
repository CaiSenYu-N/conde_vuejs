<template>
  <div class="header">
      <img src="https://o4j806krb.qnssl.com/public/images/cnodejs_light.svg" alt="">
      
      <ul>
          <li><a href="#">首页</a></li>
          <li><a href="#">新手入门</a></li>
          <li><a href="#">API</a></li>
          <li><a href="#">关于</a></li>
          <li><a href="#">注册</a></li>
          <li><a href="#">登录</a></li>
      </ul>
  </div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
.header{
    background-color: #5a5555;
    height: 50px;
}
.search{
    background: url(https://o4j806krb.qnssl.com/public/images/search.e53b380a.hashed.png) 4px 4px no-repeat #888;
    padding: 3px 5px 3px 22px;
    color: #666;
    border: 0;
    transition: all .5s;
    border-radius: 15px;
    margin-left: 15px;
}
.search-input{
    background-color: #666;
    padding: 4px 1;
    margin-bottom: 10px;
    font-size: 13px;
    font-weight: 400;
    line-height: 1;
    -webkit-border-radius: 15px;
    -moz-border-radius: 15px;
    border-radius: 15px;
}
img{
    width: 120px;
    height: 30px;
    margin-left: 50px;
    margin-top: 10px;
}
ul{
    list-style: none;
    float: right;
}
li{
    display: inline-block;
    margin-right: 15px;
}
a:hover{
    color: #fff;
}
a{
    text-decoration: none;
    color: #ccc;
    font-size: 14px;
}
</style>

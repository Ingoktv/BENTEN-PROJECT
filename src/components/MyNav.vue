<template lang="">
    <div class="nav">
        <ul>
          <li><img src="../assets/Omnitrix.png" alt="Icon"></li>
          <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: rgb(23, 194, 0);
  height: 100px;
  display: flex;
     /* จัดให้เมนูอยู่ตรงกลาง */
    align-items: center; /* จัดให้ไอคอนและข้อความอยู่ในแนวกลาง */
}
.nav img{
width: 50px;
height: 50px;
margin-right: 20px;
margin-left: 20px;

}
li {
  float: left;
}

li a {
  display: flex;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: rgb(8, 95, 0);
  transition: 0.5s;
}
</style>
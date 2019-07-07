<template>
  <div class="footer">
   <span class="left">
    <div class="pagination">
  <a href="#">&laquo;</a>
    
      <a href="#">1</a>
      <a href="#">2</a>
      <a href="#">3</a>
      <a href="#">4</a>
      <a href="#">5</a>
      <a class="active" href="#">6</a>
      <a href="#">7</a>
      <a href="#">8</a>
      <a href="#">9</a>
      <a href="#">10</a>
    
  <a href="#">&raquo;</a>
</div>
    </span>
   <span class="right"> <label>Powered by </label> <img src="../assets/Algolia.png" height="25px" /></span>
  </div>
    
 
</template>

<script>
export default {
  name: 'Footer',
}
</script>
<style scoped>
.footer {
  width: 700px;
}
.left {
  float: left;
}
.right {
  float: right;
}
.pagination {
  display: inline-block;
  background: #EDEDED;
  border-radius: 20px;
}
.pagination > a {
  float: left;
  border: 3px solid transparent;
  color: black;
  padding: 3px 1px;
  margin: 0 2px;
  text-decoration: none;
  border-radius: 50%;
}
.pagination a:hover:not(.active) {
  border-color: #ddd;
}
.pagination .active {
  background-color: #6F64F8;
  border-color: #6F64F8;
  color: #fff;
  cursor: default;
}
</style>

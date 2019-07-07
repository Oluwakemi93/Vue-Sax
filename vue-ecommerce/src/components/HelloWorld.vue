<template>
  <div class="hello">
    <h5>Vuesax Ecommerce Dashboard</h5>
    <div class="column left">
      <img src="../assets/vuesax.png" width="150px"/>
      <img src="../assets/Dashboard.png" width="160px"/>
<p>APP</p>
<ul>
    <li class="email"><a href="#">Email</a></li>
    <li class="chat"><a href="#">Chat</a></li>
    <li class="todo"><a href="#">Todo</a></li>
    <li class="calender"><a href="#">calendar</a></li>
</ul>

<p>UI</p>
<ul>
  <span><li class="grid"><a href="#">Grid</a></li> </span> <span id="side">&#8250;</span>
    <li class="colors"><a href="#">Colors</a></li>
    <span><li class="card"><a href="#">Card</a></li> </span> <span id="side">&#8250;</span>
    <li class="table"><a href="#">Table</a></li>
    <span><li class="component"><a href="#">Component</a></li> </span> <span id="side">&#8250;</span>
</ul>

<p>FORM</p>
<ul>
    <span><li class="elements"><a href="#">Form Elements</a></li> </span> <span id="side">&#8250;</span>
    <li class="layouts"><a href="#">Form Layouts</a></li>
    <li class="wizard"><a href="#">Form Wizard</a></li>
    <li class="validation"><a href="#">Form Validation</a></li>
</ul>

<p>PAGES</p>
<ul>
    <span><li class="authentication"><a href="#">Authentication</a></li> </span> <span id="side">&#8250;</span>
    <li class="soon"><a href="#">Coming Soon</a></li>
    <span><li class="error"><a href="#">Error</a></li> </span> <span id="side">&#8250;</span>
    <li class="maintenance"><a href="#">Maintenance</a></li>
    <li class="profile"><a href="#">Profile</a></li>
    <li class="faq"><a href="#">FAQ</a></li>
    <li class="knowledge"><a href="#">Knowledge</a></li>
    <li class="base"><a href="#">Base</a></li>
    <li class="search"><a href="#">Search</a></li>
  </ul>

<p><strong>Invoice</strong> <br />CHARTS & MAPS</p>
<ul>
    <span><li class="charts"><a href="#">Charts</a></li> </span> <span id="side">&#8250;</span>
    <li class="map"><a href="#">Google Map</a></li>
</ul>

<p>EXTENSIONS</p>
<ul>
    <span><li class="select"><a href="#">Select</a></li> </span> <span id="side">&#8250;</span>
    <li class="editor"><a href="#">Quill Editor</a></li>
    <li class="drop"><a href="#">Drag & Drop</a></li>
    <li class="datepicker"><a href="#">Datepicker</a></li>
</ul>

<p>OTHERS</p>
<ul>
    <span><li class="menu"><a href="#">Menu Levels</a></li> </span> <span id="side">&#8250;</span>
    <li class="disabled"><a href="#">Disabled Menu</a></li>
</ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>
<style scoped>
* {
  box-sizing: border-box;
  text-align: justify;
}
.column {
  float: left;
  padding: 10px;
  height: 1660px;
}

.left {
  width: 180px;
  margin: 0 auto;
  background: #FFFFFF;
  box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.170509);
}

h5 {
  text-align: left;
   margin-bottom: 4px;
   font-size: 14px;
}
#side {
  float: right;
  margin-top: -29px;
}
.email {
  list-style-image: url('../assets/mail2.png');
  padding-right: 73px;
  font-size: 14px;
  line-height: 35px;
}
.chat {
  list-style-image: url('../assets/chat.png');
  padding-right: 73px;
  font-size: 14px;
  line-height: 35px;
}
.todo {
  list-style-image: url('../assets/Todo.png');
  padding-right: 73px;
  font-size: 14px;
  line-height: 35px;
 }
 .calender {
  list-style-image: url('../assets/calendar.png');
  padding-right: 73px;
  font-size: 14px;
  line-height: 35px;
 }
 p {
   margin-left: 17px;
   font-size: 10px;
   text-align: justify;
   margin-bottom: -11px;
 }
 a {
   text-decoration: none;
 }
  .grid {
  list-style-image: url('../assets/grid.png');
    padding-right: 93px;
  font-size: 14px;
  line-height: 35px;
 }

.colors {
  list-style-image: url('../assets/colors.png');
  padding-right: 93px;
  font-size: 14px;
  line-height: 35px;
 }
 .card {
  list-style-image: url('../assets/card.png');
  padding-right: 93px;
  font-size: 14px;
  line-height: 35px;
 }
  .table {
  list-style-image: url('../assets/table.png');
  padding-right: 93px;
  font-size: 14px;
  line-height: 35px;
 }
  .component {
  list-style-image: url('../assets/component.png');
  padding-right: 93px;
  font-size: 14px;
  line-height: 35px;
 }
.elements {
  list-style-image: url('../assets/elements.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.layouts {
  list-style-image: url('../assets/layouts.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.wizard {
  list-style-image: url('../assets/wizard.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.validation {
  list-style-image: url('../assets/validation.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.authentication {
  list-style-image: url('../assets/authentication.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.soon {
  list-style-image: url('../assets/soon.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.error {
  list-style-image: url('../assets/error.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.maintenance {
  list-style-image: url('../assets/maintainance.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.profile {
  list-style-image: url('../assets/profile.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.faq {
  list-style-image: url('../assets/faq.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.knowledge {
  list-style-image: url('../assets/knowledge.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.base {
  list-style-image: url('../assets/base.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.search {
  list-style-image: url('../assets/search.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.charts {
  list-style-image: url('../assets/charts.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.map {
  list-style-image: url('../assets/map.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.select {
  list-style-image: url('../assets/select.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.editor {
  list-style-image: url('../assets/editor.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.drop {
  list-style-image: url('../assets/drop2.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.datepicker {
  list-style-image: url('../assets/datepicker.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.menu {
  list-style-image: url('../assets/menu.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
.disabled {
  list-style-image: url('../assets/disabled.png');
  padding-right: 23px;
  font-size: 14px;
   line-height: 35px;
}
  </style>

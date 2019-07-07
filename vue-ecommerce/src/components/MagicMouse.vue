<template>
  <div class="magic-mouse">
      <div class="watch"><img src="../assets/mouse.png" width="100" height="218"></div>
    <div class="dollar">
			<span>
				<div class="left1">4.4 <img src="../assets/star2.png" width="10"/></div>
			</span>
			<span>
				<div class="right1">$399</div>
			</span>
		</div>

  	<div class="para">
			<p class="p1">Apple Magic Mouse</p>
			<p class="p2">Redesigned from scratch and completely revised.</p>
		</div>

  	<span>
  		<div class="left2"><img src="../assets/wishlist.png" width="9"/>&nbsp;<strong>  WISHLIST</strong></div>
  	</span>
  	<span>
  		<div class="right2"><img src="../assets/shopping-bag.png" width="9"/>&nbsp;<strong>  ADD TO CART</strong></div>
  	</span>
  </div>
</template>

<script>
export default {
  name: 'MagicMouse',
}
</script>
<style scoped>
.magic-mouse {
	width: 264px;
	height: 397px;
	background: #FFFFFF;
	box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216);
	border-radius: 8px;
}
.watch {
	margin: 50px;
	margin-bottom: 5px;
	margin-top: 22px;
	margin-left: 45px;
}
.left1 {
	float: left;
	background: #6F64F8;
	border-radius: 3px;
	width: 35px;
	font-size: 12px;
	color: #FFFFFF;
	padding: 5px;
}
.right1 {
	float: right;
	font-family: Montserrat;
	font-style: normal;
	font-weight: normal;
	font-size: 18px;
	line-height: 22px;
	color: #2C2C2C;
}
.left2 {
	float: left;
	padding: 20px;
	width: 95px;
	height: 15px;
	font-size: 11px;
	background: #EDEDED;
	border-radius: 0px 0px 0px 8px;
}
.right2 {
	float: right;
	padding: 16px;
	width: 97px;
	height: 23px;
	font-size: 10px;
	color: white;
	background: #6F64F8;
	border-radius: 0px 0px 8px 0px;
}
.p1 {
	height: 7px;
	margin-top: 25px;
	font-family: Montserrat;
	font-style: normal;
	font-weight: bold;
	font-size: 11px;
	line-height: 20px;
	color: #2C2C2C;
}
.p2 {
	height: 15px;
	font-family: Montserrat;
	font-weight: 10px;
	font-size: 8px;
	line-height: 15px;
	color: #2C2C2C;
}
.dollar {
	margin: 15px;
}
.para {
	margin: 13px;
	padding-top: 12px;
	text-align: justify;
}
  </style>

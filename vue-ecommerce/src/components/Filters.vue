<template>
    <div class="filters">
            <h6>Filters</h6>
        <div class="wrap">
            <div class="multi">
                <P><strong>Multi stages</strong></P>			
                    <ul>	
                        <li><img src="../assets/Oval.png"><a href="#"> $10</a></li>	
                        <li><img src="../assets/Oval.png"><a href="#"> $10-$100</a></li>	
                        <li><img src="../assets/Oval.png"><a href="#"> $100-$500</a></li>	
                        <li><img src="../assets/Oval.png"><a href="#"> $500</a></li>		
                        <li><img src="../assets/Oval2.png"><a href="#"> All</a></li>	
                </ul>
            </div>
            <img src="../assets/Slider.png" id="slide" width="220" />
            <hr/>
            <div class="category">
                <p><strong>Category</strong></p>
                <ul>
                    <li><img src="../assets/box.png"><a href="#">Cell Phones</a><label>1920</label></li>
                    <li><img src="../assets/box.png"><a href="#">Computer & tablets</a><label>1820</label></li>
                    <li><img src="../assets/box.png"><a href="#">Cell Phone Accessories</a><label>462</label></li>
                    <li><img src="../assets/box.png"><a href="#">Appliance</a><label>6556</label></li>
                    <li><img src="../assets/box.png"><a href="#">Audio</a><label>120</label></li>
                    <li><img src="../assets/box.png"><a href="#">iPhone Accessories</a><label>353</label></li>
                    <li><img src="../assets/box.png"><a href="#">Cameras & Camcoders</a><label>45</label></li>
                    <li><img src="../assets/box.png"><a href="#">iPhone Cases & Clips</a><label>456</label></li>
                    <li><img src="../assets/box.png"><a href="#">TV & Home Theater</a><label>55</label></li>	
                    <li><img src="../assets/box.png"><a href="#">Small Kitchen Appliances</a><label>10</label></li>	
                </ul>
            </div>
            <hr/>
            <div class="brand">
                <p><strong>Brand</strong></p>
                <ul>	
                    <li><img src="../assets/box.png"><a href="#">Insigni</a><label>220</label></li>
                    <li><img src="../assets/box.png"><a href="#">Samsung</a><label>120</label></li>
                    <li><img src="../assets/box.png"><a href="#">Apple</a><label>320</label></li>	
                    <li><img src="../assets/box.png"><a href="#">HP</a><label>32</label></li>	
                    <li><img src="../assets/box.png"><a href="#">Sony</a><label>520</label></li>	
                    <li><img src="../assets/box.png"><a href="#">Metra</a><label>55</label></li>	
                    <li><img src="../assets/box.png"><a href="#">Dyne</a><label>120</label></li>
                    <li><img src="../assets/box.png"><a href="#">LG</a><label>98</label></li>	
                    <li><img src="../assets/box.png"><a href="#">Canon</a><label>99</label></li>
                    <li><img src="../assets/box.png"><a href="#">Speck</a><label>575</label></li>	
                </ul>
            </div>
            <div><img src="../assets/Rating.png" id="slide" width="255" /></div>
        </div>
        <div class="clear">CLEAR ALL FILTERS </div>
    </div>
</template>

<script>
export default {
  name: 'Filters',
}
</script>
<style scoped>
* {
    box-sizing: border-box;
}
.wrap {
    width: 260px;
    height: 1349px;
    top: 10px;
    background: #FFFFFF;
    box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216);
    border-radius: 8px;
}
h6 {
    text-align: left;
    margin-bottom: 4px;
    font-family: Montserrat;
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 22px;
    color: #2C2C2C;
}
.multi {
    padding-top: 5px
}
.category {
    margin-top: 10px;
    margin-right: 15px;
}
.brand {
    margin-top: 10px;
    margin-right: 15px;
}
.clear {
    height: 40px;
    background: #6F64F8;
    box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216);
    border-radius: 8px;
    font-family: Montserrat;
    font-style: normal;
    font-weight: normal;
    font-size: 10px;
    line-height: 22px;
    color: #FFFFFF;
    padding: 10px;
}
li {
    list-style-type: none;
    text-align: justify;
    line-height: 30px;
    color: #2C2C2C;
    font-weight: 2;
}
a {
    text-decoration: none;
    margin-left: 10px;
    font-family: Montserrat;
    font-style: normal;	
    font-weight: 300;
    font-size: 13px;
    line-height: 32px;	color: #2C2C2C;
}
p {
    margin-right: 90px;
    font-family: Montserrat;
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    line-height: 22px;
    color: #2C2C2C;
}
label {
    float: right;
    margin-right: 5px;
    font-size: 12px;
}
hr {
    margin: 20px;
    border: 1px solid #D6D6D6;
}
.clear {
    background: #6F64F8;
    box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216);
    border-radius: 8px;
    font-size: 10px;
    line-height: 20px;
    color: #FFFFFF;
    margin-top: 19px;
}
</style>

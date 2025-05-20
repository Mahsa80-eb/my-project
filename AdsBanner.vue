<template>
  <section class="Ads-Banner">
    <div class="banner">
        <p class="text-a-b">Take your customer service to the next level</p>

    <div class="btn-koli-a">
     <button class="btn-a-b"><a href="#">Get 14 Days Free Trial</a></button>
     <img src="./right.svg" alt="" class="icon-a-r">
     </div>
     <p class="no-credit">No credit card required</p>
     </div>
     <div class="Decoration">
       <img src="./Girl 1.png" alt="" class="girl">
       <img src="./Green.svg" alt="" class="green">
       <img src="./Yellow.svg" alt="" class="yellow">
       <div class="crown2">
       <img src="./crown.svg" alt="" class="crown">
       </div>
     </div>
  </section>
</template>

<script>
export default {
   name : 'AdsBanner'
}
</script>

<style> 
.Ads-Banner{
  width: 1489px;
  height: 550px;
  top: 5903px;
  background: black;
  margin-left: -9px;
}
.banner{
  width: 673px;
  height: 312px;
   text-align: left;
  margin-left: 230px;
  padding-top: 61px;
  margin-left: 186px;
}
.text-a-b{
  color: white;
  font-family: Lato;
font-weight: 700;
font-size: 60px;
line-height: 72px;
}
.btn-a-b{
    width: 273px;
height: 64px;
gap: 25px;
border-radius: 55px;
padding-top: 16px;
padding-right: 65px;
padding-bottom: 16px;
padding-left: 24px;
    background: #F0B73F;
    border: none;
}
.btn-a-b a{
  font-family: Lato;
font-weight: 700;
font-size: 18px;
line-height: 28px;
letter-spacing: 0%;
text-align: right;
vertical-align: middle;
}
.btn-koli-a{
  width: 273px;
height: 64px;
border-radius: 55px;
padding-top: 16px;
padding-bottom: 16px;
  
}
.icon-a-r{
    width: 20px;
  height: 27px;
  position: absolute;
  left: 411px;
  top: 6612px;
  background: #7979795e;
  border-radius: 100px;
  padding-left: 6px;
  padding-right: 6px;
  padding-top: 3px;
  padding-bottom: 3px;
}
.no-credit{
  font-family: Lato;
font-weight: 400;
font-size: 20px;
line-height: 30px;
letter-spacing: 0%;
   color: gray;
}
.girl{
   width: 723px;
  top: 6257px;
  position: absolute;
  height: 549px;
  left: 677px;
}
.green{
  position: absolute;
  top: 6627px;
  left: 1109px;
}
.yellow{
 margin-left: 1225px;
  margin-top: -178px;
  height: 355px;
}
.crown{
  width: 50px;
height: 569;
top: 311.13px;
left: -37px;
gap: 18px;
padding: 16px;
background: #7979795e;
  border-radius: 100px;
}
.crown2 {
  margin-top: -145px;
  margin-right: 52px;
}
</style>
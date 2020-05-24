<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>assignment</title>

<style>
  p {
  border: 2px solid black;
  background-color: grey;
  width: 200px;
  text-align: left;
  height:200px;
  margin-right: 20px;
  margin-left: 20px;
  font-family: Helvetica;
  color: black;
}
* {
  box-sizing: border-box;
}
h1 {
  margin-bottom: 15px;
}


.row { 
  text-align: left;
  width: 100%;
}
body
{
  text-align: center;
}
@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    text-align: right;
    width: 30%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 81.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    text-align: center;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
    border: 1px solid green;
  margin-left: 20px;}
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 46.66%;
  }
  .col-md-3 {
    width: 125%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 20%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}
@media (max-width: 767px) {
  .col-cg-1, .col-cg-2, .col-cg-3, .col-cg-4, .col-cg-5, .col-cg-6, .col-cg-7, .col-cg-8, .col-cg-9, .col-cg-10, .col-cg-11, .col-cg-12 {
    float: left;
  }
  .col-cg-1 {
    width: 8.33%;
  }
  .col-cg-2 {
    width: 16.66%;
  }
  .col-cg-3 {
    text-align: right;
    width: 30%;
  }
  .col-cg-4 {
    width: 33.33%;
  }
  .col-cg-5 {
    width: 81.66%;
  }
  .col-cg-6 {
    width: 50%;
  }
  .col-cg-7 {
    text-align: center;
  }
  .col-cg-8 {
    width: 66.66%;
  }
  .col-cg-9 {
    width: 74.99%;
  }
  .col-cg-10 {
    width: 83.33%;
  }
  .col-cg-11 {
    width: 91.66%;
  }
  .col-cg-12 {
    width: 100%;
  }
}

.pizza
{ 
  font-size: 20px;
  padding:.90px;
  box-sizing: content-box;
  border: 2px solid black;
  font: 30px 30px 30px;
background: pink;
}
.whitesaucepasta
{ 
  font-size: 20px;
  padding:.90px;
  box-sizing: content-box;
  border: 2px solid black;
  font: 30px 30px 30px;
background: red;
}
.burger
{ 
  font-size: 20px;
  padding:.90px;
  box-sizing: content-box;
  border: 2px solid black;
  font: 30px 30px 30px;
background: lightyellow;
}


</style>
</head>
<body>
<h1>OUR MENU</h1>
 <p class="col-lg-3 col-md-6 col-lg-3"><span class="pizza">&emsp;GOLDEN CORN PIZZA&emsp;<br></span><br>
  <span class ="col-lg-7">hello this is golden corn pizza from new pizza company downing,this flavor of pizza is very amazing,the hot corn sprinkeled over the pizza is so amazing,the falvour will make you the felling of best food you have ever tasted.</span></p>
  <p class="col-lg-3 col-md-6 row col-lg-3"><span class="whitesaucepasta">WHITE SAUCE PAASTA</span>
    <span class="col-lg-7"><br>French cuisine consists of cooking traditions and practices from France. At one time French cuisine was heavily influenced by Italian cuisine.  It was in the 17th century that some chefs led a movement that developed France’s own indigenous style by shifting it away from its foreign influences. Cheese and wine are a major part of the cuisine, playing different roles regionally and nationally, with many variations.</span></p>
  <p class="col-lg-3 col-md-6 row col-lg-3"><span class="burger">BURGER</span>
    <span class ="col-lg-7"><br>A burger is not about a fancy brioche bun or homemade ketchup. It's about achieving the ideal proportion of juicy, cheese-cloaked beef, sharp onion, crunchy lettuce, and sweet-tangy “special sauce,” wrapped in a soft toasted bun.</span>
  </p>


</body>
</html>

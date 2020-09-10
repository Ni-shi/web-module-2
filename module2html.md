# web-module-2
<!DOCTYPE html>
<html>
<head>
<title> Module 2 assignment </title>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<style>
* {
  box-sizing: border-box;
}
body{
font-family: "Comic Sans MS", cursive, sans-serif;
display:block;
}

h1 {
margin-bottom:15px;
text-align:center;
padding: 30px 0px 50px 0px;
}

.box {
border: 4px solid black;
background-color: gray;
width:90%;
height:160px;
margin: 0px 10px 20px 10px;
overflow:hidden;
display:block;
}

.box1 {
	border: 3px solid black;
	padding: 2px 6px 2px 6px;
	float: right;
	width: 30%;
	margin:0px;
	text-align:center;
	font-weight: bold;
}


.row {
width:100%;
}


@media (min-width: 768px) and (max-width: 991px){
.col-s-1,.col-s-2,.col-s-3,.col-s-4,.col-s-5,.col-s-6,
.col-s-7,.col-s-8,.col-s-9,.col-s-10,.col-s-11,.col-s-12{
float:left;
}
  .col-s-1 {width: 8.33%;}
  .col-s-2 {width: 16.66%;}
  .col-s-3 {width: 25%;}
  .col-s-4 {width: 33.33%;}
  .col-s-5 {width: 41.66%;}
  .col-s-6 {width: 50%;}
  .col-s-7 {width: 58.33%;}
  .col-s-8 {width: 66.66%;}
  .col-s-9 {width: 75%;}
  .col-s-10 {width: 83.33%;}
  .col-s-11 {width: 91.66%;}
  .col-s-12 {width: 100%;}
}

@media (min-width: 992px) {
.col-1,.col-2,.col-3,.col-4,.col-5,.col-6,.col-7,
.col-8,.col-9,.col-10,.col-11,.col-12{
float:left;
}
  .col-1 {width: 8.33%;}
  .col-2 {width: 16.66%;}
  .col-3 {width: 25%;}
  .col-4 {width: 33.33%;}
  .col-5 {width: 41.66%;}
  .col-6 {width: 50%;}
  .col-7 {width: 58.33%;}
  .col-8 {width: 66.66%;}
  .col-9 {width: 75%;}
  .col-10 {width: 83.33%;}
  .col-11 {width: 91.66%;}
  .col-12 {width: 100%;}
}

@media (max-width: 767px){
.col-ss-1,.col-ss-2,.col-ss-3,.col-ss-4,.col-ss-5,.col-ss-6,
.col-ss-7,.col-ss-8,.col-ss-9,.col-ss-10,.col-ss-11,.col-ss-12{
float:left;
}
  .col-ss-1 {width: 8.33%;}
  .col-ss-2 {width: 16.66%;}
  .col-ss-3 {width: 25%;}
  .col-ss-4 {width: 33.33%;}
  .col-ss-5 {width: 41.66%;}
  .col-ss-6 {width: 50%;}
  .col-ss-7 {width: 58.33%;}
  .col-ss-8 {width: 66.66%;}
  .col-ss-9 {width: 75%;}
  .col-ss-10 {width: 83.33%;}
  .col-ss-11 {width: 91.66%;}
  .col-ss-12 {width: 100%;}
}

</style>
</head>


<body>
<h1> Our Menu </h1>
<div class="row" style="display:block;"> 

<div class="col-3 col-s-6 col-ss-9" >
<div  class="box" >
<p class="box1" style="background-color:pink;"> Chicken </p>
 <p style="padding: 20px 10px 10px 20px;"> lorem ipsum dolor sit amet, consectetur adipicing elit, sed do eiusmod
 tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
 quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea </p> </div>
</div>

<div class="col-3 col-s-6 col-ss-9" > 
<div  class="box">
<p class="box1" style="background-color:red; color:white;"> Beef </p>
<p style="padding: 20px 10px 10px 20px;"> lorem ipsum dolor sit amet, consectetur adipicing elit, sed do eiusmod
 tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
 quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea </p> </div>
</div>

<div class="col-3 col-s-6 col-ss-9"> 
<div  class="box">
<p class="box1" style="background-color:#600808; color:white;"> Sushi </p>
<p style="padding: 20px 10px 10px 20px;"> lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor 
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
exercitation ullamco laboris nishi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa
qui officia deserunt mollit anim id est laborum. </p> </div>
</div>

</div>
</body>
</html>

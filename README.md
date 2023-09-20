<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="author" content="Quang Huy">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css">
  <script src="https://kit.fontawesome.com/0cdcf30adc.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="stylecuoiky.css">
  <title>Huy subpage </title>
  <style>
    .neon 
{  
-webkit-box-sizing: border-box;  
-moz-box-sizing: border-box;  
box-sizing: border-box;    
border: none;  
font: normal 2.2vw/normal "Dynalight", Helvetica, sans-serif;
text-align: center;   
white-space: pre;  
-webkit-transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);  
-moz-transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);  
-o-transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);  
transition: all 200ms cubic-bezier(0.42, 0, 0.58, 1);
color:lightgreen
}
 body{
 background-image: url(img/anh\ nen\ dep.png);
 background-repeat: round;
 }
.neon:hover 
{  
text-shadow: 0 0 10px rgba(255,255,255,1) , 0 0 20px rgba(255,255,255,1) , 0 0 30px rgba(255,255,255,1) , 0 0 40px #00ffff , 0 0 70px #00ffff , 0 0 80px #00ffff , 0 0 100px #00ffff ;
}  	  
	#wrapper{            
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
	}
    a.button{
      display: inline-block;
      padding: 8px 16px;
      background-color: #f5f5f5;
      text-decoration: none;
      border-radius: 20px;
      transition: all 0.25s ease;
    }
    a.button.messenger{
      background: #0099FF;
      color: #fff;
    }
    a.button.messenger:hover{
      background: #097ac5;
    }
    a.button.youtube{
      background: #fe0303;
      color: #fff;
    }
    a.button.youtube:hover{
      background: #961919;
    }
	a.button.facebook{
      background: #1877F2;
      color: #fff;
    }
    a.button.facebook:hover{
      background: #155ebd;
	}
	a.button.instagram{
	  background: #E4405F
	}
	a.button.instagram:hover{
	  background: #9c2f43
	}
.yolo{
	font-size: 5.6vw
}
.red{
	color:tomato
}
.blue{
	color:cyan
	}
.image {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 50px;
  flex-direction: column;
}
.image img {
  max-width: 50%;
  box-shadow: 5px 10px 8px #0c0c0c;
  margin-bottom: 20px;
}
.image cite {
  font-size: 20px;
}
/* table */
.container td {
	  font-weight: normal;
	  font-size: 1em;
  -webkit-box-shadow: 0 2px 2px -2px #0E1119;
	   -moz-box-shadow: 0 2px 2px -2px #0E1119;
	        box-shadow: 0 2px 2px -2px #0E1119;
}

.container {
  table-layout: fixed;
	  text-align: left;
	  overflow: hidden;
	  width: 80%;
	  margin: 0 auto;
  display: table;
  padding: 0 0 8em 0;
}

.container td, .container th {
	  padding-bottom: 2%;
	  padding-top: 2%;
  padding-left:2%;  
}

/* Background-color of the odd rows */
.container tr:nth-child(odd) {
	  background-color: #323C50;
}

/* Background-color of the even rows */
.container tr:nth-child(even) {
	  background-color: #2C3446;
}

.container th {
	  background-color: #1F2739;
}
.container td{ color:#dad5d5}

.container tr:hover {
   background-color: #464A52;
-webkit-box-shadow: 0 6px 6px -6px #0E1119;
	   -moz-box-shadow: 0 6px 6px -6px #0E1119;
	        box-shadow: 0 6px 6px -6px #0E1119;
}

.container td:hover {
  background-color: #FFF842;
  color: #403E10;
  font-weight: bold;
  
  box-shadow: #7F7C21 -1px 1px, #7F7C21 -2px 2px, #7F7C21 -3px 3px, #7F7C21 -4px 4px, #7F7C21 -5px 5px, #7F7C21 -6px 6px;
  transform: translate3d(6px, -6px, 0);
  
  transition-delay: 0s;
	  transition-duration: 0.4s;
	  transition-property: all;
    transition-timing-function:linear ;
}

@media (max-width: 800px) {
.container td:nth-child(4),
.container th:nth-child(4) { display: none; }
}
.video-container{
  display: flex;
  align-items: center;
  justify-content: center;
}
video{
  width: 68%;
}
.video{
  box-shadow: 5px 10px 8px #0c0c0c;
}
.button{
  display: flex;
  justify-content: center;
  align-items: center;
}
.Contact{
  font-size: 5rem;
}
li{
  display: inline;
  font-size: 35px;;
}
li a:hover {
  color: white;
  transition: ease-in-out;
}
.menu{
  display: flex;
  align-items: center;
  justify-content: center;
}
ul li a{
  padding: 6px 60px;
  text-decoration: none;
  background-color: #0c0c0c;
}
/* backbutton */
.backbutton {
  display: inline-block;
  padding: 15px 25px;
  font-size: 24px;
  cursor: pointer;
  text-align: center;
  outline: none;
  color: #fff;
  background-color: #4CAF50;
  border: none;
  border-radius: 15px;
  box-shadow: 0 9px #999;
}

.backbutton:hover {background-color: #3e8e41}

.backbutton:active {
  background-color: #3e8e41;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}
.backbutton-container{
  display: flex;
  justify-content: center;
  align-items: center;
}
.backbutton a{
  text-decoration: none;
  color: #0E1119;
}
  </style>
</head>
<body>
<div class="khung">                                                               
    <h1 class="neon yolo red">HUY PROFILE</h1>
    <nav class="menu">
      <ul>
        <li><a href="#About me" class="neon">About me</a></li>
        <li><a href="#Skill" class="neon">Skill</a></li>
        <li><a href="#Contact" class="neon">Contact</a></li>
      </ul>
    </nav>
    <p class="neon" id="About me">Chào mừng các bạn đã đến với trang cá nhân của mình</p>
    <p class="neon blue"> Mình tên là Nguyễn Quang Huy, năm nay mình 18 tuổi.
  Mình đang học tại trường Quản trị và kinh doanh, Đại học Quốc gia Hà nội.
  Chuyên ngành của mình là Quản trị và an ninh</p>
  <div class="image">
    <img src="img/huy.jpg" alt="" width="360" height="500"> 
    <p><cite>Nguyễn Quang Huy</cite></p>
  </div>
  <br><br><br><br><br>
  <table class="container" id="Skill">
        <tr>
            <td>SỞ THÍCH</td>
            <td>NGHE NHẠC,CHƠI GAME,XEM PHIM</td>
        </tr>
        <tr>
            <td>KỸ NĂNG</td>
            <td> KỸ NĂNG LÀM VIỆC NHÓM,KỸ NĂNG GIẢI QUYẾT VẤN ĐỀ</td>
        </tr>
    <tr>
            <td>CÔNG VIỆC TỪNG LÀM</td>
            <td>SALE,BARISTA</td>
        </tr>
    <tr>
    </tbody>  
</table>
<section class="video-container">
<video class="video" controls width="700" height="500">
  <source src="y2mate.com - TO THE MOON  hooligan Official Lyric Video_v720P.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
</section>
  <div id="wrapper">
    <p class="Contact" id="Contact">Contact me</p>   
    <div class="list-button">
        <a href="https://www.messenger.com/t/100022747339287" class="button messenger">
            <span class="button-icon">
                <i class="fab fa-facebook-messenger"></i>
            </span>              
        </a>
		<a href="https://www.instagram.com/nq_huy243/" class="button instagram">
            <span class="button-icon">
                <i class="fa-brands fa-instagram" style="color: #ffffff;"></i>
            </span>              
        </a>
		<a href="https://www.facebook.com/profile.php?id=100005065038105" class="button facebook">
            <span class="button-icon">
                <i class="fa-brands fa-facebook"></i>
            </span>              
        </a>
		<a href="https://www.youtube.com/channel/UCt9tQBcmhx5CVt7es9ER9bQ" class="button youtube">
            <span class="button-icon">
                <i class="fa-brands fa-youtube"></i>
            </span>              
        </a>
    </div>
  </div>
  <div class="backbutton-container"><button class="backbutton"><a href="../homepage cuoi ky.html">Trở về</a></button></div>
</div>
</body>
</html>

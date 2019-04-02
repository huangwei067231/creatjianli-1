body{background: #EFEFEF;
   margin: 0px;
}

a{background:inherit;
    color: white;
    text-decoration: none;
}
*{
    margin: 0px;
    padding:0px
}
hr{
    height: 0px;
    border: none;
    border-top: 1px solid #B7B7B7;
}


.clearfix::after{
    content: '';
    display: block;
    clear: both;
}
.topNavBar nav>ul{
    list-style: none;
    padding: 0;
    margin: 0;
    padding-top: 2px;
   
}

.topNavBar nav>ul>li{
    float:left;
    margin-left: 17px;
    margin-right: 17px;
    
}
.topNavBar nav>ul>li>a{
    font-size: 12px;
    color: #B7B7B7;
    text-decoration: none;
    font-weight: bold;
    border-top: 3px solid transparent;
    border-bottom: 3px solid transparent;
    padding-top: 8px;
    padding-bottom: 8px;
    display: block;
}
.topNavBar nav>ul>li>a:hover{
    border-bottom: 3px solid #e06567;
    
}

.topNavBar .logo .rs{font-size:24px;
    font-family: "Arial Black";
    margin-right: 4px;
    color:RGB(232 110 97);
}

.topNavBar .logo .card{
    font-size:24px;
    font-family: "Arial Black";
    color:RGB(151 151 155);
}

.topNavBar .logo{
    padding-top: 3.2px;
    padding-bottom: 3.2px;
}
.topNavBar{
    padding-top: 16px;
    padding-bottom: 16px;
    padding-left: 0px;
    padding-right: 0px;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;

}
.banner{
    height: 515px;
    background-image:url(./wallhaven-751660.jpg);
    width: 100%;
    background-position: center center;
    background-size: cover;
}
.topNavBar-banner{
    padding-left: 16px;
    padding-right: 16px;
}
.banner .mask{
    height: 515px;
    background-color: rgba(0, 0, 0, 0.6)
}
.usercard{
    border: 1px solid red;
    max-width: 940px;
    margin-left: auto;
    margin-right: auto;
    background-color: #FFFFFF;
}
.picture img{
    width: 280px;
    /*background-size: cover;*/
} 
.usercard .welcome{
    background: #e06567;
    color:white;
    display: inline-block;
    padding-left: 16px;
    padding-right: 16px;
    padding-top: 4px;
    padding-bottom: 4px;
    line-height: 22px; 
    position: relative;
    margin-bottom: 3px; 
}
.usercard .welcome .triangle{
    display: block;
    border: 10px solid transparent;
    width: 0px;
    border-left-color: #e06567;
    border-top-width: 0px;
    position: absolute;
    left:6px;
    top: 100%;
 
}
.usercard .picture{
    float: left;
}
.usercard .text{
    float: left;
    margin-left: 65px;
    width: 490px;
}
.usercard .text h1{
    margin-top: 18px;
    margin-bottom: 5px;
}
.usercard .text hr{
    margin: 20px 0px;
}
.usercard .pictureAndText{
    padding: 50px;
}
.usercard dl dt,
.usercard dl dd{
    float: left;
    padding: 5px 0px;
    
}
.usercard dl dt{
    width:30%;
    font-weight: bold;
}
.usercard dl dd{
    width: 70%;
    color: #B7B7B7;
} 
.usercard .media{
    height: 60px;
    background:#e06567;
    text-align: center;
    line-height: 60px;
}
.usercard .media>a{
    padding: 16px;
    border-radius: 50%;
    margin-left: 15px;  

} 
.usercard .media>a:hover{
    background:rgb(208 95 86);
  

}
.usercard .media>a:first-child{
    padding-left: 7px;
    padding-right: 7px;
   
   
} 
.usercard .media .iconfont{
    font-size: 30px;
    

    
}


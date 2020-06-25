<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <style>
        .side a:hover , a:active {
            background-color: rgb(39, 48, 109); 
            }
        .side {
            height: 100%;
            width: 200px;
            position: fixed;
            z-index: 1;
            top: 30;
            left: 0;
            background-color: #001c40;
            overflow-x: hidden;
            padding-top: 30px;
            margin : 9px 0 9px 9px;
            }
        .side a {
            padding: 6px 16px 9px 16px;
            text-decoration: none;
            font-size: 22px;
            color: #ebe6e6;
            display: block;
            }
        @media screen and (max-height: 450px) {
        .side {padding-top: 15px;}
        .side a {font-size: 18px;}
        }
        div [class= "title"] {
            text-align: left;
            font-size: 30px;
            color: rgb(241, 230, 211);
        }
        .section p{
            color: rgb(170, 167, 162);
        }
        body{
            background-color: #002451;
        }
        header{ 
            text-align: center;
            font-size: 35px;
            background-color:  #001126 ;
            color : rgb(201, 202, 198);
            left:0;
            top:0;
            position : relative;
            border : 1px rgb(6, 32, 70) solid;
            min-height: 100%;
            max-width: auto;
        }
        .section div {
            color: rgb(247, 236, 217);
        }
        .section {
            margin-top: 30px;
            margin-left: 250px;
            padding: 0px 10px;
            float: left;
            width:80%;
        }


        
        </style>
        <title>공부 노트</title>
        
    </head>
    <body>
        <header>
            <p>2020년도 청운대학교 전자공학과 3학년 1학기 수강 과목</p>
        </header>
        
        <div class="side">
            <a href="mywebsite.html"> HOME </a>
            <a href="디지털공학.html"> 디지털공학</a>
            <a href="HTML5.html"> HTML5</a>
            <a href="https://www.tinkercad.com"> 임베디드 시스템</a>
            <a href="실험.html"> 전자회로 실험I </a>
            <a href="반도체.html">반도체소자 </a>
            <a href="전자회로.html"> 전자회로 </a>
            <a href="자동제어.html"> 자동제어 </a>
        </div>
        <div class="section">
            <div>
            <h4 class="title"> 1. 디지털 공학</h4>
            </div>
        <img src="디지털 공학 이미지.jpg" alt="교재 이미지" style="width: 400px; height: 600px; position:relative">

    </body>
</html>

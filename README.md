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
            font-size: 20px;
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
            <h1 style="color : rgb(204, 115, 130)"> # 과목 소개</h1>
            <div>
            <h4 class="title"> 1. 디지털 공학</h4>
            <p> <b>학습목표</b></p>
                <ul>
                    <li>디지털 값과 아날로그 값의 변환을 공부하고 변환한 디지털 코드 값으로 논리회로를 구성할 수 있다.</li>
                    <li>디지털 값에 대한 부울대수 식에 대해 공부하고 카르노 맵, 퀸-맥클러스키 공식을 이용해서 출력 부울대수 식을 최소화 하는 과정에 대해서 이해한다.</li>  
                </ul>
            </div>
        
            <div>
            <h4 class="title"> 2. HTML5 </h4>
            <p> <b>학습목표</b></p>
            <ul>
                <li>HTML5 문서를 작성하기 위해서 인터넷 , WWW , http 등 프로그래밍 및 웹 페이지의 대해서 이해하고 클라이언트 서버의 역할,
                 <br>웹 서버와 클라이언트 간의 데이터 교환의 과정을
                이해할 수 있다.</li> <li>html 요소와 속성을 이용해서 값을 입력하고 입력한 값이나 화면에 보여지는 요소들을 
                CSS 요소를 이용해서 설정할 수 있다.</li>
            </ul>
            </div>
        
            <div>
            <h4 class="title"> 3. 임베디드 시스템 </h4>
            <p> <b>학습목표</b></p>
            <ul>
                <li>아두이노를 동작시키기 위해서 C언어의 개념을 알고 아두이노 키트가 아닌 
                ThinkerCad 페이지를 이용해서 아두이노에 대해 이해하고 여러 종류의 센서와 연결할 수 있다.</li>
                <li>직접 아두이노 보드와 센서에 맞게 연결을 하고 코드를 작성하여 아두이노를 동작시킬 수 있다.</li>
            </ul>
            </div>
            <div>
            <h4 class="title"> 4. 전자회로실험I </h4>
            <p> <b>학습목표</b></p>
            <ul>
                <li>회로를 구성하는데 필요한 소자 ( 다이오드 , 트랜지스터 , 저항 등) 에 대해서 실제 
                회로 구성을 어떻게 하는지 배우고 실험에 필요한 장비의 사용법에 대해서 이해하고 직접 장비를 
                사용할 수 있다.</li> <li>전자회로에서 배우는 각 소자의 회로법칙을 이해하고 실제로 적용해서 
                증폭기를 만들 수 있다.</li>
            </ul>
            </div>
       
            <div>
            <h4 class="title"> 5. 반도체 소자 </h4>
            <p> <b>학습목표</b></p>
            <ul>   
                <li>전자와 정공이 반도체 내에서 캐리어로써 어떤 역할을 하는지 이해하고 p형 반도체, 
                n형 반도체, 진성 반도체 에서의 캐리어에 대해서 알 수 있다. </li>
                <li>반도체에 빛을 입사 하거나 전계를 걸어 주었을 때 발생하는 확산전류, 표동 전류에 대해서 이해하고 값을 구할 수 있다.</li>
            </ul> 
            </div>


            <div>
            <h4 class="title"> 6. 전자회로 </h4>
            <p> <b>학습목표</b></p>
            <ul>  
                <li>다이오드, 트랜지스터가 회로에서 작동할 때 적용되는 전압, 전류에 대한 소자법칙을 이해하고 
                회로가 변함에 따라서 바뀌는 값들을 구할 수 있다.</li>
            </ul>  
            </div>


            <div>
            <h4 class="title"> 7. 자동제어 </h4>
            <p> <b>학습목표</b></p>
            <ul>
                <li>실생활에서 존재하는 자동제어의 종류에 대해서 알고 자동제어의 동작 과정에 대해 알 수 있다.</li>
                <li>자동제어에서 활용하는 수학적 내용을 복습을 통해 이해하고 자동제어 회로에 적용시킬 수 있다.</li>
                <li>자동제어 시스템의 논리회로도를 그릴 수 있고 간단한 그림으로 나타낼 수 있다.</li>
            </ul>
            </div>
        </div>

    </body>
</html>

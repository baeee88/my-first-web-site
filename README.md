<!DOCTYPE HTML>
<html>
<head>
    <title>20260406 수업</title>
</head>

<style>
h1 { color: YELLOW; }

.p_back {
    text-align: center;
    line-height: 30px;
    margin-top: 50px;
    background-color: red;
    color: white;
}

.p_back2 {
    font-size: 20px;
    font-weight: bold;
    color: blue;
}

dl li {
    float: left;
    width: 100px;
}

#title {
    margin: 20px !important;
}

/* Tooltip container */
.tooltip {
    position: relative;
    display: inline-block;
    border-bottom: 1px dotted black; /* Add dots under the hoverable text */
    cursor: pointer;
}

/* Tooltip text */
.tooltiptext {
    visibility: hidden; /* Hidden by default */
    width: 120px;
    background-color: black;
    color: #ffffff;
    text-align: center;
    padding: 5px 0;
    border-radius: 6px;
    position: absolute;
    z-index: 1; /* Ensure tooltip is displayed above content */
}

/* Show the tooltip text when mouse over */
.tooltip:hover .tooltiptext {
    visibility: visible;
}
</style>

<body>

<h1>로그인</h1>

<p class="p_back">
    로그인하려면 아이디 패스워드를 넣으세요.
    <br>
    <a href="http://www.syu.ac.kr" target="_blank">삼육대학교</a>
</p>

<ul>
    <li class="li_title">아이디</li>
    <li class="tooltip" style="cursor: help;">
        패스워드
        <span class="tooltiptext">패스워드는 대문자,소문자, 특수문자 순서를 조합해서 입력하세요</span>
    </li>
</ul>

<hr>

<p class="p_back2">
    엠퍼센트 ; 세미콜론 "" 더블쿼트 : 콜론 
</p>

</body>
</html>
